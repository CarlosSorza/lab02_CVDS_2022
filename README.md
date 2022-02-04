## Laboratorio 2 -DAVID LEON, CARLOS SORZA
## Crear un proyecto con maven

Busque cómo ejecutar desde línea de comandos, un proyecto maven y verifique la salida cuando\
se ejecuta con la clase App.java como parámetro en "mainClass".
Tip: https://www.mojohaus.Sorg/exec-maven-plugin/usage.html
- Se obtiene como respuesta hello world!
- mvn exec:java -Dexec.mainClass="edu.eci.cvds.patterns.App


Para ver el conjunto de archivos y directorios creados por el comando mvn ejecute el comando tree.

$ tree

![image](https://user-images.githubusercontent.com/78982514/152186996-b3df3045-4764-49f1-82a1-4474bb5ad7e0.png)

## Copilar y ejecutar

Busque cuál es el objetivo del parámetro "package" y qué otros\
parámetros se podrían enviar al comando mvn.
- Compila la aplicacion de java en torno a las dependencias declaradas en el POM\
Para compilar ejecute el comando:

$ mvn package

![image](https://user-images.githubusercontent.com/78982514/152187291-7859d48f-2738-4845-aacf-059577ffa4f2.png)

Hello World!

![image](https://user-images.githubusercontent.com/78982514/152187470-3b0a8eb1-b6e6-4f2a-a2b4-160dd65138c7.png)

Hello PepitO

![image](https://user-images.githubusercontent.com/78982514/152187793-553e40b1-902e-4da9-aea9-4a8ab6306e2c.png)


Realice el cambio en la clase App.java para crear un saludo personalizado, basado en los parámetros\
de entrada a la aplicación. Utilizar la primera posición del parámetro que llega al método "main" \
para realizar el saludo personalizado, en caso que no sea posible, se debe mantener el saludo \
como se encuentra actualmente:

- Buscar cómo enviar parámetros al plugin "exec".\
-Ejecutar nuevamente la clase desde línea de comandos y verificar la salida: Hello World!\
-Ejecutar la clase desde línea de comandos enviando su nombre como parámetro y verificar la salida. Ej: Hello Pepito!\
-Ejecutar la clase con su nombre y apellido como parámetro. ¿Qué sucedió?

Sigue imprimiendo hello world!

-Verifique cómo enviar los parámetros de forma "compuesta" para que el saludo se realice con nombre y apellido.\
-Ejecutar nuevamente y verificar la salida en consola. Ej: Hello Pepito Perez!

Al realizar los cambios correspondientes para que el archivo leyera la entrada e\
imprimiera los elementos obtenemos que al entrar los parametros los imprime automaticamente\
Ejecute múltiples veces la clase ShapeMain, usando el plugin exec de maven con los siguientes parámetros y \
verifique la salida en consola para cada una:



## Hacer esqueleto de la aplicacion 
Sin parámetros 
![image](https://user-images.githubusercontent.com/78982514/152190450-365d1781-5811-4b8d-96d8-9753d3b6ef3d.png)

Parámetro: qwerty

![image](https://user-images.githubusercontent.com/78982514/152190555-52971885-e597-4539-aba9-0f0358462fa7.png)

Triangle 

![image](https://user-images.githubusercontent.com/78982514/152190648-ce9b9e0e-c8f4-4a31-979e-0ec0fcec4ccf.png)

Pentagon

![image](https://user-images.githubusercontent.com/78982514/152190811-a1f145a6-242c-4c19-b475-5a6743a4185d.png)

Hexagon

![image](https://user-images.githubusercontent.com/78982514/152190868-3974ed0e-d19a-4ba8-b8f9-dd881c7bd3f9.png)

¿Cuál(es) de las anteriores instrucciones se ejecutan y funcionan correctamente y por qué?\
El codigo sirve bien en las entradas, ya que no entran figurar regulares\
o errores de sintaxis, se generan las respuestas esperadas

Investigue para qué sirve "gitignore" y cómo se usa. Para futuras entregas, debe estar configurado.\
Git ignore es un archivo.gitignore que permite escribir las extenciones de los archivos\
que no deseo en el repositorio, por ejemplo los .class de mi proyecto
