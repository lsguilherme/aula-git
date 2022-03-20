# GIT/GITHUB

## Comandos principais.

### Iniciando projeto no Git.

* `git init` // iniciar um projeto.
* `git add` // adicionar um projeto na branch.
- ***git add .*** // para adicionar todas alterações;
- ***git add [nome do arquivo]*** // para adicionar um arquivo específico.
* `git commit -m [mensagem]` // após o **git add** utilizar para deixar um comentário sobre o que foi alterado.
* `git log` // visualizar todas alterações do projeto, possui todos código dos commit feitos.
* `git show` // mostra detalhes de mudanças, **git show [código do commit]** mostra de um específico.
- **git diff** funciona de forma semelhante.
* `git status` // verificar quais alterações de arquivos ainda não foram adicionadas na branch, também mostra em qual branch está sendo utilizada.
* `git branch` // verifica todas branchs existentes.
- ***git branch [nome da branch]*** // criar uma nova ramificação na linha do tempo do arquivo.
- ***git branch -D [nome da branch]*** // deletar uma ramificação.
- ***git branch -M main*** // muda o nome da branch master para main.
* `git checkout [nome da branch]` // muda de ramificação *(branch)*.
- ***git checkout -b [nome da branch]*** // cria uma nova branch e já entra nela.
- ***git checkout [código do commit] -- [nome do arquivo]*** // recupera o arquivo da linha do tempo daquele commit.
- ***git checkout -- [nome do arquivo]*** // recupera um arquivo deletado antes do commit.
* `git merge [nome da branch]` // unir a ramificação na *branch* principal.

### Subindo para o GitHub.

* `git remote add origin [link github]` // adiciona em um repositório no github.
* `git push -u origin main` // subir primeiro arquivo ao repositório do github.
- ***git push*** // caso o repositório já exista para subir basta o ***git push***.

### Pegando projeto do GitHub.

* `git clone [link]` // clonar um projeto ja criado.
* `git pull` // caso já tenha clonado o projeto, o git pull puxa atualizações do projeto.

## Comandos úteis do console para usar em conjunto com o Git.

* `ls` // visualizar os arquivos da pasta.
- ***ls -al*** // visualizar de uma forma melhor os arquivos da pasta.
* `cd` // acessar uma pasta.
* `touch [nome do arquivo].[formato do arquivo]` // cria um arquivo.
* `mkdir` // criar uma pasta.
* `clear` // limpar o console.
* `vim [nome do arquivo e formato]` // escrever no arquivo. 
- Para sair do **vim** basta clicar **ESC** e escrever **:wq**

## Links úteis sobre o Git.

[Git Prático - Roger Dudler](https://rogerdudler.github.io/git-guide/index.pt_BR.html)
[Guia para iniciantes - Rocketseat](https://www.youtube.com/watch?v=2alg7MQ6_sI)
[Iniciando no Git - Rocketseat](https://www.youtube.com/watch?v=MW7hrQe6aYo)
[Curso completo Git - Bóson Treinamento](https://www.youtube.com/watch?v=YnVnFanIAzU&list=PLucm8g_ezqNq0dOgug6paAkH0AQSJPlIe)