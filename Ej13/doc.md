**Pattern:** ErroresVFS

**base on:** Bridge

**becasue:**

Con el objetivo de porder internacionalizar la aplicacion podemos contruir una clase abtracta con todos los errores posibles dentro del sistema. A la cual se le puede componer el traductor de errores dependiendo del idioma

**where:**

Abstraccion **is** ManejadorDeErrores

ImplementadorConcreto **is** MensajesErrores_es

ImplementadorConcreto **is** MensajesErrores_en 

AbstraccionRefinada **is** ManejadorDeErrores

**comments:**

Dado que no tiene sentido separar la abstracción de la refinacion dejamos un solo modulo con un metodo mensajeque dado un codigo de error devuelve el cadena de caracteres
