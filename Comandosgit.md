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

---

## git remote add 
>define o link do repositorio onde vai ser enviado os arquivos

`git remote add + link do seu repositório`

**exemplo de comando :**

`git remote add https://github.com/kainnabw/uc10_documento`

---

## enviar arquivos para branch 
> esse comando envia arquivos para uma branch

`git push -u origin main`

esse comando envia arquivos para a branch, após o uso desse comando os arquivos aparecem no git hub

---

## Verificar o Status
> esse comando é utilizado para visualizar as condições do diretório de trabalho e da área de staging

`git status`

Ele permite que você veja quais alterações foram despreparadas, quais não foram e quais arquivos não estão sendo monitorados pelo Git.


---

## Criar uma Nova Branch
> esse comando é utilizado para criar uma nova branch

`git branch nome_da_branch`

Uma branch cria uma ramificação do código principal para que seja possível fazer alterações sem nenhum tipo de problema.

**imagem de uma branch :**

![image](https://github.com/kainnabw/uc10_Documentacao/assets/135454271/557bc13a-614e-4d74-8c13-cfef5f9ebcb5)

---


## Mudar para uma Branch Existente
> Esse comando é utilizado para mudar de branch

`git checkout nome_da_branch`

como visto no tópico acima, podem existir mais de uma branch além da branch main, então esse comando é utilizado para alternar de uma branch a outra

---

**Atualizar o Repositório Local com Alterações do Repositório Remoto**

> esse comando é utilizado para atualizar o repositorio local com alterações no repositório remoto

`git pull`

---

## Ignorar Arquivos

`Crie um arquivo .gitignore e liste os arquivos/diretórios a serem ignorados.`

---
