# GIT E GITHUB

Guia prático para iniciantes.

### Intalação

https://git-scm.com/download

# SCENES

- [] Você deseja criar pontos na história da produção do seu projeto
git log

# git init (Inicializa o git)
# git add ARQUIVO (Adiciona o arquivo)
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

# git remote add origin https://github.com/Williannlemoss/FuncionalidadesGit.git (Adiciona na nuvem)
# gir remote -v (Visualiza os repozitorios remotos)
# git push -u origin master (Envia os arquivos para a nuvem)