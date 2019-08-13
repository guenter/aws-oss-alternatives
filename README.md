# Open Source Alternatives to AWS Services

Groups covered: Storage, Database, Analytics, Compute

AWS Service             | What it does              | OSS Alternatives
------------------------|---------------------------|-----------------
S3                      | Object store              | [Minio](https://min.io/), [Swift](https://launchpad.net/swift), [Ceph](https://ceph.io/), ...
EFS                     | File system
FSx                     | File system               | [Lustre](http://lustre.org/)
S3 Glacier              | Archive storage
Storage Gateway         | Hybrid storage            |
AWS Backup              | Backup for AWS services   | n/a
RDS                     | Relational database       | [MariaDB](https://mariadb.org/), [MySQL](https://www.mysql.com/), [Postgres](https://www.postgresql.org/)
DynamoDB                | NoSQL database            | [Apache Cassandra](https://cassandra.apache.org/)
ElastiCache             | In-memory cache           | [Memcached](https://www.memcached.org/), [Redis](https://redis.io/)
Neptune                 | Graph database            | [Neo4j](https://neo4j.com/)
Amazon Redshift         | Data warehousing          | [Spark SQL](https://spark.apache.org/sql/), [Apache Hive](https://hive.apache.org/), [Presto](https://prestodb.github.io/)
Amazon QLDB             | Ledger database
Amazon DocumentDB       | Document database         | [MongoDB](https://www.mongodb.com/)
Athena                  | Data warehousing          | [Spark SQL](https://spark.apache.org/sql/), [Apache Hive](https://hive.apache.org/), [Presto](https://prestodb.github.io/)
EMR                     | Hadoop / Spark            | [Apache Spark](https://spark.apache.org/)
CloudSearch             | Search                    | [Elasticsearch](https://www.elastic.co/products/elasticsearch)
Elasticsearch Service   | Elasticsearch             | [Elasticsearch](https://www.elastic.co/products/elasticsearch)
Kinesis                 | Data streaming            | [Apache Kafka](https://kafka.apache.org/)
QuickSight              | Business analytics
Data Pipeline           | ETL                       | [Apache Airflow](https://airflow.apache.org/)
AWS Glue                | ETL                       | [Apache Airflow](https://airflow.apache.org/)
AWS Lake Formation      | Data lake                 | [HDFS](http://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/HdfsUserGuide.html)
MSK                     | Data streaming            | [Apache Kafka](https://kafka.apache.org/)
EC2                     | Virtual machines
EC2 EBS                 | Block storage for EC2     | [OpenEBS](https://www.openebs.io/), [Portworx](https://github.com/portworx/px-dev)
Lightsail               | Virtual machines
ECR                     | Container registry        | [Docker Registry](https://github.com/docker/distribution), [Quay](https://quay.io/)
ECS                     | Container orchestration   | [Kubernetes](https://kubernetes.io/), [Marathon](https://mesosphere.github.io/marathon/)
EKS                     | Container orchestration   | [Kubernetes](https://kubernetes.io/)
Lambda                  | Serverless                | [Knative](https://knative.dev/), [OpenFaaS](https://www.openfaas.com/), [Fn](https://fnproject.io/)
Batch                   | Job queue                 | [Apache Airflow](https://airflow.apache.org/)
Elastic Beanstalk       | App deployment
Serverless App. Repo.   | Serverless repository