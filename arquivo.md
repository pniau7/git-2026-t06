Comentários:

1. O . indica a pasta atual
2. O .. indica a pasta pai
3. A pasta .git contem todas as informações do versionamento
4. Todo commit precisa de um autor e um contato (email). Na primeira vez que roda GIT não tem essas informações e pede na hora de realizar o primeiro commit.

   1. git config --global user.name "Pierre"
   2. git config --global user.email "pniau7@gmail.com"
5. Untracker -> não está sendo acompanhado
6. Unstaged -> o arquivo está em um estado diferente da última versão salva
7. Padrão: Nunca mexer arquivos na main! Sempre fazer branch, modificar e depois merge
8. Branch: cria uma ramificação. Carrega toda a informação

   1. Como se fosse uma cópia do diretório main
   2. Posso modificar sem impactar a main



Comandos:

1. pwd
2. ls
3. touch
4. ls -a (para ver arquivos ocultos)



Comandos git:

1. git init . -> inicia o versionamento do conteúdo da pasta
2. git status -> mostra o status do versionamento
3. git add arquivo.md -> Prepara para ser commitado
4. git commit -m "Primeiro commit" -> Executa o checkpoint/versão/snapshot/save (-m é flag para inserir uma mensagem)

   1. \[main (root-commit) fc383ab] Primeiro commit
   2. fc383ab é o CPF do commit
5. git status

   1. nothing to commit, working tree clean
   2. Working tree clean: o estado/conteudo da pasta está idêntico à última versão/commit
6. git log -> Lista todos os commits, seu identificador, autor, data e mensagem

   1. Head é o último que está na ponta. Estado atual
   2. (HEAD -> main) indica qual commit é a cabeça (representando os arquivos atuais)
7. git reset -> restaura arquivos que estava staged
8. git checkout -> Estamos saíndo (como no hotel)

   1. git checkout -b -> Muda de branch e cria a branch





Dúvidas:

1. Desfazer commit: Fiz um commit, mas esqueci um detalhe e não faz sentido realizar outro commit. Tem como desfazer o último commit?
2. Testes

