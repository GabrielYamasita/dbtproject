# Dbt Project

Projeto de Dbt realizado em curso prático.

Foi utilizada a base de dados Northwind que é gratuitamente disponibilizada pela Microsoft.

[Link da Database Northwind](https://docs.yugabyte.com/preview/sample-data/northwind/)

Tecnologias usadas no projeto:
* S3 (para realizar copy de dados em csv para o Redshift)
* Redshift Serverless (como banco de dados de dev e produção)
* Dbt Cloud (IDE web do Dbt para desenvolvimento dos modelos de transformação e testes, em SQL)

---
![DER do Northwind](https://docs.yugabyte.com/images/sample-data/northwind/northwind-er-diagram.png)
