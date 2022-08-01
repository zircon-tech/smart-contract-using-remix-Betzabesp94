## Unit 3: Ethereum | Remix IDE -English Version- 🚀

### What's this project about? | Simple Voting System for several proposals 

This Voting is an adaptation of a Zircon Tech Lunch Project but without using factory pattern, 
the smart contracts controls proposals which can have a max number of options and a state of open or close, voters can only vote once per proposal. 

Owner of the contract(deployer) can assign/ban admin roles, admin can assign voters, create proposals, add new options, open and close votations.  

You can try Voting.sol at Remix IDE. 
Deployed at: [Voting Deployed At Kovan](https://kovan.etherscan.io/tx/0x9edf5fe91eb0cc93095e67c780441438ddf3dfaa5a510aa9a841ff9a25761220)

### Some considerations 
#### Smart Contract Best Practices 

When organizing your solidity code you can follow the [Order Layout Style Guide](https://docs.soliditylang.org/en/v0.8.14/style-guide.html#order-of-layout) For example: 

```solidity
// SPDX-License-Identifier: MIT 
pragma solidity ^0.8.0; // 1. Pragma statements
// 2. Import statements (if any)
// 3. Interfaces  (if any)
// 3. Libraries (if any)

//4. Contracts
contract styledTemplate { 
// Inside each contract, library or interface, use the following order:
// a. Type declarations

// b. State variables

// c. Events

// d. Modifiers

// f. Functions

```

## Unidad 3: Ethereum | Remix IDE -Versión en español- 🚀

### ¿De qué se trata este proyecto? | Sistema de votación para varias propuestas 

Este sistema de Votación es una adaptación de un proyecto Tech Lunch de Zircon pero sin usar patrón de fábrica,
los contratos inteligentes controlan las propuestas que pueden tener un número máximo de opciones y un estado abierto o cerrado, los votantes solo pueden votar una vez por propuesta.

El propietario del contrato (quien lo desplegó) puede asignar/prohibir roles de administrador, el administrador puede asignar votantes, crear propuestas, agregar nuevas opciones, abrir y cerrar votaciones.

Puedes probar Voting.sol en Remix IDE. 
Desplegado: [Voting desplegado en Kovan](https://kovan.etherscan.io/tx/0x9edf5fe91eb0cc93095e67c780441438ddf3dfaa5a510aa9a841ff9a25761220)

### Algunas consideraciones
#### Mejores practicas
Cuando organizamos el codigo de Solidity, podemos seguir el [Order Layout Style Guide](https://docs.soliditylang.org/en/v0.8.14/style-guide.html#order-of-layout) Por ejemplo: 

```solidity
// SPDX-License-Identifier: MIT 
pragma solidity ^0.8.0; // 1.  Declaraciones Pragma
// 2. Declaraciones de importaciones (Si hubiere)
// 3. Interfaces  (Si hubiere)
// 3. Librerias (Si hubiere)

//4. Contratos
contract Plantilla { 
// Dentro de cada contrato, librería o interfaz, utilice el siguiente orden:
// a. Declaraciones de tipo

// b. Variables de estado

// c. Eventos

// d. Modificadores

// f. Funciones

```