## Sergio Andres Carrillo Muñoz - 2171714
## Juan Felipe Ortiz Trillos - 2170105

# Correr la app #

Para correr la app se hace un:  

docker build -t nombreimagen:V1 .


# Comandos #

Consultar usuario -- GET : http://localhost:18082/demo/all


Agregar usuarios -- POST : http://localhost:18082/demo/add

ejemplo del JSON para agregar usuario:

Entrada: 
{
"name":"container",
"email":"user@mail.com"
}
