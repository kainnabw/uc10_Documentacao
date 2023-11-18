# Guia de Comandos do Git

Este guia fornece uma visão geral dos comandos básicos do Git para gerenciamento de versionamento de código.

## Configuração Inicial

### Configurar o Nome de Usuário
**Define o nome de usuário a ser associado aos commits feitos no repositório.**
- git config --global user.name "Seu Nome"

**Configurar o Email**
- git config --global user.email "seuemail@example.com"

**para verificar ambos**
- git config --global --list
- git config user.name
- git config user.email



**Iniciar um Repositório**
- git init

**Adicionar Arquivos ao Stage**
- git add nome_do_arquivo

**Confirmar Alterações**
- git commit -m "Mensagem do Commit"

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
