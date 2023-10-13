# Libreria_ladeuth
"ladeuth," una herramienta versátil para gestionar archivos. "ladeuth" ofrece funciones como creación, escritura, copia, movimiento y eliminación de archivos. El manual guía a los usuarios en el uso eficiente de la aplicación y resolución de problemas.

# Como usar 
Para utilizar la libreria FileHandler en otro archivo Java, necesitas importarla y crear una instancia de la clase en tu nuevo archivo. A continuación, te muestro cómo hacerlo paso a
paso:
Asegúrate de que la clase FileHandler esté en el mismo paquete o en un paquete que sea accesible desde el archivo Java en el que deseas utilizarla. Si la clase FileHandler está en el paquete ladeuth, el archivo Java que la utiliza debe estar en el mismo paquete o importarla de manera adecuada.
En el archivo Java donde deseas utilizar la clase FileHandler, comienza por importarla. Si ambas clases están en el mismo paquete, no es necesario importarla. Si están en diferentes paquetes, debes importarla de la siguiente manera:

import ladeuth.FileHandler;

Luego, crea una instancia de la clase FileHandler en tu archivo Java. Por ejemplo:
```
public class MiClase {
 public static void main(String[] args) {
        FileHandler fileHandler = new FileHandler();

        // A partir de aquí, puedes utilizar los métodos de FileHandler.
        // Ejemplo: escribir en un archivo
        fileHandler.writeFile("archivo.txt", "Contenido de ejemplo");
    }
}
```
# Metodos
```
[Escribir un archivo] - [Write a file]
[Crear un archivo] - [Create a file]
[Mover un archivo] - [Move a file]
[Copiar un archivo] - [Copy a file]
[Borrar un archivo] - [Delete a file]
[Leer un archivo] - [Read a file]
```
# Activacion de los Metodos

Escribir un archivo:
Para escribir contenido en un archivo, utiliza la función writeFile. Proporciona la ruta del archivo y el contenido que deseas escribir.
```
FileHandler fileHandler = new FileHandler();
fileHandler.writeFile("ruta_del_archivo.txt", "Contenido del archivo");
```
Crear un archivo:
Para crear un nuevo archivo, utiliza la función createFile. Proporciona la ubicación del archivo que deseas crear.
```
FileHandler fileHandler = new FileHandler();
fileHandler.createFile("nuevo_archivo.txt");
```
Mover un archivo:
Para mover un archivo de una ubicación a otra, utiliza la función moveFile. Proporciona la ruta de origen y la ruta de destino.
```
FileHandler fileHandler = new FileHandler();
fileHandler.moveFile("origen/archivo.txt", "destino/archivo.txt");
```
Copiar un archivo:
Para copiar un archivo a una ubicación diferente, utiliza la función copyFile. Proporciona la ruta de origen y la ruta de destino.
```
FileHandler fileHandler = new FileHandler();
fileHandler.copyFile("origen/archivo.txt", "destino/archivo_copiado.txt");
```
Borrar un archivo:
Para eliminar un archivo, utiliza la función deleteFile. Proporciona la ruta del archivo que deseas eliminar.
```
FileHandler fileHandler = new FileHandler();
fileHandler.deleteFile("archivo_a_borrar.txt");
```
Leer un archivo:
Para leer el contenido de un archivo, utiliza la función readFile. Proporciona la ruta del archivo que deseas leer.
```
FileHandler fileHandler = new FileHandler();
fileHandler.readFile("archivo_a_leer.txt");
```
