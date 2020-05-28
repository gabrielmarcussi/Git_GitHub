B7Web

Projeto > Git_GitHub 

// COMITANDO ARQUIVOS E ADICIONANDO TODOS OS NOVOS NÃO LISTADOS -------------------------
 git commit -am "Preenche com as informações referente as alterações que serão enviadas"
//----------------------------------------------------------------------------------------

// TIPOS DE RESET UTILIZANDO [git reset --tipo id_Commit] --------------------------------

Copiar o código gerado no commit [git log]

O git log é utilizado para listar todos os commits já efetuados nessa branch

commit xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
commit yyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyyy

soft - voltar com os arquivos mas não commitados.
mixed - volta mas não está preparado para comitar [precisando usar o git add]
hard - ignora tudo que não existe antes perdendo todos os arquivos até o determinado commit

git reset --hard xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx [id commit]

//------------------------------------------------------------------------------------------

// GIT BRANCH ------------------------------------------------------------------------------

git branch lista todas as branchs [* é onde vc está]

Criando Branch [git branch [nome]]

Alterando de branch [git checkout nome_branch]

//------------------------------------------------------------------------------------------

//GIT DIFF ---------------------------------------------------------------------------------

git diff mostra todas as alterações que ocorream durante o projeto

git diff --name-only mostra o nome dos arquivos que sofreram alterações

git diff nome.arquivo mostra apenas as alterações que ocorreram naquele arquivo em especifico.

//------------------------------------------------------------------------------------------

// RETORNANDO ARQUIVOS ESPECIFICOS ---------------------------------------------------------

git chekout [branch] -- [nome.arquivo] volta o arquivo ao seu estado inicial.

//------------------------------------------------------------------------------------------

//GERANDO A CHAVE PARA RECONHECER SEU COMPUTADOR AO CONECTAR EM UM REPOSITORIO GIT.--------

https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

Open Git Bash.

Paste the text below, substituting in your GitHub email address.

$ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
This creates a new ssh key, using the provided email as a label.

> Generating public/private rsa key pair.

//------------------------------------------------------------------------------------------

//VINCULANDO UM REPOSITORIO A UM PROJETO ---------------------------------

git remote add origin URL REPOSITORIO GIT

git fetch (pull / buscar)

git push (envia)

//-----------------------------------------------------------------------------------------
