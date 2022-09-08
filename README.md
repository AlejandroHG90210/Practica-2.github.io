<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

<!-- Begin Jekyll SEO tag v2.8.0 -->
<title>Practica #2 Lab. Programacion Web</title>
<meta name="generator" content="Jekyll v3.9.2" />
<meta property="og:title" content="Practica-2.github.io" />
<meta property="og:locale" content="en_US" />
<link rel="canonical" href="https://alejandrohg90210.github.io/Practica-2.github.io/" />
<meta property="og:url" content="https://alejandrohg90210.github.io/Practica-2.github.io/" />
<meta property="og:site_name" content="Practica-2.github.io" />
<meta property="og:type" content="website" />
<meta name="twitter:card" content="summary" />
<meta property="twitter:title" content="Practica-2.github.io" />
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"WebSite","headline":"Practica-2.github.io","name":"Practica-2.github.io","url":"https://alejandrohg90210.github.io/Practica-2.github.io/"}</script>
<!-- End Jekyll SEO tag -->

    <link rel="stylesheet" href="/Practica-2.github.io/assets/css/style.css?v=763d87259cb074a7b4445fe35e2508989441a7b7">
    <!-- start custom head snippets, customize with your own _includes/head-custom.html file -->

<!-- Setup Google Analytics -->



<!-- You can set your favicon here -->
<!-- link rel="shortcut icon" type="image/x-icon" href="/Practica-2.github.io/favicon.ico" -->

<!-- end custom head snippets -->

  </head>
  <body>
    <div class="container-lg px-3 my-5 markdown-body">
      
      <h1><a href="https://alejandrohg90210.github.io/Practica-2.github.io/">Practica 2</a></h1>
<html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <title> Practica #2 Lab. Programacion Web </title>
  </head>
  <body>
    <nav class="navbar-expand-lg bg-light">
        <div class="container-fluid">
            <center> <b><h1>Laboratorio de Programacion Web</h1></b></center>
          </div>
        <div class="right">
          <div align="right">
            <a href="https://alejandrohg90210.github.io/index.github.io/">
            <input type="button" value="Click INDEX"/>
          </a>
        <h2><p align=left>Practica #2</p></h2> 
          </div>
</div>
    </nav> 
