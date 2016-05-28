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

crie um repositório no github sem o Readme.md

git remote add origin https://github.com/adrianoavelino/github-course.git

git remote - lista os diretórios remotos

git remote -v -lista os endereços do diretorio remoto

git push -u origin master - envia os seus arquivos para o github

git push origin master - para enviar as suas modificações ao github

git clone https://github.com/adrianoavelino/github-course.git - clona um repositorio para sua maquina local

Fazendo um fork - acesse a página que deseja contribuir realize um fork para seu repositorio do Github, clone do seu repositorio faça as alterações localmente, envie as alterações para o seu repositório e depois envie um pull request para o projeto contribuido, onde será analisado e talvez aceito.










