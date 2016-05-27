#Git e GitHub para Iniciantes - Willian Justen

`git show 1bdaa65347430f5ca10c5354a6b10c35cfd71a76`

git log

git log --decorate

git log --author "adriano"

git shortlog

git shortlog -sn

git log --graph

git log show 1bdaa65347430f5ca10c5354a6b10c35cfd71a76

git difff - visualiza as modificações antes de commitar

git diff --name-only - utilizado para ver somente o nome dos arquivos modificados

git commit -am "mensagem" - utilizado para adicionar e comiitar modificação de um arquivo já commitado com um único commando

git checkout nomdedoarquivo.txt - remove as alterações do arquivo no estado modificado

git reset HEAD nomdedoarquivo.txt - remove o arquivo do estado stage (quando foi adicionado), voltando ao estado modificado

git reset --soft 7c38e19e0c7a62451908ffb3e44b094653be23ef - remove o commit do log e volta o arquivo para o estado stage

git reset --mixed 7c38e19e0c7a62451908ffb3e44b094653be23ef - remove o commit do log e volta o arquivo para o estado modificado

git reset --hard 7c38e19e0c7a62451908ffb3e44b094653be23ef - remove o commit do log e remove todas as modificações
