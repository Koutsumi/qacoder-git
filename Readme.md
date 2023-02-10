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
