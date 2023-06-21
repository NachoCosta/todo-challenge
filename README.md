# Invera ToDo-List Challenge (Python/Django Jr-SSr)



## Pasos para levantar el proyecto:

1. Ejecutar docker-compose build
2. Ejecutar docker-compose up
3. manage.py migrate
4. manage.py createsuperuser
5. manage.py loaddata tasks/fixtures/types.json
6. manage.py loaddata tasks/fixtures/projects.json

## Cosas que quedaron fuera del alcance:
1. La posibilidad de que el admin asigne tarea por usuarios.
2. El listado de tareas no se filtra por usuario.

## Aclaraciones:
1. Para incorporar validaciones, no se permite marcar como completada una tarea de otro usuario.
