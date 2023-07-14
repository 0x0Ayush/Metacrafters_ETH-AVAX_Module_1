# Metacrafters_ETH-AVAX_Module_1

# Solidity Error Handling

This Solidity contract demonstrates error handling techniques using various functions.

## Functions

### `testAssert(uint num)`

This function uses the `assert` statement to check if the given `num` parameter is not equal to zero. If `num` is equal to zero, the assertion fails and the transaction is reverted.

### `divide(uint _numerator, uint _denominator)`

This function divides the `_numerator` by the `_denominator` parameter. It checks if `_numerator` is less than `_denominator`. If the condition is true, it reverts the transaction with an error message stating that the numerator should be greater than the denominator. If the condition is false, the division operation is performed and the result is returned.

### `mult(uint a)`

This function multiplies the parameter `a` with a predefined variable `b`. It uses the `require` statement to check if `a` is greater than zero. If `a` is not greater than zero, the transaction is reverted with an error message stating that the value of `a` should be greater than zero. If the condition is true, the multiplication operation is performed and the result is returned.

