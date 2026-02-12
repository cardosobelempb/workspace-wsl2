## **resumo dos principais comandos do Vim no Linux**

## 🚀 Abrir / sair do Vim

```bash
vim arquivo.txt
```

| Comando | O que faz              |
| ------- | ---------------------- |
| `:q`    | sair                   |
| `:q!`   | sair sem salvar        |
| `:w`    | salvar                 |
| `:wq`   | salvar e sair          |
| `ZZ`    | salvar e sair (rápido) |

---

## ✍️ Modos do Vim

| Tecla | Modo                     |
| ----- | ------------------------ |
| `i`   | inserir antes do cursor  |
| `a`   | inserir depois do cursor |
| `o`   | nova linha abaixo        |
| `O`   | nova linha acima         |
| `Esc` | voltar ao modo normal    |

---

## 🧭 Navegação

| Comando   | Função                         |
| --------- | ------------------------------ |
| `h j k l` | esquerda, baixo, cima, direita |
| `w`       | próxima palavra                |
| `b`       | palavra anterior               |
| `0`       | início da linha                |
| `$`       | fim da linha                   |
| `gg`      | início do arquivo              |
| `G`       | fim do arquivo                 |
| `:n`      | ir para linha `n`              |

---

## ✂️ Edição (cortar, copiar, colar)

| Comando    | Função           |
| ---------- | ---------------- |
| `x`        | apagar caractere |
| `dd`       | apagar linha     |
| `yy`       | copiar linha     |
| `p`        | colar            |
| `u`        | desfazer         |
| `Ctrl + r` | refazer          |

---

## 🔎 Busca

```vim
/palavra
```

| Comando            | Função              |
| ------------------ | ------------------- |
| `n`                | próxima ocorrência  |
| `N`                | ocorrência anterior |
| `:%s/velho/novo/g` | substituir tudo     |

---

## 🎯 Modo visual (seleção)

| Comando    | Função                |
| ---------- | --------------------- |
| `v`        | seleção por caractere |
| `V`        | seleção por linha     |
| `Ctrl + v` | seleção em bloco      |

---

## 🧠 Comandos úteis demais

| Comando         | O que faz                |
| --------------- | ------------------------ |
| `.`             | repete último comando    |
| `ciw`           | muda palavra inteira     |
| `dw`            | apaga palavra            |
| `>>` / `<<`     | identar / desidentar     |
| `:set number`   | mostrar números de linha |
| `:set nonumber` | esconder números         |

---

## 🛠️ Dica de ouro

Aprenda **combinações**:

```vim
3dd   " apaga 3 linhas
5w    " pula 5 palavras
```
