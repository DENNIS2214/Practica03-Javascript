# Practica03-Javascript


 	FORMATO DE INFORME DE PRÁCTICA DE LABORATORIO / TALLERES / CENTROS DE SIMULACIÓN – PARA ESTUDIANTES

CARRERA:INGENIERIA DE SISTEMAS	ASIGNATURA: PROGRAMACION HYPERMEDIAL
NRO. PRÁCTICA:	3	TÍTULO PRÁCTICA: Resolución de problemas sobre JavaScript
OBJETIVO  
•	Entender y organizar de una mejor manera los sitios de web en Internet
•	Diseñar adecuadamente elementos gráficos en sitios web en Internet.
•	Crear sitios web aplicando estándares actuales.
INSTRUCCIONES  
	A partir de los siguientes problemas se pide implementar soluciones basadas en el lenguaje de programación de JavaScript usando funciones y eventos. 
1.	Diseñar una interfaz en HTML que permita ingresar los siguientes campos en un formulario: cedula, nombres, apellidos, dirección, teléfono, fecha de nacimiento, correo electrónico y contraseña. Luego, usando funciones de JavaScript se pide validar que todos los campos han sido ingresados, además; que los valores ingresados en cada campo del formulario sean correctos teniendo en cuenta las siguientes condiciones: 
a.	Se debe validar qué, en el campo de la cedula, se ingrese sólo números y que la misma sea correcta, en base, al último dígito verificador. 
b.	Se debe validar qué, en el campo del nombres, ingrese mínimo un nombre y que permita ingresar sólo letras. 
c.	Se debe validar qué, en el campo del apellidos, ingrese mínimo un apellido y que permita ingresar sólo letras. 
d.	Se debe validar qué, en el campo del teléfono, permita ingresar sólo números y un máximo de 10. 
e.	Se debe validar que la fecha de nacimiento ingrese en el formato dd/mm/yyyy. 
f.	Se debe validar qué, en el campo correo electrónico, permita ingresar un correo válido. Se considera un correo válido, cuando comienza por tres o más valores alfanuméricos, luego un @, seguido por la extensión “ups.edu.ec” o “est.ups.edu.ec”. 
g.	Se debe validar que la contraseña ingresada tenga mínimo 8 caracteres, además, debe incluir al menos: una letra mayúscula, una letra minúscula y un carácter especial (@, _, $) 
 
Indicaciones: 
•	Para realizar las validaciones de solo letras, o sólo números. Se las debe realizar en tiempo real, es decir, a medida que el usuario escribe en el campo. 
•	Todos los campos de entrada dentro del formulario deben de ser de tipo “text”. 
•	Las demás validaciones se realizarán al momento de “enviar” (submit) la información del formulario hacia una página php. Si no cumple las validaciones, se mostrará un mensaje debajo de cada campo con el error y se pintara el campo con un borde rojo que representará que el campo tiene un error. ¡Si se cumple las validaciones, se enviará a una página php, en donde se mostrará únicamente un mensaje que diga “Bienvenido, pasaste las validaciones!”.

