# ✅ CHECKLIST DEFINITIVO – WSL 2 (WINDOWS)

---

## 🪟 1. Pré-requisitos no Windows

- [ ] Windows 10 (2004+) ou Windows 11
- [ ] Virtualização ativada na BIOS
- [ ] Windows Update em dia

Verificar:

```powershell
wsl --status
```

---

## ⚙️ 2. Instalação do WSL 2

```powershell
wsl --install
```

Após reiniciar:

```powershell
wsl --list --verbose
```

✔️ Verifique se está **Version 2**

---

## 🐧 3. Distribuição Linux (Ubuntu)

- [ ] Criar usuário
- [ ] Criar senha
- [ ] Abrir terminal do Ubuntu

Atualizar:

```bash
sudo apt update && sudo apt upgrade -y
```

---

## 🧠 4. Ajuste essencial de desempenho (MUITO IMPORTANTE)

Criar arquivo no Windows:

```text
%UserProfile%\.wslconfig
```

Conteúdo recomendado:

```
[wsl2]
memory=3GB
processors=2
swap=2GB
```

Aplicar:

```powershell
wsl --shutdown
```

---

## 🔧 5. Pacotes básicos obrigatórios

```bash
sudo apt install -y build-essential curl git unzip
```

---

## 📁 6. Organização correta de projetos

- [ ] Criar projetos em:

```bash
/home/seu_usuario/
```

- [ ] ❌ Evitar:

```bash
/mnt/c/
```

---

## 💻 7. VS Code + WSL

- [ ] Instalar VS Code (Windows)
- [ ] Instalar extensão **WSL**
- [ ] Abrir projetos via:

```bash
code .
```

---

## 🌐 8. Stack Frontend

```bash
node -v
npm -v
```

Criar projeto:

```bash
npm create vite@latest app
cd app
npm install
npm run dev
```

---

## ⚙️ 9. Stack Backend

```bash
npm init -y
npm install express cors dotenv
```

Rodar API:

```bash
node index.js
```

Dev mode:

```bash
npx nodemon index.js
```

---

## 🐍 10. Backend Python (opcional)

```bash
sudo apt install -y python3 python3-pip python3-venv
```

---

## 🗄️ 11. Banco de dados

```bash
sudo apt install postgresql
sudo service postgresql start
```

---

## 🔐 12. Variáveis de ambiente

```bash
touch .env
echo ".env" >> .gitignore
```

---

## 🧪 13. Comandos úteis do WSL

```powershell
wsl --shutdown
wsl --list --verbose
wsl
```

---

## ⚡ 14. Boas práticas (evita bugs)

- Usar Linux como ambiente principal de dev
- Evitar ferramentas pesadas
- Manter WSL limitado por memória
- Atualizar o sistema periodicamente

---

## 🏁 RESULTADO FINAL

Você fica com:

- Windows limpo e leve
- Linux real rodando no WSL 2
- Ambiente profissional
- Performance estável no seu hardware
