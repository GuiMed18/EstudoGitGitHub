# Git e GitHub
## Salvando repositórios

### Git Status

Exibe todas as informações do status do git, ex: Arquivos comitados, desconhecidos.

Pastas vazias não aparecem no status, apenas se houverem arquivos.

Para enviar um diretório vazio, basta criar o arquivo 
.gitkeep usando o comando touch

touch pasta_vazia/.gitkeep

### Git add Arquivo

Adiciona o arquivo na área de staging, aguardando para ser comitado

caso queira adicionar vários arquivos de uma vez, basta colocar . no lugar de arquivo

### Git commit -m "Mensagem"

Comita o arquivo e deixa o mesmo pronto para enviar ao github

### Git Log

Exibe o histórico do git, autor, data, branch e hash (identidade do commit)

### Git Reflog

Exibe o histórico de todas as ações feitas no git

### Git Ignore

Para que o git não considere alguns arquivos, é necessário criar o arquivo .gitignore

Para criar, ir pelo bash e executar o comando

echo arquivo > .gitignore

O que estiver aqui, não será considerado

Caso queira esvaziar, só dar o echo em o arquivo






