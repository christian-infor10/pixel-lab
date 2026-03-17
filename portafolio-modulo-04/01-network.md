## Nombre stack: 
- infra-viva-network

## Informacion redes
- PublicSubnet  -> 10.0.1.0/24
- PrivateSubnet -> 10.0.2.0/24

## Infraestructura actual es básicamente:
VPC 10.0.0.0/16
│
├── PublicSubnetA   (10.0.1.0/24)  us-east-1a
├── PublicSubnetB   (10.0.2.0/24)  us-east-1b
│
├── PrivateSubnetA  (10.0.3.0/24)  us-east-1a
└── PrivateSubnetB  (10.0.4.0/24)  us-east-1b

## Crearemos lo siguiente:
| Recurso          | Cantidad |
| ---------------- | -------- |
| VPC              | 1        |
| Public Subnets   | 2        |
| Private Subnets  | 2        |
| Internet Gateway | 1        |
| Route Table      | 1        |

Arquitectura multi-AZ, como producción.