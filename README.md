# Potafolio

# Maquetacion

# PSEUDOCLASES 

myClass:hover 

:nth-chilh: esta nos permite seleccionar elementos hijos de nuestro del selector que estemos utilizando


# PSEUDOELEMENTOS
 --> se ponen con cuatro puntos (::)

p::firt-letter 

----------------------------------------


En CSS podemos hacer variables

:root {

    todo lo que vaya acá adentro será accesible a todo nuestro código;
    Lo normal es poner los 2, 3 colores que usará nuestra web, las fuentes: lo normal es que en vez de poner el color en cada lugar pongamos el nombre que le asignamos desde este lugar al color. Ejemplo: --myVarColor: #f5f031 --> color: var(myVarColor;) --> es muy util que si cambiamos desde el root el color principal esto nos deja poder cambiar el color entero de la pagina para probar nuevas cosas de forma mas rapida.
} 


Hay funciones cerradas en CSS y se utilizan sin modificarse. Hay funciones 



min-widht: min (80%, 100px) --> si el 80% es mas pequeño que 100px aplica el 80



------------------------------------

# MANTRA
Limpiadores * {
    margin: 0;
    padding: 0;
    box-sizing: border-box; 
}


.navbar__link:hover{

    border-bottom: 1px solid var(--myVarColor) --> asi se le aplicaria cuando pasamos el cursor por el link del las secciones del menú.
}

--------------------------------------


# PROPIEDAD POSITION CSS: hay 4

# static: 
nos permie modificar la posición de los elementos mediante las propiedades top, bottom, left & right

# relative: 
nos permite modficar la posición del elemento de manera relativa a la posición actual.


# absolute: 
situa el elemento en el punto 0,0 del eje de coordenadas y en una "capa" propia. (Lo importante de esto es que el padre tenga position relative y entonces los hijos pueden tener el absolute)

-----------------------------------------


# TRANSITION

# transition-property
Especifica que propiedad sera transicionada

transition-property: widht (si quisiese que transicione solo cuando cambio el widht)

transition-property: all (cualquiera que se modifique ya transiciona)


# transition-timing-function

transition-timing-function: easeInSine;
transition-timing-function: easeOutSine;
transition-timing-function: easeInOutSine;
transition-timing-function: easeInCubic;
transition-timing-function: easeoutCubic;
transition-timing-function: easeInOutCubic;


transition-delay
transition-duration

-------------------------------------------
# SHORT HAND PROPERTY POSITION 

transition: width 0.2s 0.1s ease-in;



-------------------------------------------

# ANIMACIONES

Se ejecutan cuando las propiedades de animacion se modifican. Es decir cuando las propiedades se modifican es que la animacion sucede. 

# keyframes
Para especificar como van a suceder las cosas exactamente 





# animation-name
Define una lista de animaciones para aplicar al elemento

# animation-duration 
establece la duración de una animación

# animation-timing-function
Define la función de easing que se usará para determinar la velocidad de los cambios entre dos fotogramas

# animation-iteration-count 
establece las veces que un ciclo de animación será reproducido

Con las animaciones es mejor no usar short hand para ser mas especifico. 

