# Listas de Comandos

- Cria o ambiente

virtual na pqsta venv
```python
python -m venv  venv 
```
- Ativar o ambiente irtual 
```python
venv\Scripts\activate
```
- Instalar todos os pacotes necessários 
```python 
pip install flask
pip install flask-wtf
pip install requests
pip install pytest
pip install pytest-flask
```- salva a lista de pacotes instalados
- no arquivo requirements.txt
- Isso permite que as outras pessoas instael as mesms versões
```python
pip freeze > requirements.txt
'''
## Criar o arquivo .gitignore
- Diz ao git quais arquivos e pasta **não devem versionados**.