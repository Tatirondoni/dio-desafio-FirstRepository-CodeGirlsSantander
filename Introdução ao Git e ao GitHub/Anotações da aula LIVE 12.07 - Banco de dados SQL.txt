:scroll: **// Nota inicial:** Aproveitei o gancho deste módulo e também gerei este arquivo para testar a postagem de mais de um item no repositório e também, firmar os conhecimentos adquiridos na Live de hoje sobre Banco de dados relacional (SQL). 

<img src="https://data.whicdn.com/images/243099135/original.gif" alt="alt text" style="zoom:120%;" />

## Vamos iniciar com informações básicas

:small_orange_diamond:Banco de dados relacional 

Armazena dados em tabelas (linhas e colunas). 

:small_orange_diamond:Restrição de integridade

Garantir a exatidão e consistência dos dados.

:small_orange_diamond:Chave Primaria (Primary Key ou PK)

identificador de registro único. Impede que o ID / registro seja duplicado.

:small_orange_diamond:Chave Estrangeira (Foreign Key)

Relaciona informações de tabelas distintas (esta ação diminui o uso de dados e otimiza o armazenamento).

:small_orange_diamond:SQL

Linguagem padrão de um banco de dados. Utilizada nas mais diferentes plataformas SQL. 

## Comandos SQL - Executados no Oracle

*Exp.:*

***Obs.: apesar do exemplo utilizado pelo palestrante (no intuito de facilitar o entendimento), há a convenção de que nomes de dados no SQL sejam escritos sempre em inglês. Desta forma, irei reestruturar de forma a atender esta convenção.**

:clipboard: **create table** clients (ID number (5), name varchar (50), lastname varchar (50), city_ID number (5), state_ID number(5));

:clipboard: **alter table** clients add constraint ID_clients_PK primary key (ID);

:clipboard: **alter table** clients add constraint ID_clients_ foreign key (ID);

:clipboard: **insert into** name (ID_name, name) values (1, 'Tatiane');

:clipboard: **select * from** name; 



Estes foram alguns dos comandos utilizados na aula. Espero ter ajudado! :smile:

Att. TatiRondoni

