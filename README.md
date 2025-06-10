# Aprendendo Git

Um pouco sobre o básico de Git e GitHub

## Tabela de comandos e suas funções
|Comando|Função|
|--------|-------|
| ```git init```| Inicializa o repositório e seu versionamento|
| ```rm -rf .git```| Exclui o repositório e finaliza o versionamento da pasta|
| ```git clone [URL do repo.]```| Clona um repo. remoto no diretório local|
| ```git clone [URL do repo.] --branch <nome-da-branch> --single-branch```| Clona a única branch escolhida do repo. remoto|
|```git remote add origin```|Vincula um repo. local a um repo. remoto|
|```git status```|Mostra se há adds, commits ou pushs a serem feitos|
|```git log```|Lista informações sobre últimos commits ordenadamente (data, hash, mensagem...)|
|```git add [nome-do-arquivo ou --all]```|Prepara um arquivo e/ou suas alterações para serem commitados|
|```git commit -m "mensagem"```|Registra as alterações e cria uma nova versão do repositório|
|```git restore [nome-do-arquivo]```|Desfaz as últimas alterações feitas|
|```git push```|Envia as alterações do repo. local ao remoto|
|```git pull```|Envia as alterações do repo. remoto ao local|
|```git checkout -b [nome da nova branch]```|Cria uma nova branch|
|```git checkout [nome da branch]```|Troca para a branch escolhida|
|```git branch -v```|Lista o último commit (atual) de cada branch|
|```git branch -d```|Deleta a branch escolhida|

## Mais

### Documentações 
- [Git](https://git-scm.com/doc)
- [GitHub](https://docs.github.com/pt)
