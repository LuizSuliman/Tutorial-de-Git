# Tutorial-de-Git
Mini-Tutorial de Git usando o GitBash/CMD, ensinando como usar comandos como CLONE, ADD, COMMIT, PUSH e PULL.
Obs.: Se for usuário de Windows, instale o Git antes desse tutorial.

***

## Clonando um repositório
Antes de alterar um repositório remoto do GitHub, precisamos CLONÁ-LO para a nossa máquina.
Fazemos isso através do comando **git clone *link_do_repositório***

Você pode encontrar o link de clonagem de um repositório no botão VERDE escrito "CODE".
Copie o link deste repositório, e depois abra o Explorador de Arquivos do Windows.

Nele, crie uma pasta para colocar todos os seus repositórios do GitHub.
DICA: Minha recomendação é criar uma pasta chamada **GitHub** na pasta **Documentos**

Entre na pasta que você criou, clique com o botão direito no espaço vazio, e escolha a opção **GitBash Here**
Se estiver no Windows 11, clique com o botão direito no espaço vazio, e então **Mostrar mais opções**. Só então o Git aparecerá.

Uma alternativa é usar o CMD (Terminal). Muitos preferem usar o CMD, mas a escolha é sua. Experimente esse tutorial com o GitBash e CMD, depois escolha o seu favorito.
Para abrir o CMD na pasta desejada, selecione **Abrir no Terminal** ou **Prompt de Comando**

Agota vamos para os comandos! No terminal (GitBash ou CMD), insira o seguinte comando:

> git clone https://github.com/LuizSuliman/Tutorial-de-Git.git

Obs.: No GitBash, em vez de CTRL + V para colar o link, use SHIFT + INSERT

Depois disso, o Git criará uma pasta com o nome deste repositório.
Use o comando **CD** para entrar nessa nova pasta:

> cd Tutorial-de-Git

Ótimo! Se você seguiu os passos corretamente, já vai estar dentro deste repositório! Pode até continuar o tutorial pelo arquivo README.md dentro da pasta clonada pelo GitHub.

***

## O ABC (ou ACP) do Git!

Como exercício, crie um novo arquivo .html nessa pasta, e neste arquivo adicione alguma mensagem da sua escolha (seja educado!).

Então, tudo pronto? Chegou a hora de mostrar sua mensagem para todos através do GitHub!
Mas para isso, vou te ensinar os básicos para "subir" suas alteração para o repositório remoto. Vem comigo:

1. Primeiro, abra o GitBash/CMD na pasta onde estão os arquivos deste repositório (Tutorial-de-Git);
2. Agora, use este comando para adicionar suas mudanças e novos arquivos ao monitoramento do Git (colocando seus itens na caixa);

> git add .

3. Em seguida, use o seguinte para criar um **commit** (fechar a caixa para envio):

> git commit -m "DESCREVA AS ALTERAÇÕES QUE FEZ NESSE ESPAÇO ENTRE ASPAS"

4. Quase lá! Apenas use o comando **push** (enviar sua caixa):

> git push

Perfeito! Sempre lembre do ACP (Add, Commit, Push) e você poderá fazer qualquer mudança nos repositórios do GitHub!

... ou será que não?

Sabe, eu não te perguntei antes, mas você já informou ao Git **quem é você?**
Se você seguiu esses passos e suas alterações já estão aqui, no repositório do GitHub, ótimo.
Mas talvez você tenha recebido algum erro de autenticação na hora do push, não é?
Se esse é o seu caso, me siga...

***

## Quem é você na fila dos commits?

O que eu vou te ensinar agora deve ser, de preferência, feito antes de todo o resto.
Para fazer um push, você precisa informar ao Git **quem é você**, para ser possível rastrear o autor de cada modificação.

Para isso, use os seguintes comandos:
> git config --global user.name "Seu Nome de Usuário do GitHub"

> git config --global user.email "Seu Email do GitHub"

Obs.: NÃO USE --global em máquinas públicas (ex. faculdade)!

Com o --global, você NÃO PRECISA fazer essa configuração novamente na sua máquina pessoal. Por isso, tome cuidado e não use --global na faculdade. Apenas faça o seu push e delete a pasta por completo.

Agora, tente o **git push** novamente. Se o seu navegador abriu uma página de login do GitHub, então está tudo certo!
Apenas faça login, e seu push será feito!

***

## Meu repo, seu repo

Calma, estamos quase acabando. Só mais um comando muito útil de presente: **git pull**
Sempre use esse comando antes de começar a trabalhar em um repositório, pois se alguém atualizou ele enquanto você esteve fora, você precisará do pull para pegar os novos arquivos e mudanças.

> git pull

***

## É hora da revisão!

Está é a ordem. Revisando os comandos:

> git config --global user.name "Seu Nome de Usuário do GitHub"

> git config --global user.email "Seu Email do GitHub"

> git clone https://github.com/LuizSuliman/Tutorial-de-Git.git

> cd Tutorial-de-Git

> git pull

...Alterações...

> git add .

> git commit -m "DESCREVA AS ALTERAÇÕES QUE FEZ NESSE ESPAÇO ENTRE ASPAS"

> git push

Config Clone CD, Add Commit e Push!
Quase uma música, né? (Talvez não)

Pratique esses comandos e se desafie a usar o terminal, e quando menos perceber, vai estar voando no Git!

***

## E chegamos ao fim! (Ufa!)

E com isso, você está pronto para finalmente usar um terminal ao invés do site do GitHub para trabalhar com a sua equipe!
Se tiver alguma dúvida ou sugestão, é só entrar em contato!

#### Bons estudos!
