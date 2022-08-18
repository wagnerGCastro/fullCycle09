# Fullcycle 9 Immersion - Codebank
![Imersão Full Stack && Full Cycle](https://events-fullcycle.s3.amazonaws.com/events-fullcycle/static/site/img/grupo_4417.png)


## Technologies Used

- Bank: Golang
- Checkout and Backend Extract: Nest.js
- Checkout and Extract Frontend: Next.js
- Kafka and Kafka Connect
- Elasticsearch & Kibana
- Docker and Kubernetes
- Istio, Kiali, Prometheus and Grafana


# Useful Commands
  # Docker
    - build
      $ docker-compose build .

    - up container
      $ docker-compose up -d 
      $ docker-compose up -d services db pgadmin

    - exec container
      $ docker-compose exec workspace bash  
      $ docker exec -it id_constainer bash

    - stop/start container
      $ docker-compose stop workspace
      $ docker-compose start workspace

  * Comands in Docker container : 

    - cd codebank
      - $ make gen
      - $ go version
      - $ go run main.go


    - $ evans -r repl -p=50052
      - $ call payment


