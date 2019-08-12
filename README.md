
power shell com oadministrador:  
$  npm install --global --production windows-build-tools


$ npm install solc@0.4.24 --save-dev
$ npm install web3@1.0.0-beta.35 --save-dev

pintar colores de salida en la consola
$ npm install chalk --save-dev

libreria para test
$ npm install mocha@5.2.0 --save-dev

compilar  proyecto:
$ node .\scripts\compile.js

correr test
$ npm run test   ó   $ npx mocha

Ganache: provee una red de Ethereum de pruebas de manera sencilla
- podemos desplegar contratos, 
- ejecutar pruebas para probar su correcto funcionamiento
- ejecutar comandos
- inspeccionar todas las transacciones que tienenlugar en la red
