Meu segundo sistema no GIT

Comandos git

git log = relatório de modificações
git status = mostra os arquivos modificados ou que não foram trackeados
git branch = mostra o teu branch
git add -A = trackeia todos os arquivos (não mostra nenhuma mensagem)
git add arquivo = trackeia o arquivo indicado
git commit -m "Mensagem" = gera um novo commit
git commit -am "Mensagem" = trackeia todos os arquivos e gera o commit
git reset --soft ou --mixed ou --hard código(inteiro ou 7 primeiros)= volta para um commit anterior
git branch <nome> = cria um branch com o nome
git checkout <nome> = muda o branch ativo para nome
git diff <--name-only> = mostra as mudanças que houve nos arquivos.
O parametro name-only só exibe o nome dos arquivos em que houve alterações.
git diff arquivo = mostra as alterações somente no arquivo especificado.
git checkout HEAD -- arquivo = desfaz as alterações do arquivo especificado.

-soft = volta mas conserva alterações posteriores não comitadas (estado anterior ao último commit)
-mixed = idem, mas não vai estar preparado para commit (tem que dar add novamente)
-hard = ignora tudo que aconteceu depois do commit resetado.

git remote add origin https://github.com/renatojover/modulogit.git
(adiciona o git local no github)

git fetch = remoto para local
git push = local para remoto

