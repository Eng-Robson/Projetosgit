Esse arquivo é sobre como utilizar o GIT apresentando os principais comandos no GIT

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

git remote add origin https://github.com/Eng-Robson/Projetosgit.git

git push -u origin main