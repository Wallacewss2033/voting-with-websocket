# voting-with-websocket - Com Modo Dark e Light.

Projeto voting-with-websocket - (SPA E API) 
- Nginx
- Docker.
- VueJs (Quasar)
- Laravel
  - PHP 8.2 
  - Websocket (Pusher e echo)
  - Event
  - Broadcasting
  - Job/filas     
- MySQL
- Redis
 



## Para rodar com o projeto

1 - Clone o projeto
```
git clone git@github.com:Wallacewss2033/voting-with-websocket.git
```

2 - Dentro do projeto crie duas partas ( uma para o frontend e outra para o backend ).

  a) Para o frontend crie com o nome de "voting-websocket-app"
  
      $ mkdir voting-websocket-app
  
  b) Para o backend "voting-websocket-api"
  
      $ mkdir voting-websocket-api

3 - Entre na pasta do frontend e corra o comando abaixo para clonar o repositório do frontend. 

```
 git clone git@github.com:Wallacewss2033/voting_websocket_app.git
```

```
 npm install
```


4 - Entre na pasta do backend e corra o comando abaixo para clonar o repositório do back. 

```
  git clone git@github.com:Wallacewss2033/voting_websocket_api.git
```

```
 composer install
```

5 - Agora, volte até a pasta do projeto "voting-with-websocket" e digite o comando abaixo.

```
  docker-compose up -d --build
```

# Em construção...
