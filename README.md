![git](https://cdn.iconscout.com/icon/free/png-512/free-git-logo-icon-download-in-svg-png-gif-file-formats--wordmark-programming-langugae-language-pack-logos-icons-1175220.png?f=webp&w=256)
>  ## :octocat: Índice  

1. Conceitos
  - [O que é o Git](https://pt.wikipedia.org/wiki/Git) 
  - [Os três estados](https://git-scm.com/book/pt-br/v1/Primeiros-passos-No%C3%A7%C3%B5es-B%C3%A1sicas-de-Git#Os-Tr%C3%AAs-Estados)
   - [O que é um Branch](https://git-scm.com/book/pt-br/v1/Ramifica%C3%A7%C3%A3o-Branching-no-Git-O-que-%C3%A9-um-Branch)
2. [Instalando o Git](https://git-scm.com/book/pt-br/v1/Primeiros-passos-Instalando-Git)
3. [Configuração inicial do Git](https://git-scm.com/book/pt-br/v1/Primeiros-passos-Configura%C3%A7%C3%A3o-Inicial-do-Git)
5. [Comandos Básicos](https://github.com/paulo-souza/git-basico#comandos-básicos)
   - [Trabalhando com Tags](https://git-scm.com/book/pt-br/v1/Git-Essencial-Tagging)
   - [Colocando em Prática](https://try.github.io)
6. [Download do Git](https://github.com/paulo-souza/git-basico#download)
7. [Documentação](https://github.com/paulo-souza/git-basico#documentação-)

# Comandos Básicos

#### 1. Iniciando o Git no diretório corrente:
```console
git init
```

#### 2. Informação sobre o estado de arquivos e diretórios que estão sendo gerenciados pelo Git:
```console
git status
```

#### 3. Envio de arquivos e diretórios para staging area:
```console 
git add nome_do_meu_arquivo
  ou
git add .
```
#### 4. Envio de todos os arquivos da staging area para serem gerenciados pelo Git:
```console
git commit -m "Aqui eu escrevo a minha msg."
```

#### 5. Informações referente a modificações realizadas em arquivos ANTES de serem enviados para staging area:
```console
git diff
```
#### 6. Informações referente a modificações realizadas nos arquivos que ESTÃO na staging area:
```console
git diff --staged
```
#### 7. Informações detalhadas de todos os commits realizados:
```console
git log
```

#### 8. Informações SEM detalhes de todos os commits realizados:
```console
git log --pretty=oneline
```

#### 9. Edita o último commit realizado para que possa adicionar novos arquivos nele:
```console
git commit --amend -m "mensagem editada"
```
#### 10. Restauração de arquivo(s) para sua forma original:
```console
git checkout -- meu_arquivo
```
#### 11. Retirar um arquivo da staging area:
```console
git reset HEAD meu_arquivo
```
#### 12. Removendo um arquivo do Git:
```console
git rm meu_arquivo
```
#### 13. Lista as Tags criadas:
```console
git tag
```
#### 14. Criação de uma Tag para o atual ou último commit:
```console
git tag -a nome_da_tag -m "Mensagem de referência para a tag."
```
#### 15. Criação de uma Tag para um commit específico:
```console
git tag -a nome_da_tag chave_do_commit -m "Mensagem de referência para a tag."
```
#### 16. Acessar uma Tag ou Branch:
```console
git checkout nome_da_tag
          ou
git checkout nome_do_branch
```
#### 17. Remoção de uma Tag
```console
git tag -d nome_da_tag
```
#### 18. Listar os Branchs e mostra qual deles é o corrente:
```console
git branch
```
#### 19.  Criação de um Branch:
```console
git branch nome_do_branch
```
#### 20. Cria e troca para um novo Branch:
```console
git checkout -b novo_branch
```
#### 21. Remoção de um Branch:
```console
git branch -d nome_do_branch
```
#### 22. Realiza modificações feitas de um outro Branch para o CORRENTE:
```console
git merge outro_branch
```
#### 23. Clonar arquivos e pastas em um servidor remoto para seu diretório corrente:
```console
git clone end_serv_remoto nome_p/_pasta
```
Obs.: O nome da pasta no comando acima é opcional. 
Caso não queira o git cria uma com o nome do diretório do servidor remoto que está sendo clonado.

#### 24. Listar servidores remotos que está sendo conectados:
```console
git remote -v
```
#### 25. Envio de arquivos e diretórios do Branch corrente para um servidor remoto:
```console
git push origin master
```
#### 26. Atualização de arquivos do servidor remoto com o Branch corrente:
```console
git pull origin master
```
Obs.: Nesse comando acima é feita uma mesclagem dos arquivos. 
Por isso recomenda-se a criação de um Branch separado. 



## Download
https://git-scm.com/download

## Documentação [![Inline docs](http://inch-ci.org/github/gorails/gorails.svg?branch=master)](https://git-scm.com/doc)
