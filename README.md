# Introdução a Git e GitHub :octocat:

- Git é um sistema de controle de versão distribuído, no qual cada membro mantém uma cópia do código e contribui enviando suas modificações para o repositório principal. O GitHub é uma plataforma que hospeda repositórios Git.[Site oficial do Git](https://git-scm.com/)

## Configurando o Git

- Registrar nome do usuário globalmente: `git config --global user.name "nome_do_usuario"`
- Registrar email do usuário globalmente: `git config --global user.email "email"`

## Comandos básicos do Git

- Iniciar o repositório Git: `git init`
- Se quiser clonar algum repositório: `git clone`
- Adicionar um arquivo à área de preparação: `git add "nome_do_arquivo"`
- Para realizar um commit: `git commit`
- Atualizar seu repositório local com as mudanças do repositório remoto: `git pull`
- Enviar suas mudanças locais para o repositório remoto: `git push`
- Para mostrar o repositório remoto vinculado: `git remote -v`
- Para vincular a um repositório remoto: `git remote add origin "url"`
- Mostrar o status atual das mudanças no seu repositório: `git status`
- Mostrar o histórico do Git: `git log`
- Se quiser reverter um arquivo à versão do último commit: `git restore "nome_do_arquivo"`
- Registrar as mudanças no repositório com uma mensagem descritiva: `git commit -m "Mensagem do commit"`
- Como alterar a mensagem do último commit: `git commit --amend -m "descrição"`

## Branches
- Criar uma branch (ramificação): `git checkout -b "nome"`
- Excluir uma branch (ramificação): `git branch -d "Nome"`
- Mover entre branches (ramificações): `git checkout "nome"`
- Listar todas as branches (ramificações) no repositório: `git branch`
- Listar o último commit das branches (ramificações): `git branch -v`
- Mesclar as branches (ramificações): `git merge "nome"`

Para obter informações adicionais, recomendamos consultar a documentação do Git. [Link para documentação.](https://git-scm.com/docs)
