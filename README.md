# Assignment1
Registers's Overview
🎯 Objective

To subtract two word-sized numbers using 8086 Assembly language and store the result in memory.

# Memory Model

.model small

One Code Segment

One Data Segment

# Data Used

num1 dw 25 → First number

num2 dw 8 → Second number

result dw ? → Stores subtraction result

# Working

Initialize Data Segment using mov ax, @data and mov ds, ax.

Load num1 into AX.

Load num2 into BX.

Subtract BX from AX using sub ax, bx.

Store result in result.

Terminate program using int 21h (Function 4Ch).

# Output

25 − 8 = 17
(Result stored in memory variable result)
