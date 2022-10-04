Apresentando os principais comandos no GIT

Premissas básicas

realizar o downdload do git e do vs code ou um editor que você goste.

Links importantes:

download do git
https://git-scm.com/download/win

download do vs code
https://code.visualstudio.com/docs/?dv=win

observação: você poderá utilizar o editor de texto de sua preferência.

documentação do git
See http://git-scm.com/ for further details about Git including ports to other operating systems. Git for Windows is hosted at https://gitforwindows.org/.

Vamos lá, dando os seus primeiros comandos

//verificar a versão.

git --version

//criar repositório.

git init

//deixar o arquivo na espera para o commit.

git add nomedoarquivo.extensão

//listando para a área de commit.

git status

//dando o commit

git commit -m "coloque aqui suas considerações sobre o arquivo, pode ser o titulo do arquivo ou assunto"

//finalizando o commit, repita o comando git status para verificar se o commit deu boa.

//algumas empresas utilizam a branch principal do GIT com o nome de (master) e outras (main), então verifique com sua equipe de desenvolivimento qual é o padrão atual, caso tenha a necessidade de alterar o nome da sua branch principal basta utilizar o seguinte comando. 

git branch -M "main" 

//caso tenha a necessidade de retornar para (master) refaça o comando abaixo.

git branch -M "master"

//esse comando é apenas na primieira vez para poder atrelar seu repositório local com o repositório remoto.

git remote add origin https://github.com/Eng-Robson/Projetosgit.git

//Esse comando sobe os arquivos modificados para o git.

git push -u origin main

//Agora de posse dos principais comandos, essa é a ordem dos comandos ao realizar modificações de versionamento ou novos arquivos.

//Primeiro.

git add nomedoarquivo.extensãodoarquivo //exemplo git add readme.md. 

//segundo.

git status

//terceiro.

git commit -m "considerações sobre o versionamento"

//quarto e último comando, esse serve para subir o arquivo com a nova versão.

git push -u origin main

ou 

git push -u origin master

========================================================

bbbbbbbbbbbbbbbbbbbb............iiiiiiiiiiii
bbbbb.....bbbbbbbbbbbbbb........iiiiiiiiiiii
bbbbb..........bbbbbbbbbbb......iiiiiiiiiiii
bbbbb..........bbbbbbbbbbbb.................
bbbbb...........bbbbbbbbbb..................
bbbbb........bbbbbbbbbbb........iiiiiiiiiiii
bbbbb...bbbbbbbbbbbbb...........iiiiiiiiiiii
bbbbbbbbbbbbbbbbbb..............iiiiiiiiiiii                    
bbbbbbbbbbbbbbbbbbbbb...........iiiiiiiiiiii                              
bbbbb.....bbbbbbbbbbbbbbb.......iiiiiiiiiiii
bbbbb..........bbbbbbbbbbb......iiiiiiiiiiii
bbbbb..........bbbbbbbbbbb......iiiiiiiiiiii
bbbbb...........bbbbbbbbbb......iiiiiiiiiiii
bbbbb........bbbbbbbbbbb........iiiiiiiiiiii
bbbbb...bbbbbbbbbbbbbb..........iiiiiiiiiiii
bbbbbbbbbbbbbbbbbb..............iiiiiiiiiiii
BY: ROBSON SOUZA
=========================================================