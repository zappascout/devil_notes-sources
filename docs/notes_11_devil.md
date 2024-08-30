#**CHAPTER 11**
##**"The Gun on the Mantelpiece"**
###p. 215
Code looks so much better in its natural habitat, color-coded and onscreen. Here are the three versions of the Shakespearian Insult Engine in this much happier environment, from least to most sophisticated. I hope soon to have them runnable using a new offshoot of Python called "PyScript", which (like JavaScript) can run in a web browser—a big deal in the coding world. PyScript, incidentally, is the project Nicholas Tollervey now works on at Anaconda. A pleasing symmetry.
```Python
from random import choice

adjA = [
    "mammering",
    "saucy",
    "beslubbering",
    "spleeny",
    "yeasty",
    "mewling"
]
adjB = [
    "rump-fed",
    "plume-plucked",
    "onioneyed",
    "clay-brained",
    "beetle-headed",
]
noun = [
    "bugbear",
    "flap-dragon",
    "hedgepig",
    "joithead",
    "lewdster",
    "moldwarp",
]

word1 = choice(adjA)
word2 = choice(adjB)
word3 = choice(noun)
insult = f"{word1} {word2} {word3}"
print(insult)
```  

```Python  
from random import choice

adjA = [
    "mammering",
    "saucy",
    "beslubbering",
    "spleeny",
    "yeasty",
    "mewling"
]
adjB = [
    "rump-fed",
    "plume-plucked",
    "onioneyed",
    "clay-brained",
    "beetle-headed",
]
noun = [
    "bugbear",
    "flap-dragon",
    "hedge-pig",
    "joithead",
    "lewdster",
    "moldwarp",
]

print(f"{choice(adjA)} {choice(adjB)} {choice(noun)}!")
```  

```Python
from random import choice

adjA = [
    "paunchy",
    "reeky",
    "lumpish",
    "rank",
    "goatish",
    "surly"
]
adjB = [
    "tickle-brained",
    "weather-beaten",
    "sheep-biting",
    "swag-bellied"
]
noun = [
    "codpiece",
    "puttock",
    "minnow",
    "maggot-pie",
    "pie-face",
    "varlot"
]


def insult_engine():
    bardish_insult_bank = []
    for i in range(100):
        insult_i = f"{choice(adjA)} {choice(adjB)} {choice(noun)}!"
        if insult_i not in bardish_insult_bank:
            bardish_insult_bank.append(insult_i)
    next_action = input("Generate a Bardish insult? (y/n): ")
    while next_action == "y":
        print(f"\n{bardish_insult_bank.pop(0)}")
        next_action = input("\nPrithy another? (y/n): ")
    else:
        return f"\nFarewell, thou {bardish_insult_bank[0]}\n"


insult_engine()
```  

###223
==Finally, in line 38 we *call* the function, causing it to run==:
Download the Mu editor (my suggestion because it's free and so
immediate and easy to use, but there are plenty of alternatives) and run the Insult Engine at your leisure. If you're feeling adventurous, substitute the six-word lists of adjectives and nouns above with the full 40-word lists given below. Props to the British Library for maintaining these.
```Python
adjA = ['mammering', 'saucy', 'beslubbering', 'spleeny', 'yeasty', 'artless', 'bawdy', 'bootless', 'churlish', 'cockered', 'clouted', 'craven', 'currish', 'dankish', 'dissembling', 'droning', 'errant', 'fawning', 'fobbing', 'froward', 'frothy', 'gleeking', 'goatish', 'gorbellied', 'impertinent', 'infectious', 'jarring', 'loggerheaded', 'lumpish', 'mangled', 'mewling', 'paunchy', 'pribbling', 'puking', 'puny', 'qualling', 'rank', 'reeky', 'roguish', 'ruttish', 'spleeny', 'spongy', 'surly', 'tottering', 'unmuzzled', 'vain', 'venomed', 'villainous', 'warped', 'wayward', 'weedy']
adjB = ['rump-fed', 'plume-plucked', 'base-court', 'bat-fouling', 'beef-witted','onion-eyed', 'flap-mouthed', 'beetle-headed', 'boil-brained', 'clapper-clawed', 'clay-brained', 'common-kissing', 'crook-pated', 'dismal-dreaming', 'dizzy-eyed', 'doghearted', 'dread-bolted', 'earth-vexing', 'elf-skinned', 'fat-kidneyed', 'fen-sucked', 'fly-bitten', 'folly-fallen', 'fool-born', 'full-gorged', 'guts-griping', 'half-faced', 'hasty-witted', 'hedge-born', 'hell-hated', 'idle-headed', 'ill-breeding', 'ill-nurtured', 'knotty-pated', 'milk-livered', 'motley-minded', 'pottle-deep', 'pox-marked', 'reeling-ripe', 'rough-hewn', 'rude-growing', 'shard-born', 'sheep-biting', 'spur-galled', 'swag-bellied', 'tardy-gated', 'tickle-brained', 'toad-spotted', 'unchin-snouted', 'weather-bitten']
noun = ['clotpole', 'flap-dragon', 'gudgeon', 'hedge-pig', 'malt-worm', 'apple-john', 'baggage', 'barnacle', 'bladder', 'boar-pig', 'bugbear', 'bum-bailey', 'canker-blossom', 'clack-dish', 'coxcomb', 'codpiece', 'death-token', 'dewberry', 'flaxwench', 'flirt-gill', 'foot-licker', 'fustilarian', 'giglet', 'haggard', 'harpy', 'horn-beast', 'hugger-mugger', 'joithead', 'lewdster', 'lout', 'maggot-pie', 'mammet', 'measle', 'minnow', 'miscreant', 'moldwarp', 'mumble-news', 'nut-hook', 'pigeon-egg', 'pignut', 'puttock', 'pumpion', 'ratsbane', 'scut', 'skainsmate', 'strumpet', 'varlot', 'vassal', 'whey-face', 'wagtail']
```

