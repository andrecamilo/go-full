


### rodar o seguinte comando para criar a base de dados postgres
    docker run --name postgres9.6 -p 5454:5432 --restart=always -e POSTGRES_USER=postgres -e POSTGRES_PASSWORD=postgres -v /var/lib/postgresql/data:/var/lib/postgresql/data -d postgres:9.6