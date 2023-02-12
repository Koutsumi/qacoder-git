## Comandos no GIT
### PUSH
    git push origin main
Envia o commit para a branch main

### CLONE
    git clone git@github.com:Koutsumi/qacoder-git.git
Clona um repositório (o link deve ser substituído pelo do projeto desejado)

### PULL
    git pull
Puxa as alterações presentes na branch

### BRANCH
'Cópia' do código que permite a realização de alterações sem comprometer a versão estável 
#### Lista de branch
    git branch
#### Criar branch
    git branch nomeDaBranch
    git checkout -B nomeDaBranch
Esse último cria e acessa a branch

#### Acessar uma branch
    git checkout nomeDaBranch

#### Deletar branch
    git branch -D nomeDaBranch
OBS.: Não é possível deletar a branch que está acessada no momento

### MERGE
    git merge nomeDaGranch
Adiciona uma branch em outra branch

### REBASE
    git rebase master/main
Move toda uma branch para outro ponto da árvore

### GITIGNORE
Ignora arquivos que não devem ser versionados 

### STASH
    git stash
salva as alterações realizadas separadamente antes do add/commit

    git stash apply
Pega o ultimo statsh salvo e aplica na branch e mantem o stash na branch

    git stash save nomeDoStash
Da um nome ao stash

    git stash pop
Pega o ultimo stash e remove ele da lista

    git stash apply stash@{INDICE}
Pega um stash especifico