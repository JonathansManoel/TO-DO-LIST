# TO-DO-LIST
Projeto "To Do LIst" é um checklist construído com Django.

Desenvolvido no módulo de [Imersão Django](https://www.youtube.com/watch?v=zLIeu9cPYrY&list=PLA05yVJtRWYRgtGyrdH4Bbf2gtbk6OtTu&ab_channel=CanalPythonProBr) do [Site Python Pro](https://www.python.pro.br)

## Como rodar o projeto localmente

- Clone esse repositório
- Instale o pipenv 
- Instale as dependencias
- Copie as variáveis de ambiante
- Inicie o banco de dados
- Rode as migrações

```
https://github.com/JonathansManoel/TO-DO-LIST.git
cd todolist
python -m pip install pipenv
pipenv sync -d
pipenv run python manage.py migrate
pipenv run python manage.py runserver
```
