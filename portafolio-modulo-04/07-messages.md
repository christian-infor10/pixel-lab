## Nombre stack: 
- infra-viva-messaging

## Crearemos lo siguiente:
| Recurso      | Servicio                       |
| ------------ | ------------------------------ |
| Topic        | SNS                            |
| Queue        | SQS                            |
| Policy       | Permite que SNS envíe mensajes |
| Subscription | conecta SNS con SQS            |

## Verificar SNS
- Ir a Amazon SNS
- Entrar a: Topics
- Deberías ver: viva-notifications

## Verificar SQS
- Ir a Amazon SQS
- Entrar a: Queues
- Deberías ver: viva-queue

## Prueba rápida (muy bueno para el informe)

1️. Ir al Topic en SNS
- topic o temas
- das click en el topico ej: viva-notifications
- das click en publicar mensaje
- cuerpo del mensaje: "Pedido creado"
- Le damos a Publicar.
- Luego ir a SQS → viva-queue → Send and receive messages → Poll for messages (esta al final)
- Verás el mensaje al darle click. "Pedido creado"
- Esto demuestra comunicación entre servicios.