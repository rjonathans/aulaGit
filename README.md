# aulaGit
Aula Git with Fronthendy

Pra que serve o GITHUB?

O GitHub é um repositório WEB.

Qual a diferença entre GITHUB e o GIT e GITBASH?

GIT HUB --Pplatarforma online - repositórios WEB - A rede social dos desenvolvedores.
GIT -- Software de versionamento. (gitforwindows)
GIT BASH -- É apenas o Repositório onde nós colocamos os comandos.

existem varias formas de abrir o GITBASH.
1) botão direito do mouse dentro da PASTA que vc criou o repositório LOCAL.
2) 

Precisamos entender antes de executar os comandos para onde que enviamos os códigos.

VOCÊ ------------  OUTRO DESENVOLVEDOR
       \              /
        \            /
         \          /
          \        /
         repositorio web - nuvem (GITHUB/GITLAB/GITBUCKET) 

Imagine que vc criou seu codigo e quer compartilhar com outro desenvolvedor

Você envia o código que esta no seu computador para o repositorio WEB, e seu colega consegue copiar o clonar o código via WEB.

Comandos do BASH

Navegar entre pastas

$ pwd  |  mostra sua localização nas pastas.
$ cd .. | voltar uma pasta (cd espaço ponto ponto)
$ cd | nomeDapasta  -  entrar em uma pasta
$ ls | (equivalente ao dir no CMD)ista todos os arquivos da pasta
$ ls -la |  monstra mais informações sobre cada arquivo
$ mkdir nomeDapasta |  criar uma nova pasta 
$ touch primeiro_Arquivo.txt
$ rm nome_arquivo  |  excluir
$ rm -rf nome_da_pasta  |  excluir sem perguntar
$ mv nome_arquivo  |  mover arquivo
$ clear  | limpa a tela (nao exclui)

Vamos começar

$ git init   | criar o arquivo que vai colocar no git
$ git remote add origin  endereço_do_seu_repositório (https://github.com/rjonathans/aulaGit/)  |  adiciona o repositorio
$ git remote  | se funcionou vai aparerer Origin
$ git remote get-url origin  |  

imagine uma caixa Stage é nosso repositorio remoto
depois de *colocar os itens eu tenho que por etiqueta nessa caixa
depois eu envio para a nuvem.

$ git Status   |   
$ git add primeiro_arquivo.txt  |  coloca arquivo na caixa
$ git commit -m "criando meu primeiro arquivo"  |  coloca a etiqueta na caixa, o que esta acontecendo nesse commit

nesse momento ele vai pedir uma auttenticação caso vc ainda nao tenha

$ git config --global user.name "Robson Jonathan"
$ git config --global user.email rjonath@live.com

agora enviamos para nuvem
na primeira vez precisamos escrever assim:
$ git push -u origin master


