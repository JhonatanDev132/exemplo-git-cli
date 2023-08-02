# Exemplos de operações básicas para git via CLI

## Comando de uso geral da CLI

- Criar pasta: mkdir 
- Listar conteúdo: dir
- Limpar tela: cls
- Entrar na pasta: cd nomepasta

## Comando principais do git
`git config --global user.name "Seu nome como quiser"` e 
`git config --global user.email "seuemail@provedo.com"`

Mudar usuário e o email de forma global.

**Obs:** normalmente estes dados estão relacionados ao usuário/conta do site Github.    

`git config user.name` e `git config user.email`
Verificar usuário/email

`git init`

Inicializar um repositório (Executado dentro da pasta).

`git branch nome-branch-atual novo-nome-para-branch`

Renomear branches

para alterar a branch de **master** para **main** (novo padrão), usaríamos? `git branch master main`

`git status`

Verificar status atual do repositório

`git add nomearquivo`

Adicionar (Tornar arquivo rastreável) ao monitoramento do git.

`git remote add origin endereço-do-repositório.git`

Adicionar/conetar o repositório para a máquina remota.

`git commit -m "texto da mensagem sobre esta alteração"`

Fazer commit das alterações (salvar no histórico)

`git push origin main`

Enviar as mudanças para o GitHub (PUSH).

`git clone endereço-do-repositório.git`

Copiando/baixando um repositório para a máquina remota.

`git pull origin main`

Pegar/obter as mudanças do repositório online Github (PULL)
