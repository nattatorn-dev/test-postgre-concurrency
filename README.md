# test-postgre-concurrency
Test Postgres locks within a transaction, Isolation and Locking

I try to write database code to make sure that it's not subject to race conditions, to make sure that I've locked the correct rows or tables. But I often wonder: Is my code correct? Is it possible to force any existing race conditions to manifest? I want to be sure that if they do happen in a production environment my application will do the right thing.

### Solutions
It's concurrency testing on postgreSQL to find great solution for read/write command in a row at the same time!!
