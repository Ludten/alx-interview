# Minimum Operations
> Each file in this repository holds code that illustrates Minimum Operations
> specific to Data Structures and Algorithms.

## Description of what each file shows:
* 0-minoperations.py: In a text file, there is a single character `H`. Your text editor can execute only two operations in this file: `Copy All` and `Paste`. Given a number `n`, write a method that calculates the fewest number of operations needed to result in exactly `n` `H` characters in the file.

	- Prototype: `def minOperations(n)`
	- Returns an integer
	- If `n` is impossible to achieve, return `0`

	__Example:__

	`n = 9`

	H => `Copy All` => `Paste` => `HH` => `Paste` =>`HHH` => `Copy All` => `Paste` => `HHHHHH` => `Paste` => `HHHHHHHHH`

	Number of operations: `6`
