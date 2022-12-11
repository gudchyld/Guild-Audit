## Smart Contracts and Solidity

Smart contracts can be seen as a piece of computer code that are written and run on the Ethereum blockchain. They are  automatically executed once set conditions are met.
As computer programs they have various characters which includes been deterministic and they also immutable.

With regards to the life cycle of a smart contract it's most controlled at typically written in high level languages such as Ethereum when written they get compared and then deployed on to the blockchain to call this smart the color has to orbit unit from an externally owned account only and only on accounts. Basically contract addresses are formed by using details from the transaction itself these include combining the originating account address and the nose to form a new contract address now smart controls the light domains until being activated by transaction which of course must come from an ethnic own account now when this happens they can be said to come alive it's most contrast can also be destroyed or ended by calling special which is the self destruct It is imperative that this functionality be quoted into this month's controls to enable deleting this month controls from the blockchain initial since these colors is not deleted from the blockchain history since the button is emitted but only the code is deleted and therefore making it unusabe

When it transaction is triggered on a smooth contract this transaction has to run to finish before any state's changes can be recorded on the blockchain if by any means transition fields or changes are road back and it happens as safe transaction never executed. Fee will be collected for is equation until that point post changes wouldn't be recorded since its transaction never succeeded.

Solidity is the major language used for writing smart controls on ethereum along with the solidity projects is the solidity compiler which is also used for converting codes written in solidity to EVM byte code along with this functionality comes the ability to also generate ABI application binary interface which contains a JSON format s of the functions I'm variables that exist in this mass contract.

For writing smart contracts it is advised to you the recent version of solidity as contents updated changes and improvement from past versions there by bringing more functionality to smart contracts.

As a developer it is advised to use the Linux operating system for writing and developing smart contracts accompanied with any simple test editor such as atom or vs code.

Data types

Some of Ethereum that type includes Bool which have the values of true or false we have integers signed and on signed, these also include addresses which are 20 bytes we also have 

struct that contains user defined variables, we also have mapping that represent hash lookup table in form of key value pairs and arrays in form of fixed and dynamic

Predefined variables include such global variables like msg.sender, msg.value, TX.origin and much more

Solid did see offers objects types like interfaces and libraries interfaces are similar to contracts only that they don't have the function implemented the functions are only defined but not implemented as a library content is one that is meant to be deployed only once and used by other contracts it can contain additional functionalities the can be imported and used into a contract

Also so it is him makes use of functions that are similar to other programming language with some visibility structures such as private public internal understanding Private functions are native to the contracts where public functions can be called outside the contract

It's also make use of keywords that affects the behavior of contracts just such as marking a function as view pure or payable view functions promised not to modify this date while a pure function can neither read nor right to state payable is just a keyword that is used to allow a function to be able to accept ether

Solidity also makes use of constructors inheritance and modifiers. It handles error using assets require and revert

When transactions complete is produces transaction receipts wish I events this event can be emitted to the note the action that I've been performed by this smart for the more this can be used in development of that that index ed this event so us to avoid the blockchain for social always.

Some tips to watch out for white developing with this smart contract is gas consideration a contract properly with seem to optimize for gas is very user friendly and is advisable by the activium community now to avoid consumable gas some tips should be noted example is to avoid calls to other contracts and avoid using dynamically sized arrays
