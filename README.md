## Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos
Scraping selenium, mongoDB y aplicativo web python, flask
### PASOS CREACIÓN DE REPOSITORIO GIT 
1. Colocamos en new.
2. Ingresamos un nombre.
3. Colocamos en public
4. Damos click en añadir README.md.
5. En Add .gitignore colocamos pyhon.
6. Damos click en crear repositorio.
   
![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/1510390e-71af-4d10-a734-b00219e94aba)

### PASOS CREACIÓN PROYECTO
1. Clonamos el repositorio de git.
   
 ![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/7fe0b99d-c7f3-46fb-ba22-fdc99ba6e420)
 
2. Creamos Python interpreter en settins Project: python interpreter
   
![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/f4374f4d-1e96-4cd8-bde1-291957f02645)

4.	Crear un archivo requirements.txt
   
  ![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/ac5c0f09-e8bb-4f08-81e5-3e3740325706)

5. Ingresamos las librerías que vamos a usar, y damos en install requirements y esperamos que se instalen las librerías.

![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/430fb99a-34bc-4a8e-9acd-0a744373bb5d)

8.	Creamos nuestro archivo book.py donde vamos a escribir los comandos para acceder a la página web, la conexión a la base de datos mongoDB.
   
 ![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/4f543d3f-13b0-47e1-9b64-10f3619a4741)
 
10.	Código usado en el archivo books.py 

![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/438182e4-7fce-406a-86df-64a16f13b6be)

![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/928d53e6-78fb-4278-900a-7bbbc92d9312)

7.	Creamos el archivo mongo.py donde realizamos la conexión a la base de datos, código usado en el archivo mongo.py

![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/e5694f5e-ec81-4ac5-b0fb-a59f2b0f2b11)

![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/0ae546cc-5d57-440d-827c-815e88f69f23)

8.	Creamos un archive env., donde creamos las variables para guardar el nombre de usuario, contraseña y nombre del cluster, para la conexión en mongoDB.
 
Usuario, clave y nombre de la base MongoDB

MONGO_USER=*********** # replace with yours

MONGO_PASSWORD=**************** # replace with yours

MONGO_HOST=************************* # replace with yours

9.	Creamos una carpeta templates para crear el index.html para realizar la búsqueda de los datos en nuestra base de MongoDB
 
 ![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/c9df9879-498b-40cc-87e5-93f3ad7ea868)

10.	Creamos un html dentro de la carpeta templete donde vamos a escribir el código que realizara la consulta hacia la base de datos,
 
![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/bc58fc15-d44c-4c98-9304-e3afdcc93f89)


11.	Código usado para la creación de la página html.

![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/1854c772-47c6-4e9a-9344-3ca702be283f)

![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/d11ed0b7-0b48-459c-9d78-ba37d83c3514)

12.	Creamos un archive app.py donde creamos la aplicación para la búsqueda de datos en nuestra base MongoDB.
 
![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/a9125fae-693c-4aa9-bdbb-7d0836b55402)

13.	Código usado para la aplicación

![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/c16e2d73-e9fb-435f-b9ba-d6152bbaeeef)

![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/03cd2d94-f14e-4db4-83e0-159f1a6897d6)

## RESULTADOS 
 1. Acceso a la página web y extracción de datos

    ![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/546a2334-f633-4b20-a46e-d260768a36a7)

2. Impresión de datos en la consola

 ![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/1878a065-ac4b-474a-892e-553618b56409)

3. Visualización de datos en MongoDB

   ![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/3d28c500-bf88-42b3-80a4-f221cacffac5)

 4. Ejecución de app.py

  ![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/f20ca147-cf76-4d39-8cef-9a25bf59f033)

5. Damos click en el enlace http://127.0.0.1:5000 y nos llevara a la aplicación html 

![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/4a8b208b-fa06-4356-8084-24af65d8d0d1)

6. Ingresamos las palabras para visualizar si existe alguna coincidencia con lo que almacenamos en la base de datos mongoDB.

   ![imagen](https://github.com/juanfran1990/Ciberseguridad-Grupo-A-Prueba-Final_Analisis-de-Datos/assets/144498873/ad1c4ddc-f0a1-41e4-9eed-a8a7b09f1a8b)

## CONCLUSIÓN
Mediante la técnica de webscraping podemos extraer los datos de cualquier página web y almacenarlos en una base de datos para su posterior análisis, de esta manera podemos conseguir grandes cantidades de datos de manera automática de varios sitios webs.



