#**CHAPTER 3**
##**"PyLadies and Code Freaks"**
###p. 22
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