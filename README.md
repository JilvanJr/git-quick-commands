# Git Quick Commands

## Criando um repositório remoto

1. Criar um repositório no [GitHub](https://github.com);
1. Criar um diretório no seu computador e rodar o comando `$ git init`;
1. Copiar os comandos do bloco **"…or create a new repository on the command line"**;
1. No browser recarregue a página do repositório

## Comandos

Os comandos devem ser executados no diretório do projeto.

```bash
# verificando arquivos modificados
$ git status

# adicionando um arquivo
$ git add NOME_DO_ARQUIVO
$ git status

# incluindo um comentário no arquivo recem adicionado
$ git commit -m "update README.md"
$ git status

# enviar as modificações para o repositório remoto
$ git push origin master

# baixar arquivos do repositório remoto
$ git pull origin master

- Comandos para clonar projeto

# Mostra qual página se encontra
$ pwd

# Entra na página desejada para baixar o projeto
$ cd Desktop/ 

# Clonar projeto
$ git clone https://github.com/JilvanJr/git-quick-commands.git

# Arquivo é baixado

```