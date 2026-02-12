# ✅ CHECKLIST AVANÇADO – FRONTEND & BACKEND

---

## 🔧 1. Preparação do ambiente

```bash
sudo apt update && sudo apt upgrade -y
sudo apt install -y build-essential curl git unzip
```

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```

---

## 🌐 2. Frontend (HTML / CSS / JS / React)

### Node.js (LTS)

```bash
node -v
npm -v
```

Criar projeto frontend:

```bash
mkdir frontend && cd frontend
npm init -y
```

React (Vite – leve e rápido):

```bash
npm create vite@latest app-frontend
cd app-frontend
npm install
npm run dev
```

Comandos úteis:

```bash
npm install pacote
npm uninstall pacote
npm run build
npm run dev
```

---

## ⚙️ 3. Backend (Node.js / API REST)

Criar API simples:

```bash
mkdir backend && cd backend
npm init -y
npm install express cors dotenv
```

Rodar servidor:

```bash
node index.js
```

Dev mode:

```bash
npm install -D nodemon
npx nodemon index.js
```

Estrutura recomendada:

```text
backend/
├── src/
│   ├── routes/
│   ├── controllers/
│   ├── services/
│   ├── models/
│   └── app.js
├── .env
└── package.json
```

---

## 🐍 4. Backend com Python (FastAPI – opcional)

```bash
sudo apt install -y python3-venv
python3 -m venv venv
source venv/bin/activate
pip install fastapi uvicorn
```

Rodar API:

```bash
uvicorn main:app --reload
```

---

## 🗄️ 5. Banco de dados

### PostgreSQL

```bash
sudo apt install postgresql postgresql-contrib
sudo service postgresql start
```

### Comandos básicos:

```bash
psql -U postgres
\l
\c nome_db
\dt
```

---

## 🔐 6. Variáveis de ambiente

```bash
touch .env
```

Exemplo:

```env
PORT=3000
DB_HOST=localhost
DB_USER=postgres
DB_PASS=senha
```

Nunca versionar:

```bash
echo ".env" >> .gitignore
```

---

## 🔁 7. Git – fluxo profissional

```bash
git init
git checkout -b dev
git add .
git commit -m "feat: estrutura inicial"
git pull origin main
git merge dev
```

Padrão de commits:

```text
feat:
fix:
refactor:
docs:
```

---

## 🧪 8. Testes

```bash
npm install -D jest
npm test
```

---

## 🧰 9. Debug & inspeção

```bash
console.log()
node --inspect index.js
```

Frontend:

- DevTools do navegador
- Network / Console / Application

---

## 🚀 10. Build & deploy (conceito)

```bash
npm run build
```

Preparar produção:

- Frontend → build estático
- Backend → API separada
- Usar:
  - Nginx
  - PM2
  - Docker (mais pra frente)

---

## ⚡ Boas práticas importantes

- ❌ Não usar `/mnt/c`
- ✅ Usar `/home/seu_usuario/`
- Um repositório = um projeto
- Frontend e backend separados
- Variáveis sensíveis no `.env`

---

## 🧠 RESUMO FINAL

Você agora tem:

- Setup profissional
- Fluxo frontend + backend
- Comandos reais de mercado
- Base pra freelas e emprego
