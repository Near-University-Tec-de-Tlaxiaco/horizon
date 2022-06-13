

# Bienvenido a HORIZON :classical_building:
---
 HORIZON 
 es un smart contract el cual tiene como principal objetivo hacer uso de la WEB 3.0 y apoyar a la educacion .
Este proyecto se tiene en mente en crear una aplicación en el cual, permita a la sociedad que sepa de algún tema, o este capacitado en una área para que comparta sus conocimientos atravez de clases, a su usuario.
tiene la finalidad de dar mas oportunidad de trabajo por si solo a las personas que sepan de algún conocimiento, y no tengan trabajo y médiate la *aplicación obtengan sus ingreso, así como también las personas que lo requieran sean autodidactas
.

## Cómo utilizar este contrato ?
---
### Pré-requisitos :hammer:
1. Debe tener [Nodejs](https://nodejs.org/en/) instalado en su versión 12.0 o mayor.
2. Debe tener instalado [Yarn](https://yarnpkg.com/). Para saber si lo tiene, ejecute el comando ```yarn --version ```. En caso de no tenerlo, puede instalarlo ejecutando el comando ```sudo npm install -g yarn```
3. Instale las dependencias de yarn ejecutando ```yarn install```
4. Debe tener una cuenta en la [testnet de NEAR](https://wallet.testnet.near.org/)
5. Debe tener [NEAR-CLI](https://github.com/near/near-cli) instalado globalmente en su ordenador. Para saber si ya lo tiene instalado, ejecute ```near --version```. En caso de no tenerlo, instálelo ejecutando el comando ```sudo npm install -g near-cli``` 

Ya tenemos todo lo que necesitamos para probar nuestro contrato inteligente. Ahora vamos a ejecutarlo.

## Instalación :open_file_folder:
---
1. Clone el repositorio ```git clone https://github.com/Near-University-Tec-de-Tlaxiaco/horizon``` 
2. Vamos a iniciar sesión en nuestra wallet que creamos anteriormente: ```near login```
3. Dentro del repositorio, instalemos las dependencias del proyecto ejecutando ```npm install```, tranquilo, esto puede tomar unos segundos.
4. Si quieres desplegar el contrato y probar sus funciones, puedes hacerlo con ```yarn deploy:dev``` esto le devolverá un conjunto de caracteres que empezarán por "dev-" seguido por numeros generados por la red. Guárdelo, lo necesitará si quiere probar los métodos del contrato inteligente.
5. Por último, si queremos ejecutar los tests desarrollados, podemos hacerlo ejecutando ```yarn test```
   

## Author

- [CARLOS HERNANDEZ](https://github.com/carlos-chrs)
- [ANDRE EMMANUEL ](https://github.com/AndreLuna6)






