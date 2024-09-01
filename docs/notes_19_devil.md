#**CHAPTER 19**
##**"Strange Loops and Abstractions: The Devil in the Stack"**
###p. 405
==Hofstadter claims to have no interest in computers as such and
has expressed skepticism of current "AI" models==:
In "[The Mind Reader][mind]," *New York Times Magazine*, April 1, 2007. Like so many others, he
ultimately changed his mind: "['Human Beings Are Soon Going to Be
Eclipsed,'][ec]" *New York Times*, July 13, 2023.
[mind]:https://www.nytimes.com/1976/06/13/archives/the-mindreader.html
[ec]:https://www.nytimes.com/2023/07/13/opinion/ai-chatgpt-consciousness-hofstadter.html

###406
==To illustrate the shifty concept of recursion he not only
recruits Bach's canons==:
Most particularly in the composer's extraordinary fugue *Ricercar*, part of a collection of canons and fugues based on a single theme, originally improvised, called *The Musical Offering*. Hofstadter's explication of the structure of *Ricercar* early in Part One of the book and is among the most fascinating musical discussions I've ever come across. Afterwards I couldn't stop listening to the piece on the Hilliard Ensemble's *Ricercar* album.

==Marshall McLuhan's famous sixties adage, "the medium is the
message"==:
From *Understanding Media: The Extensions of Man*, 1964.

###407
==Put another way, mediums propagate their essences, their
*forms*, in all who use or encounter them==:
I write about this in more
detail in my book *Totally Wired: The Rise and Fall of Josh Harris and
the Great Dotcom Swindle*. On the subject of McLuhan I also recommend
Douglas Coupland's entertaining book, *Marshall McLuhan: You Know
Nothing of My Work!*—named for the famous scene in Woody Allen's
*Annie Hall*, where Allen produces McLuhan out of nowhere in a movie queue to set a fellow queuer straight about the Canadian thinker's ideas .

==We shape our tools, and thereafter our tools shape us==:
This
quote opens the door to multiple rabbit holes for McLuhan geeks. Culkin
was explaining McLuhan's thought when he said it, but McLuhan doesn't
ever appear to have claimed attribution. To complicate matters further,
none other than Winston Churchill told his Parliament in 1943, on the
subject of rebuilding the bombed House of Commons, that "We shape our
buildings and afterwards our buildings shape us." For the very nerdy
(which in this particular instance includes me, obviously), there's a [satisfyingly
labyrinthine discussion of attribution][laby] on quoteinvestigator.com.
[laby]:https://quoteinvestigator.com/?s=We+shape+our+tools%2C+and+thereafter+our+tools+shape+us

###408
==The money's quintessence, corruption, replicated in everything
it touched and may take a generation to cleanse==:
for astonishing
accounts of this process, read Oliver Bullough's *Moneyland* (2019)
and/or *Butler to the World: How Britain Helps the World's Worst People
Launder Money, Commit Crimes, and Get Away with Anything*, or listen to
*Tortoise Media's* "[Londongrad" podcast][grad].
[grad]:https://www.tortoisemedia.com/listen/londongrad/

###409
==a computer founded on similar "ternary" logic was built in the
Soviet Union as long ago as 1958==:
this computer was called "Setun" and
was considered to have some significant advantages over computers built
on binary logic. See Wikipedia entries for "Setun," "Ternary computer"
and "Decimal computer."

###410
==Every problem in computer science can be solved by another
layer of abstraction==:
This is in fact a deliberate misquotation of
something said by the Cambridge University computer scientist David
Wheeler, specifically: "All problems in computer science can be solved
by another level of indirection." Loosely defined, "indirection" refers
to the process of subsuming a value under a convenient name or symbol, a
good example being a value stored in a variable. The quote is sometimes
given as "All problems in computer science can be solved by another
level of indirection, except for the problem of too many layers of
indirection." Arcana lovers can knock rhemselves out on "[Indirection:
The Unsung Hero Of Software Engineering][indir]," *Forbes*, August 20, 2020.
[indir]:https://www.forbes.com/sites/forbestechcouncil/2020/08/20/indirection-the-unsung-hero-of-software-engineering/?sh=309b52167f47

==when I try to work out exactly how my Python gets to the
metal—the bottom of the stack—it takes days of research to trace the
steps==:
This passage owes a huge debt to Nicholas. It tells you
something about the degree of complexity and depth of abstraction
involved in the process being described, that after all my painstaking
investigation I'd got very close but still not quite there. Nicholas
consulted his colleague Dr. Antonio Cuni, respected as one of the
world's leading authorities on Python compiler design, and helped
immeasurably in producing the finished account you read in these pages.
Giant thanks to both these incredibly smart people. So this quest
involved us both in days of work . . . only afterwards did I think: we
could have just bought Guido a beer and asked him!

==a series of instructions called *bytecode*==:
As with the mostly
hidden *code objects*, you would never normally see bytecode, but a
natty tool called a *disassembler* allows you to, rendering it as
something very like the ultra-low level Assembly Code programmers like
the great Project Apollo software team leader Margaret Hamilton used
before they had high level languages to translate for them: long
sequences of numbered codes and abbreviated three-letter commands.

