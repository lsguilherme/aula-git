# GIT/GITHUB

## Comandos principais.
`git init` // iniciar um projeto.

`git add` // adicionar um projeto na branch. 
- ***git add .*** // para adicionar todas alterações;
- ***git add [nome do arquivo]*** // para adicionar um arquivo específico.

`git commit -m [mensagem]` // após o **git add** utilizar para deixar um comentário sobre o que foi alterado.
`git log` // visualizar todas alterações do projeto, possui todos código dos commit feitos.
`git show` // mostra detalhes de mudanças, **git show [código do commit]** mostra de um específico.
`git status` // verificar quais alterações de arquivos ainda não foram adicionadas na branch, também mostra em qual branch está sendo utilizada.
`git branch` // verifica todas branchs existentes.

- ***git branch [nome da branch]*** // criar uma nova ramificação na linha do tempo do arquivo.
- ***git branch -D [nome da branch]*** // deletar uma ramificação.
- ***git branch -M main*** // muda o nome da branch master para main.

`git checkout [nome da branch]` // entrar na ramificação *(branch)*.
`git merge [nome da branch]` // unir a ramificação na *branch* principal.
`git remote add origin [link github]` // adiciona em um repositório no github.
`git push -u origin main` // subir primeiro arquivo ao repositório do github.
- ***git push*** // caso o repositório já exista para subir basta o ***git push***  