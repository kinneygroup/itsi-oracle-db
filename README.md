## Summary
The ITSI Content Pack for Oracle Database from Kinney Group is specifically designed to monitor the health and performance of Oracle Database environments. It leverages Splunk ITSI to provide in-depth analysis and visualization of logs for Oracle Database, ensuring critical systems are operating optimally. This content pack is an essential tool for IT professionals looking to enhance the reliability and performance of their Oracle Database infrastructure.

* Comprehensive Performance Monitoring: Offers detailed insights into Oracle Database instance performance, storage management, query performance, and connection pool management, enabling optimized resource utilization.
* Critical System Status Tracking: Monitors the real-time operational status of Oracle Database instances and their components, helping IT professionals swiftly identify and address potential issues.
* Enhanced Resource Efficiency: Facilitates better decision-making on resource allocation and system adjustments by analyzing performance trends and detecting inefficiencies across the database environment.

This ITSI Content Pack is open source and available for community collaboration and enhancement on [GitHub](https://www.github.com/kinneygroup).

For more information about Kinney Group's Splunk Products, visit our [website](https://kinneygroup.com/atlas).

## Details
The ITSI Content Pack for Oracle Database contains service definitions and KPIs ready to import to ITSI. The KPI Thresholds and importance values are set to defaults so that they can be tuned manually for your use case. After configuration, this content pack provides a comprehensive monitoring solution for Oracle Database environments.

[Kinney Group ITSI Content Pack Blog](https://kinneygroup.com/blog/installing-itsi-content-packs/)

For more information about Kinney Group's Splunk Products, visit our [website](https://kinneygroup.com/atlas).

### Services
Oracle Database monitoring encompasses several specialized services, each targeting specific aspects of database performance:

1. Oracle Database
    * Description: The primary service representing the overall health and performance of the Oracle Database environment.
    * Source: N/A (Root service)
2. Instance Management
    * Description: Manages the health and performance of Oracle database instances.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-INSTANCE.html)
3. Storage Management
    * Description: Monitors the storage components of the Oracle Database, including tablespaces, data files, and temporary files.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/DBA_TABLESPACES.html)
4. Query Performance
    * Description: Monitors the performance of SQL queries executed within the Oracle Database.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/23/refrn/V-SQLAREA.html)
5. Connection Pool Management
    * Description: Manages the health and performance of Database Resident Connection Pools.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/23/refrn/DBA_CPOOL_INFO.html)
6. Session Management
    * Description: Monitors the health and performance of database sessions.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-SESSION.html)
7. System Metrics
    * Description: Tracks various system metrics related to the Oracle Database instances.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-OSSTAT.html)
8. SQL Execution
    * Description: Monitors the execution of SQL statements within the Oracle Database.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/23/refrn/V-SQLAREA.html)
9. SQL Plan Monitoring
    * Description: Monitors the execution plans of SQL statements to ensure optimal performance.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/23/refrn/V-SQL_PLAN_MONITOR.html)

### KPIs
Each service utilizes specific KPIs to measure its effectiveness:

1. Instance Status
    * Description: Monitors the status of the Oracle database instance (STARTED, MOUNTED, OPEN, OPEN MIGRATE).
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-INSTANCE.html)
2. Instance CPU Usage
    * Description: Tracks the CPU usage of the Oracle database instance.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-OSSTAT.html)
3. Instance Memory Usage
    * Description: Monitors the memory usage of the Oracle database instance.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-OSSTAT.html)
4. Instance Startup Time
    * Description: Records the time when the instance was started.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-INSTANCE.html)
5. Instance Logins
    * Description: Checks if the instance is in unrestricted mode (ALLOWED) or restricted mode (RESTRICTED).
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-INSTANCE.html)
6. Tablespace Usage
    * Description: Monitors the usage of tablespaces within the Oracle Database.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/DBA_TABLESPACES.html)
7. Data File Usage
    * Description: Monitors the usage of data files within the Oracle Database.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/DBA_DATA_FILES.html)
8. Temporary File Usage
    * Description: Monitors the usage of temporary files within the Oracle Database.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/DBA_TEMP_FILES.html)
