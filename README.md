
# 💸 Fique Rico ou Morra Tentando

Blog de educação financeira criado com Django + React

![Vercel Deploy](https://img.shields.io/badge/Frontend-Vercel-000?logo=vercel)
![Render Deploy](https://img.shields.io/badge/Backend-Render-blue?logo=render)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-online-brightgreen)

---

## 🌐 Link Online

- 🔗 **Frontend**: [https://fique-rico.vercel.app](https://fique-rico.vercel.app)
- 🔗 **Backend API**: [https://fique-rico-backend.onrender.com/api/posts/](https://fique-rico-backend.onrender.com/api/posts/)

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
- Vite.js
- CSS moderno e responsivo
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

- ✅ Listagem de posts financeiros
- ✅ Filtro por categoria
- ✅ Página de detalhe
- ✅ Layout responsivo (mobile / desktop)
- ✅ Painel admin do Django para gerenciar posts
- ✅ Integração API REST
- ✅ Formulário de contato funcional (EmailJS)

---

## 🖼️ Imagens do Projeto

![Home](https://via.placeholder.com/800x400?text=Homepage)
![Post](https://via.placeholder.com/800x400?text=Detalhe+do+Post)

---

## 📬 Contato

Criado por **Nathan Francisco Correa Ferreira**

- 📧 Email: contato@nathanfinanceiro.com
- 🌐 Site pessoal: [https://nathanfinanceiro.com](https://nathanfinanceiro.com)
- 💼 LinkedIn: [https://linkedin.com/in/nathanfinanceiro](https://linkedin.com/in/nathanfinanceiro)
- 📸 Instagram: [@nathanfinanceiro](https://instagram.com/nathanfinanceiro)

---

📄 Licença: MIT

> Projeto com fins educativos. Compartilhe e contribua! 💚
