# Git_GitHub
Neste tutorial, aprenderemos o básico do Git e GitHub, o sistema de controle de versão mais popular e plataforma de hospedagem para desenvolvimento de software.
# **Introdução ao Git**

Git é um sistema de controle de versão distribuído criado por Linus Torvalds em 2005, inicialmente para gerenciar o código do kernel do Linux. Ele permite que você acompanhe as alterações feitas em seu código, colabore com outras pessoas e desfaça as alterações, se necessário.

## **Instalando o Git**

Para instalar o Git no seu computador, siga estas etapas:

1. Acesse o site do Git ( **[https://git-scm.com/downloads](https://git-scm.com/downloads)**
    
    ).
    
2. Selecione a versão apropriada para o seu sistema operacional e baixe o instalador.
3. Execute o instalador e siga as instruções.

## **Configurando o Git**

Depois de instalar o Git, você precisa configurá-lo com seu nome de usuário e e-mail. Abra seu terminal ou Git Bash e digite os seguintes comandos:

```
arduinoCopiar código
$ git config --global user.name "Your Name"
$ git config --global user.email "youremail@example.com"

```

## **Criando um repositório**

Para criar um novo repositório no Git, siga estas etapas:

1. Abra seu terminal ou Git Bash.
2. Navegue até o diretório onde deseja criar o repositório.
3. Digite o seguinte comando:**`git init`**
4. Seu repositório está criado!

## **Fazendo Mudanças e Comprometendo**

Para fazer alterações em seu código e enviá-las ao seu repositório, siga estas etapas:

1. Abra seu terminal ou Git Bash.
2. Navegue até seu repositório.
3. Faça alterações no seu código.
4. Digite o seguinte comando: **`git add .`**
    
    (o ponto é um curinga que adiciona todos os arquivos no diretório atual e seus subdiretórios)
    
5. Digite o seguinte comando:**`git commit -m "Your commit message here"`**
6. Suas alterações agora estão confirmadas em seu repositório!

## **Empurrando e puxando**

Para enviar suas alterações para um repositório remoto (como o GitHub), siga estas etapas:

1. Crie um novo repositório no GitHub.
2. Copie a URL do seu repositório remoto.
3. Abra seu terminal ou Git Bash.
4. Navegue até seu repositório.
5. Digite o seguinte comando:**`git remote add origin <remote repository URL>`**
6. Digite o seguinte comando:**`git push -u origin main`**
7. Suas alterações agora são enviadas para o repositório remoto!

Para extrair alterações de um repositório remoto, siga estas etapas:

1. Abra seu terminal ou Git Bash.
2. Navegue até seu repositório.
3. Digite o seguinte comando:**`git pull`**
4. As mudanças do repositório remoto agora são puxadas para o seu repositório local.

## **Solicitação de pull**

Depois de bifurcar um repositório e fazer alterações, você pode criar uma solicitação pull para solicitar ao proprietário do repositório original que mescle suas alterações no repositório dele. Para criar uma solicitação pull, siga estas etapas:

1. Acesse seu repositório no GitHub.
2. Clique no botão "Nova solicitação pull".
3. Dê um nome e uma descrição ao seu pull request.
4. Clique no botão "Criar pull request".
5. Aguarde até que o proprietário original do repositório revise e mescle suas alterações.

## **Conclusão**

Esta é apenas uma introdução ao Git e ao GitHub, mas com essas noções básicas, você pode começar a usar o controle de versão em seus projetos. Para mais informações, confira a documentação do Git e não se esqueça de dar um like neste post e se inscrever no meu canal!
