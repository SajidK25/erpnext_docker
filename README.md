# ERPNext on Docker

- git clone https://github.com/SajidK25/erpnext_docker.git
-   cd erpnext_docker/
-   mkdir logs
-   mkdir sites
-   cp .env.example .env
-   docker network create nginx
-   docker network create erpnext
-   docker compose pull
-   docker compose up
-   

- docker-compose exec backend bench new-site --no-mariadb-socket --mariadb-root-password admin --admin-password admin new_site_sajid