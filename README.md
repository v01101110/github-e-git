# GitHub-e-Git
São ferramentas que auxiliam a equipe de desenvolvimento a controlar o versionamento do código e rastrear mudanças, possibilitandon assim que o trabalho no projeto flua sem problema, garantindo também a segurança através da encryptação e tracking de commits.
### Conceitos:
 **Git**
 
- Compartilhar o código do projeto com os integrantes da equipe;
- Realizar modificações no código;
- Manter todas as alterações que são feitas no código salvas, possibilitando que volte o projeto para o seu primeiro estado caso deseje;
- Os arquivos e históricos ficam no repositório como CVS ( Sistema de Versões Concorrentes ) e SVN ( Suberversion do Apache ).
  
 **GitHub**

 - A rede social dos desenvolvedores, pois outros programadores podem visualizar seu projeto e auxiliar em alguma operação no código, ou até mesmo na melhora de algum projeto;
 - Armazena os projetos nos repositórios;
 - Portifólio de muitos desenvolvedores.

**Gitflow**

- Auxilia na organização do versionamento de códigos;
- Gera branches de longa duração;
- Atribui especificações para cada branche e define quando elas vã interagir;
- Resolve problemas e bug no código de maneira instantânea;

# Como criar e configurar o GitHub
 Para utilizar a ferramenta é algo bem simples, basta acessar o site do GitHub (https://github.com) e criar uma conta, assim que adicionar suas informações receberá um email com um código para validar a abertura da conta, assim que o código for inserido já está tudo pronto para acessar seu GitHub.
## Instalação do Git

1. *Windows*
    - Baixe o instalador do Git para Windows a partir do site oficial: https://git-scm.com/download/win
    - Execute o arquivo .exe baixado e siga as instruções do assistente de instalação.

2. *Mac*
    - Se você tem o Homebrew instalado, basta abrir o Terminal e digitar: brew install git
    - Se não, você pode baixar o instalador do Git para Mac a partir do site oficial: https://git-scm.com/download/mac

3. *Linux*
    - Abra o Terminal e digite o seguinte comando para instalar o Git:
        - Para Debian/Ubuntu: sudo apt-get install git
        - Para Fedora: sudo dnf install git

## Configuração do Git

Após a instalação, você precisa configurar sua identidade no Git. Abra o Terminal (ou Git Bash no Windows) e digite os seguintes comandos:

- Configurar seu nome:
    
    git config --global user.name "Seu Nome"
    
- Configurar seu email:
    
    git config --global user.email "seuemail@exemplo.com"
    

Agora o Git está instalado e configurado em seu sistema. Você pode começar a usar o Git para controle de versão de seus projetos. Se você é novo no Git, eu recomendo que você leia a documentação oficial ou algum tutorial online para se familiarizar com os conceitos básicos do Git. 

## Criar um Repositório

Para criar um novo repositório, navegue até o diretório onde você deseja criar o repositório e execute o seguinte comando:

bash
git init


## Adicionar Arquivos

Para adicionar arquivos ao repositório, use o comando git add. Por exemplo, para adicionar um arquivo chamado exemplo.txt, você usaria:

bash
git add exemplo.txt


Para adicionar todos os arquivos no diretório atual, use:

bash
git add .


## Fazer Comentários (Commit)

Para salvar suas alterações, você precisa fazer um commit. Isso é feito com o comando git commit:

bash
git commit -m "Seu comentário aqui"


## Empurrar as Alterações (Push)

Para enviar suas alterações para um repositório remoto, use o comando git push:

bash
git push origin master


## Puxar as Alterações (Pull)

Para obter as alterações mais recentes de um repositório remoto, use o comando git pull:

bash
git pull origin master


## Criar Branch

Para criar uma nova branch, use o comando git branch:

bash
git branch nome_da_branch


Para mudar para essa branch, use o comando git checkout:

bash
git checkout nome_da_branch


## Reverter as Alterações

Para desfazer as alterações no seu repositório, você pode usar o comando git revert. Isso criará um novo commit que desfaz as alterações do commit especificado:

bash
git revert <commit_id>


## Consultar o Histórico de Mudanças

Para ver o histórico de commits, use o comando git log:

bash
git log
