## Nombre stack: 
- infra-viva-monitoring

## Buscar Id instance
- Ir a Amazon EC2
- Entrar a: Instances
- Copiar Instance ID
- Ejemplo: i-01cb947fe9ecfbb47

## Crearemos lo siguiente:
| Métrica      | Acción    |
| ------------ | --------- |
| CPU EC2      | monitorea |
| Threshold    | 70%       |
| Periodo      | 5 minutos |
| Evaluaciones | 2         |

Si la CPU supera 70%, la alarma cambia a: ALARM

## Verificar
- Ir a Amazon CloudWatch
- Entrar a: Alarms
- Deberías ver algo como: CPUAlarmHigh
- Estado inicial: OK