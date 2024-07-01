#**1**
##**Revenge of the SpaghettiOs**
###3
==A *shift-devil*, she called it==:
These thoughts from one of the first serious programmers I spoke to, one
of those who (without knowing it) convinced me to go further: the
inimitable coder/writer Ellen Ullman, whose books, especially *Close to
the Machine*, I can't recommend highly enough. All programmers speak of
needing "clearly defined boundaries between things," in their work but
Ullman speaks specifically of the necessity of "defined interfaces."


#**2**
##**Holy Grail**
###13
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


#**3**
##**PyLadies and Code Freaks**
###22
==hence the lower prices \[in Marin\]==:
Jan, who had lived in the Bay Area before, urges me to point out that we were at the border of
*west* Marin, acknowledging that many parts of the county, especially
those closest to the Golden Gate, are far from cheap.

###28
==a fabulously engaging tome called *Python Crash Course*==:
One of the happiest aspects of my first PyCon is that Eric Matthes and I
meet and become friends, later attend a conference (reported in this
book) together. I==m now in a much better position to understand just how
hard it is to write books like his, and what skill it takes. *Python
Crash Course* remains the best route into Python that I==ve come across,
by far. Naomi Ceder's *The Quick Python Book* is also excellent, as
clearly articulated and exampled reference, once you're up and running.
As elsewhere, freeCodeCamp is also a great place to get a feel for the
task.

###31
==to_celsius==: for comparison, what would the same function look
like in JavaScript? JavaScript (JS) was designed as the web expanded in
the mid-1990s, to work inside a browser. HMTL and CSS make pages that
are static, where JS enables the creation of algorithms to make them
active—say by offering a slideshow of images or ability to process
user input in useful ways. A weather app might benefit from a Fahrenheit
to Celsius converter, for instance. Examples of this basic algorithm are
all over the internet and studying them provides a first window into how
JS works. The first thing I learn is the centrality to programming of
the *function*, a block of code containing a reusable algorithm that
automates a chosen task. freeCodeCamp's version looks so:
```js
function toCelsius(Fahrenheit) {return (5/9) \* (Fahrenheit -32)};
```
For clarity's sake an experienced programmer might format the function
more like this:
```js
function toCelsius(Fahrenheit) {

return (5/9) \* (Fahrenheit -32)

};
```
What's going on? In programming, I learn, this is called a *function
definition*. Line one establishes the name we're giving our converter
function: "toCelsius." The parentheses following a function's name
provide a portal for any input it may require—the data we want
changed. Being a Fahrenheit to Celsius temperature converter, the
"toCelsius" function will require a temperature to convert. The word
"Fahrenheit" acts as a placeholder for the specific temperature we will
ultimately *pass* the function whenever it is *called*.

In JS, the guts of the algorithm are given within curly brackets, which
in this case open at the end of line one and close at the start of line
three, with the algorithmic work described in between. "Return" means
"return the result of the following calculation," which is based on the
classic formula for Fahrenheit-to-Celsius conversion—subtract 32, then
multiply by five ninths. Again, the word "Fahrenheit" is a placeholder
for the specific temperature we will feed the function whenever we call
it. Per mathematical convention, operations contained within parentheses
are carried out first, so in line two we are telling the machine, "Take
the given Fahrenheit number, subtract 32 from it, then multiply the
result by five ninths." In computing, an asterisk ( \* ) is used to
denote multiplication because the "x" symbol has other uses.

Having written the toCelsius function, we may now call it whenever we
need a conversion, enclosing the temperature to be converted within
the parentheses reserved for them. Output appears in the "post" window
usually located below or the right of the editor screen.

`toCelsius(77);`

will generate output of:

`25.0`

###33
==the disproportionate number of musicians in the fold==: A partial
thought on this. An aquaintance who happens to be trained in Indian and
European classical music once explained the extraordinary system of
Indian ragas to me, which consists of hundreds of complex melodic
frameworks within which to compose and improvise, each with an emotional
hue and resonance of its own. In the Hindu tradition ragas are
considered part of the spiritual physics of existence: musicians
discover rather than invent them. With such mathematical complexity
woven into the fabric of everyday life, I never again wondered why India
produces so many great mathematicians and physicists. And programmers? I
make a mental note to chase down precisely what programmers mean by
\"abstraction\" when I get home; if and how it relates to music or
anything else.

###34
=="You'll get used to it," Nicholas grins==: Perhaps more
iodiosyncratic was the man who sat next to me at the Great Lakes Science
Center dinner the next might. He was tall and built like a
mountain—clearly spent time in gyms or on special ops—and if you saw
him on a sidewalk in Williamsburg you might think him stylish in Johnny
Cash black, asymmetric hairdo, neat urban beard and expensive headphones
. . . headphones he didn't take off through the entire course of the
event—except once, to order a drink at the bar, which is how I know he
*could* speak. Shortly after arriving, with the rest of us waiting to be
invited to collect our first course from the canteen-style service, he
stalked off and returned with a piece of cheesecake, presumably wrested
from the hands of a bewildered server, which he ate on his own, staring
into a middle distance that in truth wasn't there thanks to a wall,
neither making eye contact nor uttering a single, solitary word over a
space of two hours. The funny thing is you learn to enjoy these
eccentricities around coders. I would feel poorer without them now.


#**4**
##**Minutely Organized Particulars**
###41
==ARPA was trying to offload \[the ARPAnet\] onto the private
sector==: see *Totally Wired: The Rise and Fall of John Harris and the
Great Dotcom Swindle*, by Andrew Smith, p74
