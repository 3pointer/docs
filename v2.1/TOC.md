# TiDB Documentation

<!-- markdownlint-disable MD007 -->
<!-- markdownlint-disable MD032 -->

## Documentation List

+ Introduction
  - [TiDB Introduction](/v2.1/overview.md)
  + Benchmarks
    - [How to Test TiDB Using Sysbench](/v2.1/benchmark/how-to-run-sysbench.md)
    - [Sysbench Performance Test - v2.1 vs. v2.0](/v2.1/benchmark/sysbench-v3.md)
    - [TPC-H 50G Performance Test - v2.1 vs. v2.0](/v2.1/benchmark/tpch-v2.md)
    - [DM Benchmark Report](/v2.1/benchmark/dm-v1-alpha.md)
+ Concepts
  - [Architecture](/v2.1/architecture.md)
  + Key Features
    - [Horizontal Scalability](/v2.1/key-features.md#horizontal-scalability)
    - [MySQL Compatible Syntax](/v2.1/key-features.md#mysql-compatible-syntax)
    - [Replicate from and to MySQL](/v2.1/key-features.md#replicate-from-and-to-mysql)
    - [Distributed Transactions with Strong Consistency](/v2.1/key-features.md#distributed-transactions-with-strong-consistency)
    - [Cloud Native Architecture](/v2.1/key-features.md#cloud-native-architecture)
    - [Minimize ETL with HTAP](/v2.1/key-features.md#minimize-etl-with-htap)
    - [Fault Tolerance & Recovery with Raft](/v2.1/key-features.md#fault-tolerance--recovery-with-raft)
    - [Automatic Rebalancing](/v2.1/key-features.md#automatic-rebalancing)
    - [Deployment and Orchestration with Ansible, Kubernetes, Docker](/v2.1/key-features.md#deployment-and-orchestration-with-ansible-kubernetes-docker)
    - [JSON Support](/v2.1/key-features.md#json-support)
    - [Spark Integration](/v2.1/key-features.md#spark-integration)
    - [Read Historical Data Without Restoring from Backup](/v2.1/key-features.md#read-historical-data-without-restoring-from-backup)
    - [Fast Import and Restore of Data](/v2.1/key-features.md#fast-import-and-restore-of-data)
    - [Hybrid of Column and Row Storage](/v2.1/key-features.md#hybrid-of-column-and-row-storage)
    - [SQL Plan Management](/v2.1/key-features.md#sql-plan-management)
    - [Open Source](/v2.1/key-features.md#open-source)
    - [Online Schema Changes](/v2.1/key-features.md#online-schema-changes)
+ How-to
  + Get Started
    + Start a Local Cluster
      - [From Binary](/v2.1/how-to/get-started/local-cluster/install-from-binary.md)
      - [In Kubernetes](/v2.1/how-to/get-started/local-cluster/install-from-kubernetes.md)
    - [Explore SQL with TiDB](/v2.1/how-to/get-started/explore-sql.md)
    - [Import Example Database](/v2.1/how-to/get-started/import-example-database.md)
    - [Read Historical Data](/v2.1/how-to/get-started/read-historical-data.md)
    - [TiDB Binlog Tutorial](/v2.1/how-to/get-started/tidb-binlog.md)
    - [TiDB Data Migration Tutorial](/v2.1/how-to/get-started/data-migration.md)
    - [TiSpark Quick Start Guide](/v2.1/how-to/deploy/tispark.md)
  + Deploy
    - [Hardware Recommendations](/v2.1/how-to/deploy/hardware-recommendations.md)
    + From Binary Tarball
      - [For Testing Environments](/v2.1/how-to/deploy/from-tarball/testing-environment.md)
      - [For Production Environments](/v2.1/how-to/deploy/from-tarball/production-environment.md)
    + Orchestrated Deployment
      - [Ansible Deployment (Recommended)](/v2.1/how-to/deploy/orchestrated/ansible.md)
      - [Ansible Offline Deployment](/v2.1/how-to/deploy/orchestrated/offline-ansible.md)
      - [Docker Deployment](/v2.1/how-to/deploy/orchestrated/docker.md)
      - [Kubernetes Deployment](/v2.1/how-to/deploy/orchestrated/kubernetes.md)
    + Geographic Redundancy
      - [Overview](/v2.1/how-to/deploy/geographic-redundancy/overview.md)
      - [Configure Location Awareness](/v2.1/how-to/deploy/geographic-redundancy/location-awareness.md)
    - [Data Migration with Ansible](/v2.1/how-to/deploy/data-migration-with-ansible.md)
    - [TiDB Binlog Cluster Deployment](/v2.1/how-to/deploy/tidb-binlog.md)
  + Configure
    - [Time Zone](/v2.1/how-to/configure/time-zone.md)
    - [Memory Control](/v2.1/how-to/configure/memory-control.md)
  + Secure
    + Transport Layer Security (TLS)
      - [Enable TLS For MySQL Clients](/v2.1/how-to/secure/enable-tls-clients.md)
      - [Enable TLS Between TiDB Components](/v2.1/how-to/secure/enable-tls-between-components.md)
    - [Generate Self-signed Certificates](/v2.1/how-to/secure/generate-self-signed-certificates.md)
  + Monitor
    - [Overview](/v2.1/how-to/monitor/overview.md)
    - [Monitor a TiDB Cluster](/v2.1/how-to/monitor/monitor-a-cluster.md)
    - [TiDB Binlog Monitoring](/v2.1/how-to/monitor/tidb-binlog.md)
  + Migrate
    - [Overview](/v2.1/how-to/migrate/overview.md)
    + Migrate from MySQL
      - [Migrate the Full Data](/v2.1/how-to/migrate/from-mysql.md)
      - [Migrate the Incremental Data](/v2.1/how-to/migrate/incrementally-from-mysql.md)
    - [Migrate from Aurora](/v2.1/how-to/migrate/from-aurora.md)
    - [Migrate from CSV](/v2.1/reference/tools/tidb-lightning/csv.md)
  + Maintain
    - [Common Ansible Operations](/v2.1/how-to/deploy/orchestrated/ansible-operations.md)
    - [Backup and Restore](/v2.1/how-to/maintain/backup-and-restore.md)
    - [Identify Slow Queries (2.1.8+)](/v2.1/how-to/maintain/identify-slow-queries.md)
    - [Identify Slow Queries (earlier)](/v2.1/how-to/maintain/identify-slow-queries-21.md)
    - [TiDB Binlog Cluster Operations](/v2.1/how-to/maintain/tidb-binlog.md)
  + Scale
    - [Scale using Ansible](/v2.1/how-to/scale/with-ansible.md)
    - [Scale a TiDB Cluster](/v2.1/how-to/scale/horizontally.md)
  + Upgrade
    - [Upgrade to TiDB 2.1](/v2.1/how-to/upgrade/from-previous-version.md)
    - [Rolling updates with Ansible](/v2.1/how-to/upgrade/rolling-updates-with-ansible.md)
    - [Upgrade TiDB Data Migration](/v2.1/reference/tools/data-migration/upgrade.md)
    - [Upgrade TiDB Binlog Cluster](/v2.1/how-to/upgrade/tidb-binlog.md)
  - Troubleshoot
    - [Troubleshoot Cluster Setup](/v2.1/how-to/troubleshoot/cluster-setup.md)
    - [Troubleshoot TiDB Data Migration](/v2.1/how-to/troubleshoot/data-migration.md)
    - [Troubleshoot TiDB Lightning](/v2.1/how-to/troubleshoot/tidb-lightning.md)
+ Reference
  + Tools
    - [Mydumper](/v2.1/reference/tools/mydumper.md)
    - [Syncer](/v2.1/reference/tools/syncer.md)
    - [Loader](/v2.1/reference/tools/loader.md)
    + TiDB Data Migration
      - [Overview](/v2.1/reference/tools/data-migration/overview.md)
      - [Restrictions](/v2.1/reference/tools/data-migration/overview.md#usage-restrictions)
      + Features
        - [Table Routing](/v2.1/reference/tools/data-migration/features/overview.md#table-routing)
        - [Black and White Lists](/v2.1/reference/tools/data-migration/features/overview.md#black-and-white-table-lists)
        - [Binlog Event Filter](/v2.1/reference/tools/data-migration/features/overview.md#binlog-event-filter)
        - [Column Mapping](/v2.1/reference/tools/data-migration/features/overview.md#column-mapping)
        - [Replication Delay Monitoring](/v2.1/reference/tools/data-migration/features/overview.md#replication-delay-monitoring)
        + Sharding Support
          - [Introduction](/v2.1/reference/tools/data-migration/features/shard-merge.md)
          - [Restrictions](/v2.1/reference/tools/data-migration/features/shard-merge.md#restrictions)
          - [Handle Sharding DDL Locks Manually](/v2.1/reference/tools/data-migration/features/manually-handling-sharding-ddl-locks.md)
      + Usage Scenarios
        - [Simple Scenario](/v2.1/reference/tools/data-migration/usage-scenarios/simple-replication.md)
        - [Shard Merge Scenario](/v2.1/reference/tools/data-migration/usage-scenarios/shard-merge.md)
      - [Deploy](/v2.1/reference/tools/data-migration/deploy.md)
      + Configure
        - [Overview](/v2.1/reference/tools/data-migration/configure/overview.md)
        - [Task Configuration](/v2.1/reference/tools/data-migration/configure/task-configuration-file.md)
      - [Monitor](/v2.1/reference/tools/data-migration/monitor.md)
      - [Manage the Task](/v2.1/reference/tools/data-migration/manage-tasks.md)
      - [Cluster Operations](/v2.1/reference/tools/data-migration/cluster-operations.md)
      + Migrate from MySQL compatible database
        - [Migrate from Aurora](/v2.1/how-to/migrate/from-aurora.md)
      - [Troubleshoot](/v2.1/how-to/troubleshoot/data-migration.md)
      - [Upgrade](/v2.1/reference/tools/data-migration/upgrade.md)
    + TiDB Lightning
      - [Overview](/v2.1/reference/tools/tidb-lightning/overview.md)
      - [Deployment](/v2.1/reference/tools/tidb-lightning/deployment.md)
      - [Checkpoints](/v2.1/reference/tools/tidb-lightning/checkpoints.md)
      - [Table Filter](/v2.1/reference/tools/tidb-lightning/table-filter.md)
      - [CSV Support](/v2.1/reference/tools/tidb-lightning/csv.md)
      - [Monitor](/v2.1/reference/tools/tidb-lightning/monitor.md)
      - [Troubleshoot](/v2.1/how-to/troubleshoot/tidb-lightning.md)
      - [FAQ](/v2.1/faq/tidb-lightning.md)
    - [PD Control](/v2.1/reference/tools/pd-control.md)
    - [PD Recover](/v2.1/reference/tools/pd-recover.md)
    - [TiKV Control](/v2.1/reference/tools/tikv-control.md)
    - [TiDB Control](/v2.1/reference/tools/tidb-control.md)
    - [Download](/v2.1/reference/tools/download.md)
  - [MySQL Compatibility](/v2.1/reference/mysql-compatibility.md)
  + SQL
    + SQL Language Structure
      - [Literal Values](/v2.1/reference/sql/language-structure/literal-values.md)
      - [Schema Object Names](/v2.1/reference/sql/language-structure/schema-object-names.md)
      - [Keywords and Reserved Words](/v2.1/reference/sql/language-structure/keywords-and-reserved-words.md)
      - [User-Defined Variables](/v2.1/reference/sql/language-structure/user-defined-variables.md)
      - [Expression Syntax](/v2.1/reference/sql/language-structure/expression-syntax.md)
      - [Comment Syntax](/v2.1/reference/sql/language-structure/comment-syntax.md)
    + Data Types
      - [Overview](/v2.1/reference/sql/data-types/overview.md)
      - [Default Values](/v2.1/reference/sql/data-types/default-values.md)
      + Numeric Types
        - [`BIT`](/v2.1/reference/sql/data-types/numeric.md#bit-type)
        - [`BOOL|BOOLEAN`](/v2.1/reference/sql/data-types/numeric.md#boolean-type)
        - [`TINYINT`](/v2.1/reference/sql/data-types/numeric.md#tinyint-type)
        - [`SMALLINT`](/v2.1/reference/sql/data-types/numeric.md#smallint-type)
        - [`MEDIUMINT`](/v2.1/reference/sql/data-types/numeric.md#mediumint-type)
        - [`INT|INTEGER`](/v2.1/reference/sql/data-types/numeric.md#integer-type)
        - [`BIGINT`](/v2.1/reference/sql/data-types/numeric.md#bigint-type)
        - [`DECIMAL`](/v2.1/reference/sql/data-types/numeric.md#decimal-type)
        - [`FLOAT`](/v2.1/reference/sql/data-types/numeric.md#float-type)
        - [`DOUBLE`](/v2.1/reference/sql/data-types/numeric.md#double-type)
      + Date and Time Types
        - [`DATE`](/v2.1/reference/sql/data-types/date-and-time.md#date-type)
        - [`DATETIME`](/v2.1/reference/sql/data-types/date-and-time.md#datetime-type)
        - [`TIMESTAMP`](/v2.1/reference/sql/data-types/date-and-time.md#timestamp-type)
        - [`TIME`](/v2.1/reference/sql/data-types/date-and-time.md#time-type)
        - [`YEAR`](/v2.1/reference/sql/data-types/date-and-time.md#year-type)
      + String Types
        - [`CHAR`](/v2.1/reference/sql/data-types/string.md#char-type)
        - [`VARCHAR`](/v2.1/reference/sql/data-types/string.md#varchar-type)
        - [`TEXT`](/v2.1/reference/sql/data-types/string.md#text-type)
        - [`LONGTEXT`](/v2.1/reference/sql/data-types/string.md#longtext-type)
        - [`BINARY`](/v2.1/reference/sql/data-types/string.md#binary-type)
        - [`VARBINARY`](/v2.1/reference/sql/data-types/string.md#varbinary-type)
        - [`TINYBLOB`](/v2.1/reference/sql/data-types/string.md#tinyblob-type)
        - [`BLOB`](/v2.1/reference/sql/data-types/string.md#blob-type)
        - [`MEDIUMBLOB`](/v2.1/reference/sql/data-types/string.md#mediumblob-type)
        - [`LONGBLOB`](/v2.1/reference/sql/data-types/string.md#longblob-type)
        - [`ENUM`](/v2.1/reference/sql/data-types/string.md#enum-type)
        - [`SET`](/v2.1/reference/sql/data-types/string.md#set-type)
      - [JSON Type](/v2.1/reference/sql/data-types/json.md)
    + Functions and Operators
      - [Function and Operator Reference](/v2.1/reference/sql/functions-and-operators/reference.md)
      - [Type Conversion in Expression Evaluation](/v2.1/reference/sql/functions-and-operators/type-conversion.md)
      - [Operators](/v2.1/reference/sql/functions-and-operators/operators.md)
      - [Control Flow Functions](/v2.1/reference/sql/functions-and-operators/control-flow-functions.md)
      - [String Functions](/v2.1/reference/sql/functions-and-operators/string-functions.md)
      - [Numeric Functions and Operators](/v2.1/reference/sql/functions-and-operators/numeric-functions-and-operators.md)
      - [Date and Time Functions](/v2.1/reference/sql/functions-and-operators/date-and-time-functions.md)
      - [Bit Functions and Operators](/v2.1/reference/sql/functions-and-operators/bit-functions-and-operators.md)
      - [Cast Functions and Operators](/v2.1/reference/sql/functions-and-operators/cast-functions-and-operators.md)
      - [Encryption and Compression Functions](/v2.1/reference/sql/functions-and-operators/encryption-and-compression-functions.md)
      - [Information Functions](/v2.1/reference/sql/functions-and-operators/information-functions.md)
      - [JSON Functions](/v2.1/reference/sql/functions-and-operators/json-functions.md)
      - [Aggregate (GROUP BY) Functions](/v2.1/reference/sql/functions-and-operators/aggregate-group-by-functions.md)
      - [Miscellaneous Functions](/v2.1/reference/sql/functions-and-operators/miscellaneous-functions.md)
      - [Precision Math](/v2.1/reference/sql/functions-and-operators/precision-math.md)
    + SQL Statements
      - [`ADD COLUMN`](/v2.1/reference/sql/statements/add-column.md)
      - [`ADD INDEX`](/v2.1/reference/sql/statements/add-index.md)
      - [`ADMIN`](/v2.1/reference/sql/statements/admin.md)
      - [`ALTER DATABASE`](/v2.1/reference/sql/statements/alter-database.md)
      - [`ALTER TABLE`](/v2.1/reference/sql/statements/alter-table.md)
      - [`ALTER USER`](/v2.1/reference/sql/statements/alter-user.md)
      - [`ANALYZE TABLE`](/v2.1/reference/sql/statements/analyze-table.md)
      - [`BEGIN`](/v2.1/reference/sql/statements/begin.md)
      - [`COMMIT`](/v2.1/reference/sql/statements/commit.md)
      - [`CREATE DATABASE`](/v2.1/reference/sql/statements/create-database.md)
      - [`CREATE INDEX`](/v2.1/reference/sql/statements/create-index.md)
      - [`CREATE TABLE LIKE`](/v2.1/reference/sql/statements/create-table-like.md)
      - [`CREATE TABLE`](/v2.1/reference/sql/statements/create-table.md)
      - [`CREATE USER`](/v2.1/reference/sql/statements/create-user.md)
      - [`DEALLOCATE`](/v2.1/reference/sql/statements/deallocate.md)
      - [`DELETE`](/v2.1/reference/sql/statements/delete.md)
      - [`DESC`](/v2.1/reference/sql/statements/desc.md)
      - [`DESCRIBE`](/v2.1/reference/sql/statements/describe.md)
      - [`DO`](/v2.1/reference/sql/statements/do.md)
      - [`DROP COLUMN`](/v2.1/reference/sql/statements/drop-column.md)
      - [`DROP DATABASE`](/v2.1/reference/sql/statements/drop-database.md)
      - [`DROP INDEX`](/v2.1/reference/sql/statements/drop-index.md)
      - [`DROP TABLE`](/v2.1/reference/sql/statements/drop-table.md)
      - [`DROP USER`](/v2.1/reference/sql/statements/drop-user.md)
      - [`EXECUTE`](/v2.1/reference/sql/statements/execute.md)
      - [`EXPLAIN ANALYZE`](/v2.1/reference/sql/statements/explain-analyze.md)
      - [`EXPLAIN`](/v2.1/reference/sql/statements/explain.md)
      - [`FLUSH PRIVILEGES`](/v2.1/reference/sql/statements/flush-privileges.md)
      - [`FLUSH STATUS`](/v2.1/reference/sql/statements/flush-status.md)
      - [`FLUSH TABLES`](/v2.1/reference/sql/statements/flush-tables.md)
      - [`GRANT <privileges>`](/v2.1/reference/sql/statements/grant-privileges.md)
      - [`INSERT`](/v2.1/reference/sql/statements/insert.md)
      - [`KILL [TIDB]`](/v2.1/reference/sql/statements/kill.md)
      - [`LOAD DATA`](/v2.1/reference/sql/statements/load-data.md)
      - [`MODIFY COLUMN`](/v2.1/reference/sql/statements/modify-column.md)
      - [`PREPARE`](/v2.1/reference/sql/statements/prepare.md)
      - [`RENAME INDEX`](/v2.1/reference/sql/statements/rename-index.md)
      - [`RENAME TABLE`](/v2.1/reference/sql/statements/rename-table.md)
      - [`REPLACE`](/v2.1/reference/sql/statements/replace.md)
      - [`REVOKE <privileges>`](/v2.1/reference/sql/statements/revoke-privileges.md)
      - [`ROLLBACK`](/v2.1/reference/sql/statements/rollback.md)
      - [`SELECT`](/v2.1/reference/sql/statements/select.md)
      - [`SET [NAMES|CHARACTER SET]`](/v2.1/reference/sql/statements/set-names.md)
      - [`SET PASSWORD`](/v2.1/reference/sql/statements/set-password.md)
      - [`SET TRANSACTION`](/v2.1/reference/sql/statements/set-transaction.md)
      - [`SET [GLOBAL|SESSION] <variable>`](/v2.1/reference/sql/statements/set-variable.md)
      - [`SHOW CHARACTER SET`](/v2.1/reference/sql/statements/show-character-set.md)
      - [`SHOW COLLATION`](/v2.1/reference/sql/statements/show-collation.md)
      - [`SHOW [FULL] COLUMNS FROM`](/v2.1/reference/sql/statements/show-columns-from.md)
      - [`SHOW CREATE TABLE`](/v2.1/reference/sql/statements/show-create-table.md)
      - [`SHOW CREATE USER`](/v2.1/reference/sql/statements/show-create-user.md)
      - [`SHOW DATABASES`](/v2.1/reference/sql/statements/show-databases.md)
      - [`SHOW ENGINES`](/v2.1/reference/sql/statements/show-engines.md)
      - [`SHOW ERRORS`](/v2.1/reference/sql/statements/show-errors.md)
      - [`SHOW [FULL] FIELDS FROM`](/v2.1/reference/sql/statements/show-fields-from.md)
      - [`SHOW GRANTS`](/v2.1/reference/sql/statements/show-grants.md)
      - [`SHOW INDEXES [FROM|IN]`](/v2.1/reference/sql/statements/show-indexes.md)
      - [`SHOW INDEX [FROM|IN]`](/v2.1/reference/sql/statements/show-index.md)
      - [`SHOW KEYS [FROM|IN]`](/v2.1/reference/sql/statements/show-keys.md)
      - [`SHOW PRIVILEGES`](/v2.1/reference/sql/statements/show-privileges.md)
      - [`SHOW [FULL] PROCESSSLIST`](/v2.1/reference/sql/statements/show-processlist.md)
      - [`SHOW SCHEMAS`](/v2.1/reference/sql/statements/show-schemas.md)
      - [`SHOW [FULL] TABLES`](/v2.1/reference/sql/statements/show-tables.md)
      - [`SHOW TABLE STATUS`](/v2.1/reference/sql/statements/show-table-status.md)
      - [`SHOW [GLOBAL|SESSION] VARIABLES`](/v2.1/reference/sql/statements/show-variables.md)
      - [`SHOW WARNINGS`](/v2.1/reference/sql/statements/show-warnings.md)
      - [`START TRANSACTION`](/v2.1/reference/sql/statements/start-transaction.md)
      - [`TRACE`](/v2.1/reference/sql/statements/trace.md)
      - [`TRUNCATE`](/v2.1/reference/sql/statements/truncate.md)
      - [`UPDATE`](/v2.1/reference/sql/statements/update.md)
      - [`USE`](/v2.1/reference/sql/statements/use.md)
    - [Constraints](/v2.1/reference/sql/constraints.md)
    - [Generated Columns](/v2.1/reference/sql/generated-columns.md)
    - [Character Set](/v2.1/reference/sql/character-set.md)
  + Configuration
    + tidb-server
      - [MySQL System Variables](/v2.1/reference/configuration/tidb-server/mysql-variables.md)
      - [TiDB Specific System Variables](/v2.1/reference/configuration/tidb-server/tidb-specific-variables.md)
      - [Configuration Flags](/v2.1/reference/configuration/tidb-server/configuration.md)
      - [Configuration File](/v2.1/reference/configuration/tidb-server/configuration-file.md)
    + pd-server
      - [Configuration Flags](/v2.1/reference/configuration/pd-server/configuration.md)
    + tikv-server
      - [Configuration Flags](/v2.1/reference/configuration/tikv-server/configuration.md)
  + Key Monitoring Metrics
    - [Overview](/v2.1/reference/key-monitoring-metrics/overview-dashboard.md)
    - [TiDB](/v2.1/reference/key-monitoring-metrics/tidb-dashboard.md)
    - [PD](/v2.1/reference/key-monitoring-metrics/pd-dashboard.md)
    - [TiKV](/v2.1/reference/key-monitoring-metrics/tikv-dashboard.md)
  - [Alert Rules](/v2.1/reference/alert-rules.md)
  + Security
    - [Security Compatibility with MySQL](/v2.1/reference/security/compatibility.md)
    - [The TiDB Access Privilege System](/v2.1/reference/security/privilege-system.md)
    - [TiDB User Account Management](/v2.1/reference/security/user-account-management.md)
  + Transactions
    - [Overview](/v2.1/reference/transactions/overview.md)
    - [Transaction Model](/v2.1/reference/transactions/transaction-model.md)
    - [Isolation Levels](/v2.1/reference/transactions/transaction-isolation.md)
  + System Databases
    - [`mysql`](/v2.1/reference/system-databases/mysql.md)
    - [`information_schema`](/v2.1/reference/system-databases/information-schema.md)
  - [Errors Codes](/v2.1/reference/error-codes.md)
  - [Supported Client Drivers](/v2.1/reference/supported-clients.md)
  - [Garbage Collection (GC)](/v2.1/reference/garbage-collection.md)
  + Performance
    - [Overview](/v2.1/reference/performance/sql-optimizer-overview.md)
    - [Understanding the Query Execution Plan](/v2.1/reference/performance/understanding-the-query-execution-plan.md)
    - [Introduction to Statistics](/v2.1/reference/performance/statistics.md)
    - [Optimizer Hints](/v2.1/reference/performance/optimizer-hints.md)
    - [Tune TiKV](/v2.1/reference/performance/tune-tikv.md)
  - [Best Practices](https://pingcap.com/blog/2017-07-24-tidbbestpractice/)
  - [TiSpark](/v2.1/reference/tispark.md)
  - [TiDB Binlog Cluster Overview](/v2.1/reference/tidb-binlog-overview.md)
  - [Adopters](/v2.1/adopters.md)
+ FAQs
  - [TiDB FAQs](/v2.1/faq/tidb.md)
  - [TiDB Lightning FAQs](/v2.1/faq/tidb-lightning.md)
  - [Upgrade FAQs](/v2.1/faq/upgrade.md)
+ Support
  - [Support Resources](/v2.1/support-resources.md)
  - [Report an Issue](/v2.1/report-issue.md)
+ Contribute
  - [Contribute to TiDB](/v2.1/contribute.md#contribute-to-tidb)
  - [Improve the Docs](/v2.1/contribute.md#improve-the-docs)
- [Roadmap](/v2.1/roadmap.md)
+ [Releases](/v2.1/releases/rn.md)
  + v2.1
    - [2.1.17](/v2.1/releases/2.1.17.md)
    - [2.1.16](/v2.1/releases/2.1.16.md)
    - [2.1.15](/v2.1/releases/2.1.15.md)
    - [2.1.14](/v2.1/releases/2.1.14.md)
    - [2.1.13](/v2.1/releases/2.1.13.md)
    - [2.1.12](/v2.1/releases/2.1.12.md)
    - [2.1.11](/v2.1/releases/2.1.11.md)
    - [2.1.10](/v2.1/releases/2.1.10.md)
    - [2.1.9](/v2.1/releases/2.1.9.md)
    - [2.1.8](/v2.1/releases/2.1.8.md)
    - [2.1.7](/v2.1/releases/2.1.7.md)
    - [2.1.6](/v2.1/releases/2.1.6.md)
    - [2.1.5](/v2.1/releases/2.1.5.md)
    - [2.1.4](/v2.1/releases/2.1.4.md)
    - [2.1.3](/v2.1/releases/2.1.3.md)
    - [2.1.2](/v2.1/releases/2.1.2.md)
    - [2.1.1](/v2.1/releases/2.1.1.md)
    - [2.1 GA](/v2.1/releases/2.1ga.md)
    - [2.1 RC5](/v2.1/releases/21rc5.md)
    - [2.1 RC4](/v2.1/releases/21rc4.md)
    - [2.1 RC3](/v2.1/releases/21rc3.md)
    - [2.1 RC2](/v2.1/releases/21rc2.md)
    - [2.1 RC1](/v2.1/releases/21rc1.md)
    - [2.1 Beta](/v2.1/releases/21beta.md)
  + v2.0
    - [2.0.11](/v2.1/releases/2.0.11.md)
    - [2.0.10](/v2.1/releases/2.0.10.md)
    - [2.0.9](/v2.1/releases/209.md)
    - [2.0.8](/v2.1/releases/208.md)
    - [2.0.7](/v2.1/releases/207.md)
    - [2.0.6](/v2.1/releases/206.md)
    - [2.0.5](/v2.1/releases/205.md)
    - [2.0.4](/v2.1/releases/204.md)
    - [2.0.3](/v2.1/releases/203.md)
    - [2.0.2](/v2.1/releases/202.md)
    - [2.0.1](/v2.1/releases/201.md)
    - [2.0](/v2.1/releases/2.0ga.md)
    - [2.0 RC5](/v2.1/releases/2rc5.md)
    - [2.0 RC4](/v2.1/releases/2rc4.md)
    - [2.0 RC3](/v2.1/releases/2rc3.md)
    - [2.0 RC1](/v2.1/releases/2rc1.md)
    - [1.1 Beta](/v2.1/releases/11beta.md)
    - [1.1 Alpha](/v2.1/releases/11alpha.md)
  + v1.0
    - [1.0.8](/v2.1/releases/108.md)
    - [1.0.7](/v2.1/releases/107.md)
    - [1.0.6](/v2.1/releases/106.md)
    - [1.0.5](/v2.1/releases/105.md)
    - [1.0.4](/v2.1/releases/104.md)
    - [1.0.3](/v2.1/releases/103.md)
    - [1.0.2](/v2.1/releases/102.md)
    - [1.0.1](/v2.1/releases/101.md)
    - [1.0](/v2.1/releases/ga.md)
    - [Pre-GA](/v2.1/releases/prega.md)
    - [RC4](/v2.1/releases/rc4.md)
    - [RC3](/v2.1/releases/rc3.md)
    - [RC2](/v2.1/releases/rc2.md)
    - [RC1](/v2.1/releases/rc1.md)
