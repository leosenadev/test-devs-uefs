
1 criar uma DB Mysql: crud
2 abrir o a pastaa api-app
3 realizar o comando: php artisan migrate
4 realizar  o seguintes testes no postman.


### USERS - API 

URL:  http://127.0.0.1:8000/
URI :
/api/users/
/api/users/{params}

POST -  http://127.0.0.1:8000/api/users/
Content-Type: application/x-www-form-urlencoded
Parametros: nome, email.

GET - http://127.0.0.1:8000/api/users/

PUT - http://127.0.0.1:8000/api/users/2
Content-Type: application/x-www-form-urlencoded
parametros: nome, email.

DELETE - http://127.0.0.1:8000/api/users/2 


### POSTS - API 
URL:  http://127.0.0.1:8000/
URI :
/api/posts/
/api/posts/{params}

POST http://127.0.0.1:8000/api/posts
Content-Type: application/x-www-form-urlencoded
Parametros: posts_titulo, posts_comentario.

GET - http://127.0.0.1:8000/api/posts


PUT - http://127.0.0.1:8000/api/posts/1
Content-Type: application/x-www-form-urlencoded
Parametros:  posts_titulo, posts_comentario.

DELETE - http://127.0.0.1:8000/api/posts/1 


### TAGS - API 
URL:  http://127.0.0.1:8000/
URI 
/api/tags/
/api/tags/{params}


POST - http://127.0.0.1:8000/api/tags
Content-Type: application/x-www-form-urlencoded
Parametros: tags

GET - http://127.0.0.1:8000/api/tags


PUT http://127.0.0.1:8000/api/tags/1
Content-Type: application/x-www-form-urlencoded
Parametros:  tag.

DELETE http://127.0.0.1:8000/api/tags/1