<H3>LECCION 1 DEFINICION DE HTML5:</H3>
<center><img src="iniciohtml.png" width="210" height="130"></center>  
  <b><p>Definicion de HTML5:</p></b>
  <p>HTML5 es una combinación de nuevas etiquetas de markup  HTML, propiedades CSS3, JavaScript que son independientes de HTML5. Podemos definir HTML5 como  los nuevos elementos de markup o sintaxis utilizados por los diseñadores para crear páginas web. La familia HTML5 incluye las nuevas etiquetas y tecnologías como CSS3, Geolocalización, Almacenamiento Web, Web Workers y Web Sockets. HTML5 aporta nuevas funcionalidades y herramientas con el fin de conseguir que los sitios web sean más interesantes, atractivos y útiles.</p>
  <b> <p>Historia de HTML5:</p></b>
  <p>HTML4, que se dio por cerrado en 1998, es el lenguaje de markup que conforma la base de la gran mayoría de las páginas web que podemos ver a día de hoy.
    Tras la finalización de HTML 4.0.1, el W3C continuó sus trabajos en consonancia con la evolución de la web, y comenzó con un lenguaje llamado XHTML. Uno de los objetivos de XHTML 1.0 era crear un lenguaje de markup que pudiera extenderse y resolver las necesidades de las tecnologías futuras, por ejemplo para los dispositivos móviles.
    En 2004, un grupo de representantes de los principales fabricantes de navegadores formaron un grupo  llamado WHATWG (Web Hypertext Application Technology Working Group). Su misión consistía en crear una especificación de lenguaje HTML mejor, orientada a crear un nuevo tipo de aplicaciones web pero manteniendo la compatibilidad con los navegadores existentes.
    Durante  dos años y medio el W3C y el grupo WHATWG trabajaron de manera independiente hasta que en 2006, Tim Berners-Lee, creador de la World Wide Web y fundador del W3C anunció que el W3C y WHATWG trabajarían juntos en la elaboración del estándar.
    Como resultado de todo ello, se abandonó el desarrollo de XHTML 2.0 y la especificación HTML 4.0 se reformó con el nombre HTML5.
    </p>
  <b> <p>HTML5 extiende la definicion de lo que puede hacer una pagina web:</p></b>
  <p>A día de hoy HTML no tiene capacidad para reproducir contenidos multimedia, como audio o vídeo, sin un complemento como los de adobe, flash o Microsoft. HTML tampoco tiene capacidad para almacenar datos en el ordenador del usuario, esto se hace actualmente mediante un lenguaje de scripting. Cada vez más gente depende de la web y utiliza aplicaciones web y esta demanda de los usuarios en favor de un mayor rendimiento y unos sitios web con prestaciones más avanzadas y completas se ve limitada por el lenguaje HTML que se utiliza actualmente.</p>
  <b> <p>El lenguaje HTML5:</p></b>
  <p>El lenguaje  HTML5 incorpora algunas etiquetas nuevas pensadas para hacer que la estructura de la página web sea más lógica y funcional. Antes de HTML5, la estructura de una página dependía  de las etiquetas &lt;div &gt; que son  asociadas a una clase CSS o un ID. Por ejemplo, en HTML 4.0 es una práctica comúnmente aceptada definir la cabecera de una página web de esta forma: 
    &lt;div id="header" &gt;  Esta es la cabecera &lt;/div&gt;
   Para definir la anchura y altura de la cabecera así como su color de fondo. En el código CSS podríamos tener algo así:
   #header {     
        width:960px;
        height:100px;
        background-color:gray;
      }
   El ID utilizado header es arbitrario. En la especificación HTML5 existe ya una etiqueta llamada &lt;header&gt; que viene a sustituir al elemento &lt;div&gt;  de forma que la sintaxis es mucho más lógica y coherente:
   &lt;header&gt; Esta es la cabecera &lt;/header&gt;
   Ahora ya podemos añadir directamente las propiedades de estilo
   
   
   
   header {
        width:960px;
        height:100px;
        background-color:gray;
   }
   
   La diferencia es que en el primer caso se utiliza un selector “#”que refiere a un atributo ID de CSS. En el segundo caso utilizamos un selector que es una novedad de HTML5 y nos permite aplicar un estilo al elemento directamente.
   El objetivo de los nuevos elementos HTML5 no es otro que evitar una excesiva dependencia de las etiquetas &lt;div&gt; y sustituirlas por una estructura de página más consistente y legible. Nosotros podemos seguir utilizando la etiqueta &lt;div&gt;, pero esta etiqueta ya no  tiene que ser la viga que soporte el diseño visual de toda una página web.
   </p>
  <b> <p>Breve recorrido por los principales elementos de HTML5:</p></b>
  <ul>
    <li><b>Elementos &lt;video&gt;, &lt;audio&gt; y &lt;canvas&gt;</b></li>
    <p><p>HTML5 incluye etiquetas que nos permiten integrar contenidos multimedia sin necesidad de complementos del navegador. Las etiquetas &lt;video&gt; y &lt;audio&gt; sirven para integrar video y audio en las páginas web de la misma forma que actualmente se hace con los archivos de imagen utilizando la etiqueta &lt;img&gt;. La etiqueta &lt;canvas&gt; dota al lenguaje HTML de un formato nativo para el dibujo y la animación.</p></p>
    <li><b>Elementos &lt;video&gt; y &lt;audio&gt; para incorporar contenidos multimedia</b></li>
    <p>La estructura necesaria para incorporar contenidos de audio o vídeo es la siguiente:
        &lt;video src="catz.mp4" width="400" height="300"&gt;&lt;/video&gt;
        Para insertar un archivo de audio mp3 en la página se hace de la siguiente manera
        &lt;audio src="high_seas_rip.mp3" controls preload="auto" autobuffer>&lt;/audio&gt;.
        </p>
    <li><b>El elemento &lt;canvas&gt; para dibujo y animación</b></li>
    <p>El elemento canvas funciona a modo de superficie de dibujo dentro de una página web. Dentro de esta superficie de dibujo podemos crear formas con colores, gradientes y patrones de relleno. Podemos manipular los pixeles de forma interactiva en pantalla, mostrar textos y exportar los contenidos hacia archivos de imagen estática. Para hacer uso de esto usamos:
        &lt;canvas id="myCanvas"&gt;&lt;/canvas&gt;
        Después javaScript se encarga de todo el trabajo y nos ofrece un contexto para el objeto creado.
        </p>
  </ul>
  <b> <p>Formularios web:</p></b>
  <p>Los nuevos elementos de formulario de HTML, cuando se implementen, harán que el trabajo con formularios sea más sencillo que ahora. Por ejemplo, muchos diseñadores web necesitan crear formularios en donde los datos tienen que comprobarse antes de enviarlos al servidor. Es casi obligado que el usuario, por ejemplo, tenga que escribir una dirección de correo electrónico en un campo de un formulario. A día de hoy, para validar este dato se necesita programación en  Javascript o cualquier otro lenguaje de scripting, pero HTML5 incorpora el atributo required a la lista de tipos de datos de entrada utilizables en formularios, como se muestra en este ejemplo:</p>
    <p>&lt;input type="email" required&gt;</p>
    <p>Se han definido unos cuantos tipos de datos nuevos para los formularios, como es el caso de email para las direcciones de correo,  search para designar los campos de formulario que deben recibir términos de búsqueda, url para los campos de direcciones web y algunos más.</p>
  <b> <p>Muchos elementos nuevos en HTML5:</p></b>
  <p>Aparte de los nuevos elementos &lt;video&gt;, &lt;audio&gt;, &lt;canvas&gt;, y tipos de datos de formulario, hay otros nuevos elementos dentro de HTML5 que podemos utilizar, como &lt;figure&gt; y &lt;figurecaption&gt;, que se emplean para etiquetar imágenes dentro de la página web, el elemento &lt;hgroup&gt; para agrupar una serie de elementos de cabecera dentro de una sección lógica, etc. HTML5 además resuelve el caso de ciertas etiquetas que aparecen en HTML 4.01 pero que han quedado obsoletas o necesitaban ciertas precisiones, como ocurre con &lt;i&gt;, &lt;b&gt;, &lt;small&gt;, &lt;strong&gt; y &lt;abbr&gt;, que ahora tienen significados y usos nuevos con HTML5.</p>
  <b><p>Introduccion a las APIs de HTML5 y las tecnologías de apoyo:</p></b>
  <ul>
  <li><p><b>¿Qué es una API?</b></p></li>
  <p>Las APIs (Application Programming Interfaces o, en español, Interfaces de Programación de Aplicaciones o simplemente "interfaces de programación") son una forma de crear aplicaciones utilizando componentes preconfigurados cuyo uso no se restringe a la web, ni siquiera a los lenguajes de scripting. Sitios web como Twitter o YouTube entre otros, ofrecen APIs al público de manera que los diseñadores y desarrolladores pueden con ellas integrar algunas de sus funcionalidades dentro de sus propios sitios web. Uno de los objetivos principales de una API es el de normalizar el modo de trabajo de ciertos mecanismos y simplificar tareas de programación, que de lo contrario, serían bastante complejas. Las APIs son un aspecto muy importante dentro del entorno de HTML5 y hay una serie de ellas que conviene conocer, como Web Storage, Microdata o Geolocation, entre otras.
    Para utilizarlas, lo primero que tenemos que saber es que la documentación oficial de estas APIs es independiente de la documentación oficial de HTML5.</p>
  <li><b> <p>La API de Geolocalizacion en accion:</p></b></li>
  <p>Geolocation es una API que nos permite conocer el punto geográfico desde el cual se conecta el navegador a Internet. Esta información se emplea para enviar al usuario datos de interés para él, ajustados a su ubicación. Como ejemplo de su utilidad están las páginas web de búsqueda asociadas a un mapa en el cual nos indican dónde están situados ciertos comercios o restaurantes a una distancia concreta a pie desde el punto donde estamos en ese momento. En vez de tener que introducir a mano la dirección, un navegador habilitado para geolocalización nos puede devolver estos resultados de manera automática y transparente.</p>
  </ul>
  <b> <p>Web Workers:</p></b>
  <p>Web Workers es otra API que se suele considerar de la familia HTML5. Web Workers es un marco de programación que resuelve problemas de rendimiento de los navegadores. Al acceder a aplicaciones web avanzadas, como las de mapas o aquellas que generan gráficos o diagramas al entrar en la página web, se inician ciertas operaciones de computación que consumen una gran cantidad de recursos de procesador y que pueden reducir notablemente el rendimiento de la aplicación. Gran parte de la ralentización es debida a que se produce un conflicto a nivel de máquina entre las tareas interactivas de usuario y la necesidad de la propia aplicación de acceder a recursos como datos, tarjeta gráfica u otros.
    Los Web Workers son scripts que se ejecutan en threads independientes. Esto quiere decir que ciertos procesos como puede ser obtener datos desde una base de datos, se ejecutan de forma independiente de las actividades que desarrolle el usuario, lo que da como resultado un entorno mucho más fluido para éste.</p>
  <b> <p>Almacenamiento web:</p></b>
  <p>El Almacenamiento Web (Web Storage) es un ejemplo de uso de modelos preexistentes de tecnologías web bajo nuevas modalidades, más potentes. El Web Storage mejora el concepto de cookies del navegador. Actualmente las cookies permiten que los sitios web puedan guardar información en cantidades muy reducidas en los equipos de los usuarios, datos que normalmente sirven para volver a utilizarlos en momentos posteriores, y de esta manera, por ejemplo, ciertos sitios web recuerdan la información del usuario desde el último acceso.
    Las cookies son una tecnología bastante limitada y no resulta fácil su utilización por parte de los diseñadores web. Ahora, Web Storage actualiza este modelo para que las aplicaciones web puedan almacenar una cantidad de datos muy superior y que su acceso y utilización sea mucho más fácil y eficiente.
    HTML5 nos ofrece dos maneras de guardar datos: localStorage y sessionStorage. Los datos guardados con localStorage quedan a disposición del navegador en todo momento, aunque cerremos el programa o se reinicie el sistema. Los datos guardados bajo la modalidad  sessionStorage se pierden al cerrar el navegador.
    </p>
  <b> <p>CSS3 no forma parte de HTML5:</p></b>
  <p>Muchos de los aspectos novedosos designados bajo el nombre "HTML5" son en realidad una combinación de las tecnologías HTML5 descritas antes junto con JavaScript o CSS. CSS (iniciales de Cascading Style Sheets) es un lenguaje en evolución que se identifica mediante números de versión, y la última de ellas es la CSS 3.0, que ha ido evolucionando en paralelo con la especificación de HTML5. Algunos componentes de CSS3 suelen considerarse erróneamente como componentes de HTML5, como es el caso de las transiciones o la animación. </p>
  <b> <p>Transformaciones CSS 2D y 3D:</p></b>
  <p>La propiedad transform de CSS nos permite rotar, cambiar la escala o sesgar un elemento de una página web. Un ejemplo puede ser el girar levemente una foto dentro de una página para conseguir un efecto estéticamente muy atractivo. También podemos dar animación a las transformaciones: por ejemplo, mediante animación aplicada a la propiedad "scale" podemos conseguir un efecto de ampliación o reducción del tamaño de una imagen o de cualquier otro elemento. Podemos también añadir la propiedad "perspective" al efecto de transformación para simular la visión de un objeto en un espacio tridimensional, estático o en movimiento.</p>
  <b> <p>Fondos, bordes, colores RGBa, gradientes, sombras y esquinas redondeadas:</p></b>
  <p>Con CSS3 es posible aplicar mejoras muy interesantes a la presencia visual de una página. Un ejemplo sencillo es la propiedad "border-radius", con la que podemos poner esquinas redondeadas a los objetos rectangulares, y también podemos crear muchos efectos nuevos, como gradientes de color o sombreados. Algunos efectos tradicionales, como background-image y la propiedad border han sido mejorados en CSS3. Por ejemplo, podemos utilizar la propiedad border-image para utilizar imágenes como bordes de objetos, o añadir varias imágenes de fondo a un mismo contenedor, evitando así la limitación actual a una sola imagen que permite la propiedad background-image. La descripción del espacio de color RGBa es otra novedad de CSS3, ya que la "a" representa el grado de transparencia. Con la notación RGBa de color ahora podemos aplicar efectos de transparencia a cualquier objeto de la página.</p>
  <b> <p>Fuentes de letra Web @font-face:</p></b>
  <p>Cada vez está más extendido el soporte para añadir tipos de letra especiales a las páginas web mediante la propiedad @font-face, que permite especificar una fuente concreta y un enlace desde el cual el navegador pueda descargarla. Esta característica puede cambiar de forma radical el aspecto de las páginas web, pero lamentablemente también se ve afectada por los muchos problemas de compatibilidad con navegadores antiguos que se pueden ver en otras funcionalidades de HTML5.</p>
  <b> <p>Media Queries de CSS:</p></b>
  <p>La interacción del usuario con Internet se basa casi de forma exclusiva en lo que se puede ver dentro de una pantalla, y el tamaño de las pantallas que podemos encontrar varía enormemente. Un monitor de ordenador de gran formato puede llegar a resoluciones de 2.000 pixels de anchura, mientras que un pequeño teléfono móvil apenas nos ofrecerá 320 pixels. El reto que supone presentar una experiencia equivalente en ambas pantallas puede resolverse mediante las nuevas directivas de CSS de consulta de tipo de medios ("media queries"). En esencia se trata de lanzar una consulta al navegador para determinar el tipo de pantalla en el cual se va a restituir la página y, a partir de esta información, enviar un estilo específico, optimizado para esas dimensiones.</p>
  <b> <p>Animaciones con CSS:</p></b>
  <p>Ciertas tecnologías como Flash o Silverlight se han venido utilizando hasta ahora para animar objetos dentro de las páginas web. Ahora ya podemos conseguir algunos de estos efectos utilizando las reglas y propiedades de CSS3. En el futuro, el elemento Canvas de HTML5 y las transiciones de CSS3 permitirán crear elementos animados e interactivos sobre la página. Las animaciones de CSS, y el tema siguiente, las transiciones, probablemente estarán soportadas por la mayoría de los navegadores en los próximos años.</p>
  <b> <p>Transiciones de CSS:</p></b>
  <p>Las transiciones de CSS están muy relacionadas con el concepto de animación, pero son algo completamente distinto. Una transición permite variar el valor de una propiedad CSS de manera continua a lo largo de un intervalo de tiempo definido.
    Actualmente podemos conseguir este tipo de transiciones utilizando JavaScript y Flash, pero igual que sucede con otros muchos elementos de CSS3, las transiciones ofrecen a los diseñadores web una alternativa para conseguir los mismos resultados sin necesidad de convertirse en programadores expertos.
  </p>
  <b> <p>HTML5 esta en un momento de transicion:</p></b>
  <p>Las tecnologías que hay detrás de HTML5 están en fase de transición, por lo que es necesario tener claro cuándo debemos utilizarlas y cuándo no.
    Todos los navegadores de mayor difusión hoy en día (Microsoft Internet Explorer, Mozilla Firefox, Apple Safari, Google Chrome y Opera) ofrecen soporte, en grado variable, para las funcionalidades de HTML5 en cuanto a su sintaxis y tecnologías relacionadas. En algunos casos una página que ofrece alguna funcionalidad nueva o un aspecto especial en un navegador puede que no se consiga ver en absoluto en otro, o que algunas características no estén presentes aunque la página siga siendo funcional. Estos escenarios sin duda van a cambiar en el futuro, pero el mundo de los navegadores web en equipos de sobremesa evoluciona muy lentamente, por lo que seguiremos observando en el futuro próximo este tipo de situaciones y diferencias.
  </p>
  <b> <p>Perspectivas de soporte por parte de los navegadores:</p></b>
  <p>No se puede prever con exactitud una fecha en la que tengamos cierta seguridad de que habrá soporte completo para HTML5 en todos los navegadores, pero el W3C ha marcado la segunda mitad de 2014 como la fecha en que debe estar finalizada la especificación de HTML5. Los diseñadores web más conservadores pueden optar por esperar hasta entonces para incorporar el HTML5 a sus entornos en producción, pero el estándar es independiente del soporte de los navegadores. La mayoría de los navegadores actuales soportan ya una serie de funcionalidades de HTML5. Algunas de ellas ya se muestran relativamente estables, bien desarrolladas y su uso parece fiable y seguro. Otras, sin embargo, siguen aún en fase de desarrollo y los diseñadores pueden utilizarlas con fines experimentales, o incluso en sitios en producción, pero sabiendo de antemano que están apostando por la innovación a costa de la fiabilidad.</p>
  <b> <p>¿Quien utiliza HTML5 a dia de hoy?:</p></b>
  <p>Existen numerosas demos de HTML5 que no se podrían poner en entornos en producción debido al distinto grado de soporte que ofrecen los navegadores. Si decides incorporar funciones de estilo de CSS3, hay muchos sitios web personales y de empresas que utilizan los elementos más vistosos, como border-radius o las funciones de transformación. En estos casos, los diseñadores pueden utilizar las funcionalidades y añadir alternativas adicionales para asegurarse de que la restitución de estas páginas en navegadores no compatibles no es demasiado diferente de cómo se ven en los navegadores más modernos.
    Un área donde el uso de las funcionalidades de HTML5 está siendo muy activo es entre los dispositivos móviles y smartphones. En este mundo podemos encontrar aplicaciones web que aprovechan las ventajas de los nuevos tags de Video o Audio, puesto que ciertos dispositivos como Windows Phone o iPhone soportan HTML5 pero no soportan complementos como Flash o Silverlight.
    </p>
  <b> <p>Funcionalidades y caracteristicas futuras de HTML5:</p></b>
  <p>Las funcionalidades de HTML5 se presentan en distintos grados de madurez y aquí solo hemos visto unas pocas. La lista siguiente es una enumeración de otras funcionalidades que forman parte de la especificación HTML5 o de sus tecnologías adscritas que deben añadirse a los navegadores del futuro.</p>
  <ul>
    <li><b>Drag and Drop</b></li>
    <p>Las operaciones Drag-and-Drop ("arrastrar y soltar") permiten al usuario mover en pantalla los elementos de forma visual en lugar de hacerlo pulsando botones. La API Drag and Drop de HTML5 se basa en la implementación original de Internet Explorer. Han cambiado algunos detalles y ciertos navegadores ofrecen una sintaxis diferente, pero ya está a punto de cerrarse una API normalizada. En el momento de escribir este libro, no todos los navegadores ofrecen soporte para algunas de las funcionalidades de drag-and-drop.</p>
    <li><b>La API File (Archivo)</b></li>
    <p>La API llamada "File" (Archivo) permite a los desarrolladores acceder a archivos del disco duro de la máquina cliente sin necesidad de instalar extensiones o complementos. Con esta API, al fin podremos disponer de un modelo unificado de acceso mediante el cual las aplicaciones web podrán operar con archivos. Una aplicación de edición de fotos basada en web, por ejemplo, podría ofrecer el mismo modo de operación en todos los navegadores compatibles utilizando esta API.</p>
    <li><b>Disposición de objetos en pantalla con Flexbox</b></li>
    <p>CSS3 introduce una nueva forma de crear diseños para la distribución de los objetos en pantalla, llamado Flexible Box Layout ("Flexbox"). En este sistema se pueden crear disposiciones fluidas sin necesidad de acudir a las habituales directivas "float" y "clear" de CSS. Su objetivo es ofrecer herramientas más fiables y potentes a los diseñadores y desarrolladores para crear estructuras visuales complejas, válidas para la web y para dispositivos móviles.</p>
    <li><b>Distribuciones en rejilla y columnas múltiples</b></li>
    <p>También dentro de CSS, las definiciones de distribuciones en pantalla en formato de columnas múltiples y rejillas ("grids") son dos mejoras más orientadas a facilitar la presentación visual de las páginas web. La propiedad Multi-column de CSS nos permite distribuir un contenido en dos o más columnas, facilitando así su lectura sin tener que recurrir a complicados juegos visuales. El sistema de rejilla o Grid se relaciona de alguna forma con los Flexbox en el sentido de que esta funcionalidad está pensada para crear disposiciones en pantalla más complejas, tanto para las páginas web como para las aplicaciones. En el sistema Grid se introduce el concepto de filas y columnas y también el procedimiento para apilar y alinear objetos dentro de estas rejillas.</p>
  </ul>
  <b> <p>Identificacion de sitios web basados en HTML5:</p></b>
  <p>En enero de 2010 el W3C presentó el logo de HTML5 para uso público, con el cual quieren promocionar las nuevas capacidades de HTML5 y sus tecnologías asociadas</p>
  <center><img src="html5.png" width="100" height="130"></center>
  <p> Este logo puede obtenerse como archive gráfico y se puede incorporar a los sitios web o cualquier otro contenido para indicar que se utiliza esta tecnología. Conviene saber que el W3C utiliza el término HTML5 en un sentido amplio e incluye otras tecnologías también. Además, el HTML5 se convertirá en el año 2014 en un estándar oficial, pero se recomienda a los diseñadores y desarrolladores que empiecen ya a utilizar la especificación.</p>
        <br>
        <br>
        <h4> Conclusiones </h4>
        <br>
        <b><p>Diego Alberto Oliva Gonzalez </p></b>
        <p>En este capítulo aprendí mucho acerca de que es un html5 su estructura y funciones que tiene además de elementos extras que usa el html5 para que funcione de la mejor manera posible, ya que esto me ayuda a ampliar mi conocimiento en este tipo de temas y no batallar a la hora de hacer las practicas.</p>
        <b><p>Edrik Alejandro Hernandez Garcia </p></b>
        <p>En esta práctica a través de la lectura del tema visto que trata sobre el HTML5 aprendimos sobre ella y su historia en cómo se ha ido avanzando este lenguaje con cada una de sus versiones y como fue mejorando y orientándose a la compatibilidad de los navegadores web que existían antes para así que pudiera funcionar en cualquier lugar este lenguaje y así podemos ver cómo es que w3c inicio con su desarrollo para tomar liderazgo en ella, pudimos ver cuáles eran sus principales elementos ya sean con las etiquetas y viendo cuales es su función en cada uno de los casos ya sean para modificar el texto y con estas darles un poco de estructura a nuestra página web.
            En toda esta lectura encuentras información que es de gran ayuda para aprender sobre la web porque se explica de manera sencilla lo que nos trata a dar entender.
            </p>
        <b><p>Carlos Alberto Salazar Beltran </p></b>
        <p>Como conclusión sobre el resumen de HTML es el lenguaje que se utiliza para crear las páginas web a las que se accede mediante internet. Ya que HTML es el lenguaje con el que se escriben la mayoría de páginas web.
            Los diseñadores utilizan el lenguaje HTML para crear páginas web, los programas que se emplean generan páginas escritas en HTML y los navegadores que utilizamos  Google Chrome se muestran las páginas web después de leer e interpretar su contenido HTML. Sabemos que HTML es un lenguaje que utilizan los ordenadores y los programas de diseño de páginas web.</p>
        <b><p>Jesus Ruben Balleza Rojas </p></b>
        <p>En conclusión, esta lección es una introducción hacia HTML5, ya que nos muestra algunos de sus aspectos que son básicos para poder utilizarlo, como lo son los elementos para poder poner video, imágenes, usar el div. En lo personal lo que más me llamo la atención fue como se desarrolló HTML, ya que el que antes de este, se usaba el XHTML 1.0 y que para desarrollar el HTML5 se unieron dos grandes grupos de desarrolladores para poder crear un mejor HTML como lo son los grupos W3C y WHATWG.</p>
        <b><p>Diana Nahomi Santos Ortega  </p></b>
        <p>En esta práctica los temas de esta lección me parecieron muy interesantes ya que la información es muy importante y es muy servible ya que tiene la finalidad de dejar en claro cada uno de estos conceptos como también de una manera muy entendible, también es muy útil y es muy completa para si en algún momento se llega a presentar algo relacionado al tema, poder participar sin el temor de no conocer absolutamente nada.
            Así mismo con estos conceptos aclaré con más entendimiento cada duda que tenía y poder tener más clara la información.
            En esta segunda práctica pude poner en práctica los conocimientos del lenguaje HTML, CSS, etc. como también el agregar las definiciones de los diferentes conceptos que nos pide la práctica, nos ayuda a refrescar nuestros conocimientos y conocer cada vez más este tipo de temas.
            </p>
        <br>
        <br>
        <h4>Elaborado por:</h4>
        <table class="default">
          <div class="container-fluid">
              <tr>
                <b>
                <th><h5>Nombre:</h5></th>
                <th><h5><center>Hora</center></h5></th>
              </b>
              </tr>
              <tr> 
                <td>Edrik Alejandro Hernandez Garcia</td>
                <td><center>M5</center></td>
              </tr>
              <tr>
                <td>Diego Alberto Oliva Gonzalez</td>
                <td><center>M5</center></td> 
              </tr>
              <tr>
                  <td>Diana Nahomi Santos Ortega</td>
                  <td><center>M5</center></td>
              </tr>
              <tr>
                <td>Carlos Alberto Salazar Beltran</td>
                <td><center>M5</center></td>
              </tr>
              <tr>
                <td>Jesús Rubén Balleza Rojas</td>
                <td><center>M5</center></td>
              </tr>
          </div>
            </table>
        <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.14.7/dist/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.3.1/dist/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
  </body>
</html>
