# Projeto-Git-Luan
Tutorial de Git e GitHub

# Teste Prático de Git e GitHub

Este projeto foi criado com objetivo de praticar os principais comandos e
fluxos de trabalho com Git e GitHub

## Objetivo do teste

- Aprender a inicializar repositório (`git init`)
- Trabalhar com brances (`git checkout`)
- Realizar merges e simular conflitos
- Praticar push, pull, clone e reset
- Usar GitGub para gerenciar versões e pull request

## O que foi realizado

- Criação de arquivos fictícios (`texto_1.txt`, `texto_2.txt`,
sistemadelogin.txt', etc.)
- Simulação de merge e resolução de conflitos
- Teste com comandos como:
 - `git init`, `git add`, `git commit`
 - `git branch`,`git checkout`, `git merge`
 - `git push`, `git pull`, `git clone`, `git reset`
 - Pull request no GitHub

## Aprendizados

- Entendimento da importância dos branches para desenvolvimento em paralelo
- Compreensão do ciclo `add -> commit -> push -> pull`
- Experiência com resolução de conflitos simples
- Familiarização com a interface do GitHub

## Problemas encontrados

Durante o uso do Git, enfrentei o seguinte erro ao tentar dar push:

> Updates were rejected because the remote contains work that you do not have locally...

Esse problema occoreu porque o repositório no GitHub já possuía um `README.md`
(criado durante a criação inicial do repositório), mas meu repositório local
ainda não tinha essa versão sincronizada. Tentei adicionar meu próprio
`README.md` local utilizando `touch`, mas falhou ao tentar fazer o push, o Git
bloqueou a operação para eviar sobrescrever o conteúdo remoto.

Para resolver, executei:

`git pull origin main`
`git push`


## Observações

- Este projeto contém arquivos fictícios apenas para testes de versionamento
- Não representa um projeto funcional de software
