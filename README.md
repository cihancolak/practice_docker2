# myapp app

This app was bootstrapped with [Imagine.ai](https://imagine.ai) 💛

> Imagine.ai is an app starter on steroids!

### Run the app in terminal

1. Start a MySQL database server on your machine or in the cloud.
2. Set the following environment variables in your .env file

```
MYSQL_HOST=<address-where-database-running>
MYSQL_PORT=<port-where-database-running>
MYSQL_USER=<username-for-database>
MYSQL_DATABASE=<database-name>
MYSQL_PASSWORD=<password-to-database>
// root password is only needed if using docker
MYSQL_ROOT_PASSWORD=<root-password-to-database>
DB_DIALECT=mysql
```

3. Install packages and start the application server.

```
$ yarn install
$ yarn start
```

### Make API calls against the server

1. Go to [http://localhost:8000/swagger](http://localhost:8000/swagger) to see Swagger documentation for API endpoints.
2. Run the APIs by clicking the "Try it now" button on the Swagger page.

### Run admin bro dashboard

Go to [http://localhost:8000/admin](http://localhost:8000/admin)

### Run tests and check code coverage

```
$ yarn test
$ yarn coverage
```

### Lint your code

```
$ yarn lint
$ yarn format
```

### Learn More

1. Learn more about:

- the [Node architecture choices](https://imagine.ai/docs/architecture-node) used.
- the [best practices](https://imagine.ai/docs/best-practices) followed.

2. Imagine is in beta - here are the [known issues](https://imagine.ai/docs/known_issues) that we are working to fix.
