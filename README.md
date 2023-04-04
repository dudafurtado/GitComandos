# Comandos

## Git 
Performatico com a disponibilidade de todo o histórico de commits.  
Responsável por controlar versões de um arquivo, ou seja, faz o versionamento do código.  
Possui configuração de explicar cada mudança e a comparação da versão anterior e a atualizada.  
Possibilita que várias pessoas tenham acesso aos dados do documento e assim versões da mesma história sejam alteradas.

 - *git init*  
 Cria um repositório vazio na pasta no modelo local, ao qual, futuramente pode se associar a um repositório remoto.
 ! arquivos que iniciam com "." são ocultos
 
 - *git clone*  
 Utilizado para adicionar os dados do repositório remoto a uma pasta na maquina local.  
 Depois do comando é preciso adicionar o link ssh ou https no botão de code > local disponibilizado pelo github.
 
 - *git status*  
 Mostra informações da ramificação do repositório em visualização, ou seja, o satus de arquivos em stage ou que foram modificados e precisam de outros comandos para mandar para o repositório remoto.
 
 #### Stage x Not Stage  
 **Stage** = arquivos que sofreram modificações e estão preparados para registrar no controle de versão.  
 **Not Stage** = sofreram alteração, mas ainda não foram enviados para a área de preparação.
 
 - *git add*  
 Adiciona arquivos a área de preparação.  
 O "." possibilita adicionar todos os arquivos modificados de uma vez, já para adicionar um arquivo em especifico é preciso completar ao lado do comando o nome dele.
 
 - *git reset*  
 Remove arquivos da área de preparação e faz eles voltarem para o not stage.  
 O "." possibilita adicionar todos os arquivos modificados de uma vez, já para adicionar um arquivo em especifico é preciso completar ao lado do comando o nome dele.  
 
 - *git commit*  
 Marco histórico no projeto para identificar a situação e quais foram as mudanças no código a apartir do ínicio do arquivo.  
 Pós comando é preciso adicionar o -m para o comentário venha circulado pelas aspas duplas "".  
 É importante que a mensagem do commit seja uma referência a qual passo o projeto anda para que no futuro as próprias melhoras de código sejam facilmente identificáveis.
 
 - *git remote add origin*  
 Conecta o repositório remoto, já existente, com o local.  
 Depois do comando é preciso adicionar o link ssh ou https no botão de code > local disponibilizado pelo github.
 
 - *git push*  
 Envia as alterações do repositório local para o remoto.  
 Após o comando é preciso colocar a palavra reservada "origin" e em seguida o nome da branch, ao qual, tem interesse de mandar as modificações.
 
 - *git pull*  
 Atualiza o repositório local com as modificações recentes do repositório remoto.  
 Após o comando é preciso colocar a palavra reservada "origin" e em seguida o nome da branch, ao qual, tem interesse de mandar as modificações.  
 Utilizado principalmente para acompanhar atualizações de outros colaboradores no projeto.
 
 - *git checkout*  
 Para navegar em outras branchs é preciso após o comando adicionar o nome da branch já existente.  
 Caso haja a necessidade de criar uma branch nova utilizamo o "-b" e o nome.
 
 - *git branch -d nomeDoBranchLocal*   
 Para excluir uma branch do repositório local
 
 - *git push origin --delete nomeDoBranchRemoto*  
 Para excluir uma branch no repositório remoto
 
 !! Para facilitar as mudanças para stage podemos usar: *git add . && git commit -m ""*

### Branch
Ramificações de um arquivo.  
Utilizada para duplicar projetos e alterar partes de um código separadamente.  
Exemplos de nomes: master, main, develop, feature...

## Terminal
 - *dir*  
Lista todos os arquivos daquela pasta, ao qual, o terminal foi aberto.
- *cd /*  
Acessa a pasta raiz da máquina.
- *cd "nome do arquivo"*  
Entra no arquivo filho do que estiver aberto no momento da escrita do comando.

## Github
Biblioteca dos códigos exposto virtualmente pela conta do desenvolvedor.  
Possibilidade de contribuir ao código de terceiros.  
Rede social para o mercado de trabalho.

#### Dicionário

Repositório local = arquivo da maquina do desenvolvedor  
Reposítorio remoto = arquivo virtual localizado dentro do github
