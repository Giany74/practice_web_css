Fundamentos Web: HTML5, CSS3
Enunciado de la práctica Full Stack Web Bootcamp
INFORMACIÓN DE CONTACTO DEL INSTRUCTOR
Kevin Martínez
Discord Tag: kevinccbsg#2306
https://www.linkedin.com/in/kevinjmartinez/
Creación de un portfolio
Consideraciones generales
● No se permite el uso de librerías y frameworks externos como Bootstrap,
Spectre.css o similares.
● Se tiene que crear una o más hojas de estilo CSS para aplicar el diseño deseado a
la web.
● La página web debe visualizarse correctamente en las versiones actuales de Google
Chrome, Mozilla Firefox y Microsoft Edge.
● No se puede usar JavaScript.
Descripción de la práctica
Nuestro objetivo es contruir un portfolio sobre nosotros (o un personaje de ficción). Este
proyecto tiene que cumplir los siguientes requisitos:
● Crear un header con barra de navegación, la cual tiene que tener enlaces a cada
elemento del portfolio. Todos los links tendrán que tener el estado hover suavizado
con una transición. Estos links no son necesarios en la versión móvil.
● Una sección con una descripción de nosotros y con nuestras habilidades como
barras de progreso. Estas barras de progreso tienen que estar animadas con
animaciones css.
● Banner que deberá tener una imagen de fondo. En pantallas moviles deberá ser
otra, para darle más sentido al diseño en dicha resolución.
● Formulario de contacto con estos inputs. Todos ellos tienen que tener tanto los tipos
correctos como la validación html de cada input.
○ Nombre - (campo requerido)
○ Apellidos - (campo requerido)
○ Teléfono - (campo requerido)
○ Unos radio input para responder a la pregunta "¿como me conociste?" -
(requerido)
■ Universidad
■ Keepcoding kick-off
■ Colegio
■ En Github
○ Tag de github (Usar regexp “^@[^\s]+” para la validación - @username)
○ Mensaje con más información del usuario (Text area max 180 characters) -
(campo requerido)
○ Acceso a la newsletter (Checkbox)
○ Botón de guardado
○ Botón de reset
● Footer con links a nuestras redes sociales. Importante tener en cuenta que son links
a recursos externos.
● Nueva página que tenga un video que se reproduzca al entrar en la web y aparezca
con una animación de fadeIn.
● En la nueva página crear un grid con nuestros proyectos. Ver capturas para el
diseño.
● README con toda la información necesaria para facilitar la forma de evaluar la
práctica. https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/
● (Opcional) Podemos hacer un menu burger con solo CSS y un input checkbox, para
no usar JS pero esto es bastante avanzado.
● (Opcional) Despliegue en Github pages
● (Opcional) Página de 404. Libre diseño
● (Opcional) Página 500. Libre diseño
Detalles de implementación
● La estructura de la web tiene que tener en cuenta las etiquetas de contenido
semántico.
● Debéis incluir las media queries necesarias para que el diseño sea responsivo. Tiene
que SER MOBILE FIRST!! Sino es un NO APTO.
● Las animaciones o interactividad propuesta deben realizarse exclusivamente
mediante técnicas CSS sin el uso de librerías externas.
● Los apartados marcados como opcionales no son necesarios para obtener la
calificación de APTA, pero se valorarán positivamente.
● Tiene que entregarse en a traves de Gtihub. No se valorará, pero un buen uso de
commits será algo positivo. Una entrega en un solo commit, no es algo correcto.
Anexos posibles diseño

Guía de desarrollo
La primera práctica puede ser complicado de empezar. En esta guía te voy a dar algunos
tips sin nada de código.
Toma referencias
Antes de empezar un proyecto de este tipo es importante que tomes referencias de webs
que te gusten o de templates del mercado. Te dejo algunos links a modo de ejemplo:
https://themeforest.net/search/portfolio
https://bashooka.com/html/free-html-css-portfolio-web-design-templates/
Ýo suelo tomar ideas y luego pensar la estructura en un papel para luego empezar a
maquetar. Normalmente se suele recomendar usar un color base (amarillo en el ejemplo de
shin chan) y luego jugar con blancos, negros y grises. Cuidado con la mezcla de colores y el
uso de sombras excesivo.
Empezemos creando el proyecto
Lo primero es crear una carpeta donde montar nuestro proyecto y añadir un index.html con
la estructura que nos da vscode al escribir html:5.
Recuerda crear un proyecto de Git, con git init y hacer un commit de este primer paso.
En este punto yo crearía la carpeta css o styles. Para guardar los archivos de css del
proyecto.
Dividir cada sección. Footer
Podemos empezar con el footer. Para ello crea las variables con tus colores para la app o la
fuente. Recuerda añadir el css correctamente en tu proyecto, usar html semántico, centrar
el texto y jugar con los diferentes estilos de la fuente en el footer.
Cuando termines con la sección haz un commit. Siempre es mejor hacer commit de algo sin
terminar que subir todo en un solo commit.
Navbar
Para la navbar vas a tener que alinear dos bloques, el logo y la navegación de forma
horizontal. Recuerda como hicimos esto en clase. En este apartado probablemente tengas
que añadir media queries. Ya que los links en móvil no se ven pero en desktop si.
Info
En esta sección se busca poner en práctica animaciones, el manejo de fuentes y el uso
correcto de etiquetas semánticas.
Para las animaciones, te recomiendo ir probando con diferentes anchos para simular el
efecto de barra de progreso.
Recuerda ir haciendo commits.
Banner
En esta sección tenemos que prácticar los background image y otra vez añadir media
queries para cambiar el background dependiendo de la resolución.
Recuerda ir haciendo commits.
Form
Mi recomendación es que maquetes el formulario primero sin ningún estilo y te asegures de
que funciona bien, que tiene el method correcto y los campos están bien validados. Luego
puedes añadirle el estilo que quieras. Te recomiendo que los inputs sean lo más anchos
posibles y que no uses anchos fijos tipo “px” sino relativos “%”.
Recuerda ir haciendo commits.
Projects Page
En esta nueva página intenta usar lo máximo posible archivos de css que tengas creados
de antes. Recuerda que tendrás que poner en práctica el CSS grid y las animaciones otra
vez. Pero en este caso más sencilla.
Recuerda ir haciendo commits.