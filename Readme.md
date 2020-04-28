# Git Learning

### pull vs fetch --all
pull會把遠端資源拉下來並且merge到本地端的資源；
fetch --all只會將資源拉下來，不會merge，所以本地端資源不改變，要更新成遠端資源，
需使用git merge origin/develop or git reset --hard origin/develop

### rebase vs rebase -i
rebase -i 是用來rebase過去的commit；rebase 則是更換新的基準branch。
