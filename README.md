SCA ARCHITECTURE

• what is it?

a simple risc inspired 8-bit instruction set.

• how does it work?

its similar to a harvard architecture, so rom and ram are seperate.
it has 1,5 kilobytes of operation ram,
6 kilobytes of rom,
even though its 8 bit, it has a limit of 64 digits at once in a cell of ram.

• the isa

ORG [how much cells of ram to use].

ADD [a digit, up to 64] [a ram cell to add the digit]

SUB [a digit, up to 64] [a ram cell to subtract the digit from]

HAL [wait time]

JMA [flag to point where it is]

JMP [jump to the JMA flag] [repeat how many times]

MOV [original cell adress] [new cell adress]

CLS [a cell to clear]

SND [a cell to output]

IIV [the pin] [X volts] $[then execute any instructions]

END
