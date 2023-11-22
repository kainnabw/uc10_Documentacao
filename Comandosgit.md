# Guia de Comandos do Git

Este guia fornece uma visão geral dos comandos básicos do Git para gerenciamento de versionamento de código.

---

## Configuração Inicial
**é recomendado verificar e fazer essa configuração todo dia antes de realmente começar a uitlizar o git**

` git config --global --list` (utilizado para verificar o nome e email)

`git config user.name` (utilizado para modificar o nome)

`git config user.emai` (utilizado para modificar o email)

---

## Iniciar um Repositório
> Esse comando é utilizado para inicializar um repositorio

`git init`

git init cria um novo repositório do Git. Ele pode ser usado para converter um projeto existente e não versionado em um repositório do Git ou inicializar um novo repositório vazio.

---

## Adicionar Arquivos ao Stage
> O git add é usado para adicionar arquivos novos e modificados mas não os deletados.

`git add nome_do_arquivo`

Esse comando realiza a inclusão ou modificação do arquivo no diretório local, preparando ele para ser entregue ao servidor remoto
  
--- 

## Confirmar Alterações
> esse comando é utilizado para confirmar alterações 

`git commit -m "Mensagem do Commit"`

O Git commit permite que você crie um commit, ou seja, você consegue guardar o estado do seu repositório naquele momento.
Você consegue incluir uma mensagem no seu commit.

**Verificar o Status**
- git status

**Criar uma Nova Branch**
- git branch nome_da_branch

**Mudar para uma Branch Existente**
- git checkout nome_da_branch

**Atualizar o Repositório Local com Alterações do Repositório Remoto**
- git pull

**Ignorar Arquivos**
- Crie um arquivo .gitignore e liste os arquivos/diretórios a serem ignorados.
