# Testing AWS RDS

Testing project of Amazon PostgreSQL

## How to run

- Set the db password as an environment variable in shell (or in IntelliJ run config)
    ```bash
    export AWS_POSTGRES_PASSWORD_TESTING_PROJECT="<password value>"
    ```

- Run the app
    ```bash
    mvn spring-boot:run
    ```