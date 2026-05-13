# ¿Por qué usar ruta relativa? 
Se usa para que el proyecto sea portable y pueda ejecutarse en diferentes computadores sin modificar rutas absolutas.

# ¿cómo separaste modelo y persistencia?
La clase Producto representa únicamente el modelo de datos, mientras que la clase Archivo se encarga de la persistencia, así se separaron segun las responsabilidades de cada uno en el programa.

# ¿cómo manejaste el caso de archivo inexistente?
Se creó el método cargar() el cual retorna una lista vacía si el archivo no existe, evitando que el programa falle en la primera ejecución, además, se creó automáticamente la carpeta
data/ usando otro método llamado createDirectories().
