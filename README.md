# ==========> Git <==========
      ![Logo do Git](./img/git.png)
# ========> COMANDOS DO GIT <========
-----------------------------------------------------------------------------------------------------------------

- [x] Para iniciar uma repo:
  - git init

- [x] Pode ser feito pela linha de comando cedida pelo GitHub:
  - echo "# teste" >> README.md
  - git init
  - git add README.md
  - git commit -m "first commit"
  - git branch -M main
  - git remote add origin https://(nome_da_repo/endereço_da_repo)
  - git push -u origin main

- [x] Para saber status da repo:
  - git status

- [x] Para adicionar arquivos na repo.
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
- [x] Clonar da repo
  - Clonagem do repo total:
    - git clone https://endereço do repo 
  - Clonagem apenas dos arquivos acrescenta o . :
    - git clone https://endereço do repo espaço  .

- [x] Apagando um arquivo
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

-------------------------------------------------------------------------------------------------------------------
# Branch 

- [x] Atualizando REPO
 
- [x] Enviar branch para repo
  - git push --set-upstream origin nome_branch

- [x] fetch --->
  - Atualizar todos os branches e tags que ainda não estão reconhecidos por você
    - git fetch -a  

  - Atualizar repo 
    - git pull

  - Para fazer as modificações na branch master
    - git merge origin/nome_branch (que foi feita o código)

-----------------------------------------------------------------------------------------------------------------

# Análise e inspeção de repositórios

  - [x] git show
    - Mostra detalhes e modificações das branches e tags.
  - [x] git diff 
    - Mostra modificações e diferença da branch para outra branch o até mesmo da mesma branch.
  - [x] git diff HEAD:a.txt a.txt
    - Mostra as modificações entre as repos. 
  - [x] git shortlog 
    - Dá um log resumido do projeto e trás cada commit será unido por nome do autor, independente de branch.
----------------------------------------------------------------------------------------------------------------    
# Administrando Repositórios

  - [x] Comando para administrar um repositórios.

    - [x] git clean remove os arquivos não adicionado.

      - git clean -f

    - [x] git gc comando que otimiza repo, ele indentifica arquivos que não são necessários e os exclui.
      - git gc

    - [x] git fsck verifica a integridade de arquivos e sua conectividade, verifica se estão corrompidos.
    comando de rotina, para verificação;
      - git fsck

    - [x] git reflog vai mapear todos os seus passos no repositório, até uma mudança de branch, inserindo neste log esse comando ficam salvos no tempo de 30 dias;
  
    - [x] uso do git reset
      - git reset --hard bdc980d (número_do_registro)

    - [x] Comando para transformar o repo em um arquivo
      - git archive --format zip --output nome_do_arquivo.zip nome_da_branch
        - o arquivo vai estar zipado mater_files.zip

-----------------------------------------------------------------------------------------------------------------

# Técnicas de private branch

  - [x] git rebase nome_arquivo private_nome_arquivo -i
    - irá mostrar os commits para editar click i = insert
    - aonde escrito pick
    - squash = delete o commit 
    - reword = edita o commit 

|=============================================================================|
 - p, pick = use commit                                                      
 - r, reword = use commit, but edit the commit message                     
 - e, edit = use commit, but stop for amending                             
 - s, squash = use commit, but meld into previous commit                   
 - f, fixup = like "squash", but discard this commit's log message         
 - x, exec = run command (the rest of the line) using shell                
                                                                             
 - Para salvar modificação                                                   
 - comando :x!                                                               









              


  


  
