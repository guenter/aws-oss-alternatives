# Open Source Alternatives to AWS Services

Groups covered: Storage, Database, Analytics, Compute

AWS Service             | What it does              | OSS Alternatives
------------------------|---------------------------|-----------------
S3                      | Object store              | Minio, Swiftstack, Ceph, ...
EFS                     | File system
FSx                     | File system               | Lustre
S3 Glacier              | Archive storage
Storage Gateway         | Hybrid storage            |
AWS Backup              | Backup for AWS services   | n/a
RDS                     | Relational database       | MySQL, Postgres, Oracle, SQL Server
DynamoDB                | NoSQL database            | Apache Cassandra
ElastiCache             | In-memory cache           | Memcached, Redis
Neptune                 | Graph database            | Neo4J
Amazon Redshift         | Data warehousing          | Hive
Amazon QLDB             | Ledger database
Amazon DocumentDB       | Document database         | MongoDB
Athena                  | Data warehousing          | Presto
EMR                     | Hadoop / Spark            | Apache Spark
CloudSearch             | Search                    | Elastic
Elasticsearch Service   | Elasticsearch             | Elastic
Kinesis                 | Data streaming            | Apache Kafka
QuickSight              | Business analytics
Data Pipeline           | ETL                       | Apache Airflow
AWS Glue                | ETL                       | Apache Airflow
AWS Lake Formation      | Data lake                 | Apache HDFS
MSK                     | Data streaming            | Apache Kafka
EC2                     | Virtual machines
EC2 EBS                 | Block storage for EC2     | OpenEBS, Portworx
Lightsail               | Virtual machines
ECR                     | Container registry        | Docker, Quay
ECS                     | Container orchestration   | Kubernetes, Marathon
EKS                     | Container orchestration   | Kubernetes
Lambda                  | Serverless                | Knative, OpenFaaS, Fn
Batch                   | Job queue                 | Apache Airflow
Elastic Beanstalk       | App deployment
Serverless App. Repo.   | Serverless repository