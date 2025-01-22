## Commits 
Informação de alteração
- após testado todo o código
- git add *
- git commit -m "mensagem"
- git push (envia alteração para o repositório GitHub)
- git pull (puxar / trazer informações do GitHub para sua máquina)

## GitFlow
Fluxo do Git

## Branchs
São ramificações / versões paralelas

- main / master (Vai para produção quando o projeto é publicado)
- develop
- DOD definition of Done: critérios de aceite
- versionamento

git checkout -b dev (cria uma branch)
git checkout master (mudar de branch)


### Merge
Mescla de branchs
Você pode precisar resolver os conflitos manuelamente

git merge main


### Pull Requests
mescla de branch no repositório
permite code review
o repositorio resolve os conflitos automaticamente


### configura o GitFlow
git flow init
git flow feature start (nome-da-feature)