# Set up
This adonis JS template has basic config done.
1. webpack js + sass mixer is configured
2. Bootstrap css + js
3. Configured to use mysql in dev and pg during production.

## Additional Config
1. Update mysql db name (DB_DATABASE) in .env file
2. Create db (with name -> DB_DATABASE) before running migrations

### Migrations
Run the following command to run startup migrations.

```js
adonis migration:run
```
