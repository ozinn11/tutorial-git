165479
# Guia Básico para Criar Conta e Usar o GitHub

Este guia explica como criar uma conta no GitHub, como usar o GitHub, além dos comandos básicos do Git para começar a versionar e colaborar em projetos.

## 1. Como Criar uma Conta no GitHub

### Passos:

1. **Acessar o GitHub**:
   - Vá até o site [GitHub](https://github.com).

2. **Criar Conta**:
   - Clique em "Sign up" no canto superior direito.
   - Preencha as informações solicitadas:
     - **Username**: Escolha um nome de usuário único.
     - **Email**: Insira seu email.
     - **Password**: Crie uma senha segura.
   - Clique em "Create account" e siga os passos para finalizar a criação.

3. **Verificar seu E-mail**:
   - O GitHub vai enviar um link de verificação para o seu e-mail. Clique no link para confirmar sua conta.

## 2. Como Criar um Repositório no GitHub

Após criar sua conta, você pode começar a criar repositórios.

### Passos:

1. **Criar um Novo Repositório**:
   - Acesse a página principal do GitHub.
   - Clique no botão **"+"** no canto superior direito e selecione **"New repository"**.
   
2. **Configurar o Repositório**:
   - **Nome**: Dê um nome ao seu repositório.
   - **Descrição** (opcional): Escreva uma breve descrição.
   - **Público ou Privado**: Escolha se o repositório será público ou privado.
   - **Iniciar com README**: Marque esta opção para que o repositório seja inicializado com um arquivo `README.md`.
   - Clique em **"Create repository"**.

## 3. Como Usar o Git

O Git é uma ferramenta de controle de versão que permite gerenciar o histórico do seu projeto.

### 3.1 Instalando o Git

1. **Baixar Git**: Acesse o site [Git Downloads](https://git-scm.com/) e baixe a versão correspondente ao seu sistema operacional.
2. **Instalar Git**: Siga o assistente de instalação. No caso do Windows, marque a opção **"Git Bash Here"** durante a instalação para facilitar o uso do terminal.

### 3.2 Configurando o Git

Após instalar o Git, é importante configurar seu nome de usuário e e-mail. Execute os seguintes comandos no terminal:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@dominio.com"
