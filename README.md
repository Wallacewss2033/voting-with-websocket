# voting-with-websocket - Votação em Realtime.

- Responsivo
- Modo Dark e Light.


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
 



# Para rodar com o projeto

## Instalação 

1 - Clone o projeto
```
git clone git@github.com:Wallacewss2033/voting-with-websocket.git
```

2 - Dentro do projeto 

  a) Corra o comando abaixo para clonar o repositório do frontend. 

```
 git clone git@github.com:Wallacewss2033/voting_websocket_app.git
```
  b) Entre na pasta do frontend e rode o comando abaixo
```
 npm install
```
  
3 - Volte para a raiz do projeto "voting-with-websocket".

  a) Corra o comando abaixo para clonar o repositório do backend.

```
  git clone git@github.com:Wallacewss2033/voting_websocket_api.git
```
  b) Entre na pasta do backend e rode o comando abaixo
  
```
 composer install
```

5 - Agora, volte até a pasta do projeto "voting-with-websocket" e digite o comando abaixo.

```
  docker-compose up -d --build
```

## Configurações

  1 - Entre na pasta do backend e rode o comando abaixo para entrar no terminal do container
  
    docker exec -it voting-api bash
    
  2 - Rode o comando abaixo para execultar as filas
  
  ```
  php artisan queue:work
  ```

# IMAGENS - projeto rodando!

### Responsivo para desktop
<div> 
   
  - Dark Mode  
  
  ![image](https://github.com/Wallacewss2033/voting-with-websocket/assets/39920409/fe2e1905-c0a6-424d-a79f-e50c7d84194f)

  - Light Mode
  
  ![image](https://github.com/Wallacewss2033/voting-with-websocket/assets/39920409/5de02885-56f9-4427-8f22-448dfc4ba39d)
    
</div>
 
### Responsivo para mobile

<div align="center"> 
  
![image](https://github.com/Wallacewss2033/voting-with-websocket/assets/39920409/353b88d7-e113-4f00-b1c3-02edae816348) ![image](https://github.com/Wallacewss2033/voting-with-websocket/assets/39920409/39938022-bd6c-4718-9984-3a0856822619)
    
</div>
  
  
# Gifs

### Responsivo para desktop

![Video_1699983265](https://github.com/Wallacewss2033/voting-with-websocket/assets/39920409/50b74061-5310-42ea-a5ae-77f7d722f4bf)


### Responsivo para mobile

<div align="center"> 
  
![Video_1699978358_1_](https://github.com/Wallacewss2033/voting-with-websocket/assets/39920409/ab1e1382-cec9-4000-9d94-52113d02f465)
    
</div>






