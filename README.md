# Git

#....CURSO DE GIT....

para iniciar um repo

comando EX:
  git init

ou pode usar essa linha cedida pelo GitHub

echo "# teste" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://(nome do repo/endereço do repo)
git push -u origin main

Para saber o modificações status dos arquivos
Comando EX:
  git status

Para adicionar arquivos no repo
Comando EX: adiona apena um arquivo precisa 
colocar nome do arquivo sua extensão.
  git add nome_arquivo.extensão
  git add pasta/nome_arquivo.extensão (add pasta e arquivo)

  git add index.html 

Para adicionar todos os arquivos de uma vez:
Comando EX:
  git add .

commit: Quando faz fizer alterações dos arquivos
fazemos commit com msg explicando as alteações. 

Comando EX:
commit apenas um modificação.
  git commit nome_arquivo.extensão -m "mensagem"
  git commit a.txt -m " msg "

Comando EX: 
commit para toda as modificações.
  git commit -a -m "mensagem" 

Como enviar arquivo para repo
Comando EX:
  git push

Clonando o repo
Comando EX:
  Clonagem do repo total:
    git clone https://endereço do repo 
  
  Clonagem apenas dos arquivos do repo acrescente . :
    git clone https://endereço do repo .
              
Apangando um arquivo
Comando EX:
  git rm c.txt
  
  git rm nome_do_arquivo.extensão

 Acessar um log (historico de commits)
 Comando EX:
  git log
 para sair clique no q 

Renomear arquivo ou mover arquivo para pasta
Comando EX:
  movendo arquivo para pasta
  git mv rodape.css css/rodape.css

  modificando nome do arquivo:
  git mv css/bannerinicial.css css/banner_inicial.css

  git mv css/nome_do_arquivo.extensao nome_pasta/nome_do_arquivo.extensao
  
Retornando ao estado original (Desfazendo alterações);
Comando EX:git checkout 

  git checkout pasta/nome_arquivo.extensão
  git checkout css/styles.css

.gitignore
serve para ignorar alguns tipos arquivos
 ou pastas
EX:
DS_STORE
node_modules

Desfazendo alterações da branches
resetar e exclui todas as mudanças feitas
no commit ou que estão pendentes;
Comando EX:
  esse comando se usa dessa forma abaixo 
  git reset --hard origin/master
  
  resultado vai trazer para ultimo commit
  excluindo toda alterações feita.
  sempre colocando no da branch que quer ser resetada.
  nesse exemplo foi a branch master.
  
