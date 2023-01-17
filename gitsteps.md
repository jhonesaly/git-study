
## init

    git init 

> Cria a pasta .git e torna a pasta atual um repositório
> No vscode o git init pode ser criado em source control

## config

    git config --list
    git config --global

> 'list' vai listar todas as configurações do Git
> 'global' vai aplicar alterações em todos os repositórios

### user

    git config --global user.email "example@email.com"
    
    git config --global user.name namexample

> atribui um e-mail e apelido para o usuário do git

## Atributos Git

- Untracked (U - green)
- Unmodified ( - gray)
- Modified (M - orange)
- Staged

> Alterar arquivo muda o seu sha1, que altera atributo de Unmodified para Modified
> Remover arquivo Unmodified o torna Untracked

## Add
    
    git add *

> Muda o atributo de um arquivo para Staged
> '*' seleciona todos os arquivos
> '.' também seleciona tudo

## commit

    git commit -m "commit inicial"

> Cria snapshot (como checkpoint) dos arquivos Staged 
> Modifica atributos para Unmodified
> Nomeia snapshot
> Arquivos do Commit passam a integrar o Local Repository
> Local Repository pode ser empurrado para um Remote Repository (GitHub)

## status

    git status





