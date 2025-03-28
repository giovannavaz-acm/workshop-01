# Workshop-01

### Instalação e Configuração
1. Clone o repositório

'''
git clone https://github.com/lvgalvao/Workshop-aberto-aovivo
cd Workshop-aberto-aovivo
'''

2. Configure a versão correta do Python com pyenv:

'''
pyenv install 3.11.5
pyenv local 3.11.5
'''

3. Instale as dependências do projeto:

'''
python -m venv .venv
# O padrao é utilizar .venv
source .venv/bin/activate
# Usuários Linux e mac
.venv\Scripts\Activate
# Usuários Windows
pip install -r requirements.txt  
'''

4. Rode o projeto

'''
task run
'''

5. Rode os testes

'''
task test
'''

6. Rode a documentação
''' 
task docs
'''