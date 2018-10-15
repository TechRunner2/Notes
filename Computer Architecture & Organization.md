Computer Architecture & Organization
========================

## Computer is a binary digital system 2.1.1

### Digital system:
- Finite number of symbols
- Binary (base two) system:
	- Two states: 0 and 1
- Bit (binary digit): Basic unit of information
	- Having one of two states, 0 or 1
	- Implemented with 2-state device
- Values with more than two states require multiple bits:
	- A colection of 2 bits has 4 possible states: 
		- 00, 01, 10, 11
	- A collection of 3 bits has 8 possible combinations
		- 000, 001, 010, 011, 100, 101, 110, 111


| # of bits | values|
| --- | --- |
| 1 | 2 |
| 2 | 4 |
| 3 | 8 |
| n | 2^n |

Unsigned Integers
non-negative integer value represented as string of bits using weighted positional notation
- Think of decimal numbers: "329"
- "3" is worth 300, because of its position, while "9" is worth 9


Design goal
- Easy to understand
	- Pattern for mapping code to value

1's Compliment<br>
1. Get binary code for +X <br>
2. flip every bit of step 1 <br>
3. Output = -X <br>

2's Compliment

1. Get binary code for +X <br>
2. flip every bit of step 1 <br>
3. Add 1 to setp 2

Integers | (n-1) bits Unsigned binary | n bits nigned magnitude | n bits 1's complement | n bits 2's complement <br>
0 & positive | weighted positional notation | prepend 0 to leading bit | same | same | <br>
negative | X | flip the leading sign bit to 1 | flip every bit | Flip every bit + 1 | <br>

Integer | Representation

Unsigned | Weighted Positional notation

Signed | 2's complement

int 2/4 bytes
unsigned int 2/4 bytes
long 4 bytes
unsigned long 4 bytes
char 1 byte
unsigned char 1 byte - Used for storing numbers

ALU - Arethmatic Logic Unit

Operations on bits
2.5 Arithmetic
- Addition & Subtration on 2's complement binary
- SExt oon 2's complement binary
- Overflow 2's complement binary unsigned binary

2.6 Logical operations
1. AND
2. OR
3. NOT
4. XOR


```cpp
short int a; //2 Bytes
long int b; //4 Bystes
	b = 15;
	a = b;
```

5 - bit 2's complent

-2^4 ~ 2^4 -1

-16 ~ +15


5 -bit unsigned 
0 ~ 2^5 -1
0 ~ 31

## Limitations of Integer Representations
Most numbers are not integers!

Real Numbers in Decimal

Q: How to represent non-integer real numbers decimal?

A: 2 approaches

1. Fixed point notation:
	- Use

2. Floating point (scientific) notation
	- The mass of an electron: 9.109 x 10^-31 kg
	- In scientific notation all numbers are written in the form of a x10^b

2 Considerations in representing a numeric calue:

- Range: The magnitude of the numbers we can represent
- Precision: The exactness with which we can specify a number



# Floating Point
- Floating (scientific) representation
	- 6.023 x 10^23

- Sign is 1: number is negative
- Exponent field is 011111110 = 126 (decimal)
- Fraction is 0.100000000000 = 0.5 (decimal)
- Mantissa is 1.100000000000... = 1.5 (decimal)


Q: C1E00000
12, 1, 14, 0, 0, 0, 0, 0
bin: 1 10000011 11000000000000000000000
Decimal: - 131.75


a. + 128.0
b. -  131.0625
c. + 255.0
d. - 128.5625

# Real numbers in Binary
mimic the decimal floating point notation




# C programming
## Literals
- Integer
	- 123 decimal
	- -123
	- 0x123 hexadecimal
- Floating point
- Character

## Scope: Global and Local
Where is the variable accessible?
- Global: accessed anywhere in program
- Local: only accessible in a particular region

Compiler infers

- n flits = 3^n values
- n digits = 10^n values
- n bits = 2^n values

# Transistors

- N-type
	- When Gate has positive voltage, short circuit between #1 and #2 (switch closed)
	- when Gate has zero voltage, open circuit between #1 and #2 (switch open)
- P-type


# Building Functions from Logic Gates
- Combinational Logic Circuit
	- Output depends only on the current inputs
	- Stateless
	- Ex:
		- Decoder
			- Exactly one output is 1 for each possible input pattern
- Sequential Logic Circuit
	- Output depends on the sequence of input (past and present)
	- Storage of information (state)


Instruction Processing: 6 phases
ISA:
	- Format of Instruction

LC-3
CPU: 8 registers, 16 bits
Memory: 2^16 x 16
I/O: Keyboard

