# PUXANDO MODIFICAÇÕES DO REPOSITORIO REMOTO
- Antes de começar o trabalho na sua branch atual, fazer um git pull para pegar as alterações de outros colaboradores

git pull {pegar atualizações do repositorio remoto/online}

# CLONANDO PROJETO

git clone {fazer clone de um repositorio}

# COMANDOS GERAIS

touch {criar arquivo}

mkdir {criar pasta ou diretorio}

ls {mostrar arquivos e pastas}

cd {Entrar em um arquivo ou pasta/ exemplo "cd projeto/"}

git checkout {Direcionar pra uma versão da breanch ou commit}

# CRIANDO UMA BRANCH

git checkout -b {Cria uma branch e te direciona pra ela / git checkout -b pagina-home}
- Criar um nome de branch sem espaços, separando por "-"
- Usa git checkout para entrar ou sair da branch criada "Git chekout pagina-home"

git branch {Verificar se criou uma branch}

git branch -D {Deletar branch}

# ADICIONAR ARQUIVOS MODIFICADOS OU CRIADOS NO CONTENER

git add . {adicionar todos os arquivos ao contener}

git add (nome do arquivo) {adicionar um arquivo}

## RETIRAR ARQUIVOS DO CONTENER

git reset head {retirar aquivo do contener}

# PROCESSO PARA A CRIAÇÃO DE COMMIT
## Verificar arquivos antes de commitar
- Anter de fazer o commit verificar as mudanças dos arquivos 

git diff {mostrar as modificações e mudanças}

## Commit somente com arquivos modificados

git diff {mostrar as modificações antes de colocar no contener}

git status {verificar arquivos}

git commit -am 'descrição da mudança' {Esta comando adiciona no contener e faz o commit}

## Processo normal de commit

git status {verificar arquivos}
- Antes de fazer o commit verificar se é a branch correta para o que for fazer

git add (nome do arquivo) {adicionar um arquivo}

git commit -m {adicionar uma mudança e fazer um commit}

## Verificat se o commit foi salvo e ver a lista de commit

git log --oneline {mostrar os commit's da branch atual}

git log --oneline --all {mostra todos os commits em todas as branch's}

# ENVIAR MODIFICAÇÕES PARA REPOSITORIO REMOTO
- Este comando só funciona na branch main ou em alguma branch que esteja no repostorio remoto 

git pull {pegar atualizações do repositorio remoto/online}

git push {mandar os arquivos para o repositorio online} (só funciona na branch main)
