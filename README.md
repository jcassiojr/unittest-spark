# Teste unitário no Apache Spark

## Descrição
Projeto de exemplo de aplicação de teste unitário no Apache Spark.


####Configuração do Ambiente:

* Apache Spark 1.5 (configuração local para rodar os testes)
* Python 2.7 (Anaconda 2)
* Adicionar as bibliotecas abaixo ao projeto que podem ser encontradas dentro da pasta python/lib do Spark (versão de download source. Ex: spark-1.6.0-bin-hadoop2.6): py4j-0.9-src.zip e pyspark.zip
* Caso esteja utilizando a ferramenta lieclipse para desenvolvimento apontar o interpretador do python para o do Anaconda e setar o pydev_pythonpath adicionando o source do projeto.
* Para funcionamento dos testes configurar as variáveis de ambiente do projeto conforme abaixo:

#####PYSPARK_SUBMIT_ARGS
 
--master local[*] --queue PyDevSpark1.5.2 --packages com.databricks:spark-csv_2.10:1.4.0 pyspark-shell

#####SPARK_HOME

~/spark-1.5.2


