# ¿Qué validaste con IllegalArgumentException?
En la clase Producto se realizaron validaciones usando IllegalArgumentException:
Se verificó que el código y el nombre no estuvieran vacíos y que el precio fuera mayor que cero.  
# ¿Qué regla manejaste con excepción personalizada? ¿dónde capturaste y por qué?
Se creó una excepción personalizada llamada ProductoDuplicadoException:
Esta excepción representa una regla de negocio específica que no permite productos con el mismo código, lo anterior es utilizado por la clase Inventario cuando se detecta un código repetido.  
En la clase App se utilizaron bloques try/catch para capturar los errores:
Se capturaron tanto IllegalArgumentException como ProductoDuplicadoException, permitiendo mostrar mensajes al usuario sin que el programa se cerrara de forma abrupta.  

