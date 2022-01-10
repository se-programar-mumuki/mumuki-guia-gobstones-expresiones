Supongamos ahora que queremos "copiar" las bolitas verdes, haciendo que haya la misma cantidad de rojas y pensemos cómo podría ser ese procedimiento.

Una tarea que seguro tenemos que hacer es poner muchas bolitas, y para eso ya sabemos que existe el procedimiento `PonerN` que construimos varios ejercicios atrás. El color de las bolitas que tenemos que poner también lo sabemos: Rojo, pero... ¿cómo sabemos cuántas poner?

Miremos algunos ejemplos:

* Si hay 4 bolitas verdes, hay que poner 4 bolitas rojas.
* Si hay 2 bolitas verdes, hay que poner 2 bolitas rojas.
* Si no hay bolitas verdes, no hay que poner ninguna roja.

Lo que nos está faltando es una forma de **contar cuántas bolitas verdes hay**, y para eso necesitamos otra función que nos da Gobstones: `nroBolitas(color)`. Lo que hace es simple: nos retorna la cantidad de bolitas de un color determinado **en la posición actual**.

> Invocando `nroBolitas`, definí el procedimiento `CopiarVerdesEnRojas`.
