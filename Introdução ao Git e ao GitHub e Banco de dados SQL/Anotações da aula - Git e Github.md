:scroll: **// Nota inicial:** Tive a ideia de estruturar este repositório com as minhas anotações das aulas, de forma a disponibilizar este conteúdo (dentro da minha perspectiva de entendimento) á quem interessar, e também, com a escrita das informações, firmar ainda mais estes conteúdos e conhecimentos adquiridos.

Desta forma, inicio agora a primeira anotação referente as aulas do Bootcamp Santander Code Girls.

<img src="https://static.vakinha.com.br/uploads/vakinha/image/1150859/79480e87d9fcb11532f5fa7100f1644d.gif" alt="alt text" style="zoom: 67%;" />

## Para iniciar, é interessante já realizar o Download do Git

Link para download: https://git-scm.com/downloads

Neste momento, estou utilizando a versão **2.37.0** para Windowns, porém, nas aulas foi utilizada a versão **2.32.0** se não me engano. Vale lembrar que sou user do Windows logo, minhas anotações estão todas mais direcionadas à esse OS. :smirk: 

## Agora vamos para as linhas de comando básicas mais usadas

- dir :arrow_right:  Lista os diretórios
- cd / :arrow_right:  entra na pasta
- cd windows :arrow_right:  move para a pasta windows
- cls (Ou Crtl + L) :arrow_right:  limpa a tela
- Tecla: TAB :arrow_right:  completa a digitação
- mkdir *nomedapasta* :arrow_right:  cria uma pasta (repositório)
- echo *nomedoarquivo* :arrow_right:  cria o arquivo
- rmdir *nomedapasta* /S /Q :arrow_right:  descarta o repositório
- del :arrow_right: descarta o arquivo

## Conhecimento geral sobre o funcionamento do Git

### :cop: SHA - Secure Hash Algorithm

Trata-se de um algoritmo que gera uma chave de 40 dígitos. Utilizamos aqui para realizar o transito de dados seguro no github. 

### :large_blue_circle:  Blobs

Objeto usado para armazenar o conteúdo de cada arquivo em um repositório (guarda metadados).

### :evergreen_tree: Tree

Uma árvore de blobs. Pode apontar para outros dados e árvores.

### :memo: Commit 

Os commits são as unidades estruturais de um cronograma de projeto no git. Guarda os dados e descrição dos blobs e árvores. Verificando o SHA do Commit, é possível saber se um arquivo de código foi alterado ou não. 

 ## Chave SSH

Para criar, utilizamos o comando abaixo:

:heavy_check_mark:**ssh-keygen -t ed25519 -c (*seu e-mail no github*)**

**Obs.: ** Em algumas situações no Windows, este comando não funciona. No meu caso, meu Windows está com alguns problemas de atualização;drives e creio que me impediu de utilizar este comando. Após pesquisar no help do github, pude substituir este código pelo comando abaixo e deu certo:

:heavy_check_mark:**ssh-keygen -t rsa -b 4096 -C "*Seu e-mail no github*"**

Em seguida, use os comandos abaixo:

:heavy_check_mark: **eval $ (ssh-agent -s)**

:heavy_check_mark: **ssh-add id_*id informado no passo anterior***

## Token de acesso Pessoal

Para utilizar o token, basta gerar na página do github e copiar o código. Vale lembrar que o código deve ser guardado assim que gerado pois não será exibido novamente. Este código também pode expirar dependendo do tempo na configuração aplicada.

## Comandos do Git para ação e commit

- git init :arrow_right:  Cria novo repositório
- git add * :arrow_right:  Adiciona todos os arquivos
- git commit -m "*Nome do commit*":arrow_right:  Cria a descrição que receberá o commit
- git push *NomeDaMaquina(normalmente usa-se Origin)* main :arrow_right: ' empurra' o conteúdo para o github
- git pull *NomeDaMaquina(normalmente usa-se Origin)* main :arrow_right: 'puxa' o conteúdo do github
- git clone (*url do código*) :arrow_right: clona o código do github escolhido



:scroll: // Espero que estas informações sejam úteis! Att. TatiRondoni

Bons estudos para todos nós :pray:







  







