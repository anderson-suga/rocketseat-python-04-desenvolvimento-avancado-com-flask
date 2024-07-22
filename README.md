# Formação Python do Rocketseat

## Nível 02 - Desenvolvimento Avançado com Flask

### Desenvolvimento de APIs com Flask

Módulo focado no entendimento e aplicação de autenticação usando Flask-Login e também dedicado a apresentar conceitos e integração de banco de dados utilizando SQLAlchemy.

URL: https://www.rocketseat.com.br/formacao/python

## Criar o tabela do User

```
flask shell
db.create_all()
db.session.commit()
exit()
```

## Cadastrando um usuário na tabela do User

```
flask shell
user = User(username="admin", password="123")
db.session.add(user)
db.session.commit()
exit()
```

## Extensão do VS Code para visualizaro o SQLite

Name: SQLite Viewer</br>
Publisher: Florian Klampferr</br>
Link: https://marketplace.visualstudio.com/items?itemName=qwtel.sqlite-viewer
