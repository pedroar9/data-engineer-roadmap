> Versão de texto para usuários com deficiência visual

# Engenheiro de dados em 2024

* Fundamentos de CS
  * Uso básico de terminal [recomendação geral]
  * Estruturas de dados e algoritmos [recomendação geral]
  * APIs [recomendação geral]
  * REST [recomendação geral]
  * Dados estruturados vs. não estruturados [recomendação geral]
  * Serialização
    * Linux [recomendação geral]
    * CLI
    * Vim
    * Shell scripting
    * Cronjobs
  * Como o computador funciona? [recomendação geral]
  * Como a Internet funciona? [recomendação geral]
  * Git — Controle de versão [recomendação geral]
  * Noções básicas de matemática e estatística [recomendação geral]

**Observação: o Git é usado para rastrear alterações no código-fonte e coordenar o trabalho entre os programadores. No seu trabalho diário, você usará o servidor Git como um serviço como GitHub, GitLab ou Bitbucket.**

* Aprenda uma linguagem de programação
  * Python [recomendação pessoal]
  * Java [recomendação geral]
  * Scala
  * Go

**Observação: aprenda a escrever código limpo e extensível. Passe algum tempo entendendo paradigmas de programação (funcional vs. OOP) e melhores práticas (padrões de design, YAGNI, aplicativos com estado vs. sem estado). Familiarize-se com um IDE ou editor de código como o VSCode.**

* Testes
  * Testes unitários [recomendação geral]
  * Testes de integração [recomendação geral]
  * Testes funcionais [recomendação geral]

* Fundamentos de banco de dados
  * SQL [recomendação geral]
  * Normalização [recomendação geral]
  * Transações ACID [recomendação geral]
  * Teorema CAP [recomendação geral]
  * OLTP vs OLAP [recomendação geral]
  * Escala horizontal vs vertical [recomendação geral]
  * Modelagem dimensional [recomendação geral]

* Bancos de dados relacionais
  * MySQL [recomendação geral]
  * PostgreSQL [recomendação geral]
  * MariaDB
  * Amazon Aurora
  * SQLite
  * DuckDB

* Bancos de dados não relacionais
  
* Bancos de dados orientado a documentos
  * MongoDB [recomendação geral]
  * Firebase Firestore
  * Elasticsearch [recomendação geral]
  * Apache CouchDB
  * Azure CormosDB
  * Amazon DocumentDB
* 
* Bancos de dados de colunar
  * Apache Cassandra [recomendação geral]
  * Apache HBase [recomendação geral]
  * Google BigQuery [recomendação pessoal]
  * Amazon Redshift
  * Snowflake
  * Kudu
  * InfiniDB
  * MonetDB
  * ClickHouse

* Bancos de dados de Grafos
  * Neo4j
  * Amazon Neptune
  * OrientDB
  * ArangoDB
  * JanusGraph
  * TigerGraph
 
* Bancos de dados chave-valor
  * Redis [recomendação pessoal]
  * Memcached
  * Amazon DynamoDB [recomendação geral]
  * Riak KV
  * LevelDB
  * RocksDB
  * Couchbase
  * Tair
 
**Observação: entenda a diferença entre bancos de dados NoSQL, de documento, colunares, grafos e chave-valor. Recomendamos dominar um banco de dados de cada categoria.**

* Data warehouses
  * Snowflake [recomendação geral]
  * Presto
  * Apache Hive
  * Apache Impala
  * Amazon Redshift [recomendação geral]
  * Google BigQuery [recomendação pessoal]
  * Azure Synapse
  * ClickHouse

* Armazenamento de objetos
  * AWS S3 [recomendação geral]
  * Azure Blob Storage
  * Google Cloud Storage
  * Apache Ozone

* Fundamentos da computação em cluster
  * Apache Hadoop [recomendação geral]
  * HDFS [recomendação geral]
  * MapReduce [recomendação geral]
  * Arquiteturas Lambda e Kappa
  * Managed Hadoop [recomendação geral]
    * Amazon EMR
    * Google Dataproc
    * Azure Data Lake

**Observação: a maioria das estruturas modernas de processamento de dados é baseada no Apache Hadoop e no MapReduce até certo ponto. Entender esses conceitos pode ajudar você a aprender estruturas modernas de processamento de dados muito mais rápido.**

* Processamento de dados
  * Batch (em Lote)
    * Apache Pig [recomendação geral]
    * Apache Arrow
    * Ferramenta de construção de dados [recomendação pessoal]
  * Híbrido
    * Apache Spark [recomendação geral]
    * Apache Beam [recomendação pessoal]
    * Apache Flink [recomendação geral]
    * Apache NiFi
  * Streaming (em eventos ou fluxos)
    * Apache Kafka [recomendação pessoal]
    * Apache Storm [recomendação geral]
    * Apache Samza
    * Amazon Kinesis

**Observação: estruturas híbridas são capazes de processar dados em lote e em streaming.**  
**O processamento de dados em lote geralmente é feito por aplicativos de data warehouse analíticos. Veja a seção Data warehouses para mais informações.**

* Mensagens
  * RabbitMQ [recomendação geral]
  * Apache ActiveMQ
  * Amazon SNS e SQS
  * Google PubSub
  * Azure Service Bus

* Agendamento de fluxo de trabalho
  * Apache Airflow [recomendação pessoal]
  * Google Composer
  * Apache Oozie
  * Luigi

**Observação: o Cloud Composer é um serviço gerenciado do Apache Airflow no Google Cloud Platform.**

* Monitoramento e observabilidade para pipelines de dados
  * Prometheus [recomendação geral]
  * Datadog [recomendação geral]
  * Sentry [recomendação geral]
  * Monte Carlo
  * Datafold
  * Soda Data
  * StatsD
  * Dagster
  * Prefect

* Redes
  * Protocolos [recomendação geral]
    * HTTP / HTTPS
    * TCP
    * SSH
    * IP
    * DNS
  * Firewalls [recomendação geral]
  * VPN [recomendação geral]
  * VPC [recomendação geral]

* Infraestrutura como código
  * Contêineres
  * Docker [recomendação pessoal]
  * Linux Containers (LXC)
* Orquestração de contêineres
  * Kubernetes [recomendação geral]
  * Docker Swarm
  * Apache Mesos
  * Google Kubernetes Engine (GKE) [recomendação geral]
* Provisionamento de infraestrutura
  * Terraform [recomendação pessoal]
  * Pulumi
  * AWS CDK [recomendação geral]
  
* CI/CD