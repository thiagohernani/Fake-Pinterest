📌 Fake Pinterest

Um clone simples do Pinterest desenvolvido com Python (Flask), HTML, CSS e JavaScript.
O projeto foi criado com foco em estudos de Back-End e Front-End, explorando autenticação de usuários, upload de imagens e persistência de dados com Flask SQLAlchemy.

🚀 Tecnologias Utilizadas

Python 🐍

Flask (framework web)

Flask-SQLAlchemy (ORM para banco de dados)

HTML5

CSS3

JavaScript

⚙️ Funcionalidades

✅ Cadastro de usuários
✅ Login e autenticação com Flask-Login
✅ Upload de imagens
✅ Visualização de imagens no feed estilo Pinterest
✅ Logout de usuário
✅ Estrutura organizada com Blueprints e templates

📦 Dependências

O projeto utiliza os seguintes pacotes Python:

Flask==3.0.3
Flask-SQLAlchemy==3.1.1
Flask-WTF==1.2.1
Flask-Login==0.6.3
email-validator==2.1.1
WTForms==3.1.2
Werkzeug==3.0.3
bcrypt==4.1.2


Instale tudo com:

pip install -r requirements.txt

📂 Estrutura do Projeto
fake-pinterest/
│-- fakepinterest/       # Código principal do projeto
│   │-- static/          # Arquivos estáticos (CSS, JS, imagens)
│   │-- templates/       # Páginas HTML
│   │-- models.py        # Modelos do banco de dados
│   │-- forms.py         # Formulários Flask-WTF
│   │-- __init__.py      # Configuração do app Flask
│-- venv/                # Ambiente virtual
│-- requirements.txt     # Dependências do projeto
│-- run.py               # Arquivo para rodar a aplicação

▶️ Como Executar o Projeto

Clone o repositório:

git clone https://github.com/seu-usuario/fake-pinterest.git


Acesse a pasta do projeto:

cd fake-pinterest


Crie e ative o ambiente virtual:

python -m venv venv
venv\Scripts\activate   # Windows
source venv/bin/activate   # Linux/Mac


Instale as dependências:

pip install -r requirements.txt


Inicie o servidor:

flask run

Acesse no navegador:

http://127.0.0.1:5000

