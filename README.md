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