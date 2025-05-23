# Comandos Git úteis para iniciantes

## Inicialização e configuração
- `git init`  
  Cria um novo repositório Git local.

- `git config --global user.name "Seu Nome"`  
  Configura seu nome para os commits.

- `git config --global user.email "seu@email.com"`  
  Configura seu e-mail para os commits.

## Clonagem
- `git clone <url>`  
  Clona um repositório remoto para sua máquina.

## Verificação do estado do repositório
- `git status`  
  Mostra o status atual dos arquivos (modificados, não rastreados, etc).

- `git log`  
  Exibe o histórico de commits.

## Controle de versões
- `git add <arquivo>`  
  Adiciona arquivo(s) para serem incluídos no próximo commit.

- `git add .`  
  Adiciona todos os arquivos modificados e novos.

- `git commit -m "mensagem"`  
  Cria um commit com uma mensagem descritiva.

- `git commit -am "mensagem"`  
  Adiciona e commita arquivos modificados (não adiciona arquivos novos).

## Trabalhando com branches
- `git branch`  
  Lista as branches locais.

- `git branch <nome-branch>`  
  Cria uma nova branch.

- `git checkout <nome-branch>`  
  Muda para a branch especificada.

- `git checkout -b <nome-branch>`  
  Cria e muda para uma nova branch.

- `git merge <nome-branch>`  
  Mescla a branch especificada na branch atual.

## Sincronização com repositório remoto
- `git remote -v`  
  Lista os repositórios remotos configurados.

- `git remote add origin <url>`  
  Adiciona um repositório remoto chamado origin.

- `git push -u origin <branch>`  
  Envia commits da branch para o remoto, definindo upstream.

- `git push`  
  Envia commits para o remoto na branch atual.

- `git pull`  
  Puxa alterações do repositório remoto e faz merge.

## Outros comandos úteis
- `git diff`  
  Mostra diferenças entre arquivos modificados e último commit.

- `git reset <arquivo>`  
  Remove arquivo da área de staging (undo do `git add`).

- `git rm <arquivo>`  
  Remove arquivo do diretório e do controle de versão.

- `git stash`  
  Salva temporariamente mudanças que ainda não quer commitar.

- `git stash pop`  
  Recupera as mudanças salvas no stash.

