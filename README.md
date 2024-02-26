# SomeContract
This is a smart contract written in the Move programming language. The contract defines a SomeContract that contains a SomeStruct and a SomeResource. It also provides functions to interact with these structures.

# SomeStruct
SomeStruct is a struct defined within SomeContract. It contains four variables and three functions.

# Variables
a: A string variable that is publicly settable.
b: A string variable that is publicly accessible.
c: A string variable that is accessible only within the contract.
d: A string variable that is accessible only within instances of SomeStruct.
# Functions
publicFunc(): A public function.
contractFunc(): A function accessible only within the contract.
privateFunc(): A function accessible only within instances of SomeStruct.
structFunc(): A public function defined within the struct.
Initialization
Upon initialization, the struct's variables are assigned initial values.

# SomeResource
SomeResource is a resource defined within SomeContract. It contains one variable and one function.

# Variables
e: An integer variable.
Functions
resourceFunc(): A function defined within the resource.
Initialization
Upon initialization, the resource's variable e is assigned an initial value of 17.

# Functions
createSomeResource(): A public function that creates and returns an instance of SomeResource.
questsAreFun(): A public function.
Initialization
Upon initialization of SomeContract, an instance of SomeStruct is created and assigned to the variable testStruct.

# Usage
The contract provides functionality to interact with SomeStruct, SomeResource, and other public functions.
