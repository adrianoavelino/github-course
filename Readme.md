#Git e GitHub para Iniciantes - Willian Justen

git config --global user.name "Adriano Avelino" - configura o usuário do git

git config --global user.email "adriano-st777@hotmail.com" - conffigura o e-mail do git

git config --global core.editor vim - configura o editor padrão

git config user.name - exibe o usuário configurado

git config user.email - exibe o e-mail conigurado

git config --list - lista as configurações

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

git checkout -b testing - cria um novo branch e entra dentro dele

git branch - lista os branchs existentes

git checkout master - muda de brannch (o exeplo muda para o branch master)

git checkout -D testing - deleta o branch testing

git merge modificacao - junta os logs do branch modificacao, mas cria um commit para juntar o conflito nos logs (mantem a ordem cronoligica)

git rebase modificacao - junta os logs do branch modificado, porém lança os commits do branch modificacao acima dos commits do branch atual (perde a sequência lógica)

git stash - esconde as modificações para serem usadas futuramente

git stash apply - aplica as modificações escondidas

git stash list - lista os stashs

git stash clear - limpa os stashs existentes

git config --global alias.s status - criar um alias (atalho) chamado s

git tag -a 1.0.0 -m "readme finalizado" - cria uma nova tag

git push origin master --tags - envia para o repositorio remoto as tags criadas

git tag - lista todas as tags criadas

git revert 4e3938f2171e01897a04a0c14005fd0e3a05a394 - reverte as modificações sem perder os commits anteriores, utilizado por exemplo quando o código quebra em produção e deseja verificar futuramente o motivo do erro

git tag -d 1.0.0 - deleta a tag localmente

git push origin :1.0.0 - deleta a tag do diretorio remoto (o mesmo poderia ser feito com a deleção de branches remotos)






















