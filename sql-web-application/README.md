A full-featured web-based database client for managing SQL queries and asynchronous execution.

My role: idea conception, product design and owner, architect and initial/lead developer

Technologies: Python, Django, PostgreSQL, Redis, RQ, Bootstrap, AWS Redshift, Presto, gunicorn, nginx


## Features

* Edit, save, and version control SQL queries
* Automatic SQL reformatting & syntax highlighting
* Document and share links to queries and execution results, search/browse other users' work
* Database schema browser
* Query execution is server-side, long-running queries don't require user to remain on the network
* Deliver results to an email address, Amazon S3, or to a table in any managed database
* Copy results from one database type to another, (eg. PostgreSQL to MySQL,) translating data types as needed 
* Email notifications and alerts based on query execution status and conditions in results data
* Scheduled query execution
* Scheduled workflows of arbitrary sequences of operations
* Query execution metadata allows warnings and alerts about long-running queries, bad query patterns
* Interpretation and categorization of query failure error messages (user error vs. server error)
* Automatic retry of non-user-error failures
* REST API and Python library for programmatic use
* Supported databases: PostgreSQL, Presto, Redshift, MySQL



## Screenshots

[Home Page](https://raw.githubusercontent.com/fura-ness/portfolio/master/sql-web-application/docs/ss-01.png)

[Database Browser & Query Editor](https://raw.githubusercontent.com/fura-ness/portfolio/master/sql-web-application/docs/ss-02.png)

[Query Execution Details w/chart](https://raw.githubusercontent.com/fura-ness/portfolio/master/sql-web-application/docs/ss-03.png)

[Workflow Editor](https://raw.githubusercontent.com/fura-ness/portfolio/master/sql-web-application/docs/ss-05.png) - Workflows of multiple steps can be created and scheduled

[Execution Queue](https://raw.githubusercontent.com/fura-ness/portfolio/master/sql-web-application/docs/ss-06.png) - Status page with running and queued executions

[Markdown Page](https://raw.githubusercontent.com/fura-ness/portfolio/master/sql-web-application/docs/ss-07.png) - A light CMS feature for people to document and share their work

[Alert Editor](https://raw.githubusercontent.com/fura-ness/portfolio/master/sql-web-application/docs/ss-08.png)

[Database Home Page](https://raw.githubusercontent.com/fura-ness/portfolio/master/sql-web-application/docs/ss-09.png)

[Usage Explorer](https://raw.githubusercontent.com/fura-ness/portfolio/master/sql-web-application/docs/ss-04.png) - An experimental visualization of table/query usage