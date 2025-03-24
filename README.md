# INTRODUCCIÓN
En este proghrama se realizan pruebas unitarias de Java usando librerias JUnit.
Adjunto repositorio para su comprobacion:https://github.com/Elibo93/PRACTICA.git

# ESTRUCTURA DE CARPETAS
- `src` En esta carpeta está el aquete tienda con las clases Producto, Inventario e InventarioTest

- `lib` Aquí están las librerias que nos ayudarán con las pruebas unitarias

- `gitignore` En este documento de texto se encuentra  todos los elementos del proyecto que queremos
que no sean rastreados por git. Se exclute el archivo README.md

# EJECUCION DE PRUEBAS
- `testActualizarStock` En este metodo método comprobamos que al añadir un producto
al inventario,este se actualiza correctamente,para ello usamos assertEquals para comprobar que el producto añadido a la posición X está correctamente agregado.

- `testAñadirProducto` En este método comprobamos que al añadir el primer producto,este se añade correctamente,para ello usamos assertNotNull para asegurarnos de que al añadir el producto la lista ya no está vacia(Ya no es nula)

- `testBuscarProductoPorCodigo` En este método comprobamos que podemos buscar un producto por su código,para ello usamos assertNotNull pafra comprobar que la lista no está vacia(No es nula) y assertEquals para comprobar que tiene eñl nombre correcto e intentamos buscar por un código erroneo y usamos assertNull para comprobar q`testEliminarProducto`ue nos da error ya que el código no debería existir.

- `testEliminarProducto` En este método comprobamos que al eliminar un producto este se elimina correctamente,para ello usamos el assertEquals para comprobar que el producto ya no está en el inventario

- `testListarProductos` En este metodo comprobamos que la lista se miestra correctamente,para ello usamos assertEquals para buscar los productos y comprobar si se listan correctamente.


# SUBIDA DEL PROYECTO 

- `git init` Empezamos inicializando la carpeta donde se ha gardado el proyecto.
- `git remote add origin https://github.com/Elibo93/PRACTICA.git` para vincular el repositorio remoto con el repositorio local
- `git add .` para añadir los archivos modificados
-`git commit -m "comentario"`Para hacer un comentario de los cambios realizados
- `git push -u origin main` Para subirlo al repositorio remoto en la rama principal del proyecto



