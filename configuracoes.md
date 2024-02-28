# Git e GitHub
## Configurando o Git

### Git config
Varíavel --global = Config de usuário
Variável --system = Config de sistema
Variável --local = Config do repositório

### Definir nome do user 

git config --global user.name "NomeUser"

#### Para verificar o nome registrado

git config --global user.name

### Definir o email do user

git config --global user.email guilhe1811@gmail.com

#### Para verificar o email registrado

git config --global user.email

### Para definir o nome padrão das branchs

git config --global init.defaultbranch NomeBranch

#### Para verificar a branch padrão

git config init.defaultbranch

### Para verificar todas as configurações

git config --list

(Caso haja a necessidade de ver apenas uma, colocar por exemplo --global antes do --list)
