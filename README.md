# Taller8-AREP
### Integrantes: Julia Mejia y Cristian Rodriguez  

Aclaración: El profesor nos dió plazo de entrega para el laboratorio hasta el viernes 3/11  

API que permita a los usuarios hacer posts de 140 caracteres e ir registrandolos en un stream único de posts (a la Twitter).  

## EJECUCIÓN
1. Guardamos los archivos estaticos en un bucket S3  
   <img width="286" alt="image" src="https://github.com/CrisRod8/Taller8-AREP/assets/111186898/02e848e6-b39d-40ce-bd8e-f6ab2186753b">  
   <img width="627" alt="image" src="https://github.com/CrisRod8/Taller8-AREP/assets/111186898/9b289e23-5386-4d97-8248-bb6b02812abe">
3. Creamos una base de datos y una coleccion en mongo atlas  
   <img width="786" alt="image" src="https://github.com/CrisRod8/Taller8-AREP/assets/111186898/35171fed-7f84-4e18-8708-5a5dfd61cc54">  
2. Creamos una instancia en EC2  
3. Dentro de la consola de la EC2 instalamos QUARKUS con los siguientes comandos  
* Desde una consola linux:  
`curl -Ls https://sh.jbang.dev | bash -s - trust add https://repo1.maven.org/maven2/io/quarkus/quarkus-cli/`  
`curl -Ls https://sh.jbang.dev | bash -s - app install --fresh --force quarkus@quarkusio`  
4. corremos QUARKUS con : `quarkus dev`

Video de prueba:  

https://youtu.be/TJPJuGt38Yg






