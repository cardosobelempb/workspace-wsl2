## **guia prático dos principais comandos de Shell Script (Linux/bash)**

---

## 🐚 O que é Shell Script?

É basicamente um **arquivo com comandos Linux**, executados em sequência pelo **bash**.

Exemplo de início de script:

```bash
#!/bin/bash
```

---

## 📂 Comandos básicos de arquivos e diretórios

| Comando             | Função                 |
| ------------------- | ---------------------- |
| `ls`                | listar arquivos        |
| `ls -l`             | lista detalhada        |
| `pwd`               | mostra diretório atual |
| `cd pasta`          | entrar em diretório    |
| `mkdir pasta`       | criar diretório        |
| `rm arquivo`        | remover arquivo        |
| `rm -r pasta`       | remover pasta          |
| `cp origem destino` | copiar                 |
| `mv origem destino` | mover / renomear       |

---

## 📄 Manipulação de arquivos

| Comando           | Função              |
| ----------------- | ------------------- |
| `cat arquivo`     | mostrar conteúdo    |
| `less arquivo`    | visualizar paginado |
| `head arquivo`    | primeiras linhas    |
| `tail arquivo`    | últimas linhas      |
| `tail -f log.txt` | acompanhar log      |
| `touch arquivo`   | criar arquivo vazio |

---

## 🔎 Busca e filtros

| Comando                 | Função             |
| ----------------------- | ------------------ |
| `grep "texto" arquivo`  | buscar texto       |
| `grep -r "texto" pasta` | busca recursiva    |
| `find . -name "*.sh"`   | buscar arquivos    |
| `wc -l arquivo`         | contar linhas      |
| `sort`                  | ordenar            |
| `uniq`                  | remover duplicados |

---

## 🔗 Pipes e redirecionamento (MUITO importante)

| Símbolo | Função               |                        |
| ------- | -------------------- | ---------------------- |
| `       | `                    | pipe (saída → entrada) |
| `>`     | sobrescrever arquivo |                        |
| `>>`    | adicionar ao arquivo |                        |
| `<`     | entrada              |                        |

Exemplo:

```bash
cat arquivo | grep erro | wc -l
```

---

## 📦 Variáveis

```bash
NOME="João"
echo $NOME
```

Variáveis especiais:

| Variável | Significado          |
| -------- | -------------------- |
| `$0`     | nome do script       |
| `$1`     | primeiro argumento   |
| `$2`     | segundo argumento    |
| `$#`     | número de argumentos |
| `$@`     | todos os argumentos  |

---

## 🔁 Estruturas de controle

### IF

```bash
if [ $IDADE -ge 18 ]; then
  echo "Maior de idade"
else
  echo "Menor de idade"
fi
```

### CASE

```bash
case $1 in
  start) echo "Iniciando" ;;
  stop) echo "Parando" ;;
  *) echo "Opção inválida" ;;
esac
```

---

## 🔄 Laços (loops)

### FOR

```bash
for i in 1 2 3
do
  echo $i
done
```

### WHILE

```bash
while true
do
  echo "Rodando..."
  sleep 1
done
```

---

## ⚙️ Permissões e execução

| Comando              | Função            |
| -------------------- | ----------------- |
| `chmod +x script.sh` | tornar executável |
| `./script.sh`        | executar          |
| `bash script.sh`     | executar via bash |

---

## 🛠️ Comandos úteis em scripts

| Comando    | Função                   |
| ---------- | ------------------------ |
| `echo`     | imprimir texto           |
| `read var` | ler entrada              |
| `sleep 5`  | pausa                    |
| `exit 0`   | sair com status          |
| `$?`       | status do último comando |

---

## 🧠 Dicas de ouro

- Sempre use:

```bash
set -e
```

para parar o script em erro

- Use `#!/bin/bash` no topo
- Teste scripts com:

```bash
bash -x script.sh
```

---

Se quiser, posso:

- montar um **script exemplo completo**
- criar uma **cola (cheat sheet) resumida**
- explicar **Shell Script pra iniciantes**
- ou focar em **scripts de automação real (backup, deploy, logs)**

Só falar 👊
