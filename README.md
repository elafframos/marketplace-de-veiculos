# 🚗 Marketplace de Carros — Django

> **Vehicle Listing and Registration Platform** | Plataforma de Cadastro e Listagem de Veículos

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white)](https://www.djangoproject.com/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![Deploy](https://img.shields.io/badge/deploy-render-46E3B7?logo=render&logoColor=white)](https://render.com/)

---

## 🌐 Demo ao vivo | Live Demo

🔗 **[carros-m4tr.onrender.com](https://carros-m4tr.onrender.com/)**

> O servidor pode demorar alguns segundos para iniciar por estar em plano gratuito do Render.

---

## 📋 Sobre o projeto | About

**PT-BR:** Marketplace de veículos desenvolvido com Django, onde o usuário pode cadastrar e visualizar carros à venda. O projeto passou por uma refatoração completa com foco em responsividade, organização de arquivos e separação entre lógica e apresentação. Interface construída com Bootstrap e boas práticas de usabilidade.

**EN:** Vehicle marketplace built with Django where users can register and browse cars for sale. The project underwent a full refactor focused on responsiveness, file organization, and separation between logic and presentation. Interface built with Bootstrap following usability best practices.

---

## ⚡ Destaques técnicos | Technical Highlights

- **Cadastro de veículos** — formulário completo com upload de imagens e exibição em listagem
- **Refatoração focada em qualidade** — reorganização de arquivos e melhoria de responsividade
- **Separação de responsabilidades** — lógica de negócio separada da camada de apresentação
- **Interface responsiva** — layout adaptado para diferentes tamanhos de tela com Bootstrap
- **Arquitetura MVT** — organização seguindo o padrão Model-View-Template do Django

---

## 🛠️ Tecnologias | Tech Stack

| Camada | Tecnologia |
|--------|-----------|
| Backend | Python, Django |
| Frontend | HTML5, CSS, Bootstrap |
| Deploy | Render |
| Versionamento | Git & GitHub |

---

## 🚀 Como rodar localmente | How to run locally

```bash
# Clone o repositório
git clone https://github.com/elafframos/carros.git

# Entre na pasta
cd carros

# Crie e ative o ambiente virtual
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Instale as dependências
pip install -r requirements.txt

# Rode as migrations
python manage.py migrate

# Inicie o servidor
python manage.py runserver
```

---

## 👨‍💻 Autor | Author

**Élaff Ramos** — [LinkedIn](https://linkedin.com/in/elaff-ramos) · [GitHub](https://github.com/elafframos) · [Portfólio](https://portifolio-elafframos.vercel.app)
