# ENLACES
Permiten navegar de una página a otra en el mismo sitio u otro.

## ATRIBUTOS ENLACES

1. href: Obligatorio, establece el url o la ruta del elemento a redirigir. (ejm. todas las webs)
2. rel="nofollow" : Atributo para que no se agarren de tu  página (ejm. promocional.html)
3. target=_"blank": redirige a otra ventana (ejm. juegos_blizzard.html)
4. download: descarga automáticamente el recurso del enlace (ejm. promocional.html) 

## TIPOS DE ENLACES SEGÚN SU RUTA

1. Rutas absolutas : Es una ruta completa, cuenta con protocolo HTTP o HTTPS    (ejm. juegos_blizzard.html)
2. Rutas Relativas :
    2.1 Ruta relativa al origen (carpeta): se utliza para acceder a recursos locales    (ejm. index.html, razas, contacto.html)
    2.2 ruta relativa a la raiz del servidor: accede recursos en un ambiente servidor   (ejm. juegos_blizzard.html, nosotros.html, promocional.html, index.html)

# LISTAS

1. Ordenada(ol): conjunto de elementos ordenados, números por defecto(ejm. juegos_blizzard.html, contacto.html)
2. Desordenada(ul): conjunto de elementos desordenados, uso de viñetas (ejm. index.html)

# MENU DE NAVEGACIÓN

Estructura que nos permite navegar en nuestra web de una página a otra, se crea usando la etiqueta NAV, lista no ordenadas y enlaces (ejm index.html)

# EMMET

1.  table>(tr>td*2)*4    ............  Usado en razas.html
2.  ol>li*3     .....................  Usado en contacto.html
3.  nav>ul>(li>a>)*6     ............  Usado en index.html