9. Tablespace Free Space
    * Description: Monitors the free space available in tablespaces within the Oracle Database.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/DBA_FREE_SPACE.html)
10. Data File Status
    * Description: Monitors the status of data files within the Oracle Database.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/DBA_DATA_FILES.html)
11. SQL Execution Time
    * Description: Monitors the execution time of SQL statements within the Oracle Database.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/23/refrn/V-SQLAREA.html)
12. SQL Plan Efficiency
    * Description: Monitors the efficiency of SQL execution plans.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/23/refrn/V-SQL_PLAN_MONITOR.html)
13. Buffer Gets
    * Description: Sum of buffer gets over all child cursors.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/23/refrn/V-SQLAREA.html)
14. Disk Reads
    * Description: Sum of the number of disk reads over all child cursors.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/23/refrn/V-SQLAREA.html)
15. SQL Fetches
    * Description: Number of fetches associated with the SQL statement.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/23/refrn/V-SQLAREA.html)
16. Connection Pool Status
    * Description: Monitors the status of connection pools within the Oracle Database.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/23/refrn/DBA_CPOOL_INFO.html)
17. Active Connections
    * Description: Monitors the number of active connections in the connection pool.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/23/refrn/DBA_CPOOL_INFO.html)
18. Inactive Connections
    * Description: Monitors the number of inactive connections in the connection pool.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/23/refrn/DBA_CPOOL_INFO.html)
19. Connection Requests
    * Description: Monitors the number of connection requests made to the connection pool.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/23/refrn/DBA_CPOOL_INFO.html)
20. Connection Releases
    * Description: Monitors the number of connection releases from the connection pool.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/23/refrn/DBA_CPOOL_INFO.html)
21. Active Sessions
    * Description: Monitors the number of active database sessions.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-SESSION.html)
22. Inactive Sessions
    * Description: Monitors the number of inactive database sessions.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-SESSION.html)
23. Session Wait Events
    * Description: Monitors the wait events for database sessions.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-SESSION.html)
24. Session Activity
    * Description: Monitors the activity of database sessions.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-SESSION.html)
25. Session CPU Usage
    * Description: Tracks the CPU usage of database sessions.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-SESSION.html)
26. CPU Usage
    * Description: Tracks CPU-related metrics for the Oracle Database instances.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-OSSTAT.html)
27. Memory Usage
    * Description: Tracks memory-related metrics for the Oracle Database instances.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-SGA.html)
28. I/O Metrics
    * Description: Tracks I/O-related metrics for the Oracle Database instances.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-FILESTAT.html)
29. System Load
    * Description: Monitors the current number of processes that are either running or in the ready state.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-OSSTAT.html)
30. Network Latency
    * Description: Tracks network latency that could affect database performance.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/V-OSSTAT.html)
31. Data File Size
    * Description: Monitors the size of data files in bytes.
    * Source: [Oracle Documentation](https://docs.oracle.com/en/database/oracle/oracle-database/19/refrn/DBA_DATA_FILES.html)

### Relationships
#### Dependencies:
Services are interconnected; for instance, Oracle Database is dependent on Instance Management, Storage Management, Query Performance, and Connection Pool Management. Similarly, Instance Management relies on Session Management and System Metrics to ensure smooth operation.

#### Hierarchical Structure:
Some services form a hierarchy, such as Storage Management depending on Tablespace Management, Data File Management, and Temporary File Management, illustrating a layered approach to performance monitoring where base metrics support broader performance indicators.

## Installation

### Installation prerequisites:

[Splunk Addon for Oracle Database](https://splunkbase.splunk.com)

[Splunk App for Content Packs](https://splunkbase.splunk.com/app/5391)

[Splunk ITSI](https://www.splunk.com/en_us/products/it-service-intelligence.html)

## Troubleshooting

[Kinney Group ITSI Content Pack Blog](https://kinneygroup.com/blog/installing-itsi-content-packs/)

[Github and Readme](https://www.github.com/kinneygroup)

support@kinneygroup.com

## Contact

To provide feedback, visit our [Github and Readme](https://www.github.com/kinneygroup) for our content packs.

support@kinneygroup.com

For more information about Kinney Group's Splunk Products, visit our [website](https://kinneygroup.com/)