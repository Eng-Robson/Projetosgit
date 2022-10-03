Esse arquivo é sobre como utilizar o GIT apresentando os principais comandos no GIT

Links importantes:

download do git
https://git-scm.com/download/win

download do vs code

documentação do git
See http://git-scm.com/ for further details about Git including ports to other operating systems. Git for Windows is hosted at https://gitforwindows.org/.

observação: você poderá utilizar o editor de texto de sua preferência.

//verificar a versão
git --version

//criar repositório
git init

//deixar o arquivo na espera para o comit
git add nomedoarquivo.extensão

/listando para a área de commit

git status

//dando o commit

git commit -m "coloque aqui suas considerações sobre o arquivo, pode ser o titulo do arquivo ou assunto"

//finalizando o commit, repita o comando git status para verificar se o commit deu boa.

//algumas empresas utilizam a branch principal do GIT com o nome de (master) e outras (main), verifique com sua equipe de desenvolivimento qual é o padrão atual, caso tenha a necessidade de alterar o nome da sua branch principal basta utilizar o seguinte comando. 

git branch -M "main" 

//caso tenha a necessidade de retornar para (master) refaça o comando abaixo

git branch -M "master"

//esse comando é apenas na primieira vez
git remote add origin https://github.com/Eng-Robson/Projetosgit.git

//Esse comando sobe os arquivos modificados para o git 
git push -u origin main

//Agora de posse dos principais comandos, ordem dos comandos ao realizar modificações de versionamento ou novos arquivos

//Primeiro

git add nome do arquivo.extensão do arquivo

//segundo
git status

//terceiro
git commit -m "considerações"

//quarto e último para subir o arquivo com a nova versão

git push -u origin main

ou 

git push -u origin master


Texto para refletir, quando se deparar discutindo com alguém que é dono da verdade mesmo que a "verdade" dessa pessoa seja falsa perante a fatos e dados, não perca seu tempo precioso discutindo.

O burro disse ao tigre: "A grama é azul".

O tigre respondeu: "Não, a grama é verde".

A discussão esquentou e os dois decidiram submeter o assunto à arbitragem, então abordaram o leão.

Ao se aproximarem do leão em seu trono, o burro começou a gritar: "Sua Alteza, não é verdade que a grama é azul?"

O leão respondeu: "Se você acredita que é verdade, a grama é azul".
O burro avançou e continuou: “O tigre discorda de mim, me contradiz e me irrita. Por favor, castigue-o."

O rei então declarou: "O tigre será punido com 3 dias de silêncio".
O burro pulou de alegria e seguiu seu caminho, feliz e repetindo "A grama é azul, a grama é azul..."

O tigre perguntou ao leão: "Vossa Majestade, por que você me puniu, afinal, a grama é verde?"

O leão respondeu: "Você sabe e vê que a grama é verde".

O tigre perguntou: "Então por que você me pune?"

O leão respondeu: "Isso não tem nada a ver com a questão de saber se a grama é azul ou verde. A punição é porque é degradante para uma criatura corajosa e inteligente como você perder tempo discutindo com um tolo, e ainda por cima , você veio e me incomodou com essa pergunta apenas para validar algo que você já sabia que era verdade!"

A maior perda de tempo é discutir com o tolo e fanático que não se importa com a verdade ou a realidade, mas apenas com a vitória de suas crenças e ilusões. Nunca perca tempo com argumentos que não fazem sentido. Há pessoas que, por todas as provas que lhes são apresentadas, não têm capacidade de compreender. Outros que estão cegos pelo ego, ódio e ressentimento, e a única coisa que querem é estar certos, mesmo que não estejam.

Quando a IGNORÂNCIA GRITA, a inteligência segue em frente.

A moral da história é não discuta com um tolo!
