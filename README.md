# sample-flask-auth

Repositório criado para armazenar o código da API de autenticação com banco de dados.

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
