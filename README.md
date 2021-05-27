# Descriptive-Programming-Language

## Description

The Descriptive Programming Language (DPL) is an auxiliary language used for computer programming. It is simple, easy to understand, convenient for communication between programmers in different languages and non - technical personnel reading. 

## Grammar

- All codes are in capital case format; 
- Code statements are separated by "\ n\r"" ; 
- Inentation is non - necessary, but it can increase the reading of the code; 
- Comments need to be placed before or after the code, cannot be in the same line as the code, and start with the character '#' . 

### Keywords

- ABORT
- BEGIN
- BOOLEAN
- CALL
- CONST
- DEF
- END
- FALSE
- FIND
- FOR
- FUNCT
- GOTO
- IF
- JUMPBACK
- KILL
- LEFT
- MIDDLE
- NUMERIC
- POINT
- RETURN
- STACK
- STRING
- STRUCT
- UNTIL
- USE
- VARIANT
- WHILE
- YES

### Grammar

#### Basic Type

##### Boolean:

***BOOLEAN V***
Boolean variant has only two values: True and False. 

##### Numeric:

***NUMERIC V***
Numeric variant stands a mathematical value.

##### String:

***STRING V***
String variants are usually ued for queues of characters.

#### Composite Type

##### Array:

***BasicType[] V***
***BasicType[n1,n2...] V***
Arrays are defined just like the C language.

##### Stack:

***Stack V[d]***
Stack variants are seldom used, but they are useful in some occasions.

##### Extended Type

##### Struct:

***DEF STRUCT V:***
***-BasicTypeOrCompositeTypeOrExtendedType V1***
***-BasicTypeOrCompositeTypeOrExtendedType V2***

##### Enumeration:

***DEF ENUM V:***
***-V1***
***-V2***

##### Dictionary:

***DEF DICT V:***
***-{KEY1:VALUE1}***
***-{KEY2:VALUE2}***

##### Tree:

***DEF TREE V:***
***->S1***
***->>p1***
***->>p2***
***->S2***
