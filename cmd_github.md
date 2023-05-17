Funçoes CMD GITHUB:

- git init -> comando que inicializa e cria o repositorio é o primeiro comando a ser dado
- git help ->
- git status -> Show the working tree status
- git add -A -> Add file contents to the index
- git commit -m "Primeiro Commit" ->  Record changes to the repository
- git log -> Show commit logs
- git branch -> List, create, or delete branches
- git reset --hard 3afa558d68823ca2307a08ddb47999c6392fdd54 -> Reset current HEAD to the specified state
- git checkout "nome do branch" ->Troca de branch colocando o nome do branch pretendido 
    * Comando para voltar os arquivos na versão anterior ou um arquivo a escolher (* git checkout HEAD -- nome do arquivo)
- gif diff -> Trás as modificações feitas nos arquivos antes de commitar - Show changes between commits, commit and working tree, etc -.
    * gif diff --name only -> irá trazer somente o nome dos arquivos alterados
- git push -> Para enviar na nuvem
    * git push origin nome do branch - origin e o local que determinamos e nome de qual branch iremos enviar
    * git push origin :(nome do branch) -> exclui o branch escolhido do remoto
    * git branch -D (nome do branch) -> exclui o branch escolhido do local - tem que sair do branch na raiz do cmd para que esta operação funcione.
- git revert - recupera as alterações efetuadas
    * git revert --no-edit (+o codigo do comite que quer se reverter) neste comando vc reverte exatamente o commit que quis reverter.
 