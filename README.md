# Proportional Token Farm

Este proyecto implementa una simple Token Farm DeFi que permite a los usuarios realizar depósitos y retiros de un token mock LP, así como reclamar recompensas generadas durante el staking.

## Contratos

- `LPToken.sol`: Contrato del token LP, utilizado para el staking.
- `DappToken.sol`: Contrato del token de la plataforma, utilizado como recompensa.
- `TokenFarm.sol`: Contrato de la Farm.

## Despliegue

Para desplegar los contratos en un entorno local, sigue estos pasos:

1. Clona el repositorio y navega al directorio del proyecto.
2. Instala las dependencias necesarias:

   ```sh
   npm install
