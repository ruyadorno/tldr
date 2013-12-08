# curl

- Transfers data from or to a server
- Supports most protocols including HTTP, FTP, POP

## Head request

`curl --head http://localhost`

## Send form-encoded data

`curl --data name=bob http://localhost/form`

## Send JSON data

`curl -X POST -H "Content-Type: application/json" -d '{"name":"bob"}' http://localhost/login`

## Specify an HTTP method

`curl -X DELETE http://localhost/item/123`