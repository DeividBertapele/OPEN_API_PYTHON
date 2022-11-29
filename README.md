# OPEN_API_PYTHON


## Criando uma pequena API de tarefas a fazer (um todo list)


O que precisamos fazer isso?

- Listar tarefas
- Criar tarefas
- Alterar tarefas
- Deletar tarefas

Estrutura do OPEN_API 3.0

![openapi3structure](https://user-images.githubusercontent.com/43301551/204619060-22af658a-b7c0-4384-95e2-a4288369b4d9.png)


Swagger editor => link: https://editor.swagger.io/

![Swagger editor](https://user-images.githubusercontent.com/43301551/204618563-2229a4eb-27a0-44a4-93c8-532af17a1ef6.jpg)


-----------------------------------------------------------------
Para converter o spec.yaml que vai criar arquivo em python:

   - fastapi-codegen -i spec.yaml -o tarefas_app_todo 

-----------------------------------------------------------------

Finalizado usando uvicorn para acessar o API:

![imagem2](https://user-images.githubusercontent.com/43301551/204619505-b6b22e69-dade-4f77-b14d-fd2671cd69f3.jpg)

-------------------------------------------------------------
Funciona também:

Python + OpenAPI

=> Django:

	- django-openapi (Equema de rotas + documentação)
  	
	*drf:
	  - drf-swagger
    
	  - drf-yasg

=> Flask:

	- flaskgger
  
	- flask-pydantic-spec


-------------------------------------------------------------
Links:

- https://spec.openapis.org/oas/latest#openapi-document
- https://swagger.io/specification/
- http://redocly.github.io/redoc/
- https://ostranme.github.io/swagger-ui-themes/