###227
==no language is an island and there are things to worry about
here, too==:
Not that the outside world is giving us a free pass.
Shortly before conference, there was a media story about an abrupt leap
in demand for university computer science (CS) courses, at the same time
the industry was sucking up actual and would-be teachers.
In reaction to the increased demand, colleges would start offering CS places
only to those accepted them in advance of arrival, a move some academics
considered likely to disadvantage already underrepresented groups—who are
less likely to have taken CS in high school. See *The New York Times*,
"[The Hard Part of Computer Science? Getting Into Class][compsci]."
[compsci]:https://www.nytimes.com/2019/01/24/technology/computer-science-courses-college.html

###228
=="I am extremely proud to work at Facebook"==:
I'll watch a similar display when an "evangelist" from Microsoft tells the
conference, "People always ask, 'Why is Microsoft here at the Python
conference?' the answer is because we love developers. We love you.
Your code will change the world. Because of your code, some people
around the world get to eat. Because of your code, we know what black
holes look like..." The assertion, "You're changing the world," is
made half a dozen-plus times in five minutes, always with breathless
approval. And it's true, many people in this room do wonderful things
with code. Others compromise elections by providing platforms for
misinformation, refine facial recognition technology for use by
totalitarians, write bias-reinforcing software that lends special
interests a cloak of bogus objectivity—to the point where software is
both miraculous enabler and existential threat. But there is no mention
of any threat here, in what amounts to a giant collective self-delusion. I
re-enter the conference hall feeling bereft, leaf through the
recruitment leaflets in my swag bag and find the parade of boasts about
"Making the world a better place," most of them specious at best. Even
at the most trivial level I find myself wondering, "Have none of these
people seen *Silicon Valley*?"

###229
==the controversial Python Enhancement Proposal (or PEP)
admitting the Walrus Operator into the language==:
It may be hard for non-programmers to understand how something so small could cause so much
trouble. As explained earlier, "operator" is the term for a symbol that performs an operation: the plus sign (+) and minus sign (-) are operators, as is the asterisk used to denote multiplication. In computing the "equals"
symbol is known as the "assignment operator" because we use it to
*assign* values to variables, as in x = 7, while "is equal to/the same as" is denoted by two standard equals signs together (==). The "Walrus Operator" gets its colloquial moniker not, per Lewis Carroll, from a penchant for
oysters, but from its appearance (:=). Technically known as the
"assignment expression," its function is a little obscure and I'm not
sure I would have voted for its adoption. I do trust that Guido knows
better than me, though, and that this is not a matter of life and death, unlike a vociferous minority of Pythonistas. More on the Walrus Operator controversy [here][wal]
[wal]:https://www.youtube.com/watch?v=KN2TTiGpDvM&t=13s

###232
==anything new will change your brain==:
"[The Knowledge][know]" is a 150-year-old process by which would-be London cabbies memorizes the name and
location of every street within a six-mile radius of Charing Cross in
the center of London—sadly now a little compromised by satnav. More recently researchers
writing in the journal *Nature Human Behaviour* claim to have found a
"Pokemon region" of the brain in adults who played with Pokemon cards
as children ("[A Pokémon-sized window into the human brain][poke]," 6 May, 2019.)
[know]:https://tfl.gov.uk/info-for/taxis-and-private-hire/licensing/learn-the-knowledge-of-london
[poke]:https://www.nature.com/articles/s41562-019-0594-6

###233
==seeing images of my own brain==:
with software Janet's colleague Norman Pietek pointed me to—MeshLab, written in C++ and JavaScript, it
turns out.

==our brains, minds, selves can only be understood with reference to the gut, nervous system, internet, everything==:
for more on this idea see Dan Siegel, *Mind: A Journey to the Heart of Being
Human*; or "[Scientists Say Your 'Mind' Isn't Confined to Your Brain, or
Even Your Body][mind]" by Olivia Goldhill, in one of my favorite science
journals, *Quartz*. Goldhill quotes Siegel saying: "I
realized if someone asked me to define the shoreline but insisted, is it
the water or the sand, I would have to say the shore is both sand and
sea. You can't limit our understanding of the coastline to insist it's
one or the other. I started thinking, maybe the mind is like the
coastline—some inner and inter process. Mental life for an
anthropologist or sociologist is profoundly social. Your thoughts,
feelings, memories, attention, what you experience in this subjective
world is part of mind." Her piece is very worth reading for anyone
interested in understanding themselves and the people they know.
Goldhill ends on this note:
>Siegel says he wrote his book now because he sees so much misery in
society, and he believes this is partly shaped by how we perceive our
own minds. He talks of doing research in Namibia, where people he spoke
to attributed their happiness to a sense of belonging. When Siegel was
asked in return whether he belonged in America, his answer was less
upbeat: "I thought how isolated we all are and how disconnected we
feel," he says. "In our modern society we have this belief that mind
is brain activity and this means the self, which comes from the mind, is
separate and we don't really belong. But we're all part of each others'
lives. The mind is not just brain activity. When we realize it's this
relational process, there's this huge shift in this sense of
belonging."
[mind]:https://qz.com/866352/scientists-say-your-mind-isnt-confined-to-your-brain-or-even-your-body