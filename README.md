# GIT E GITHUB

Aprendendo através do guia prático

# SCENES

- [X] Criação de pontos na história
- [X] Verificação de mudanças feitas

# PARALELS UNIVERSES (branchs)
- [X] Iniciar nova funcionalidade (feature) sem perder o que foi feito
- [X] adicionar novas funcionalidades ao projeto
- [X] apagar a branch depois de já ter se unido à master

- [X] colocar o projeto na nuvem

- [X] pegar projeto já iniciado para trabalhar com o time
- [X] precisa resolver um conflito

- [X] Antes de enviar a resolução, precisa usar o mesmo repositório local

Explicação do professor:
- `git init` // inicia a linha do tempo
- `git add` // adiciona ou atualiza mudanças para irem para a linha do tempo
- `git commit` // adiciona um ponto na linha do tempo 
- `git log` // visualiza os commits (pontos na linha do tempo)
- `git status` // informa o estado das alterações no projeto
- `git show` // apresenta determinado ponto na história
- `git branch` // gerenciar novas linhas do tempo
- `git checkout` // manipula as linhas do tempo
- `git merge` // unir linhas do tempo
- `git push` // envia alterações para repositório remoto

### MY NOTES:

A tabela ainda está sofrendo modificações

Comando | Sobre 
:---: | :--- 
git init | para iniciar a linha do tempo, é o primeiro comando 
git add | adiciona o arquivo à branch, utiliza depois de fazer alteração, complemento: ?
git add . | adiciona todas as mudanças feitas 
git show | mostra a última mudança feita, quando usa: ?, complemento: ?
git log | ver os pontos na história do projeto, como uma linha do tempo das mudanças
git status | mostra o desenvolvimento no git, util quando quer conferir se os commits foram feitos
git commit -m ""| envia o arquivo para o repositório, dentro das aspas insira uma breve mensagem sobre o commit
git checkout | para mudar de branch, utilizada quando quer trabalhar em uma branch diferente da atual, necessário inserir após o comando o nome da branch que deseja entrar
git branch | lista as branchs, quando usar: ?, complemento: ?
git merge | serve para unir universos, quando quer juntar uma branch à brach master, não esqueça de inserir o nome da branch que deseja unir
git branch -D | deleta branch, gerlamente é utilizasa após já ter sido unida à master e não ter mais motivo para existir, complemento: ?
git remote | definir qual o repositório remoto, utiliza-se quando quer definir qual será o repositório remoto, como o repositório no github por exemplo, complento: ?
git push | empura o repositório local para o github, depois de alterar o repositório local (na sua máquina) e quiser mandar para o github
git pull | puxa o repositório do github para sua máquina, case: quando já tiver o repositório na máquina e quiser atualizá-lo
git clone | pega projeto do github e clona em sua máquina, após digitar o comando digite o link do repositório que deseja clonar
