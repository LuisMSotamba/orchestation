# Orquestación de microservicios

Este proyecto consta de 4 microservicios y una carpeta de configuración centralizada que sirve para otros microservicios.
1. Admin service: Encargado de mostrar un dashboard con analíticas de los microservicios asociados.
2. Config service: Encargado de enviar el archivo de configuración solicitado por otros microservicios.
3. Gateway service: Funciona como una puerta de enlace única para hacer peticiones a diferentes microservicios
4. Registry service: Microservicio que contiene Eureka server, el cual muestra la salud del microservicio asociado.
5. Config data: carpeta que contiene los archivos de configuración de cada microservicio.

# Ejecución
Dentro de cada microservicio emitir los siguientes comandos para construir y ejecutar el servidor de desarrollo.

`gradlew build` y

`gradlew bootRun`