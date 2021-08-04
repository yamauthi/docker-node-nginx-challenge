## Docker Node.JS - NGINX - MySQL Challenge

Generate the following docker images:
- **NGINX:** A configured NGINX with reverse proxy pointing to **Node.js** application in another container.

- **Node.js:** An application that access the **MySQL** database in another container and inserts a name record in a people table and returns 
    ~~~html
    <h1>Full Cycle Rocks!</h1>
    --List of all people names--
    ~~~

- **MySQL:** Database image with a volume mounted to persist all the data in disk

PS: When run the command bellow all the containers need to be running and the application available at 8080 port
~~~Docker
docker-compose up -d
~~~

**This is a challenge from Full Cycle Developer course from Code Education.**
