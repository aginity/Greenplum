# Greenplum Package Summary

|Package Name| Package Description| Number of Queries in Package|
|------------|--------------------|-----------------------------|
|Aginity-Pro-GP-Admin-Set1|Contains administrative queries to do common tasks in Greenplum   | 5  |
|Aginity-Pro-GP-Table-Column-Search   | Contains search queries to find where tables or columns exist within Greenplum   | 6  |



### The table below details all queries within the Aginity-Pro-GP-Admin-Set1 package.



|Catalog Item Name               |Catalog Item Description            | Required Table     |
|--------------------------|------------------------------------|--------------------|
|Current sessions and their queries  | Shows current user activity    | pg_stat_activity  |
|Databases actual size   | Shows the databases and their actual size   |pg_database   |
|List users   |List all users that have been created in database   | pg_user  |
|Running Queries and Lock Statuses   |Show all running queries and the locks they have created   | pg_stat_activity, pg_locks  |
|Unused indexes   | Shows created indexes that are not being referenced   |pg_stat_all_indexes   |


### The table below details all queries within the Aginity-Pro-GP-Table-Column-Search-Queries package.



|Catalog Item Name               |Catalog Item Description            | Required Table     |
|--------------------------      |------------------------------------|--------------------|
|Search for Columns by exact name - All schemas       | This query allows you to search for any column across all schemas with an exact name match|INFORMATION_SCHEMA.COLUMNS|
|Search for Columns by exact name - Public schema|This query allows you to search for any column across Public schema with an exact name match|INFORMATION_SCHEMA.COLUMNS|
|Search for Columns by partial name - All schema|This query allows you to search for any column across all schemas with a partial name match|INFORMATION_SCHEMA.COLUMNS|
|Search for Columns by partial name - Public schema|This query allows you to search for any column across Public schemas with a partial name match|INFORMATION_SCHEMA.COLUMNS|
|Search for Tables by partial name - All schema|This query allows you to search for any table across all schemas with a partial name match|INFORMATION_SCHEMA.COLUMNS|
|Search for Tables by partial name - Public schema|This query allows you to search for any table across Public schemas with a partial name match|INFORMATION_SCHEMA.COLUMNS|
