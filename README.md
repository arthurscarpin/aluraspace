# 🚀 Aluraspace 
Esse Web App de uma galeria de fotos do espaço, foi desenvolvido em linguagem Python e Django.

Com o objetivo de colocar em prática os conhecimento adquiridos em Python orientado a objetos.

## 🖥️ Tecnologias utilizadas
<div align="left">
    <a href="https://skillicons.dev">
        <img src="https://skillicons.dev/icons?i=html,css,python,django,sqlite"/>
    </a>
</div>

## 🌙 Interface - Aluraspace
![img-aluraspace](https://github.com/user-attachments/assets/d28093a0-648e-4370-92ca-5ba98ea7beb6)

## 🛠️ Como executar?
Para executar esse projeto é necessário seguir o passo a passo a seguir:

1. Criar o ambiente virtual do Python.

Na pasta raíz do repositório local, execute o comando:
```
python -m venv <nome do ambiente virtual>
```

2. Ativar o ambiente virutal
```
.\venv\Scripts\activate
```

3. Instalar as dependências do **requirements.txt**.
```
pip install -r requirements.txt  
```

4. Executar as **Migrations** do banco de dados.
```
python manage.py migrate
```

5. Criar usuário super no Django.
```
python manage.py createsuperuser
```

6. Perform SQLite Migration.
```
python manage.py runserver
```

## 📁 Documentações de referência
[Documentação Django](https://www.djangoproject.com/)
