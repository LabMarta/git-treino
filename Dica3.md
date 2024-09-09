git commit
Commits

Armazena o conteúdo atual do índice em um novo commit, juntamente com uma mensagem de registro do usuário que descreve as mudanças.
Se usa o commit depois de já ter feito o git add, para fazer o commit:

git commit -m "Mensagem"
Para commitar também os arquivos versionados mesmo não estando no Stage basta adicionar o parâmetro -a

git commit -a -m "Mensagem"
Refazendo commit quando esquecer de adicionar um arquivo no Stage:

git commit -m "Mensagem" --amend
O amend é destrutivo e só deve ser utilizado antes do commit ter sido enviado ao servidor remoto.
