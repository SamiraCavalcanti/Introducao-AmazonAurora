# Introduction-to-Amazon-Aurora
Laboratório 


# O Amazon Aurora é um Relational Database Management System (RDBMS – Sistema de gerenciamento de banco de dados relacional)
Criado para a nuvem com total compatibilidade com MySQL e PostgreSQL. O Aurora oferece a performance e a disponibilidade de
bancos de dados de nível comercial por um décimo do custo.

  fonte: https://aws.amazon.com/pt/rds/aurora/

# O Amazon Relational Database Service (Amazon RDS) 
É uma coleção de serviços gerenciados que facilita a configuração, operação e escalabilidade de bancos de dados na nuvem. Escolha entre sete opções de mecanismos bastante utilizados: Amazon Aurora compatível com MySQL, Amazon Aurora compatível com PostgreSQL, MySQL, MariaDB, PostgreSQL, Oracle e SQL Server. Depois, implante on-premises com o Amazon RDS no AWS Outposts.

fonte: https://aws.amazon.com/pt/rds/?gclid=CjwKCAiAvJarBhA1EiwAGgZl0P2Lw2XhBnFZXxJrpzz4nIXkJWSYZxNdYjLJtIQoDkWM-ao86_7RkhoC9cEQAvD_BwE&trk=eca03f9c-ce0f-4704-b08e-e6fe66f1f54d&sc_channel=ps&ef_id=CjwKCAiAvJarBhA1EiwAGgZl0P2Lw2XhBnFZXxJrpzz4nIXkJWSYZxNdYjLJtIQoDkWM-ao86_7RkhoC9cEQAvD_BwE:G:s&s_kwcid=AL!4422!3!548640877181!e!!g!!amazon%20rds!12024809973!118832469809




OBJETIVOS:
Nesse laboratório aprendi:

	 Criar uma instância do Amazon Aurora  
 	 Conectar-se a uma instância pré-criada do Amazon RDS para MySQL
 	 Conectar-se a uma instância pré-criada do Amazon EC2 que tenha o MySQL Workbench instalado
 	 Carregar dados na instância do Amazon RDS para MySQL a partir de um arquivo de despejo
 	 Carregar dados na instância do Amazon Aurora a partir do mesmo arquivo de despejo
 	 Consultar os dados na instância do Amazon Aurora
 	 Consultar os dados na instância do Amazon RDS para MySQL e comparar os resultados

Tarefa 1: criei uma instância do Amazon Aurora

![image](https://github.com/SamiraCavalcanti/Introducao-AmazonAurora/assets/86758007/6a548d64-dce0-4803-a83d-c1f987b9eb5e)

Tarefa 2: login na minha instância Amazon EC2 usando o Gerenciador de frota do AWS Systems Manager


![image](https://github.com/SamiraCavalcanti/Introducao-AmazonAurora/assets/86758007/d08391bb-30de-47b8-ab0b-687b8b3d8b55)



Tarefa 3: conectando à minha instância do Amazon RDS

Antes de se conectar aos bancos de dados a partir da instância do Windows, você precisa obter os detalhes da conexão do banco de dados para seu banco de dados

1-OBTENHA SEU ENDPOINT MYSQL

2-OBTENHA SEU ENDPOINT DO AURORA

3-INICIEI O MYSQL WORKBENCH


![image](https://github.com/SamiraCavalcanti/Introducao-AmazonAurora/assets/86758007/edd808e3-32a7-497f-b38f-5f361b5857a8)



4-CONECTANDO AOS MEUS BANCOS DE DADOS

![image](https://github.com/SamiraCavalcanti/Introducao-AmazonAurora/assets/86758007/c049f7c5-a79e-4be0-a08e-e168be48a202)

Finalização da tarefa 3,as duas conexões com o Aurora e MySQL foram realizadas com sucesso

![image](https://github.com/SamiraCavalcanti/Introducao-AmazonAurora/assets/86758007/2f6f0e00-099d-4806-8ec8-91ef3fbdc974)


Tarefa 4: importar um arquivo de despejo SQL para seus bancos de dados

1-IMPORTAR O ARQUIVO DE DESPEJO PARA O BANCO DE DADOS MYSQL

Apos via powershell colocar o arquivo na área de trablho

![image](https://github.com/SamiraCavalcanti/Introducao-AmazonAurora/assets/86758007/3b653d8d-91a4-4967-9e1b-77036066299b)

Realizei o import

![image](https://github.com/SamiraCavalcanti/Introducao-AmazonAurora/assets/86758007/7be0ada9-1e67-4e2f-ad16-70d4a2909158)


E o banco de dados chamado world foi criado

![image](https://github.com/SamiraCavalcanti/Introducao-AmazonAurora/assets/86758007/a001461b-005a-47c0-a138-a8555c603cd7)

2-IMPORTAR O ARQUIVO DE DESPEJO PARA O BANCO DE DADOS DO AURORA
Usei as mesmas etapas para despejo do arquivo no BD Aurora

![image](https://github.com/SamiraCavalcanti/Introducao-AmazonAurora/assets/86758007/5a608bff-85a1-4528-b242-dbb4a1292e50)


Tarefa 5: consultar os bancos de dados

EXECUTE UMA CONSULTA NO BANCO DE DADOS MYSQL

![image](https://github.com/SamiraCavalcanti/Introducao-AmazonAurora/assets/86758007/9c75a4f1-67cd-4f78-aa06-4f703c7fe554)

EXECUTAR UMA CONSULTA NO BANCO DE DADOS DO AURORA

![image](https://github.com/SamiraCavalcanti/Introducao-AmazonAurora/assets/86758007/03df2775-af9a-44bb-aa74-cb6533e490a2)