==a *Python virtual machine*—a simulated computer, written in
C, that compiles to the C interpreter==:
Another one for lovers of the
long grass. During an extended period of trying to piece together this
process—it appears written down like this almost nowhere—I grasp for
the first time that the Python programming language I experience exists
independently of the particular *implementation* that interprets my own
code, and that there is more than one such implementation—i.e. more
than one available interpreter. The standard implementation such as I
and most people use is called CPython because it is written in C and
compiles to the C interpreter, while Jython compiles to Java bytecode in
order to be processed by the Java interpreter. But the source code I
write for each will look (and be) the same.

###412
==scientists began to flag a dangerous link between carbon
emissions and global heating from the late 1960s on==:
the English
engineer Guy Stewart Callendar began to publish evidence of a link in
1938, but thought the resultant warming would be beneficial. From the
late 1950s scientists began to model and monitor the effects of warming,
leading to the first serious public warnings from the late 1960s.
Politicians and the public engaged en masse from the late 1980s.

###413
==likelihood of committing a crime and therefore suitability to
being searched or arrested==:
"[Predictive policing algorithms are racist.
They need to be dismantled][rac]." *MIT Technology Review*, July 17, 2022.
Cathy O'Neil lays out the dangers of algorithmic decision-making and
gives many, many examples of what she means in *Weapons of Math
Destruction*.
[rac]:https://www.technologyreview.com/2020/07/17/1005396/predictive-policing-algorithms-racist-dismantled-machine-learning-bias-criminal-justice/

==research claiming mathematical proof that code fixes Facebook
proposed for its algorithms would inevitably worsen their effects==:
See
"[Emergent dynamics of extremes in a population driven by common
information sources and new social media algorithms][dyn]," N. F. Johnson et
al, *Scientific Reports*, 15 August, 2019. The abstract reads:
>We quantify how and when extreme subpopulations emerge in a model
society despite everyone having the same information and available
resources -- and show that counterintuitively these extremes will likely
be enhanced over time by new social media algorithms designed to reduce
division. We verify our analysis mathematically, and show it reproduces
(a) the time-dependent behavior observed in controlled experiments on
humans, (b) the findings of a recent study of online behavior by
Facebook concerning the impact of 'soft' and 'hard' news, (c) the
observed temporal emergence of extremes in U.S. House of Representatives
voting, and (d) the real-time emergence of a division in national
opinion during the ongoing peace process in Colombia. We uncover a novel
societal tipping point which is a 'ghost' of a nearby saddle-node
bifurcation from dynamical systems theory, and which provides a novel
policy opportunity for preventing extremes from emerging.
[dyn]:https://www.nature.com/articles/s41598-019-48412-w

==We need to understand that over time the logic of
recommendation engines is to narrow individual and collective scope==:
I
don't want to write these off as part of a balanced portfolio, however.
I use the Tidal streaming music service and frequently appreciate tips
from the algos—but only in conjunction with recommendations from
friends, newspapers and magazines, radio, playlists in cafes and so on.
On their own the algos would tend to narrow my listening. They can only
work on the basis of what I've responded to in the past.

==nutritional labelling on food (something the food industry
fought tooth and nail, lest we forget)==:
and still do. See the struggles
around identifying genetically modified foods, sugar etc.

###414
==We've seen Machine Learning programs do remarkable things
within closed systems (and also disturbing things, as per High Frequency
Trading on the stock market)==:
See my own "[Fast money: The battle
against the high frequency traders][fast]," *The Guardian* magazine, 7 June
2014, or (for more) Michael Lewis's book *Flash Boys*.
[fast]:https://www.theguardian.com/business/2014/jun/07/inside-murky-world-high-frequency-trading?ref=thebrowser.com

==Frances Haugen's eloquent testimony before Congress made plain
that Facebook had been grooming kids for monetization and knew it was
harming teenage girls==:
"[Here are 4 key points from the Facebook
whistleblower's testimony on Capitol Hill][hill]," *NPR*, October 5, 2021.
[hill]:https://www.npr.org/2021/10/05/1043377310/facebook-whistleblower-frances-haugen-congress

###415
==Even these could be a handful to manage==:
See Julian Dibbell, *My Tiny Life*, ibid.

==Most of the work I see coders doing on next-generation social
networks resembles these first iterations==:
One I especially enjoyed
exploring while making the book was Scuttlebutt, whose Rubyite
proprietor, Rabble, is one of the smartest and most colorful people I
spent time with. He disapproves of Python, thinking it way too
restrictive. Nicholas still harbors a yen to flesh out TextSmith, too.

==a lecturer named Nir Eyal taught a course on "behavioral
engineering" at Stanford==:
"[The professor who wrote the book on making
addictive technology is having second thoughts][nir]," *CNBC*, January 30, 2013. *Oh, really?*
[nir]:https://www.cnbc.com/2018/01/30/nir-eyal-addictive-design-expert-says-tech-industry-needs-new-ethics.html
