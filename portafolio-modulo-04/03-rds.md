## Nombre stack: 
- infra-viva-rds

## Usaremos:
- Amazon RDS con motor MySQL

## Reemplazar
- vpc-xxxxxxxx
- subnet-xxxxxxxx
- subnet-xxxxxxxx

Para encontrarlos:
1. Ve a Amazon VPC
2. Entra a Your VPCs
3. Copia el VPC ID
Luego:
4. Ve a Subnets y Copia los IDs de las 2 privadas:
- PrivateSubnetA
- PrivateSubnetB

## DB
- DBUsername: admin
- DBPassword: Admin12345!

## Crearemos lo siguiente:
| Recurso        | Uso                              |
| -------------- | -------------------------------- |
| Subnet Group   | Permite que RDS use tus subredes |
| Security Group | Controla acceso a la base        |
| Instancia RDS  | Base de datos MySQL              |
