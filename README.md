
# Uala-movies 

Uala-movies es una empresa pujante que nos ha encargado relevar su negocio, que consiste en ofrecer por streaming series, películas y documentales. De éstos se sabe el año de estreno y la duración. Dentro del sistema también están los usuarios, que se suscriben y tienen acceso a todo el contenido.

* Un producto es viejo si pasó más de 2 años de la fecha de estreno.
* También sabemos cuándo un producto es interesante
    * En una serie, tiene que tener 4 ó 5 temporadas
    * En una película, porque ganó al menos un Oscar
    * En un documental, si en el título dice la palabra "unofficial"
* Además hay distintos canales de comunicación para el sistema con los usuarios: por SMS, notificación al celular y por mail, donde cada usuario puede tener activados 1, todos o ninguno, deben poder agregarse o eliminarse medios de comunicación para cada usuario (no es necesario desarrollar las funcionalidades de notificar al cliente, lo importante es el manejo de los medios de comunicación, con poner un comentario especificando la acción a realizar es suficiente para esta prueba de concepto).
* Los usuarios pueden estar tristes, contentos o melancólicos. En la hora de pedir las recomendaciones al sistema difiere según su estado:
    * Si está triste le interesan las películas que duran más de 2hs.
    * Si está contento le viene bien cualquier película.
    * Si está melancólico solo quiere ver las que hayan sido estrenadas hace más de 10 años.

**Se pide los siguientes requerimientos junto con los testeos unitarios correspondientes:**

* Saber si un cliente es un antiguo. Lo es cuando solo mira productos viejos.
* Saber si un cliente mira algo interesante.
* Efectuar cobro por parte de Uala-movies, donde debe realizar el cobro necesario y notificarle al usuario una vez efectivizado. Cada usuario tiene créditos disponibles dentro del sistema. El monto es el mismo para todos, sin embargo puede cambiar en cualquier momento.
* Poder pedirle recomendaciones al sistema.
* Especificar patrones de diseño en caso de haber utilizado y dónde se usaron.
* Diagrama de clases de la solución planteada.


#### Aclaraciones importantes:
* Lo mas importante es el diseño, para eso necesitamos algún diagrama de clases de la solución, si te resulta mas fácil hacerlo en papel y subir la foto no hay problema, mientras se entienda para nosotros es suficiente.
* La solución debe ser con Java puro, **no usar ningún framework (Spring, Spark, Jersey, etc)**.
* Nos interesa ver como pantearías el testing, no es necesario cubrir toda la casuística, con que sea un happy path estamos bien. 
