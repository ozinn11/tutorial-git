# tutorial-git


1---Criando uma Conta no GitHub

Acesse GitHub e clique em Sign up.

Preencha nome, e-mail e senha.

Confirme a conta pelo e-mail.


2 Baixar e instalar: git-scm.com

Configurar usuário:

*terminal:*

git config --global user.name "Seu Nome"

git config --global user.email "seu-email@example.com"


3 Criando um Repositório

*pelo terminal:*

git init  echo "# Meu Projeto" > README.md  
git add README.md  
git commit -m "Adicionando README"

4 Conectando ao GitHub e Enviando Arquivos

git remote add origin https://github.com/seu-usuario/seu-repo.git  
git push -u origin main

5 Comandos Básicos do Git

*terminal:*

git status           
git add .            
git commit -m "msg"   
git push origin main 
git pull origin main   
git log --oneline    
