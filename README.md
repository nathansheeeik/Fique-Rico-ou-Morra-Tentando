
# 💸 Fique Rico ou Morra Tentando

Blog de educação financeira criado com Django + React

## 🌐 Link Online

- Frontend: [https://fique-rico.vercel.app](https://fique-rico.vercel.app)
- Backend API: [https://fique-rico-backend.onrender.com/api/posts/](https://fique-rico-backend.onrender.com/api/posts/)

---

## 🛠️ Tecnologias

### Backend (Django + DRF)
- Django 4+
- Django REST Framework
- Django CORS Headers
- PostgreSQL (Render)
- Deploy: [Render.com](https://render.com)

### Frontend (React + Vite)
- React 18+
- React Router DOM
- Axios
- CSS Moderno responsivo
- Deploy: [Vercel.com](https://vercel.com)

---

## 📂 Estrutura do Projeto

```
.
├── backend/                # Projeto Django
│   ├── blog/               # App principal com models, views, serializers
│   ├── backend/            # Configuração principal
│   ├── manage.py
│   ├── requirements.txt
│   ├── Procfile
│   └── render.yaml
├── fique-rico-frontend/    # Projeto React + Vite
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
```

---

## 🚀 Como rodar localmente

### Backend:
```bash
cd backend
python -m venv env
source env/bin/activate  # ou .\env\Scripts\activate no Windows
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

### Frontend:
```bash
cd fique-rico-frontend
npm install
npm run dev
```

---

## ✨ Funcionalidades

- Listagem de posts financeiros
- Filtro por categoria
- Página de detalhe
- Responsivo (mobile / desktop)
- Painel admin do Django para gerenciar posts
- Integração API REST

---

## 📬 Contato

Criado por [Seu Nome] — contato: seu@email.com
