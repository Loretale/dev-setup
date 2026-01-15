## Developing for Loretale

There's a couple of main components to the loretale stack. These are:
1. The Hytale server with its plugins
2. The Discord bot

These components use PostgreSQL as a database.

To set up a database with the following credentials:

```
user: dev
password: devpassword
database: loretale
```

You should run the provided `docker-compose`. For more information about Docker compose, please visit the official documentation: https://docs.docker.com/compose/.

Applications that use the PostgreSQL database use environment variables for the username, password, database, and URL. Please consult the readme of the application in question to find out what these environment variables are.

## Setting up a Second Git Account

