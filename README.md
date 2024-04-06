## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

### How to connect to postgres database on vercel

1. Get the database password and export it on your terminal.
    ```
    export PGPASSWORD='${database_password}'
    ```

2. Get the other database information:
    1. Postgres host
    2. Postgres database user
    3. Postgres database name

3. Log in to remote postgres database using this command. Remember to replace the values of the parameters.
    ```
    psql -h ${POSTGRES_HOST} -U ${DATABASE_USER} -d ${DATABASE_NAME} 
    ```