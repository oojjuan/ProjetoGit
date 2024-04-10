Esse projeto ensina você a usar o Git :D

git {
1) init >> inicia um repositório git vazio
2) add "arquivo" >> manda os arquivos na area de 'staging'
3) commit -m "mensagem" >> tira da area do staging e adiciona um título do commit
4) branch -M "main" >> muda o 'master' para o 'main' 
5) remote add origin "link.git" >> faz conexão do repositorio local com o do repositorio do git
6) push -u origin main >> coloca os commits do repositorio local pro git
}

outros comandos git {
1) add . >> adiciona TODOS os arquivos que foram alterados na area de staging
2) push origin main >> mesma coisa só que sem o remote, que serve quando for adicionar mais coisas novamente
3) checkout -b "novo-botao" >> branch é uma ramificação do projeto que serve para desenvolver alguma feature (adicionar pág nova no projeto)

--> MUDA O LOCAL ATUAL DA SUA BRANCH! <-- 
altera tudo da branch ATUAL!
para voltar na branch main, só utilizar o comando checkout 'branch'.
4) merge "branch" >> mescla a branch selecionada com a atual
}


