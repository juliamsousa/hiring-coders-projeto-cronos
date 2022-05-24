# Hiring Coders - Git

- mkdir: cria um diretório
- touch: crua um arquivo
- git init: cria um repositório git e configura a branch principal
- git status: fornece o status do repo, arquivos adicionados, modificados e arquivos não rastreados
- git add file_name: adiciona um arquivo para um novo commit
- git commit -m "": forma de descrever a alteração que foi feita no momento no projeto. A flag -m permite adicionar um comentário para descrever o commit.
- git config --global user.email "email@email.com": configuração do email do usuário que realizará o commit
- git config --global user.name "Name": configuração do nome do usuário que realizará o commit

Após o commit temos algumas informações retornadas:

        $ git commit -m "Created files"
nome da branch | commit em repo local | código do commit
        [master (root-commit) 8a56bbb] Created files
arquivos que foram modificados, inserções e deleções
          2 files changed, 0 insertions(+), 0 deletions(-)
          create mode 100644 README.md
          create mode 100644 index.txt

- git checkout < branchName >: navega entre branches
- git remote add < originName > < url >: conecta o repositório local com o repositório remoto
-  git push -u origin < branchName > || git push --set-upstream origin master: envia a branch para o repositório remoto
- git push origin --delete < branchName >: apaga remotamente a branch cujo nome foi passado
- git branch: lista as branches no repositório local
- git branch -d < branchName >: apaga a branch local cujo nome foi passado
- git branch < branchName >: cria uma branch com o nome passado


