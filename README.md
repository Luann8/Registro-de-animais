### Criar Ambiente Virtual e Instalar Bibliotecas

#### Linux/macOS:

```bash
# Instalar virtualenv se necessário
pip install virtualenv

# Criar e ativar ambiente virtual
cd caminho/para/seu/projeto
virtualenv .venv
source .venv/bin/activate

# Instalar dependências do projeto
pip install -r requirements.txt

# Configurar e executar o projeto Django
python manage.py migrate
python manage.py runserver

```
# Instalar virtualenv se necessário
```bash
pip install virtualenv

# Criar e ativar ambiente virtual
cd caminho\para\seu\projeto
virtualenv .venv
.venv\Scripts\activate

# Instalar dependências do projeto
pip install -r requirements.txt

# Configurar e executar o projeto Django
python manage.py migrate
python manage.py runserver

