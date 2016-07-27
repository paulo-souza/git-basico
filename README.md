#![Git logo] (http://www.ultraedit.com/assets/images/powertips/ues/git/git-icon.png)

#Comandos Básicos

####1. Iniciar o git no diretório corrente:
```console
git init
```

####2. Informação sobre o estado de arquivos e diretórios que estão sendo gerenciados pelo git:
```console
git status
```

####3. Envio de arquivos e diretórios para staging area* :
```console 
git add nome_do_meu_arquivo
  ou
git add .
```
####4. Envio de todos os arquivos da staging area para serem gerenciados pelo git:
```console
git commit -m "Aqui eu escrevo a minha msg."
```

####5. Informações referente a modificações realizadas em arquivos ANTES de serem enviados para staging area:
```console
git diff
```
####6. Informações referente a modificações realizadas nos arquivos que ESTÃO na staging area:
```console
git diff --staged
```
####7. Informações detalhadas de todos os commits realizados:
```console
git log
```

####8. Informações SEM detalhes de todos os commits realizados:
```console
git log --pretty=oneline
```

####9. Edita o último commit realizado para que possa adicionar novos arquivos nele:
```console
git commit --amend -m "mensagem editada"
```
####10. Restauração de arquivo(s) para sua forma original:
```console
git checkout -- meu_arquivo
```
####11. Retirar um arquivo da staging area:
```console
git reset HEAD meu_arquivo
```
####12. Remoção de um arquivo do sistema de gerenciamento de versão(git):
```console
git rm meu_arquivo
```
####13. Lista as tags* criadas:
```console
git tag
```
####14. Criação de uma tag para o atual ou último commit:
```console
git tag -a nome_da_tag -m "Mensagem de referência para a tag."
```
####15. Criação de uma tag para um commits específico:
```console
git tag -a nome_da_tag chave_do_commit -m "Mensagem de referência para a tag."
```
16. Acessar uma tag ou branch*:
```console
git checkout nome_da_tag
          ou
git checkout nome_do_branch
```
####17. Remoção de uma tag
```console
git tag -d nome_da_tag
```
####18. Lista os branchs e mostra qual deles é o corrente:
```console
git branch
```
####19.  Criação de um branch:
```console
git branch nome_do_branch
```
####20. Criação e mudança de branch:
```console
git branch -b nome_do_branch
```
####21. Remoção de um branch:
```console
git branch -d nome_do_branch
```
####22. Realiza modificações feitas em um outro branch para o branch CORRENTE:
```console
git merge outro_branch
```
####23. Clonar arquivos e pastas em um servidor remoto para seu diretório corrente:
```console
git clone end_serv_remoto nome_p/_pasta
```
Obs.: O nome da pasta no comando acima é opcional. 
Caso não queira o git cria uma com o nome do diretório do servidor remoto que está sendo clonado.

####24. Listar servidores remotos que está sendo conectados:
```console
git remote -v
```
####25. Envio de arquivos e diretórios do branch corrente para um servidor remoto:
```console
git push origin master
```
####26. Atualização de arquivos do servidor remoto com o branch corrente:
```console
git pull origin master
```
Obs.: Nesse comando acima é feita uma mesclagem dos arquivos

####27. Downloads de arquivos do servidor remoto para o branch corrente:
```console
git fetch origin master
```
Obs.: Nesse comando acima é feito somente o download dos arquivos sem mesclar.

##Downloads
https://git-scm.com/download

## Documentação [![Inline docs](http://inch-ci.org/github/gorails/gorails.svg?branch=master)](https://git-scm.com/doc)
