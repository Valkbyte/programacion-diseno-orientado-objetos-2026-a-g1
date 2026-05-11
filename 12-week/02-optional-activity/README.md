# ¿Por qué usaste Map?

Para almacenar los productos se utilizó Map<String, Producto>, ya que permite realizar búsquedas rápidas usando el código como clave única, por otro lado, se usó también Map<String, Integer> para manejar las cantidades de stock de cada producto.  

# ¿Qué problemas resolvería Set en otro contexto? 
Set sería útil en contextos donde se necesite evitar elementos duplicados automáticamente, por ejemplo, podría utilizarse para almacenar correos electrónicos, contraseñas únicos, etiquetas o usuarios registrados sin repetir información.  
A diferencia de List, Set no permite duplicados, siendo de gran ayuda para mantener datos únicos de manera más eficiente y organizada.  

# ¿Qué errores comunes evitaste al iterar?
Durante el ejercicio se evitaron errores comunes al iterar colecciones, también se evitó acceder a claves inexistentes en el Map sin validación previa.  
La iteración del inventario se realizó usando entrySet() para recorrer correctamente las claves y valores del Map.  

