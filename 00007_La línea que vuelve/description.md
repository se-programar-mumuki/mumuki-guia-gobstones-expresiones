Ahora que sabés usar la función `opuesto`, podemos finalmente resolver el problema de definir un procedimiento que dibuje una línea **en cualquier dirección** y **deje el cabezal en la posición inicial**.

La versión que sabíamos hacer hasta ahora era esta:

```gobstones
procedure Linea(direccion, color, longitud) {
  repeat(longitud) {
    Poner(color)
    Mover(direccion)
  }
}
```

> Valiéndote de tus nuevos conocimientos sobre expresiones, modificá el procedimiento `Linea` para que el cabezal quede en el lugar donde empezó.

