# Curso Front-end 💻
#### EBAC

# GIT 🦊
## Conceitos de versionamento
 - Histórico
 - Controle de versão
 - Quem alterou
 - O quê alterou
 - Quando alterou
 - Todos os arquivos
 - Evolução contínua

 Arquivo A  | Versão 1 | Versão 2
 Arquivo B  | Versão 1 | Versão 2

 ## Instalação do Git ⚙
https://git-scm.com/

- Windows: https://git-scm.com/download/win
- Linux (apt-get): sudo apt-get install git
- Mac (brew): brew install git

 ## Criar conta no GitHub

 ## Clonar o projeto
 git clone https://github.com/cavalcantemmarcelo/curso-frontend.git

 ## Commits
 Informação de alteração
 - após testado todo seu código
 > git add *
 > git commit -m "mensagem"
 > git push (enviar alterações para o repositório GitHub)
 > git pull (puxar / trazer alterações do GitHub para sua máquina)

## GitFlow ⚙
Fluxo do Git

### Branchs 📂
são ramificações / versões paralelas

- main / master (vai para produção, quando o projeto é publicado)
- develop 
- DOD Definition of Done: critérios de aceite
- versionamento 1.0.20

 (projeto todo concluido p/ enviar p master),(atualização mto import no cod),(correção de bugs)

> git checkout -b dev (cria uma branch)
> git checkout master (mudar de branch)


### Merge
Mescla de branchs
Você pode precisar resolver conflitos manualmente

> git merge main 

### Pull Requests
Mescla de branchs no repositório
Permite code review
O respositório resolve os conflitos automaticamente


### configura o GitFlow
> git flow init
> git flow feature start {nome-da-feature}
