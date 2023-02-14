# Repositório de estudo Git/GitHub

> Linha de comando Git

Clonar um repósitorio:

````
git clone "path do repositório"
````

> Executar os comandos abaixo na pasta clonada

Verificar o log:

````
git log ou git log --oneline (para estruturar linha a linha)
````

Verificar se ocorreram alterações nos arquivos do repositório:

````
git status
````

Trazer as alterações realizadas para o reposiótio local(sincrinizar):

````
git pull
````

Commit em todos os arquivos:

````
git commit . -m "mensagem de alteração"
````

Restore commit:

````
git restore --source "hash da modificação" .
````

> Branch

Criar uma nova branch:

````
git branch -b <nome-da-branch>
````

Trocar entre as branchs:

````
git switch
````

> Merge

Unificar os códigos - merge (estando na branch main):

````
git merge <nome-da-branch>
````







