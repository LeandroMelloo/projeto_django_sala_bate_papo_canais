# projeto_django_sala_bate_papo_canais

Projeto criação de uma sala de bate-papo assíncrona com Django e canais

# Criando o ambiente virtual python
python -m venv venv

# Instalando as bibliotecas do projeto
pip install django
pip install channels

# Criando o arquivo requirements.txt
pip freeze > requirements.txt

# Criando o projeto Django
django-admin startproject core .

# Criado um app no Django
python manage.py startapp chat
