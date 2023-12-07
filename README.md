# Baby-Php
A zero configuration App built with Php, Docker, Postgresql, Flyway
### initial Setup (only once)
```bash
chmod +x bin/build
chmod +x bin/reset
```
### Boot-Up the project
```bash
bin/build
```

### Addresses
```bash
php-server: http://localhost:1234/
phpMyAdmin: http://localhost:4321/ 
Note: (username, pass & database are in .env)
```

## Useful Commands
### Rests Database & create & run migrations (you will lose all data)
```bash
bin/reset
```


## Run Database Migration (optional)
```bash
dc up migration
```




