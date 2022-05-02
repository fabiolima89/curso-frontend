# curso-frontend
### EBAC

# GIT
## Conceitos de versionamento
Histórico 
Controle de versão
Quem alterou
Quando alterou
Todos os arquivos
Evolução contínua

Arquivo A | Versão 1

## Instalação do Git

## Criar conta no GitHub

## Clonar o projeto

## Comits
Informação de alteração
- após testado todo seu código
- git add *
- git commit -m "mensagem"
-git push ( enviar alterações para o repositório)
- git pull ( puxar / trazer alteraçõs do GitHub)

# GitFlow
Fluxo do Git


### Branchs
São ramificaçõs / versões paralelas

-main - mater ( vai para produção, quando o projeto é publicado)
-develop / 
- DOD  Definition of done: crietério de aceite

git checkout -b dev ( cria uma branch)
git checkout master ( mudar de branch )

-versionamento 1.0.0

### Merge
Mecla de branchs
Você pode precisar resolver conflitos manualmente

> git merge main    

### Pull Requests
Mecla de branchs no repositório
Permite code review
O repositório resolve os conflitos automaticamente

### configura o GitFlow
>git flow init
>git flow feature start