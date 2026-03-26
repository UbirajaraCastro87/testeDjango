# 🐍 Projeto Django - testeDjango

Este é um projeto de estudo em **Django**, criado para aprender e praticar os principais conceitos do framework, incluindo:
- Estrutura de projetos e apps
- Modelos e migrações
- Painel administrativo
- Integração com banco de dados SQLite3

## 🚀 Tecnologias utilizadas
- Python 3.x
- Django 5.x
- SQLite3
- IPython (para shell interativo)
- Visual Studio Code (editor)

## 📂 Estrutura do projeto
mysite/          # Projeto principal │ ├── polls/       # App de exemplo (enquetes) │   ├── models.py │   ├── views.py │   ├── urls.py │   └── admin.py │ ├── db.sqlite3   # Banco de dados ├── manage.py    # Utilitário de gerenciamento └── README.md


## ⚙️ Como rodar o projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/UbirajaraCastro87/testeDjango.git
   cd testeDjango
2-- Crie e ative o ambiente virtual:

   python -m venv venv
.\venv\Scripts\Activate

3- Instale as dependências:
pip install -r requirements.txt

4- Execute as migrações:
python manage.py migrate

5-Crie um superusuário:
python manage.py createsuperuser

6- Rode o servidor:
python manage.py runserver


Objetivo
Este projeto tem como objetivo servir de laboratório para aprender Django, explorando:
- Criação de apps
- Customização do admin
- Manipulação de modelos e consultas
- Integração com Git/GitHub








