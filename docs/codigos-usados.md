# Codigos usados códigos

## Cotrole de versão

`git init` - Inicia o git em um arquivo

`git add` - Adiciona os arquivos no controlador de versão

`git commit -m` - Comenta as modificações antes de dar um `push`

`git pull` - Recebe atualização da branch atual direto do servidor

`git merge <branch>` - Junta os códigos de diferentes _branches_. Primeiramente você precisarar ir na _branch_ principal, efetuar o `git pull` para receber atualzação da branch na nuvem, logo em seguida usar o `git merge`.

`git remote add origin "<url>"` - Repositório em nuvem onde serão mandado as alterações

`git push` - envia o _commit_ para a nuvem

`git status` - Mostra o status dos arquivos

`git reflog` - Lista o histórico de versões/commits

`git reset --hard <codigo da versão>` - Altera a versão

`git checkout <branch>` - Altera a _branch_ que está sendo trabalhada localmente

`git checkout -b <brench nova> <brench baseada>` - Esse comando serve para criar uma branch com em outra com uma linha de código

`git push --set-upstream origin <branch>` - Selecionar a branch onde se vai fazer o push
