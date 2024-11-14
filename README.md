# Compweek 7 - Git na Prática
Repositório com intuito de documentar o conteúdo abordado no minucurso "Git na prática" lecionado ao pessoal da Fatec e Etec de Jales, na 7ª edição da Compweek.

## Sistema de controle de versão 
- Software versioning
- Gerenciamento de mudanças

## Porque utilizar?
- Segurança
- Colaboração
- Organização
- Controle das versões
- Rastreio de modificações

## Estrutura do Git
- Repositórtio Local
  - Working Directory
  - Staging area
  - Repository
- Repositório Remoto

## Conventional commits
- Commits semânticos
- Convenção do Angular
- Padronização de commits
- Auxílio para automatizações

## Convetional commits
- build: mudanças envolvendo configurações e dependências
- ci: integração contínua
- feat: nova funcionalidade
- fix: correção de bug
- refactor: alteração que não é bug, nem novo recurso
- perf: refatoração visando aumento de performance
- raw: alterações em arquivos de configuração
- chore: atualizações de tarefas de build, configurações de administrador e pacotes
- docs: alterações envolvendo documentação
- cleanup: remoção de linhas desnecessárias
- remove: remoção de arquivos desnecessários
- style: formatações de código
- test: testes unitários

## Exemplos de SCV
- Git
- Mercurial
- TFS

## Commit atômico
- Boa prática
- Facilita mensagem do commit
- Melhor descrição

## Conflito no git
- Mesclagem de alterações
- Ex: pull, merge, rebase, push...
- Commits em arquivos iguais

## Git x GitHub 
![git_vs_github](https://github.com/user-attachments/assets/8ba66618-3d88-47d3-8174-8f9f03eeb46e)

### HISTORICO
- `git log`
- `git log --graph`
- `git log --oneline`
- `git diff <hashcommit> <hashcommit>`

### BRANCHES
- `git checkout <branch>`
- `git checkout -b <new-branch>`
- `git branch -d <branch>`
- `git stash`
- `git tag <tag-name>`

### ATUALIZAR E PUBLICAR
- `git remote add <shortname> <url>`
- `git fetch <remote>`
- `git pull <remote> <branch>`
- `git push <remote> <branch>`
- `git push --tags`

### FUNDIR E REBASE
- `git merge <branch>`
- `git rebase <branch>`
- `git rebase --abort`
- `git rebase --continue`

### DESFAZER
- `git reset HEAD~<quant-commit(s)>`
- `git revert <hash-commit>`
- `git reset <hash-commit>`

### OUTROS COMANDOS
- `git init`
- `git clone <link-rep-remoto>`
- `git help`

## Bibliografia
- https://git-scm.com/docs 
- https://blog.betrybe.com/desenvolvimento-web/versionamento-software-codigo/ 
- https://aws.amazon.com/pt/devops/continuous-integration/ 
- https://github.com/angular/angular/ 
- https://github.com/iuricode/padroes-de-commits 

