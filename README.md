# ==========> Git <==========

# ========> CURSO DE GIT <========
-----------------------------------------------------------------------------------------

- [x] Para iniciar um repo:
  - git init

- [x] Pode a linha de comando cedida pelo GitHub:
  - echo "# teste" >> README.md
  - git init
  - git add README.md
  - git commit -m "first commit"
  - git branch -M main
  - git remote add origin https://(nome do repo/endereço do repo)
  - git push -u origin main

- [x] Para saber status do repo:
  - git status

- [x] Para adicionar arquivos no repo.
  - Adiona apena um arquivo precisa: 
    - git add nome_arquivo.extensão
    - git add pasta/nome_arquivo.extensão (add pasta e arquivo)
    - Feito dessa forma: git add index.html 
  - Para adicionar todos os arquivos de uma vez:
    - git add .

- [x] Commit: Quando fizer as modificações é necessário fazer commit uma msg explicando as alteações. 
  - commit apenas um modificação.
    - git commit nome_arquivo.extensão -m "mensagem"
        - Feito dessa forma: git commit a.txt -m " msg "
  - commit para todas as modificações.
    - git commit -a -m "mensagem" 

- [x] Como enviar arquivo para repo
  - git push
- [x] Clonar um repo
  - Clonagem do repo total:
    - git clone https://endereço do repo 
  - Clonagem apenas dos arquivos acrescenta o . :
    - git clone https://endereço do repo espaço  .

- [x] Apangando um arquivo
  - git rm c.txt
    - git rm nome_do_arquivo.extensão

- [x] Acessar um log (historico de commits)
  - git log
    - para sair clique q 

- [x] Renomear arquivo ou mover arquivo para pasta 
  - movendo arquivo para pasta
    - git mv rodape.css css/rodape.css
  - modificando nome do arquivo:
    - git mv css/bannerinicial.css css/banner_inicial.css
    - git mv css/nome_do_arquivo.extensao nome_pasta/nome_do_arquivo.extensao

- [x] Retornando ao estado original (Desfazendo alterações);
  - git checkout 
  - Movendo arquivo para uma pasta
    - git checkout pasta/nome_arquivo.extensão
  - Movendo arquivo 
    - git checkout css/styles.css

- [x] Criando git ignore
  - Criar um arquivo chamado .gitignore
  - Serve para ignorar alguns tipos arquivos ou pastas
  - DS_STORE
  - node_modules/*

- [x] Desfazendo alterações da branches resetar e exclui todas as mudanças feitas no commit ou que estão pendentes;
  - esse comando se usa dessa forma abaixo 

    - git reset --hard origin/master
  
  - resultado vai trazer para ultimo commit excluindo toda alterações feita.
  - sempre colocando no da branch que quer ser resetada, nesse exemplo foi a branch master.

-----------------------------------------------------------------------------------------------
# Branch 

# Atualizando REPO
 
- [x] Enviar branch para repo
  - git push --set-upstream origin nome_branch

# Fecth --->
  - Atualizar todos os branches e tags que ainda não estão reconhecidos por você
    - git fetch -a  

  - Atualizar repo 
    - git pull

  - Para fazer as modificações na branch master
    - git merge origin/nome_branch (que foi feita o código)

-----------------------------------------------------------------------------------------------









              


  


  
