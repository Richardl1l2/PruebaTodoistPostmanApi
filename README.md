# Proyecto Todoist Api Postman :nerd_face:

En el siguiente archivo encontrarán toda la información sobre el Proyecto todoist Automation QA Api.

La automatización permite agregar, editar y eliminar tareas

- Precondición
- Estructura

## Precondición

Se debe resgistrar en la plataforma https://app.todoist.com/auth/login e ingresar el apitoken directamente de la cuenta en la opcion desarrolladores 

## Estructura
Estructura de la Colección de Postman
Colección: Gestión de Tareas
- Active Tasks (GET)
Descripción: Obtener todas las tareas activas.
```bash
Endpoint: /tasks/active
Método: GET
Parámetros: Ninguno
```
 - Active Task Unique
Descripción: Obtener una tarea específica.
```bash
Endpoint: /tasks/:id
Método: GET
Parámetros:
id: Identificador único de la tarea.
```
 - Create New Task (POST)
Descripción: Crear una nueva tarea.
```bash
Endpoint: /tasks
Método: POST
```
 - Update a Task (POST)
Descripción: Actualizar una tarea existente.

```bash
Endpoint: /tasks/:id
Método: POST id: 
Identificador único de la tarea.
```

- Delete a Task (DELETE)
Descripción: Eliminar una tarea.
```bash
Endpoint: /tasks/:id
Método: DELETE
Parámetros:
id: Identificador único de la tarea.
```
- Environment: Access
 Descripción: Configuración del entorno con el ID de acceso.   
```bash
Variables:
id: Identificador utilizado en las solicitudes
```
 
