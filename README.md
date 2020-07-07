# Desenvolvimento web com Django, React (back-end)

Projeto com fins de estudo para integrar APIs Django com React framework utilizando as melhores praticas

### Aplicando migrações

Ao rodar o projeto pela primeira vez, é necessário aplicar migrações das tabelas do Banco de dados.

- docker-compose run django python manage.py migrate

#### Criando super usuário

- docker-compose run django python manage.py createsupersuser

#### Iniciando conteiner

- docker-compose up
