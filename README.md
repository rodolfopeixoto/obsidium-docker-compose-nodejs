# obsidium-docker-compose-nodejs

Requisitos
 * Docker
 * Docker Compose

Docker-compose desenvolvido para inicializar os microsserviços

#### Instruções

Clone para o seu computador todos os microsserviços

Acesse a pasta

```
cd obsidium-docker-compose-nodejs && docker-compose up
```

***Observações Importantes***

* Todos os microsserviços devem estar fora da pasta ou caso queira modificar, 
poderá alterar o docker-compose em volumes de cada container para apontar para a pasta
* Seus .env devem estar configurados com as variáveis de ambiente. (Todos os microsserviços)

#### Link de todos os microsserviços

Aplicativo (React Native)
 
 É necessario o uso do Expo

[https://github.com/amog-oliveira/obsidium/tree/develop](https://github.com/amog-oliveira/obsidium/tree/develop)

Autenticação e Autorização

[https://github.com/rodolfopeixoto/obsidium-users-api](https://github.com/rodolfopeixoto/obsidium-users-api)

API Gateway

[https://github.com/rodolfopeixoto/obsidium-gateway-api](https://github.com/rodolfopeixoto/obsidium-gateway-api)

Posts e Comentários

[https://github.com/rodolfopeixoto/obsidium-postit](https://github.com/rodolfopeixoto/obsidium-postit)
