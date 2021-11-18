# Manual Mentor Soft

Manual de uso do sistema Mentor Soft.


## Setup inicial?

01. Clone o repositório;
02. Crie uma "virtualenv" com Python 3.6;
03. Ative a "virtualenv";
04. Atualize o "pip";
05. Instale as dependências;
06. Rode o projeto;
07. Faça deploy do projeto;

```console
git clone https://github.com/KmSistemas/mentorsoft-manual.git
cd mentorsoft-manual
python -m venv .venv

# OSX
source .venv/bin/activate

#windows
.venv\Scripts\activate.bat

pip install --upgrade pip
pip install -r requirements.txt
mkdocs serve
mkdocs gh-deploy
```


## Como desenvolver?

```console
# Navega até o repositório
# Puxa todas as alterações do servidor de outros usuários
git pull

# OSX
source .venv/bin/activate

#windows
.venv\Scripts\activate.bat

mkdocs serve
#Servidor na Rede
mkdocs serve -a 0.0.0.0:8000
```

## Para atualizar o site  
1. Verifica o que foi modificado.  
2. Adicionar todos os arquivos para serem enviados.  
3. Commita com uma mensagem de alteração.  
4. Puxa todas as alterações do servidor de outros usuários.
5. Envia o código para o repositório.  
6. Faz o deploy no site.  

```console
git status
git add .
git commit -m "Mensagem de Alteração"
git pull
git push
mkdocs gh-deploy
```

## Links Úteis

Projeto criado com MkDocs
 - http://www.mkdocs.org/

Tema: Material
 - http://squidfunk.github.io/mkdocs-material/

Linguagem: Markdown
 - https://blog.ghost.org/markdown/
 - https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet
