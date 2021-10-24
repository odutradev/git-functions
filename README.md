# Git e GitHub 


## Nesse repositorio irei colocar alguns comandos de suas funções do famosos **GIT**, tudo em português para um melhor aprendizado.




[git website](https://git-scm.com/)

[git download](https://git-scm.com/downloads)

[git documentation](https://git-scm.com/docs)


#### Fazendo login com git 
~~~javascript
$ git login 
~~~

#### Criando um repositorio 
~~~javascript
$ git init  
~~~

#### Adicionando ou removendo um arquivo do movitoramento do git 
~~~javascript
sintaxe: git [ add / remove ] [ arquivo / -A ] //ao usar -A adiciona todos os arquivos no monitoramento 

$ git add index.js
$ git remove main.js
$ git add -A
~~~

#### Configurando algumas informações sobre o usuario
~~~javascript
$ git config --global user.name "DARKnx" //setando nome do usuario
$ git config --global user.email "example@gmail.com" //setando email do usuario
$ git config --global core.editor "Visual Studio" //setando editor
~~~

#### Puxando informações do usuario 
~~~javascript
$ git config --list //puxando todas infomações
$ git config user.email //puxando uma informação especifica
~~~

#### Verificando status do projeto
~~~javascript
$ git status
~~~

#### Realizando um commit 
~~~javascript
sintaxe: git commit [ -m / -am ] "commit message"

$ git commit -m "Adicionando arquivo config.json"
$ git commit -am "Adicionando arquivo README.md"
~~~

#### Voltando para algum commit 
~~~javascript
sintaxe: $ git reset [ --soft / --mixed / --hard ] <commitID>

$ git reset --soft hG7la2k //anula todos os commits feitos depois de hG7la2k 
$ git reset --mixed jh7g89L // anula todos commits e arquivos adicionados depois de jh7g89L
$ git reset --hard kjsd83y //Apaga todas modificações feitas depois de kjsd83y
~~~

#### Vendo alterações feitas nos ultimos commits 
~~~javascript
$ git log 
~~~

#### Verificando branchs ativos
~~~javascript
$ git branch 
~~~
#### Criando um novo branch
~~~javascript
sintaxe: git branch <name>

$ git branch equipeOne
~~~

#### Mudando de um branch para outro
~~~javascript
sintaxe: git checkout <name>

$ git checkout equipeOne
~~~

#### Verificando alterações feitas apartir do ultimo commit 
~~~javascript
$ git diff //mostra todas as alterações feitas
$ git diff --name-only //mostra o nome de todos os arquivos que foram alterados
$ git diff index.js //mostra as alterações de um arquivo especifico 
~~~

#### 
~~~javascript

~~~




```
Copyright © 2021 DARKnx
```
