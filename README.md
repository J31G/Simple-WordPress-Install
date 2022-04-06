## Simple WordPress Install

Once Docker is installed, copy the `.env.example` and create a `.env`

```
cp .env.example .env
```

Fill our the `WORDPRESS_DB_NAME` & `WORDPRESS_DB_PASSWORD` in the `.env` file and make any other changes you require.

When happy, run the following command and enjoy wordpress:

```
docker-compose up -d
```
