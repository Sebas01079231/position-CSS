# position-CSS
Guia de Position CSS

La propiedad position nos permite posicionar los elementos. Hay algunos conceptos que para entender position.

    Flujo de renderizado -> Por norma general Los elementos se dibujan de izquierda a derecha y de arriba abajo. El punto 0,0 de los elementos, por norma general, es la esquina superior izquierda.

    Espacio reservado -> Es el espacio que tiene un elemento asignado en el navegador.

    Elemento posicionado -> Esto significa que el elemento tiene la propiedad position con un valor distinto de "static", que es el valor que tiene esta propiedad por defecto.

    Stackin context -> Contexto de apilamiento. Es el orden en el que se apilarán las cajas que se superponen, dentro del mismo contenedor.

AL posicionar un elemento se habilitan 5 propiedades que podemos utilizar para mover Los elementos en los 3 ejes.

    top -> El elemento se moverá desde la parte superior La distancia que le hayamos indicado.

    right -> EL elemento se moverá desde la parte derecha La distancia que Le hayamos indicado.

    bottom -> EL elemento se moverá desde La parte inferior la distancia que le hayamos indicado.

    Left -> EL elemento se moverá desde la parte izquierda La distancia que le hayamos indicado.

    z-index -> Nos permite mover el elemento en el contexto de apilamiento (eje z)

NOTA: Si a un elemento le declaramos La propiedad top y/o Left, Las propiedades bottom y/o right no funcionarán.

Los posibles valores que le podemos dar a position son. 

    Static -> Es el valor que tiene por defecto un elemento, con este valor el elemento NO ESTÁ POSICIONADO y por lo cual no podremos moverlo

    Relative -> EL elemento mantendrá su posición y medidas en el flujo de renderizado y mantendrá su espacio reservado. Si Lo movemos Lo hará usando su posición en el html como punto de referencia.

    Absolute -> El elemento perderá sus medidas y su espacio reservado. Si Lo movemos usará el elemento posicionado contenedor como referencia. Si no tiene ninguno, usará el elemento html de referencia.

    Fixed -> El elemento perderá sus medidas y su espacio reservado. Si Lo movemos usará el elemento html de referencia, y además se quedará fijo en esa posición aunque hagamos scroll.

    Sticky-> Es una mezcla de position relative y fixed. Con este tipo de posicionamiento Los valores top, left, bottom y right no sirven para mover el elemento, si no para indicarle en qué punto pasará a tener un comportamiento de posicionamiento fixed, hasta Llegar a ese punto se comportará como si tuviera relative. 
