# Simple Traefik example

This example, runs two webs site in containers (web1 and web2) Traefik is then used to route traffic based on host headers to the different apps

http://web1.localhost will resolve to the web1 application and http://web2.localhost will resolve to the web2 application

Routes are set up based on the labels parameter in the docker-compose.yml file

A UI for Traefik can be accessed via http://localhost:8080


## Deploying

    git clone https://github.com/RamSailopal/Traefik-Demo
    cd Traefik-Demo
    docker-compose up

## References

https://traefik.io/traefik/