Autores: Juan Pablo Castaño Duque - Mateo Florez Restrepo - Kevin Gutierrez Gómez.
Patrón de diseño: Template method.
Justificación: Cuando se construyen jerarquías de clases complejas para una aplicación, a menudo se duplican distintas partes del código. Esa situación no es deseable, porque la intención es reutilizar todo el código que sea posible.
Lenguaje: PHP.
Descripción del código: El código en las clase usuario y administrador tienen una función llamada "consulta", la cual realiza una consulta SQL con parámetros diferentes pero luego de recibir los parametros realiza exactamente la misma función, por ende, decidimos crear una clase dónde la función esté definida y en el momento que cualquiera de las dos clases (usuario ó administrador" realice la consulta SQL, llame a esta clase con su método para no reescribir código.
Referencias:
https://www.adictosaltrabajo.com/2011/10/04/patron-template-method/
https://informaticapc.com/patrones-de-diseno/template-method.php
