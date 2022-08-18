# Portfolio-FrontEnd- (en general aca se ponen las licencias)
# Puse añadir archivo y le meti index.html
# En ese archivo escribi html:5 oara que aparezca la estructura (esqueleto)
# En <title>Mi primer HTML</title> aparece lo que aparece en la pestaña
# En el head va el famicon (loguito), los estilos, los meta que hacen al s(i/o)
# body es lo que se ve en la pagina
# Etiquetas de HTML: (h1 a h6: tamaños de letras de mayor a menor)
# <b></b> casi no se usa para negrita. Se usa <strong></strong>
# <div> es un contenedor
# <img> no tiene etiqueta de cierre
# <audio src="02 money machine.m4a" autoplay loop controls></audio>
# autoplay arranca solo
# loop se repite
# controls controles de reproducción
# <form>
# <p>Nombre: <input type="text" name="nombre" size="40" placeholder="Ingrese su Nombre" required></p>
# required me hace que sea condición poner el dato
# placeholder me dice lo ue dice la cajita por defecto antes de poner una letra o número
# <p>Título: <input type="text" name="rol" size="40" placeholder="Este es tu rol" readonly></p>
# readonly hace que no pueda editar, me puede tirar un dato de una base de datos
# subir a github
# nueva terminal o control+shift+ñ
# poner Git Bash si no estaba por defecto
# git init
# ver en las hojas que esta pasando con los archivos
# inicializamos el repositorio
# git add .
# git commit -m "Probamos html"
# git push -u origin
# el <body> es lo que va a ver la gente
# antes de que cierre <body> ponemos todos los scripts
# antes de que cierre <head> ponemos todos los estilos
# Para agregar estilos a mi página agrego a <head>:
# <link rel="stylesheet" type="text/css" href="styles.css">
# Hago el archivo de estilos styles.css
# Creo carpeta assets y dentro de esa la carpeta css y muevo el styles.css ahí
# en assets tambien hago una carpeta js para los scripts y una img para las imágenes
# en styles.css se usa *{} para que sea general
# por el styles.css esta en una carpeta uso: <link rel="stylesheet" type="text/css" href="assets/css/styles.css">
# styles.css
# *{
#     width: 70%; (ancho) (atributo: valor)
#     margin: 0 9% 5% 7%; (margen) (12:00 03:00 06:00 09:00) se le puede meter solo 2 valores y el primerp va a 12:00 y # 6:00 y el segundo de 03:00 y 09:00; con margin: auto se acomoda solo) (seria en sentido de la agujas del reloj) (se 
# puede usar con %, px)
#     padding: 0; ()
# }
# el padding es el deplazamiento interno de lo que queremos seleccionar. Hay padding positivo y negativo
# para hacer comentario en css se usa /*comentario*/
# Atajo para hacer comentario: control + k + c
# Class 
# Se pueden poner estilos desde cualquier lado, pero prefible poner en css
# Si es para una sola página los puedo poner antes del </head>, sino se pone otra hoja de estilos para esa pagina y la linkeo con solo esa página
# Para poner un fondo s
# Las clases se pueden llamar como se quiera
# Si a un <div> se le pone una te cambia todo el <div>
# Para verificar como realizar páginas se puede usar https://codepen.io
# Generamos una página html nueva (dashboard) que sería la página de (adaptación?)
# Cada documento html que hago necesita la referencias a todo (css, bootstrap, javascript)
# Agregamos un tab pero como en responsibe puede dar problemas usamos List Group o Button Group (de Bootstrap)
# Definimos que hacer: se pone como ejemplo hacer como en la página de Bootstrap.
# Poner una columna a la izquierda
# Buscar carrousel en bootstap (si lo haces con aspect ratio recortas las imágenes para que tengan todas el mismo tamaño)
# Armar la maqueta con bootstrap
# No meter muchas cosas raras de javascript sino con las animaciones de bootstrap (carrousel de imágenes, filtro de imágenes), para que despues nose haga mucho lío con Angular.
# Inicio la maqueta
# Usamos Font Awesome para agregar los iconitos
# Voy a Bootstrap y de Ahí a Docs y Modal. Elegí la Verically centered.
# Primero copie todo lo que esta en Live Demo. Lo copie despues del <ul>
# Lo que quiero es que en vez de aparecer el botón aparezca con el logito de la persona y que este al ser presionado llame a la ventana modal
# Copio todo el botón y lo pego en <li class="list-group-item"><i class="fa-solid fa-user fa-2xl"></i></li>
# Cómo me queda el botón y el iconito lo que hago es mezclo ambos quedando asi
# Saco un formulario de Bootstrap de Bootstrap Forms form control para ingresar usuario y contraseña y lo pongo en el <modal body>
# css lee de abajo para arriba. Razon por la cual si defino algo abajo de lo mismo ya definido el que escribi despues predomina.
# Tratar de nunca usar en css los colores con los nombres. Usar hexadecimal.
# Ahora quiero el banner. Voy a Bootstrap y busco banner, como no lo encontre use uso un carousel
# Le agrego padding al Sobre Mí para que no quede por debajo de la nav-bar class="pt-5"
# Para seguir hacemos mas secciones
# Tuve un problema con la modal
# Copio la ventana modal de la navbar para las modales del dashboard
# Para que el boton sea mas grane le agregamos a la clase btn-lg y para que tenga aire le agregamos p-5
# Buscamos Gutter para separar los botones 