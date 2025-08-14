# Open Source Alternatives to AWS Services

Groups covered: Storage, Database, Analytics, Compute

AWS Service             | What it does              | OSS Alternatives
------------------------|---------------------------|-----------------
S3                      | Object store              | [Minio](https://min.io/), [Swift](https://launchpad.net/swift), [Ceph](https://ceph.io/), ...
EFS                     | File system               | [Gluster](https://github.com/gluster/glusterfs)
FSx                     | File system               | [Lustre](http://lustre.org/)
Storage Gateway         | Hybrid storage            | [SeaweedFS](https://github.com/seaweedfs/seaweedfs)
RDS                     | Relational database       | [MariaDB](https://mariadb.org/), [MySQL](https://www.mysql.com/), [Postgres](https://www.postgresql.org/)
DynamoDB                | NoSQL database            | [Apache Cassandra](https://cassandra.apache.org/)
ElastiCache             | In-memory cache           | [Memcached](https://www.memcached.org/), [Redis](https://redis.io/), [Valkey](https://github.com/valkey-io/valkey)
Neptune                 | Graph database            | [Neo4j](https://neo4j.com/)
Amazon Redshift         | Data warehousing          | [Spark SQL](https://spark.apache.org/sql/), [Apache Hive](https://hive.apache.org/), [Trino](https://github.com/trinodb/trino), [StarRocks](https://github.com/StarRocks/starrocks), [Clickhouse](https://github.com/ClickHouse/ClickHouse)
Amazon QLDB             | Ledger database           | [Hyperledger Fabric](https://github.com/hyperledger/fabric)
Amazon DocumentDB       | Document database         | [MongoDB](https://www.mongodb.com/)
Athena                  | Data warehousing          | [Spark SQL](https://spark.apache.org/sql/), [Apache Hive](https://hive.apache.org/), [Trino](https://github.com/trinodb/trino)
EMR                     | Hadoop / Spark            | [Apache Spark](https://spark.apache.org/)
CloudSearch             | Search                    | [Opensearch](https://github.com/opensearch-project/OpenSearch)
Opensearch Service      | Opensearch                | [Opensearch](https://github.com/opensearch-project/OpenSearch)
Kinesis                 | Data streaming            | [Apache Kafka](https://kafka.apache.org/), [AutoMQ](https://github.com/AutoMQ/automq)
QuickSight              | Business analytics        | [Apache Superset](https://github.com/apache/superset), [Metabase](https://github.com/metabase/metabase)
AWS Glue                | ETL                       | [Apache Airflow](https://airflow.apache.org/), [Apache NiFi](https://github.com/apache/nifi)
AWS Lake Formation      | Data lake                 | [HDFS](http://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/HdfsUserGuide.html)
MSK                     | Data streaming            | [Apache Kafka](https://kafka.apache.org/)
EC2                     | Virtual machines
EC2 EBS                 | Block storage for EC2     | [OpenEBS](https://www.openebs.io/), [Portworx](https://github.com/portworx/px-dev)
Lightsail               | Virtual machines
ECR                     | Container registry        | [Docker Registry](https://github.com/docker/distribution), [Quay](https://quay.io/), [Harbor](https://github.com/goharbor/harbor)
ECS                     | Container orchestration   | [Kubernetes](https://kubernetes.io/), [Marathon](https://mesosphere.github.io/marathon/)
EKS                     | Container orchestration   | [Kubernetes](https://kubernetes.io/)
Lambda                  | Serverless                | [Knative](https://knative.dev/), [OpenFaaS](https://www.openfaas.com/), [Fn](https://fnproject.io/)
Batch                   | Job queue                 | [Apache Airflow](https://airflow.apache.org/)
Elastic Beanstalk       | App deployment
Serverless App. Repo.   | Serverless repository
CloudFormation          | Infrastructure as Code    | [OpenTofu](https://github.com/opentofu/opentofu), [Pulumi](https://github.com/pulumi/pulumi), [Crossplane](https://github.com/crossplane/crossplane)
CodeBuild               | Continuous Integration    | [Jenkins](https://github.com/jenkinsci/jenkins), [Woodpecker](https://github.com/woodpecker-ci/woodpecker),
CodePipeline            | Continuous Delivery       | [ArgoCD](https://github.com/argoproj/argo-cd), [Woodpecker](https://github.com/woodpecker-ci/woodpecker), [Spinnaker](https://github.com/spinnaker/spinnaker)
CodeCommit              | Git Repository            | [Forgejo](https://codeberg.org/forgejo/forgejo)
CloudWatch              | Observability             | **Monitoring:** [Prometheus](https://github.com/prometheus/prometheus) + [Grafana](https://github.com/grafana/grafana), **Logging:** [Opensearch](https://github.com/opensearch-project/OpenSearch) + [Vector](https://github.com/vectordotdev/vector) + [Opensearch Dashboards](https://github.com/opensearch-project/OpenSearch-Dashboards), **Incident Management:** [GoAlert](https://github.com/target/goalert)
Secrets Manager         | Secret Management         | [OpenBao](https://github.com/openbao/openbao)
App Mesh                | Service Mesh              | [Istio](https://github.com/istio/istio), [Kuma](https://github.com/kumahq/kuma), [Linkerd](https://github.com/linkerd/linkerd2)
Cognito                 | Identity Provider         | [Keycloak](https://github.com/keycloak/keycloak), [Casdoor](https://github.com/casdoor/casdoor)
API Gateway             | API Gateway               | [Apache APISIX](https://github.com/apache/apisix)
ALB                     | L7 load balancer          | [NGINX](https://github.com/nginx/nginx), [Envoy](https://github.com/envoyproxy/envoy)
NLB                     | L4 load balancer          | [NGINX](https://github.com/nginx/nginx), [Envoy](https://github.com/envoyproxy/envoy)
MQ                      | Message broker            | [RabbitMQ](https://github.com/rabbitmq/rabbitmq-server), [ActiveMQ](https://github.com/apache/activemq)
SQS                     | Message queue (pull)   | [Apache Kafka](https://kafka.apache.org/), [AutoMQ](https://github.com/AutoMQ/automq)
SNS                     | Message queue (push)   | [RabbitMQ](https://github.com/rabbitmq/rabbitmq-server)
Aurora DSQL             | Distributed SQL DB     | [YugabyteDB](https://github.com/yugabyte/yugabyte-db), [TiDB](https://github.com/pingcap/tidb)
