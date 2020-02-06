# GIT E GITHUB

Guia prático para iniciantes.

### Intalação

https://git-scm.com/download

# SCENES

- [] Você deseja criar pontos na história da produção do seu projeto
git log

# git init (Inicializa o git)
# git add ARQUIVO (Adiciona o arquivo)
# git add .(Adiciona todas as auterações)
# git commit -m "menssagem" (Envia o arquivo)

- [] Você deseja verificar mudanças feitas no seu projeto

# git log (Verifica todas as mudanças que foram feitas)
# git status (Verifica o status do git)
# git show + codigo commit obtido pelo git log (Verifica todas alterações que foram feitas no commit) 


- [] Você começa uma nova funcionalidade  no seu projeto, sem estragar o que já foi feito

# git branch (Mostra as ramificações)
# git branch NOME (Cria uma nova ramificação)
# git checkout NOME (ALtera entre as ramificações)
# git status (para verificar em qual branch estou)

- [] Você adiciona as novas  funcionalidades ao seu projeto em produção 

# git merge NOME (Uni as ramificações)

- [] Você que deletar um brash da nova funcionalidade, depois  de aplicar  em seu projeto

# git branch -D NOME (Deleta a ramificação)

- [] Você quer colocar seu projeto na nuvem

# gir remote -v (Visualiza os repozitorios remotos)
# git remote add origin https://github.com/willianlemoss/GitComandos.git
# git push (-u origin master apenas na primeira vez)

- [] comandos extras
# git config credential.helper store (usuario e senha para não ficar digitando direto)
# git commit -am "" (adiciona e faz o commit junto)

- [] Você vai pegar um projeto já inicializado, para trabalhar com o time

# git clone link do projeto (Pega io projeto da nuvem)

- [] Você precisa resolver um conflito
# git checkout -b NOME (Cria uma linha do tempo para teste)

- [] Antes de enviar a resolução, precisamos atualiza o projeto local
# git pull

- [] você precisa voltar um arquivo para determinado momento ou recuperar algo deletado da linha do tempo
# git checout codigo do commit( volta no tempo)