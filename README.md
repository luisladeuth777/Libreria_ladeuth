# Libreria_ladeuth
Este repositorio contiene el Manual de Usuario de "ladeuth," una herramienta versátil para gestionar archivos. "ladeuth" ofrece funciones como creación, escritura, copia, movimiento y eliminación de archivos. El manual guía a los usuarios en el uso eficiente de la aplicación y resolución de problemas.

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