2.	Diseñar una interfaz en html que tenga tres botones que diga “Anterior”, “Iniciar”, “Siguiente”, y una imagen. Luego, desde javascript se debe controlar para al hacer clic sobre uno de los botones realice una acción relacionada a una galería de imágenes (ver ejemplo, https://gihp4c.blog.ups.edu.ec/) 
Indicaciones: 
• Se debe tener, un arreglo con los nombres de diez imágenes, previamente descargadas y almacenadas en una carpeta llamada “images”.
• La galería de imágenes debe visualizar exclusivamente 5 imágenes.  
• Cada vez que se haga clic en le botón iniciar se deben escoger de manera aleatoria cinco imágenes de las diez que se mostrarán en la galería de imágenes. 
• Al hacer clic en el botón siguiente y haber llegado a la última imagen disponible, el botón siguiente deberá ser deshabilitado (sólo cuando se ha llegado a la última imagen el botón siguiente deberá estar deshabilitado) 
• Al hacer clic en el botón anterior y haber llegado a la primera imagen disponible, el botón anterior deberá ser deshabilitado (sólo cuando se ha llegado a la última imagen y cuando se inicie la galería de imágenes el botón anterior deberá estar deshabilitado)
ACTIVIDADES DESARROLLADAS
1.	Crear un repositorio en GitHub con el nombre “Practica03 – Javascript” 
Creamos un nuevo repositorio con las especificaciones dadas .
 
2.	Crear una carpeta para la solución de cada ejercicio antes mencionado
3.	Realizar un commit y push por cada requerimiento de los puntos antes descritos.
 
4.	Luego, se debe crear el archivo README del repositorio de GitHub
a.	Generar informe de los resultados en el formato de prácticas. Debe incluir:
b.	El desarrollo de cada uno de los puntos antes descritos.
1.	Diseñar una interfaz en HTML que permita ingresar los siguientes campos en un formulario: cedula, nombres, apellidos, dirección, teléfono, fecha de nacimiento, correo electrónico y contraseña. Luego, usando funciones de JavaScript se pide validar que todos los campos han sido ingresados, además; que los valores ingresados en cada campo del formulario sean correctos teniendo en cuenta las siguientes condiciones: 
a.	Se debe validar qué, en el campo de la cedula, se ingrese sólo números y que la misma sea correcta, en base, al último dígito verificador. 
 
b.	Se debe validar qué, en el campo del nombres, ingrese mínimo un nombre y que permita ingresar sólo letras. 
   
c.	Se debe validar qué, en el campo del apellidos, ingrese mínimo un apellido y que permita ingresar sólo letras. 
 
d.	Se debe validar qué, en el campo del teléfono, permita ingresar sólo números y un máximo de 10. 
               

e.	Se debe validar que la fecha de nacimiento ingrese en el formato dd/mm/yyyy. 
 
f.	Se debe validar qué, en el campo correo electrónico, permita ingresar un correo válido. Se considera un correo válido, cuando comienza por tres o más valores alfanuméricos, luego un @, seguido por la extensión “ups.edu.ec” o “est.ups.edu.ec”. g
               

g.	Se debe validar que la contraseña ingresada tenga mínimo 8 caracteres, además, debe incluir al menos: una letra mayúscula, una letra minúscula y un carácter especial (@, _, $)
  
2.	Diseñar una interfaz en html que tenga tres botones que diga “Anterior”, “Iniciar”, “Siguiente”, y una imagen. Luego, desde javascript se debe controlar para al hacer clic sobre uno de los botones realice una acción relacionada a una galería de imágenes (ver ejemplo, https://gihp4c.blog.ups.edu.ec/) 
                    Indicaciones: 
                     • Se debe tener, un arreglo con los nombres de diez imágenes, previamente descargadas y 



almacenadas en una carpeta llamada “images”. 













 
         • La galería de imágenes debe visualizar exclusivamente 5 imágenes.  

                      






• Cada vez que se haga clic en le botón iniciar se deben escoger de manera aleatoria cinco imágenes de las diez que se mostrarán en la galería de imágenes. 

















         
• Al hacer clic en el botón siguiente y haber llegado a la última imagen disponible, el botón siguiente deberá ser deshabilitado (sólo cuando se ha llegado a la última imagen el botón siguiente deberá estar deshabilitado) 












 
        • Al hacer clic en el botón anterior y haber llegado a la primera imagen disponible, el botón anterior deberá ser deshabilitado (sólo cuando se ha llegado a la última imagen y cuando se inicie la galería de imágenes el botón anterior deberá estar deshabilitado)
 

3.	La evidencia de la correcta estructuración de las páginas HTML. Para lo cual, se puede generar fotografías instantáneas (pantallazos).
            GALERIA
                CARPETA DE IMÁGENES, ARCHIVO JS, ARCHIVO CSS Y ARCHIVO HTML
 
             VALIDACION
              ARCHIVO JS, ARCHIVO PHP, ESTILOS CSS Y ARCHIVO HTML
 
GALERIA.ESTILO.CSS
 
GALERIA.MOSTRAR.JS
 
GALERIA.PRINCIPAL.HTML
 

VALIDACION.JS.VALIDAR.JS
 
VALIDACION.PHP.CONECTAR.PHP
 
VALIDAR.ESTILO.CSS
 
VALIDACION.FORMULARIO.HTML
 
4.	El informe debe incluir conclusiones apropiadas.
5.	En el informe se debe incluir la información de GitHub (usuario y URL del repositorio de la práctica) 
USUARIO: DENNIS1994
                    URL: https://github.com/DENNIS2214
6.	En el informe se debe incluir la firma digital del estudiante.
7.	En el archivo README del repositorio debe constar la misma información del informe de resultados de la práctica que se indica en el siguiente punto.
 

RESULTADO(S) OBTENIDO(S):
PRINCIPAL
 
CLIC EN INICIO
 
SIGUIENTE HASTA FINAL
 
ANTERIOR HASTA INICIO
 
FORMULARIO
 
CONCLUSIONES:
•	Los estudiantes podrán organizar sitios web basados en el lenguaje de etiquetado HTML
•	Dentro de la creación de páginas web vemos que los conocimientos de HTML son muy importantes y de mucha facilidad a la hora de desarrollar.
•	Así también en este punto es de mucha importancia el uso de combinaciones con otras herramientas como JavaScript, CSS, etc.
•	HTML cumple con la facilidad de desarrollo de páginas web así también es de mucha ayuda para comenzar a formarse como desarrolladores web.
RECOMENDACIONES:
•	Probar la solución de la práctica en al menos tres navegadores web; Google Chrome, Firefox y Safari
•	Revisar los conceptos básicos de este tema para así poder ejecutar el desarrollo de mejor manera.

Nombre de estudiante: DENNIS ALEJANDRO PEÑARANDA TELLO

Firma de estudiante:  


