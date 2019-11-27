# StuKi®

Projeto referente à disciplina de Engenharia de Software I - IFPI

#### Clone/Configure

`$ git clone https://github.com/PaulloClara/stuki.git`\
`$ cd stuki`\
`$ python -m venv .env`\
`$ source .env/bin/activate`\
`$ pip install -r requirements.txt`\
`$ git update-index --assume-unchanged src/store/database.sqlite`

#### Ativar/Desativar Env

`$ source .env/bin/activate`\
`$ deactivate`

#### Rodar App

`$ python -B run.py --dev`

#### Rodar Testes

`$ python -B run.py --test`

#### Gerar execultavel

`$ cxfreeze run.py --target-dir dist`
