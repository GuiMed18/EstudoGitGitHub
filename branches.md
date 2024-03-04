# Git e GitHub
## Trabalhando com Branches

É importante pesquisar sobre convenções para nomear as branches

### Para criar uma nova branch

git checkout -b nomebranch

### Para alternar entre as main

git checkout nomebranch

### Listar o último commit de cada branch

git branch -v

### Para mesclar (Unir as branches)

git merge nomebranchcriada

### Para listar as branchs criadas

git branch

### Para excluir a branch

Quando não for mais utilizar ou já tiver mesclado

git branch -d nomebranchcriada

## Conflitos que podem acontecer

### Conflito de merge

Ex: Duas pessoas mexem na mesma linha, mesma branch e enviam ao gitHub, ele não vai entender qual deve manter

Ao dar push, ele vai dar erro, se der pull, ele vai puxar as duas alterações no mesmo arquivo para decidir qual deve ser mantido.

Após escolher, basta dar add, commit e push.

### Comandos Úteis

#### Git Fetch e Git Diff

Baixam os arquivos da branch remota sem mesclar com a branch local.

#### git clone URL --branch nome_branch --single-branch

Clonar apenas uma branch específica de um repositório

Se não passar o nome da branch, ele vai puxar a principal

#### git stash

Arquiva as modificações que ainda não foram adicionadas.

git stash list 

Retorna os arquivados

git stash pop 

Trazer as alterações arquivadas e sobrescrever as atuais

git stash apply

Desarquivar as alterações


