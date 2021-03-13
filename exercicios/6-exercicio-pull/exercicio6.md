### Atualizando seu repositório local
- Entrar no Git Bash dentro da pasta que deseja atualizar.
- `git remote -v`: verificar se o endereço remoto está apontando para o repositório remoto correto.
- `git checkout master`: voltando para branch `master`.
- `git pull origin master`: atualizando a branch `master` conforme endereço `origin`.
- Visualizar as atualizações no projeto abrindo-o no navegador.
- `git branch -d ex-aula-seuNome` ou `git branch -D ex-aula-seuNome`: deletando a sua branch localmente, pois suas alterações já foram unidas (**merged**) no repositório remoto.a
- `git remote prune origin`: Para saber quais branches no repositorio online foram apagadas.

**Extra**
- `git push origin branch --delete`: Para apagar uma branch no repositorio online.