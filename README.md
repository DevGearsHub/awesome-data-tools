# Awesome Data Tools

A curated list of cloud-based data tools, platforms, and services with free tiers for data engineers, analysts, and scientists.

This list focuses on helping developers and data professionals discover cloud services that offer free tiers for data processing, storage, analytics, and machine learning. All services listed must have a genuinely free tier (not just a trial) that lasts at least one year.

**🌟 Contributions welcome!** Please read the contribution guidelines first.

---

## Table of Contents

- [Major Cloud Providers - Data Services](#major-cloud-providers---data-services)
- [Cloud Data Warehouses](#cloud-data-warehouses)
- [Cloud Databases](#cloud-databases)
- [Cloud Storage for Data](#cloud-storage-for-data)
- [Cloud Analytics & BI](#cloud-analytics--bi)
- [Cloud ETL & Data Integration](#cloud-etl--data-integration)
- [Cloud Data Streaming](#cloud-data-streaming)
- [Cloud Machine Learning & AI](#cloud-machine-learning--ai)
- [Cloud Data Orchestration](#cloud-data-orchestration)
- [Cloud Data Quality & Observability](#cloud-data-quality--observability)
- [Cloud Notebooks & IDEs](#cloud-notebooks--ides)
- [Cloud APIs & Serverless](#cloud-apis--serverless)
- [Cloud Monitoring & Logging](#cloud-monitoring--logging)
- [Data Format Tools & Converters](#data-format-tools--converters)
  - [JSON Tools](#json-tools)
  - [XML Tools](#xml-tools)
  - [YAML Tools](#yaml-tools)
  - [TOON Format Tools](#toon-format-tools)
  - [API Testing & Development](#api-testing--development)

---

## Major Cloud Providers - Data Services

### Amazon Web Services (AWS)

**Data Warehousing & Analytics:**
- **Amazon Redshift** — Free trial available for new users. Query up to 1TB of data per month in S3 using Redshift Spectrum free tier (always free).
- **Amazon Athena** — First 10GB of data scanned per month free (always free).
- **AWS Glue** — 1 million objects stored and 1 million requests per month in Data Catalog (always free). First 1 million ETL requests per month (always free).

**Databases:**
- **Amazon RDS** — 750 hours per month of db.t2.micro, db.t3.micro, or db.t4g.micro instances (enough to run one DB instance continuously). 20GB of General Purpose (SSD) storage, 20GB of backup storage.
- **Amazon DynamoDB** — 25GB of storage, 25 provisioned Write Capacity Units (WCU), 25 provisioned Read Capacity Units (RCU), enough to handle up to 200 million requests per month.
- **Amazon ElastiCache** — 750 hours of cache.t2micro or cache.t3.micro node usage, enough to run one cache node continuously each month.
- **Amazon DocumentDB** — 750 hours of db.t3.medium instance usage, 5GB of storage, 1GB of backup storage free for 1 year.

**Storage:**
- **Amazon S3** — 5GB of standard storage, 20,000 GET requests, 2,000 PUT requests per month for 12 months.
- **Amazon S3 Glacier** — Retrieve up to 10GB of data per month for free.

**Machine Learning:**
- **Amazon SageMaker** — 250 hours per month of t2.medium or t3.medium notebook usage for first 2 months. 50 hours per month of m4.xlarge or m5.xlarge for training. 125 hours per month of m4.xlarge or m5.xlarge for hosting.
- **Amazon Comprehend** — 50,000 units per month for first 12 months (text analysis).
- **Amazon Rekognition** — 5,000 images per month for first 12 months, 1,000 minutes of video per month.

**Data Streaming:**
- **Amazon Kinesis Data Streams** — First 1 million PUT payload units and 2GB of data retention per month (data streams pay-per-use).
- **Amazon MSK (Managed Kafka)** — No free tier but pay-as-you-go pricing available.

**Serverless:**
- **AWS Lambda** — 1 million free requests per month, 400,000 GB-seconds of compute time per month, always free.

### Google Cloud Platform (GCP)

**Data Warehousing & Analytics:**
- **BigQuery** — First 10GB of storage per month free. First 1TB of query data processed per month free. BigQuery ML: First 10GB per month of data processed by ML.CREATE MODEL queries free.
- **Looker Studio (formerly Data Studio)** — Completely free for creating dashboards and reports, unlimited reports and data sources.

**Databases:**
- **Cloud Firestore** — 1GB storage, 50,000 reads, 20,000 writes, 20,000 deletes per day (always free).
- **Cloud SQL** — 30GB HDD storage, 1 shared-core instance with 614MB RAM, 10GB backups (always free, applicable to MySQL, PostgreSQL, and SQL Server).
- **Bigtable** — No perpetual free tier. New user trial credits available.
- **Cloud Spanner** — No free tier, pay-as-you-go pricing.

**Storage:**
- **Cloud Storage** — 5GB-months of regional storage (US regions only), 5,000 Class A operations per month, 50,000 Class B operations per month.
- **Cloud Filestore** — No free tier.

**Machine Learning:**
- **Vertex AI** — New user trial credits available. AutoML services: First 1,000 units per month free for Vision, Natural Language, and Video Intelligence (always free).
- **AI Platform Notebooks** — Managed Jupyter notebooks. New user trial credits available.
- **Natural Language API** — 5,000 text analysis units per month (always free).
- **Vision API** — 1,000 units per month for feature detection (always free).
- **Speech-to-Text API** — 60 minutes per month (always free).
- **Text-to-Speech API** — 1 million characters per month (always free).

**Data Streaming:**
- **Pub/Sub** — First 10GB of messages per month (always free).
- **Dataflow** — New user trial credits available. No perpetual free tier.

**Serverless:**
- **Cloud Functions** — 2 million invocations per month, 400,000 GB-seconds, 200,000 GHz-seconds compute (always free).
- **Cloud Run** — 2 million requests per month, 360,000 GB-seconds memory, 180,000 vCPU-seconds compute (always free).

**Data Processing:**
- **Dataproc (Managed Hadoop/Spark)** — New user trial credits available. Pay-per-use pricing.

### Microsoft Azure

**Data Warehousing & Analytics:**
- **Azure Synapse Analytics** — First 12 months free: 100GB of storage. Pay-as-you-go for compute.
- **Azure Data Lake Storage Gen2** — First 12 months: 5GB of LRS storage. 20,000 read operations, 2,000 write operations.

**Databases:**
- **Azure SQL Database** — 250GB storage free for 12 months.
- **Azure Cosmos DB** — First 1000 RU/s and 25GB of storage free, always free tier.
- **Azure Database for PostgreSQL** — 750 hours of Flexible Server - Burstable B1MS instance per month, 32GB storage and 32GB backup storage for 12 months.
- **Azure Database for MySQL** — 750 hours of Flexible Server - Burstable B1MS instance per month, 32GB storage and 32GB backup storage for 12 months.

**Storage:**
- **Azure Blob Storage** — 5GB LRS hot block blob storage, 20,000 read and 2,000 write operations for 12 months.
- **Azure Files** — 100GB file storage for 12 months.

**Machine Learning:**
- **Azure Machine Learning** — Free tier available with limited compute (standard_d1 instances for training, 2 hours/month).
- **Cognitive Services** — Various free tiers:
  - Text Analytics: 5,000 transactions per month
  - Computer Vision: 5,000 transactions per month
  - Speech Services: 5 audio hours per month for speech-to-text
  - Translator: 2 million characters per month

**Data Streaming:**
- **Azure Event Hubs** — 1 million events per month in Basic tier.
- **Azure Stream Analytics** — First 225,000 Streaming Units (SU) per month free for 12 months.

**Serverless:**
- **Azure Functions** — 1 million requests per month, 400,000 GB-seconds of execution time, always free.

**Data Processing:**
- **Azure Databricks** — Free trial available. No perpetual free tier.
- **Azure HDInsight** — No free tier. Pay-per-use for Hadoop and Spark clusters.

### Oracle Cloud Infrastructure (OCI)

**Always Free Services:**
- **Autonomous Database** — 2 databases (20GB each, 1 OCPU each) for both ATP (Transaction Processing) and ADW (Data Warehouse).
- **Compute** — 2 AMD-based Compute VMs with 1/8 OCPU and 1GB memory each. 4 Arm-based Ampere A1 cores and 24GB of memory usable as 1 VM or up to 4 VMs.
- **Block Volume** — 200GB total of Block Volume and Object Storage. 10GB of Archive Storage.
- **NoSQL Database** — 133 million reads per month, 133 million writes per month, 25GB storage per table, up to 3 tables.
- **Streaming** — 50GB per month.

### IBM Cloud

**Databases:**
- **Db2** — Lite plan: 200MB of data storage, limited to 5 connections.
- **Cloudant (NoSQL)** — Lite plan: 1GB of data storage, 20 lookups/sec, 10 writes/sec, 5 queries/sec.

**Storage:**
- **Cloud Object Storage** — Lite plan: 25GB per month.

**Machine Learning:**
- **Watson Studio** — Lite plan with 50 capacity unit-hours per month.
- **Watson Machine Learning** — Lite plan: 1,000 predictions per month, 5 model deployments.
- **Watson Natural Language Understanding** — Lite plan: 30,000 NLU items per month.

**Analytics:**
- **Cognos Dashboard Embedded** — Lite plan available.

### Alibaba Cloud

**Databases:**
- **AnalyticDB for MySQL** — Free trial available with credits.
- **MaxCompute** — Pay-as-you-go with first-time user promotions.

**Machine Learning:**
- **Machine Learning Platform for AI (PAI)** — Free trial with credits.

---

## Cloud Data Warehouses

- **[Snowflake](https://www.snowflake.com/)** — Free trial available. Starter tier available for testing and development.
- **[Google BigQuery](https://cloud.google.com/bigquery)** — 10GB storage and 1TB query processing per month (always free).
- **[Amazon Redshift Serverless](https://aws.amazon.com/redshift/redshift-serverless/)** — Free trial available for new users.
- **[Azure Synapse Analytics](https://azure.microsoft.com/en-us/services/synapse-analytics/)** — 100GB storage free for first 12 months (new accounts).
- **[Oracle Autonomous Data Warehouse](https://www.oracle.com/cloud/free/)** — Always free: 2 databases (20GB each, 1 OCPU each).
- **[ClickHouse Cloud](https://clickhouse.com/)** — Free trial and always-free tier: 100GB storage with limited compute.
- **[Firebolt](https://www.firebolt.io/)** — Free tier: 50GB storage, limited compute hours per month.

---

## Cloud Databases

### Relational Databases (SQL)

- **[Amazon RDS](https://aws.amazon.com/rds/)** — 750 hours/month of db.t2.micro, 20GB storage, 20GB backup for 12 months.
- **[Google Cloud SQL](https://cloud.google.com/sql)** — 1 shared-core instance, 30GB HDD storage, 10GB backups, always free (with limitations).
- **[Azure SQL Database](https://azure.microsoft.com/en-us/services/sql-database/)** — 250GB storage free for 12 months.
- **[PlanetScale](https://planetscale.com/)** — Free plan: 5GB storage, 1 billion row reads per month, 10 million row writes per month.
- **[Supabase](https://supabase.com/)** — Free plan: 500MB database space, 2GB bandwidth, 50MB file storage, unlimited API requests.
- **[Neon](https://neon.tech/)** — Serverless Postgres, free tier: 3GB storage per project, 1 project, unlimited queries.
- **[CockroachDB Cloud](https://www.cockroachlabs.com/product/cockroachdb-cloud/)** — Free forever: 5GB storage, 50 million RUs per month.
- **[ElephantSQL](https://www.elephantsql.com/)** — PostgreSQL as a service, free plan: 20MB database size, 5 concurrent connections.

### NoSQL Databases

- **[MongoDB Atlas](https://www.mongodb.com/cloud/atlas)** — Free tier (M0): 512MB storage, shared RAM, no credit card required.
- **[Amazon DynamoDB](https://aws.amazon.com/dynamodb/)** — 25GB storage, 25 WCU, 25 RCU (200M requests/month), always free.
- **[Google Firestore](https://firebase.google.com/products/firestore)** — 1GB storage, 50K reads, 20K writes, 20K deletes per day, always free.
- **[Azure Cosmos DB](https://azure.microsoft.com/en-us/services/cosmos-db/)** — 1000 RU/s and 25GB storage, always free.
- **[Astra DB (DataStax)](https://www.datastax.com/products/datastax-astra)** — Free tier: 25GB storage, 5 million writes/month, 25 million reads/month.
- **[Upstash](https://upstash.com/)** — Serverless Redis and Kafka. Free tier: 10,000 commands per day for Redis.
- **[FaunaDB](https://fauna.com/)** — Free tier: 100,000 read ops, 50,000 write ops, 500,000 compute ops per month.
- **[Cloudflare D1](https://www.cloudflare.com/developer-platform/d1/)** — Free tier: 5GB storage, 5 million rows read per day, 100,000 rows written per day.

### Time-Series Databases

- **[InfluxDB Cloud](https://www.influxdata.com/products/influxdb-cloud/)** — Free tier: 30-day data retention, unlimited queries, 10,000 write requests per minute.
- **[TimescaleDB Cloud](https://www.timescale.com/cloud)** — Free trial available. Paid plans start at low monthly fees.
- **[Grafana Cloud](https://grafana.com/products/cloud/)** — Free tier: 10,000 series for Prometheus metrics, 50GB logs, 14-day retention (always free).

### Graph Databases

- **[Neo4j Aura](https://neo4j.com/cloud/aura/)** — Free tier: 200k nodes, 400k relationships, no time limit.
- **[Amazon Neptune](https://aws.amazon.com/neptune/)** — 750 hours of db.t3.medium for 2 months (new customers).

---

## Cloud Storage for Data

- **[Amazon S3](https://aws.amazon.com/s3/)** — 5GB standard storage, 20,000 GET, 2,000 PUT requests/month for 12 months (new accounts).
- **[Google Cloud Storage](https://cloud.google.com/storage)** — 5GB regional storage (US), 5,000 Class A ops, 50,000 Class B ops/month (always free).
- **[Azure Blob Storage](https://azure.microsoft.com/en-us/services/storage/blobs/)** — 5GB LRS storage, 20,000 read, 2,000 write operations for 12 months (new accounts).
- **[Cloudflare R2](https://www.cloudflare.com/products/r2/)** — 10GB storage per month, 1 million Class A operations, 10 million Class B operations (always free).
- **[Backblaze B2](https://www.backblaze.com/b2/cloud-storage.html)** — 10GB storage, first 1GB download per day (always free).
- **[Wasabi](https://wasabi.com/)** — Free trial available (verify current terms).
- **[MinIO](https://min.io/)** — Self-hosted, open-source, S3-compatible object storage (free to use on your infrastructure).

---

## Cloud Analytics & BI

- **[Google Looker Studio](https://lookerstudio.google.com/)** — Unlimited reports and data sources.
- **[Microsoft Power BI](https://powerbi.microsoft.com/)** — Free version with 1GB storage, limited sharing capabilities.
- **[Tableau Public](https://public.tableau.com/)** — Free, but all visualizations must be public.
- **[Metabase Cloud](https://www.metabase.com/pricing)** — Free tier for 5 users, unlimited queries and dashboards.
- **[Apache Superset](https://superset.apache.org/)** — Open source, free to self-host (requires your own infrastructure).
- **[Redash](https://redash.io/)** — Open source, free to self-host. Managed cloud starts at $49/month.
- **[Mode Analytics](https://mode.com/)** — Free plan for public data analysis and sharing.
- **[Observable](https://observablehq.com/)** — Free tier for public notebooks with unlimited views.
- **[Grafana Cloud](https://grafana.com/products/cloud/)** — Free tier: 10,000 series, 50GB logs, 50GB traces, 14-day retention.

---

## Cloud ETL & Data Integration

- **[Airbyte Cloud](https://airbyte.com/)** — Free tier: 20GB data synced per month, unlimited sources and destinations.
- **[Fivetran](https://www.fivetran.com/)** — Free trial available, paid plans start at low monthly fees.
- **[Stitch (Talend)](https://www.stitchdata.com/)** — Free trial available with data row limits.
- **[AWS Glue](https://aws.amazon.com/glue/)** — 1 million objects and 1 million requests per month in Data Catalog (always free). First 1 million ETL requests per month (always free).
- **[Google Cloud Dataflow](https://cloud.google.com/dataflow)** — No perpetual free tier. New user trial credits available.
- **[Azure Data Factory](https://azure.microsoft.com/en-us/services/data-factory/)** — First 5 low-frequency activities per month for 12 months (new accounts).
- **[Hevo Data](https://hevodata.com/)** — Free tier: 1 million events per month, limited sources.
- **[Singer (Open Source)](https://www.singer.io/)** — Open source ETL tool, self-hosted.
- **[Meltano (Open Source)](https://meltano.com/)** — Open source data integration platform, self-hosted.

---

## Cloud Data Streaming

- **[Amazon Kinesis](https://aws.amazon.com/kinesis/)** — 1 million PUT payload units per month, 2GB data retention for first 12 months (new accounts).
- **[Google Pub/Sub](https://cloud.google.com/pubsub)** — First 10GB of messages per month (always free).
- **[Azure Event Hubs](https://azure.microsoft.com/en-us/services/event-hubs/)** — 1 million events per month in Basic tier for 12 months (new accounts).
- **[Confluent Cloud (Kafka)](https://www.confluent.io/confluent-cloud/)** — Free trial available. Basic cluster with limited monthly usage.
- **[Upstash Kafka](https://upstash.com/)** — Free tier: 10,000 messages per day, 1 topic, 1 partition.
- **[Redpanda Cloud](https://redpanda.com/)** — Free tier: 10GB storage, 10MB/s throughput.
- **[Apache Kafka (Open Source)](https://kafka.apache.org/)** — Free to self-host.
- **[Apache Pulsar (Open Source)](https://pulsar.apache.org/)** — Free to self-host.

---

## Cloud Machine Learning & AI

### ML Platforms

- **[Google Colab](https://colab.research.google.com/)** — Free Jupyter notebooks with GPU/TPU access (limited compute hours).
- **[Kaggle Notebooks](https://www.kaggle.com/code)** — Free notebooks with 30 hours/week of GPU/TPU time.
- **[Amazon SageMaker](https://aws.amazon.com/sagemaker/)** — Free tier for first 2 months (new accounts): 250 hours notebooks, 50 hours training, 125 hours hosting.
- **[Azure Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/)** — Free tier with limited compute hours.
- **[Google Vertex AI](https://cloud.google.com/vertex-ai)** — New user trial credits available. Free tier for certain APIs.
- **[Hugging Face](https://huggingface.co/)** — Free hosting for models and datasets, limited inference API.
- **[Replicate](https://replicate.com/)** — Free tier with monthly credits for running AI models.
- **[Paperspace Gradient](https://www.paperspace.com/gradient)** — Free tier with limited GPU hours.

### AI APIs

- **[OpenAI API](https://openai.com/api/)** — Free trial credits for new users (time-limited).
- **[Anthropic Claude](https://www.anthropic.com/)** — API access with usage-based pricing (no perpetual free tier).
- **[Google Gemini API](https://ai.google.dev/)** — Free tier: 60 queries per minute.
- **[Cohere](https://cohere.com/)** — Free tier for testing with limited API calls.
- **[Hugging Face Inference API](https://huggingface.co/inference-api)** — Free tier with rate limits.

---

## Cloud Data Orchestration

- **[Apache Airflow (Cloud Composer)](https://cloud.google.com/composer)** — No perpetual free tier. New GCP user trial credits available.
- **[Astronomer (Managed Airflow)](https://www.astronomer.io/)** — Free trial available, then paid plans.
- **[Prefect Cloud](https://www.prefect.io/)** — Free tier: 20,000 task runs per month.
- **[Dagster Cloud](https://dagster.io/cloud)** — Free tier: 1 deployment, unlimited jobs.
- **[AWS Step Functions](https://aws.amazon.com/step-functions/)** — 4,000 state transitions per month (always free).
- **[Azure Logic Apps](https://azure.microsoft.com/en-us/services/logic-apps/)** — 4,000 built-in actions per month for 12 months (new accounts).
- **[Kestra](https://kestra.io/)** — Open source, free to self-host. Managed cloud in development.
- **[Temporal Cloud](https://temporal.io/)** — Free tier: 1,000 workflow executions per month.

---

## Cloud Data Quality & Observability

- **[Monte Carlo](https://www.montecarlodata.com/)** — 14-day free trial, then paid.
- **[Datafold](https://www.datafold.com/)** — Free tier for open source projects.
- **[Great Expectations Cloud](https://greatexpectations.io/)** — Open source core is free; cloud has free trial.
- **[Bigeye](https://www.bigeye.com/)** — Free trial available.
- **[Soda Cloud](https://www.soda.io/)** — Free tier: 1 million rows scanned per month.
- **[dbt Cloud](https://www.getdbt.com/pricing/)** — Free tier: 1 developer seat, 3,000 model runs per month.
- **[Lightup](https://www.lightup.ai/)** — Free trial available.
- **[Databand](https://databand.ai/)** — Free trial, then paid.

---

## Cloud Notebooks & IDEs

- **[Google Colab](https://colab.research.google.com/)** — Free Jupyter notebooks with GPU/TPU, limited compute.
- **[Kaggle Notebooks](https://www.kaggle.com/code)** — Free with 30 hours/week GPU/TPU time.
- **[Deepnote](https://deepnote.com/)** — Free tier: unlimited notebooks, 5GB storage, basic compute.
- **[Observable](https://observablehq.com/)** — Free for public notebooks, unlimited views.
- **[Hex](https://hex.tech/)** — Free tier: 3 editors, unlimited viewers, 60 hours compute per month.
- **[Databricks Community Edition](https://community.cloud.databricks.com/)** — Free tier: 15GB cluster, limited compute hours.
- **[JupyterLab on AWS SageMaker](https://aws.amazon.com/sagemaker/)** — 250 hours per month for 2 months (new accounts).
- **[Vertex AI Workbench](https://cloud.google.com/vertex-ai-workbench)** — New GCP user trial credits available.
- **[Azure ML Notebooks](https://azure.microsoft.com/en-us/services/machine-learning/)** — Free tier with limited compute.
- **[Replit](https://replit.com/)** — Free tier for coding and collaboration (not data-specific but useful).

---

## Cloud APIs & Serverless

- **[AWS Lambda](https://aws.amazon.com/lambda/)** — 1 million requests per month, 400,000 GB-seconds compute, always free.
- **[Google Cloud Functions](https://cloud.google.com/functions)** — 2 million invocations, 400,000 GB-seconds, 200,000 GHz-seconds per month, always free.
- **[Azure Functions](https://azure.microsoft.com/en-us/services/functions/)** — 1 million requests, 400,000 GB-seconds execution time per month, always free.
- **[Cloudflare Workers](https://workers.cloudflare.com/)** — 100,000 requests per day free on free plan.
- **[Vercel Serverless Functions](https://vercel.com/)** — Free tier: 100GB bandwidth, 100 hours execution time per month.
- **[Netlify Functions](https://www.netlify.com/products/functions/)** — Free tier: 125,000 requests, 100 hours runtime per month.

---

## Cloud Monitoring & Logging

- **[Grafana Cloud](https://grafana.com/products/cloud/)** — Free tier: 10,000 series, 50GB logs, 50GB traces, 14-day retention.
- **[Datadog](https://www.datadoghq.com/)** — Free tier: 5 hosts, 1-day retention.
- **[New Relic](https://newrelic.com/)** — Free tier: 100GB/month data ingest, unlimited users.
- **[AWS CloudWatch](https://aws.amazon.com/cloudwatch/)** — 5GB log data ingestion, 5GB archived logs, always free tier.
- **[Google Cloud Logging](https://cloud.google.com/logging)** — First 50GB per month free per project.
- **[Azure Monitor](https://azure.microsoft.com/en-us/services/monitor/)** — First 5GB data ingestion per month free for 12 months.
- **[Sentry](https://sentry.io/)** — Free tier: 5,000 events per month, 1 user.
- **[Logtail by Better Stack](https://betterstack.com/logtail)** — Free tier: 1GB per month, 3-day retention.
- **[LogDNA (Mezmo)](https://www.mezmo.com/)** — Free tier: 500MB per day, 1-day retention.

---

## Data Format Tools & Converters

### JSON Tools

**General JSON Resources:**
- **[JSON.org](https://www.json.org/)** — Official JSON specification and documentation. Free reference for JSON format and standards.
- **[MDN JSON Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON)** — Comprehensive JSON documentation and tutorials by Mozilla. Free educational resource.

**JSON Utilities:**
- **[JSON Formatter](https://jsonformatter.ai/)** — Format, validate, and beautify JSON data. Includes validation and formatting tools.
- **[JSON Viewer](https://jsontotable.org/)** — View, convert, and analyze JSON data. Includes JSON to Table, JSON to CSV, JSON to Excel, and other conversion tools.
- **[JSON Parser](https://jsonparser.ai/)** — Parse, transform, and analyze JSON data. Extract and manipulate JSON with advanced parsing features.
- **[Quicktype](https://quicktype.io/)** — Generate types and converters from JSON for multiple programming languages. Free online tool.

### XML Tools

**General XML Resources:**
- **[W3C XML](https://www.w3.org/XML/)** — Official XML specification and standards by W3C. Free reference documentation.
- **[MDN XML Guide](https://developer.mozilla.org/en-US/docs/Web/XML)** — Comprehensive XML documentation and tutorials by Mozilla. Free educational resource.
- **[XML Formatter](https://jsontotable.org/xml-formatter)** — Format, validate, and beautify XML data. Includes XML validation and formatting tools.
- **[XML to Table](https://jsontotable.org/xml-to-table)** — Convert XML data to table format. View and analyze XML in a structured table layout.

### YAML Tools

**General YAML Resources:**
- **[YAML.org](https://yaml.org/)** — Official YAML specification and documentation. Free reference for YAML format and standards.
- **[Learn YAML](https://learnxinyminutes.com/docs/yaml/)** — Quick YAML tutorial and reference guide. Free educational resource.
- **[YAML Formatter](https://jsontotable.org/yaml-formatter)** — Format, validate, and beautify YAML data. Includes YAML validation and formatting tools.
- **[YAML to JSON](https://jsontotable.org/yaml-to-json)** — Convert YAML to JSON format. Bidirectional conversion between YAML and JSON.

### TOON Format Tools

**General TOON Resources:**
- **[TOON GitHub Repository](https://github.com/toon-format/toon)** — Official TOON specification, documentation, and TypeScript SDK. Token-Oriented Object Notation for efficient LLM prompts.
- **[TOON Specification](https://github.com/toon-format/toon/blob/main/SPEC.md)** — Complete TOON format specification with syntax rules and implementation guidelines.

**TOON Tools:**
- **[TOON Formatter](https://jsontotable.org/toon-formatter)** — Format and beautify TOON data with proper indentation and structure.
- **[JSON to TOON](https://jsontotable.org/json-to-toon)** — Convert JSON data to TOON format for LLM optimization.
- **[TOON to JSON](https://jsontotable.org/toon-to-json)** — Convert TOON format back to standard JSON.

### API Testing & Development

- **[Postman](https://www.postman.com/)** — API development platform. Free tier: unlimited collections, unlimited requests, 3 team members, 25 API mocks.
- **[API Testing Tool](https://jsontotable.org/api-testing)** — Professional browser-based API testing tool. Test REST APIs with full HTTP support, authentication, cURL import, and instant responses.
- **[Insomnia](https://insomnia.rest/)** — API client and design platform. Free for individuals with unlimited requests and collections.
- **[Hoppscotch](https://hoppscotch.io/)** — Open-source API development platform. No login required for basic features.
- **[HTTPie](https://httpie.io/)** — API testing client. Free tier for web and desktop app with basic features.

---

## Contributing

We welcome contributions! Please read our [Contributing Guidelines](CONTRIBUTING.md) before submitting a pull request.

### Criteria for Inclusion

- Must have a genuine free tier (not just a trial)
- Free tier must last at least 1 year (or be "always free")
- Must be cloud-based or SaaS offering
- Must be relevant to data engineering, analytics, or data science
- Active and maintained service

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [DevGearsHub](https://github.com/DevGearsHub) has waived all copyright and related or neighboring rights to this work.

