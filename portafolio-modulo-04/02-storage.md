## Nombre stack: 
- infra-viva-storage

## Usaremos:
- Amazon S3
- Amazon S3 Glacier (a través de lifecycle)

## Crearemos lo siguiente:
| Recurso          | Uso                       |
| ---------------- | ------------------------- |
| Bucket principal | Archivos de la aplicación |
| Bucket backup    | Respaldo                  |
| Lifecycle policy | Mover datos a Glacier     |
