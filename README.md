SCA ARCHITECTURE

• what is it?

a simple risc inspired 8-bit instruction set.

• how does it work?

its similar to a harvard architecture, so rom and ram are seperate.
it has 1,5 kilobytes of operation ram,
6 kilobytes of rom,
even though its 8 bit, it has a limit of 64 digits at once in a cell of ram.

• the isa

(have got) hag [library name]

(organize) ORG [how much cells of ram to use].

(add) ADD [a digit, up to 64] [a ram cell to add the digit]

(subtract) SUB [a digit, up to 64] [a ram cell to subtract the digit from]

HAL [wait time]

(jump adress) JMA [flag to point where it is]

(jump) JMP [jump to the JMA flag] [repeat how many times]

(move) MOV [original cell adress] [new cell adress]

(clear) CLS [a cell to clear]

(send) SND [a cell to output] [the pin for output]

(if input value) IIV [the pin] [X volts] $[then execute any instructions]

(execute or ignore) EOI [the pin] [x volts] $[then execute any instructions]

END
