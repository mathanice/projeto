# PUXANDO MODIFICAÇÕES DO REPOSITÓRIO

- Antes de começar o trabalho na sua branch atual, fazer um git pull para pegar as alterações de outros colaboradores

git pull {pegar atualizações do repositório remoto/online}

# CLONANDO PROJETO

git clone {fazer clone de um repositório}

# COMANDOS GERAIS

touch {criar arquivo}

mkdir {criar pasta ou diretorio}

ls {mostrar arquivos e pastas}

cd {Entrar em um arquivo ou pasta/ exemplo "cd projeto/"}

git checkout {Direcionar pra uma versão da branch ou commit}

# CRIANDO UMA BRANCH

git checkout -b {Cria uma branch e te direciona pra ela / git checkout -b pagina-home}

- Criar um nome de branch sem espaços, separando por "-"
- Usa git checkout para entrar ou sair da branch criada "git checkout pagina-home"

git branch {Verificar se criou uma branch}

git branch -D {Deletar branch}

# ADICIONAR ARQUIVOS MODIFICADOS OU CRIADOS NO CONTAINER

git add . {adicionar todos os arquivos ao container}

git add (nome do arquivo) {adicionar um arquivo}

## RETIRAR ARQUIVOS DO CONTAINER

git reset head {retirar aquivo do container}

# PROCESSO PARA A CRIAÇÃO DE COMMIT

## Verificar arquivos antes de commitar

- Antes de fazer o commit verificar as mudanças dos arquivos

git diff {mostrar as modificações e mudanças}

## Commit somente com arquivos modificados

git diff {mostrar as modificações antes de colocar no container}

git status {verificar arquivos}

git commit -am 'descrição da mudança' {Esta comando adiciona no container e faz o commit}

## Processo normal de commit

git status {verificar arquivos}

- Antes de fazer o commit verificar se é a branch correta para o que for fazer

git add (nome do arquivo) {adicionar um arquivo}

git commit -m {adicionar uma mudança e fazer um commit}

### Fazer um commit com uma descrição

git commit -m "Title" -m "Description" / exemplo: git commit -m "modificado arquivo" -m "arquivo modificado para atualizar informações"

- É o mesmo comando que você já conhece, mas com uma segunda parte para a descrição. Portanto, “-m ‘title'” permite que você escreva o título abreviado do commit, e “-m ‘description'” permite que você escreva a descrição se precisar fornecer mais detalhes.

## Verifica se o commit foi salvo e ver a lista de commit

git log --oneline {mostrar os commit's da branch atual}

git log --oneline --all {mostra todos os commits em todas as branch's}

# ENVIAR MODIFICAÇÕES PARA REPOSITÓRIO REMOTO

- Este comando só funciona na branch main ou em alguma branch que esteja no repositório remoto

git pull {pegar atualizações do repositório remoto/online}

git push {mandar os arquivos para o repositório online} (só funciona na branch main)
