CE5_Stolze
==========

Computer Exercise 5

# Task 1 

```addi $S0, $0, 44``` Loads 44 into register 0

```addi $S1, $0, -37``` Loads -37 into register 1 

```add $S0, $S1, $S2``` Adds the contents of registers 0 and 1 and puts this value into register 2

```sw x54, $S2 store``` the contents of register 2 into the memory address x54

# Task 2

```addi $S0, $0, 44```

Binary Code: 00100000000100000000000000101100

Hex Code: 0x2010002C

```addi $S1, $0, -37```

Binary Code: 00100000000100010000000000100101

Hex Code: 0x2011FFDB

```add $S0, $S1, $S2```

Binary Code: 00000010001100001001000000100000

Hex Code: 0x02309020

```sw x54, $S2 store```

Binary Code: 10101110010000000000000001010100

Hex Code: 0xAE400054

The waveform generated from the testbench is shown below:

![alt text](https://raw.githubusercontent.com/aaronstolze/CE5_Stolze/master/MipsWaveform.PNG "MIPSWaveform")

I am not sure that the above waveform is right since I did not get all of the necessary commands to show up.
