#**CHAPTER 2**
##**Holy Grail**
###p. 13
==more astronauts in the UK than pro tubists==:
Don't scoff at the tuba though. David Bowie claimed *Tubby the Tuba* to have been a [major
influence on his future musical direction][bowie]. I concur.
[bowie]:https://www.youtube.com/watch?v=HhH86U0gk5Y

==no one's idea of the classic coder cowboy==:
for the record, Tollervey still thinks of himself very much as a musician who codes
rather than the other way round.

###16
==That stuff is not comfortable, is it?==:
Given the rococo mechanism—the *stack*—required to make high-level languages work,
why do we bother with them? Why aren't I simply learning C or Assembly?
When I speak to Jack Ganssle, a recently retired embedded software
expert who writes a stylish blog called *The Embedded Muse*, he tells me
old school Assemblyheads asked the same question when C appeared in the
1970s. What modern high-level coders now regard as C's monkish
asceticism owed nothing to machismo, he says: computer memory was still
expensive and limited, so sacrificing kilobytes and performance to
convenience struck some Assembly nerds as the closest they were ever
likely to get to sin. "I was in the room when the shouting was going
on," Ganssle chuckles at this distance. "People were really upset!"

But even this wasn't the first outbreak of Religious Wars. The veteran
MIT and NASA programmer Margaret Hamilton recalls similar puce faced
rage attending the shift from \"some very low machine language\" *to*
Assembly in 1964.Why did The Stack keep climbing? For perspective I do a
little research on what these shifts meant to the coders in question.
Programmers have a tradition, one of the few available in an otherwise
skittish environment, that a newcomer's first program should be to print
the legend "Hello World!" to the post window in their editor. A
Pythonista simply calls the "print" *built-in* function and tells it
what to print, as per:
```py
print("Hello World!")
```
In this way they avoid the equivalent in C, namely:

```c
#include \<stdio.h\>

#include \<stdlib.h\>

int main(void)

{

printf(\"Hello, World!\\n\");

return EXIT_SUCCESS;

}
```
And this is what the poor assemblymeisters were livid about sacrificing
to C in the mid-seventies:
```Assembly
bdos equ 0005H ; BDOS entry point\
start: mvi c,9 ; BDOS function: output string\
lxi d,msg\$ ; address of msg\
call bdos\
ret ; return to CCP\
\
msg\$: db \==Hello, world!\$\==\
end start
```
C is still widely used in situations where the machine's resources take
precedence over the coder's (where memory is limited or speed of the
essence, for instance.) So is Assembly on occasion. But even when it's
not *explicitly* there, it's often still present somewhere in the stack.