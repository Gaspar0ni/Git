# Comandos git

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

git branch -M main
git branch -M master

git add .
git add -A
git add nome_do_arquivo_e_extensao
git commit -m "comentario_do_commit"
git push

git commit -am "comentario_do_commit"
git push origin master

git remote add origin endereco_do_repositorio
git push -u origin master
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
