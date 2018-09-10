# Software

# ¿Qué es un patrón de diseño?

Solución reutilizable a un problema recurrente.

# Factory Method
Es un patrón de diseño creacional que proporciona una interfaz para crear objetos en superclase, pero permite que las subclases modifiquen el tipo de objetos que se crearán.

Veamos un ejemplo del método factory. El método factory, devuelve un nuevo objeto de cualquier tipo dependiendo de la entrada. El ejemplo trata sobre conducir carros.

[Ejemplo](Factory.py)

# Singleton 
Es un patrón de diseño creacional que le permite garantizar que una clase tenga solo una instancia y proporcione un punto de acceso global a esta instancia.

[Ejemplo](Singleton.py)

# Prototype 
Es un patrón de diseño creacional que le permite producir objetos nuevos copiando los existentes sin comprometer sus partes internas.

En en ejemplo siguiente; Object, es la clase que puede ser clonada. La cual es solo una clase base, por lo que el método clone () no está implementado. Pero todas las subclases tienen que sobrescribirlo.

[Ejemplo](Prototype.py)

# Builder 
Es un patrón de diseño creacional que le permite producir diferentes tipos y representaciones de un objeto utilizando el mismo proceso de construcción. El constructor permite construir objetos complejos paso a paso.

En el ejemplo que sigue vemos una clase Director, la cual tiene un constructor asociado con ella. Director delega la construcción de las partes más pequeñas al constructor y las ensambla juntas.

[Ejemplo](Builder.py)

# Referencias

https://es.slideshare.net/SebastianRamrez2/patrones-diseo-1
https://www.youtube.com/watch?v=cwfuydUHZ7o
https://refactoring.guru/design-patterns
https://es.wikipedia.org/wiki/Patrón_de_diseño
