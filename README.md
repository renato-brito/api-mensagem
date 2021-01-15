# api-mensagem
Trabalho final da disciplina de Containers and Virtualization da FIAP

Integrantes:

- Harold Isaac Campero Stoffers Murillo - 337233
- Renato Santana Brito - 337364

## Executando

```
docker-compose up -d
```

## Testando

Acessar URL e enviar requisições GET, POST, PUT, DELETE

```
GET:
http://localhost:8000/mensagens

POST:
http://localhost:8000/mensagens
-- exemplo de body abaixo

PUT and DELETE
http://localhost:8000/mensagens/{ID}

Obs: Em caso de PUT adicionar Boby
```

### Exemplo objeto para requisição POST 

```
{
  "text": "Texto para ser salvo"
}
```

