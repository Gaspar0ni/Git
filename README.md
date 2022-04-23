# Comandos git

### importante clone de git forkado: git clone https://github.com/Gaspar0ni/test


[Site de comandos GIT](https://education.github.com/git-cheat-sheet-education.pdf)

----------------------------------------------------------------
[Comando importante](https://laravel.com/docs/7.x/migrations)

The --table and --create options may also be used to indicate the name of the table and whether or not the migration will be creating a new table. These options pre-fill the generated migration stub file with the specified table:

php artisan make:migration create_users_table --create=users
 
php artisan make:migration add_votes_to_users_table --table=users

If you would like to specify a custom output path for the generated migration, you may use the --path option when executing the make:migration command. The given path should be relative to your application's base path.

----------------------------------------------------------------

git config --global user.name "seu_nome"
git config --global user.email "you@example.com"

git log
git status
git config --list

ls
dir
tree /f

cd ..
cd ../
cd nome_do_proximo_diretorio

#### git branch -M main
git branch -M master

#### git add .
git add -A
git add nome_do_arquivo_e_extensao
#### git commit -m "comentario_do_commit"
git push

git commit -am "comentario_do_commit"
git push origin master

#### git checkout -b nome_da_feature
#### git merge nome_da_branch_mais_atualizada

#### git remote add origin endereco_do_repositorio.git
#### git push -u origin master
git pull -u origin master

git pull
git pull origin master

git remote add origin <-------------------- não entendi

git reset --hard identificador_do_commit
git reset -soft identificador_do_commit

git checkout nome_da_branch_que_deseja_logar??????????
git branch nome_da_nova_branch????????????
git branch????????????

## Não sei controlar branchs, quando arrumar tempo, procurar por vídeos sobre o assunto

git diff
git diff --name-only
git diff nome_do_arquivo

git checkout -- nome_do_arquivo_que_deseja_voltar_o_estado_original

## Não entendi 100% o comando acima, quando tiver tempo, procurar

## entender repositório local e repositório remoto

[Gerar ssh key](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

git remote
git remote -v

## entender fetch e push

## entender o arquivo .gitignore

[Sobre gitignore](https://docs.github.com/pt/get-started/getting-started-with-git/ignoring-files)
[Site de Gitignore](https://github.com/github/gitignore)

git revert --no-edit codigo_do_commit_a_ser_revertido

git push origin :teste

git branch -D nome_da_branch_a_ser_deletada

git clone url_do_projeto_a_ser_clonado
