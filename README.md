# python_06

- poetry init
- poetry env use 3.12
- poetry shell

- poetry add flake8 -> aponta correções no arquivo informado
- poetry run flake8 main.py

- poetry add black -> realiza a padronização do codigo
- poetry run black main.py

-- pre-commit -> garante padrao de codigo antes do commit
- poetry add pre-commit
- .pre-commit-config -> cria arquivo com os hoks
- poetry run pre-commit install -> instala
- git add .pre-commit-config.yaml ->
- git commit -m 'teste pre-commit'
