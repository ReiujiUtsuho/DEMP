# DNMP
Dockerized Nginx MySQL PHP (for Typecho)

## How to use

1. Put your code or programs into `/www`
2. Check the `docker-compose.yml` if there is any configuration to modify
3. Remember to change the database name, user and password by editing the environment variables
4. The database connect address is `mysql` as the service name in the `docker-compose.yml`
5. Generate or put SSL certificate and key to `/ssl`, then add corresponding configurations to the files under `/conf` (Optional)
6. Just `docker-compose up -d`
