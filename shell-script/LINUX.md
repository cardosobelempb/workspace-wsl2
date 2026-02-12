## **guia prático dos principais comandos Linux**

---

## 🐧 Comandos básicos do Linux

| Comando    | O que faz                    |
| ---------- | ---------------------------- |
| `pwd`      | mostra diretório atual       |
| `ls`       | lista arquivos               |
| `ls -la`   | lista completa (com ocultos) |
| `cd pasta` | entra na pasta               |
| `cd ..`    | volta um nível               |
| `clear`    | limpa a tela                 |
| `exit`     | sair do terminal             |

---

## 📂 Arquivos e diretórios

| Comando               | Função           |
| --------------------- | ---------------- |
| `touch arquivo`       | cria arquivo     |
| `mkdir pasta`         | cria diretório   |
| `mkdir -p a/b/c`      | cria árvore      |
| `rm arquivo`          | remove arquivo   |
| `rm -r pasta`         | remove pasta     |
| `cp origem destino`   | copia            |
| `cp -r pasta1 pasta2` | copia pastas     |
| `mv origem destino`   | mover / renomear |
| `stat arquivo`        | info do arquivo  |

---

## 📄 Visualizar arquivos

| Comando           | Função           |
| ----------------- | ---------------- |
| `cat arquivo`     | mostra conteúdo  |
| `less arquivo`    | paginado         |
| `more arquivo`    | paginado simples |
| `head arquivo`    | início           |
| `tail arquivo`    | final            |
| `tail -f log.txt` | acompanhar log   |

---

## 🔎 Busca e filtros

| Comando                 | Função         |
| ----------------------- | -------------- |
| `find / -name arquivo`  | buscar arquivo |
| `locate arquivo`        | busca rápida   |
| `grep "texto" arquivo`  | busca texto    |
| `grep -r "texto" pasta` | recursivo      |
| `wc -l arquivo`         | contar linhas  |

---

## 🔗 Pipes e redirecionamento

| Símbolo | Função       |      |
| ------- | ------------ | ---- |
| `       | `            | pipe |
| `>`     | sobrescrever |      |
| `>>`    | adicionar    |      |
| `<`     | entrada      |      |

Exemplo:

```bash
ps aux | grep nginx | wc -l
```

---

## 🔐 Permissões e usuários

| Comando                    | Função             |
| -------------------------- | ------------------ |
| `chmod 755 arquivo`        | permissões         |
| `chmod +x script.sh`       | executável         |
| `chown user:grupo arquivo` | dono               |
| `whoami`                   | usuário atual      |
| `id`                       | info do usuário    |
| `su`                       | trocar usuário     |
| `sudo comando`             | executar como root |

---

## ⚙️ Processos

| Comando       | Função           |
| ------------- | ---------------- |
| `ps aux`      | processos        |
| `top`         | monitor          |
| `htop`        | monitor avançado |
| `kill PID`    | matar processo   |
| `kill -9 PID` | forçar           |
| `uptime`      | tempo ligado     |

---

## 🌐 Rede

| Comando     | Função          |
| ----------- | --------------- |
| `ip a`      | interfaces      |
| `ping host` | testar conexão  |
| `ss -tuln`  | portas          |
| `curl url`  | requisição      |
| `wget url`  | download        |
| `hostname`  | nome da máquina |

---

## 📦 Pacotes (depende da distro)

### Debian / Ubuntu

```bash
apt update
apt install pacote
apt remove pacote
```

### RedHat / CentOS / Rocky

```bash
dnf install pacote
```

---

## 💾 Disco e sistema

| Comando        | Função          |
| -------------- | --------------- |
| `df -h`        | espaço em disco |
| `du -sh pasta` | tamanho         |
| `free -h`      | memória         |
| `mount`        | discos montados |
| `lsblk`        | discos          |

---

## 🧠 Dicas de ouro do Linux

- **Tab** completa comandos
- `Ctrl + c` → interrompe
- `Ctrl + r` → busca histórico
- `history` → comandos usados
- `!!` → último comando

---
