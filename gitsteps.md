
## init

    git init 

> Cria a pasta .git e torna a pasta atual um repositório
> No vscode o git init pode ser criado em source control

## user

    git config --global user.email "example@email.com"
    
    git config --global user.name namexample

> 

## Atributos Git

- Untracked ( - gray)
- Unmodified (U - green)
- Modified (M - orange)
- Staged

> Alterar arquivo muda o seu sha1, que altera atributo de Unmodified para Modified
> Remover arquivo Unmodified o torna Untracked

## Add
    
    git add *

> Muda o atributo de um arquivo para Staged

## Commit

    git commit -m "commit inicial"

> Cria snapshot (como checkpoint) dos arquivos Staged 
> Modifica atributos para Unmodified
> Nomeia snapshot



