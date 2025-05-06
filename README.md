# Estudando-Git-e-GitHub
### Início dos estudos de Git & GitHub: 30/03/2022
### Fim dos estudos de Git & GitHub: 01/04/2022
---

Antes de começar a usar o git / github é necessário criar uma chave ssh, salvar globalmente seu email e nome. Salvar sua chave ssh no github, para que assim voce possa dar um clone ou init no seu projeto.
## Termos:
---

* **Pull** - Puxar coisas do repositório remoto para a maquina 

* **Push** - Empurrar coisas da máquina para o repositório remoto 

* **Commit** - Empurrar coisas da máquina para o repositório local 

* **U** - Untracked 

* **M** - Modified 

* **fork** - pegar um repositório de outra pessoa e jogar para o seu perfil

* **Pull Request** - mandar uma solicitação para a pessoa "dona do repositório" dar um pull em algo que você fez (contribute -> open pull request)

* **Branch**: ramos / o tronco principal se chama master. Cada commit é uma nova versão de um trabalho, cada push é uma jogada de versão para uma origin

    * **Dica**: evite comitar tudo em uma master:
 Crie uma nova branch para criar uma feature nova, assim que a feature nova estiver bonitinha prontinha faça um merge para unir a nova branch com a master

* É possível **clonar repositórios**, mas não é possível alterar o repositório do dono, se acharmos que tem algo errado podemos fazer issues para que o dono, aceite as mudanças e caso ele não aceite é possível criar um fork e continuar 

* **Issues** são literalmentes problemas, notificar um problema ou uma questçao e pull requests é a partir da análise de um problema/questão você levantar uma maneira de consertar e pede para que os donos/colaboradores analisem 

* É possvel fazer uma **assinatura padrão** - bastar ir em settings -> saved replies -> add a saved reply e cria-la depois para usar basta clicar na seta''<-''>

## Markdown:
---

Usar Markdown em Readme.md, em issues e em Pull reqquests com varios comandos que não precisam ser decorados como por exemplo: **Negrito**, __Negrito__, *Itaálico*, ou _Itálico_, [Links, esse no caso manda para uma lista de comandos Markdown](https://github.com/luong-komorebi/Markdown-Tutorial/blob/master/README_pt-BR.md), quebras de linha são feitas com um duplo espaço 
* '+'  
* enter
* e também é possível fazer citações como por exemplo:  
* > Se você julgar um peixe pela capacidade de escalar uma arvore, este paassará o resto da vida, acreditando que é estúpido -  Einstein, Albert
* > A dor do arrependimento é maior que a dor da disciplina
* da pra fazer uma tabelinha também:  

 Eu | Acordo| Melhor 
 ---|---|---|
 1|2|3


## Terminal:
---

* Na parte do terminal é necessário:
    * um git init para inicializar, 
    * git add para adicionar o arquivo no stage, 
    * depois um "git commit -m 'mensagem' " 
    * além disso temos o "git branch para -M 'Nome da branch' "(para mudar o nome da branch )
    * git remote add origin (url do perfil do GitHub), cria um reposiótio com o nome no github
        * Se aparecer " remote origin already exist" apenas dar um "remote set-url origin "url"
    * git push -u "apelido" "nome da branch"
    * git add . (manda todos os files para o stage)
    * depois da primeira conecção não precisa dar o add origin 
    nem colocar o -u no git push 
    * git checkout -b "nova-feature" (criação de uma nova branch + se direciona para a nova-feature)
    * git push origin "nome da branch que voce está"
    * git merge (na brach que "principal") "nome da branch que você quer dar merge"
    * git clone + url do repositório que você quer clonar
    * git pull para puxar mudanças feitas por outras pessoas ou por mim, que não estão na minha máquina
    * git branch -d "nome" da branch - para deletar uma branch
    * git push origin --delete "nome da branch"

