Clase Tareas:
Define una clase que se encarga de gestionar una lista de tareas almacenadas en un archivo (por ejemplo, "tareas.txt").

Métodos de la clase:

agregar_tarea:
Abre el archivo en modo "añadir" y escribe una nueva tarea al final, informando al usuario que la tarea se ha agregado.
mostrar_tareas:
Abre el archivo en modo lectura, lee todas las tareas y las muestra numeradas. Si el archivo está vacío o no existen tareas, lo indica.
marcar_completada:
Lee todas las tareas del archivo, valida que el número de tarea ingresado sea correcto, elimina la tarea correspondiente (ajustando el número ingresado al índice de la lista) y luego actualiza el archivo escribiendo la lista sin la tarea completada.
Menú interactivo:
Un ciclo que presenta al usuario un menú con opciones para agregar, mostrar, marcar como completada una tarea o salir del programa. Según la opción elegida, se invoca el método correspondiente.
