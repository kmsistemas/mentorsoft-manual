# Manual MentorSoft

Manual de uso do sistema MentorSoft.


## Como desenvolver?

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
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
mkdocs serve
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
