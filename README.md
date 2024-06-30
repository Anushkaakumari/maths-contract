Creating a Math Contract! - Readme
This Solidity contract provides various mathematical functions and functionalities for storing and retrieving named results.

Description
Features
Arithmetic Operations: Add, subtract, multiply, and divide integers with named results.
Factorial: Calculate the factorial of a non-negative number.
Random Number Generation: Generate a random number within a specified range (implementation omitted for brevity).
Result Storage: Store calculation results with user-defined names using a mapping.
Result Retrieval: Retrieve stored results by name.
Error Handling:
revert with custom messages for unexpected errors.
require to check for specific conditions before proceeding.
assert to verify assumptions about the contract state (should always be true).
Asset Reversion: Remove a named result from storage (effectively reverting it).
Note: The random number generation function is omitted for brevity. You should replace it with a secure random number generation function from a trusted library.

Execution program
 Go to Ethereum IDE(https://remix.ethereum.org/)
 Create a new file and write your code • // SPDX-License-Identifier: MIT • pragma solidity 0.8.18;
Deploy the Math contract to your desired blockchain network.
Use the provided functions to perform calculations and store results:
add(name, a, b): Add a and b, store the result with name name.
subtract(name, a, b): Subtract b from a, store the result with name name.
multiply(name, a, b): Multiply a and b, store the result with name name.
divide(name, a, b): Divide a by b (ensure b is not zero), store the result with name name.
factorial(n): Calculate the factorial of non-negative integer n.
random(min, max): Generate a random number between min and max (inclusive).
Use getResult(name) to retrieve the stored result associated with name.
Utilize error handling functions like unexpectedError(), checkValidResult(name), and handleErrors(name, a) for robust error management.
Use revertAsset(name) to remove a named result from storage.

Authors
Anushka kumari anushka.ak29@gmail.com
8168563516
