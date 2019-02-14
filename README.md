# UyA

Introduccion al HTTP:
Dada las siguientes paginas, conteste a una serie de preguntas.

Pagina 1: http://www.gobiernodecanarias.org/istac/api/
Pagina 2: https://www3.gobiernodecanarias.org/istac/api/operations/v1.0/operations?limit=5

    Qué peticiones desencadena la consulta.
    - En la página 1 realizamos una peticion GET, sin embargo, en la peticion realizada en la pagina 2,
    se trata de una peticion post, dado que se le pasa un parameto ("?limit=5").
    
    ¿Qué tipo de petición estás realizando?
    - En este caso, tanto la pagina 1 como la pagina 2 realizan peticiones GET.

    Qué código de estatus devuelve.
    - La primera vez que se carga la pagina se devuelven estatus del tipo 200.
    Es interesante observar que a medida que refrescamos la pagina comienzan a aparecer status del tipo 3xx,
    como lo son el codigo 302("Found") y el 304("Not Modified") , ya que se esta accediendo a la cache.
    
    Qué DNS tiene el servidor.
    - http://www.gobiernodecanarias.org/
    
    Qué IP tiene tiene el servidor.
    Hecho con Chrome.
    - Pagina 1: Remote Address: 93.188.137.123:80
    - Pagina 2: Remote Address: 93.188.137.126:443
    
    ¿La página tiene alguna cookie?, ¿Cuáles?.
    - Detectamos la presencia de una cookie asociada a la direccion de www.gobiernodecanarias.org en la pagina 1.
    - En la pagina 2 la cookie es https://www3.gobiernodecanarias.org
    
    ¿Qué idioma acepta?.
    - Los idiomas aceptados en la pagina de xml son Español ("xml:lang="es") e Ingles (xml:lang="en").
    
    Alguna línea de código JavaScript
    - No existen líneas de codigo javascript.
    
    Alguna línea de código CSS que se aplique
    Pagina 1:
    - 	font-family: "Droid Sans", sans-serif;
    -   <link href="/istac/resources/css/istac.css" media="screen" rel="stylesheet" type="text/css">
    
    Alguna línea de código HTML que se aplique.
    -   <div class="der">		<img src="/istac/resources/imagenes/logo_edatos.jpg" alt="">	</div>
