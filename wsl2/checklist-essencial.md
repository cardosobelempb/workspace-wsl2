## ✅ CHECKLIST ESSENCIAL – COMANDOS LINUX PARA DEV

---

## 📁 Navegação no sistema

```bash
pwd            # Mostra o diretório atual
ls             # Lista arquivos e pastas
ls -la         # Lista detalhada (mostra ocultos)
cd pasta       # Entra em uma pasta
cd ..          # Volta uma pasta
cd ~           # Vai para a home
clear          # Limpa o terminal
```

---

## 📂 Arquivos e pastas

```bash
mkdir projeto          # Cria pasta
rm arquivo.txt         # Remove arquivo
rm -r pasta            # Remove pasta
cp a.txt b.txt         # Copia arquivo
mv a.txt pasta/        # Move arquivo
mv antigo novo         # Renomeia
touch index.html       # Cria arquivo vazio
```

---

## 📄 Visualizar arquivos

```bash
cat arquivo.txt        # Mostra conteúdo
less arquivo.txt       # Visualização paginada
head arquivo.txt       # Primeiras linhas
tail arquivo.txt       # Últimas linhas
tail -f log.txt        # Acompanha arquivo em tempo real
```

---

## 🔧 Permissões

```bash
chmod +x script.sh     # Torna executável
ls -l                  # Ver permissões
sudo comando           # Executa como administrador
```

---

## 📦 Gerenciador de pacotes (APT)

```bash
sudo apt update                    # Atualiza lista de pacotes
sudo apt upgrade -y                # Atualiza sistema
sudo apt install nome-do-pacote    # Instala pacote
sudo apt remove nome-do-pacote     # Remove pacote
sudo apt autoremove                # Limpa pacotes inúteis
```

---

## 🧠 Processos e sistema

```bash
top            # Monitor de processos
htop           # (se instalado) melhor monitor
free -h        # Uso de memória
df -h          # Uso de disco
uname -a       # Info do sistema
```

---

## 🌐 Rede

```bash
ip a            # Info de rede
ping google.com # Testa conexão
curl url        # Requisição HTTP
wget url        # Baixar arquivo
```

---

## 🧰 Git (controle de versão)

```bash
git init
git clone url
git status
git add .
git commit -m "mensagem"
git pull
git push
git branch
git checkout -b nova-branch
```

---

## 🌍 Node.js / JavaScript

```bash
node -v
npm -v
npm init -y
npm install pacote
npm run dev
```

---

## 🐍 Python

```bash
python3 --version
pip3 --version
pip3 install pacote
python3 app.py
```

---

## 🧪 WSL (no PowerShell)

```powershell
wsl --list --verbose
wsl --shutdown
wsl
```

---

## 💻 VS Code + WSL

```bash
code .          # Abre o VS Code no diretório atual
```

---

## ⭐ DICAS DE OURO

- Trabalhe sempre em:

```bash
/home/seu_usuario/
```

- Use **Tab** para autocompletar comandos
- Use **Ctrl + C** para parar processos
- Use **Ctrl + R** para buscar comandos antigos

---

Se quiser, eu posso:

- 📄 Transformar isso em **PDF**
- 🧪 Criar um **checklist avançado** só pra web / backend / python
- 🚀 Montar um **mini projeto prático** usando esses comandos

É só dizer 👌
