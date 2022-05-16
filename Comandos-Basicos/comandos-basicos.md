# Comandos Básicos

 - ## GIT INIT
O comando "git init" irá inicializar o repositório em sua máquina local.

- ## GIT CLONE
O comando "git clone url do repositório"  irá clonar, trazer do github, um repositório inicialmente criado lá, iniciando assim o repositório git na sua máquina local.

 - ## GIT STATUS
O comando "git status", irá nos mostrar o estado do repositório; se esse repositório possuí arquivos "untracked", "tracked" ou "staged".

 - ## GIT ADD
 O comando "git add", irá preparar os arquivos que serão empacotados no commit; transferindo-os para a "staged area".<br>
 Ele pode ser feito de duas formas, preparando um arquivo individualmente ou todos os arquivos contidos no repositório de uma só vez:
 ### git add nome_arquivo.md
 ### git add .
 ### git add * (se estiver no git bash)

 - ## GIT COMMIT
 Preparados os arquivos, após o "git add", é hora de enviar a atualização para o repositório através do comando "git commit".<br>
 ### git commit -m "Descrição do commit"<br>

## OBS: ✏️ </h2>

 - ### UNTRACKED FILES
"Untracked files", como o próprio nome diz, são arquivos que não estão sendo rastreados pelo GIT. Estes arquivos podem até estar em seu repositório, mas não foram preparados para ser empacotados em um "commit".

 - ### MERGED FILES
"Merged Files", são arquivos prontos a serem commitados, você já apontou através do comando "add"

- ### TRACKED FILES
Ao contrário dos "untracked files", estes serão aqueles arquivos que já foram empacotados e identificados em um "commit". Logo após realizar um commit, se você der um "git status", ele identificará os arquivos que foram rastreados.

