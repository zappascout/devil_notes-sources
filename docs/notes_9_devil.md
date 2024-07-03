#**CHAPTER 9**
##**"Catch 32"**
###159
==a friend of a friend who is in his early 20s . . . does an
inspired job==:
And his name was Jack Greenberg

###162
==I was long puzzled that the word "argument" should be employed
for this purpose==:
For lovers of the long grass, there's a [delightful etymological discussion][stackex] on StackExchange.
[stackex]:https://softwareengineering.stackexchange.com/questions/186293/why-are-actual-parameters-called-arguments

###165
==In British English, where "git" is synonymous with "asshole"==:
Torvalds was perfectly well aware of this useage. In the FAQ section of
the Linux kernel site, he is quoted as having said "[I'm an egotistical
bastard][torv1], and I name all my projects after myself. First 'Linux', [now
'Git][torv2].'"
[torv1]:https://git.wiki.kernel.org/index.php/GitFaq
[torv2]:https://git.wiki.kernel.org/index.php/GitFaq#Why_the_.27Git.27_name.3F

==until 2018 Linux developers had not a Code of Conduct, but of a
Code of *Conflict*==:
For a decent account of Torvald's (perhaps former?) attitude to his work, reputation and community, see "[Linus
Torvalds Defends His Right to Shame Linux Kernel Developers][shame]," from
*ArsTechnnica* in 2013. The piece is subheaded "'My culture is
cursing: Linux kernel world is a hostile place—by design"
[shame]:https://arstechnica.com/information-technology/2013/07/linus-torvalds-defends-his-right-to-shame-linux-kernel-developers/

==the day was saved by a women's tutorial site called Women
2.0==:
The tutorial that helped me, "[Git 101: Git and GitHub for
beginners][talk]," was from an excellent 2016 talk by Meghan Nelson, then a
software engineer at HubSpot.
[talk]:https://women2.com/2016/02/09/20160209git-101-for-beginners

###166
==At the end of 2022, site administrators claimed more than
eighty million users==:
This from a February 2020 [company blog][blog]. Not only is this a big number, it is almost double the corresponding
figure from just 15 months earlier. The 100m repo milestone was reached
in November 2018 according to another official [GitHub blog][gitblog]. At that point new repos
were being created every 1.6 seconds, three-fifths of them outside the
US.
[blog]:https://github.blog/2021-02-03-fighting-for-developers-github-policy-2020-in-review/
[gitblog]:https://github.blog/2018-11-08-100M-repos/

==John Conway's thrilling evolution simulator, *Game of Life*==:
*Wikipedia*'s "Conway's Game of Life" page is decent on this, but the
 site is immense fun, inviting you to [make your own cellular automata][cell]. This is what the web was made for.
[cell]:https://playgameoflife.com

==ending—deliriously—with the assembly language source code
for the Apollo 11 lunar module==:
This was posted to GitHub as recently as 2016. Apollo fans
may further enjoy the ABC New piece, "[Apollo 11's Source Code Has Tons
of Easter Eggs, Including an Ignition File Titled 'Burn Baby Burn:
There are jokes, Shakespeare quotes and a reference to the Black Power
movement][burn]."
[burn]:https://abcnews.go.com/Technology/apollo-11s-source-code-tons-easter-eggs-including/story?id=4051522

==GitHub remained the rare example of a high-profile American
website that almost never got hacked==:
Which said, on occasion hackers have targeted GitHub pages inconvenient to the Chinese government with
denial-of-service attacks. "[How Will Microsoft Handle GitHub's
Controversial Code?][ms]," *Wired*, 2 June, 2018
[ms]:https://www.wired.com/story/microsoft-github-code-moderation

==the assembly language source code for the Apollo 11 lunar
module==:
Even an untrained eye can recognize the caution baked into
*Burn Baby Burn*, the program designed to ignite the lunar lander rocket
and shoot Armstrong and Aldrin back into space from the surface of the
moon, from the number of Boolean "flags" used to confirm the program's
correct running at critical points. To give a sense of what this looks
like, here's a portion of the Assembly-like code for *Burn Baby Burn*:
```Assembly
COMFAIL TC UPFLAG \# (15)

ADRES IDLEFLAG

TC UPFLAG \# SET FLAG TO SUPPRESS CONFLICTING DISPLAY

ADRES FLUNDISP

CAF FOUR \# RESET DVMON

TS DVCNTR

CCS PHASE6 \# CLOCKTASK ACTIVE?

TCF +3 \# YES

TC BANKCALL \# OTHERWISE, START IT UP

CADR STCLOK1

+3 CS VB97DEX

TS DISPDEX

TC PHASCHNG \# TURN OFF GROUP 4.

OCT 00004

TCF ENDOFJOB

COMFAIL1 INDEX WHICH

TCF 2

COMFAIL3 CA Z \# (15) KILL CLOKTASK USING Z

TCF +2

COMFAIL4 CS CNTDNDEX

TS DISPDEX

TC DOWNFLAG \# RECONNECT DV MONITOR

ADRES IDLEFLAG

TC DOWNFLAG \# PERMIT GUIDANCE LOOP DISPLAYS

ADRES FLUNDISP

TCF ENDOFJOB

COMFAIL2 TC PHASCHNG \# KILL ZOOM RESTART PROTECTION

OCT 00003

INHINT

TC KILLTASK \# KILL ZOOM IN CASE IT'S STILL TO COME

CADR ZOOM

TC IBNKCALL \# COMMAND ENGINE OFF

CADR ENGINOF4

TC UPFLAG \# SET THE DRIFT BIT FOR THE DAP.

ADRES DRIFTDFL

\# Page 743

TC INVFLAG \# USE OTHER RCS SYSTEM

ADRES AORBTFLG

TC UPFLAG \# TURN ON ULLAGE

ADRES ULLAGFLG

CAF BIT1

INHINT

TC TWIDDLE

ADRES TIG-5

TCF ENDOFJOB
```
###167
==Larry Ellison of software giant Oracle is reported to have deemed the open—source movement "un-American"==:
Of course, Ellison's idea of "un-American" must be seen in the context of his hosting of
fundraiser for Donald Trump in 2020. See "[Trump to visit Palm Springs
area next week for fundraising event at Oracle chairman Larry Ellison's
estate][larry]," *Desert Sun*, February 13, 2020; or "[Larry Ellison is doing an
unthinkable thing for a tech titan: Hosting a fundraiser for Donald
Trump: It's the most significant endorsement that Trump has gotten from
a Silicon Valley leader][trump]," *Vox*, February 12, 2020.
[larry]:https://www.desertsun.com/story/news/politics/2020/02/12
[trump]:https://www.vox.com/recode/2020/2/12/21135722/larry-ellison-donald-trump-endorsement-fundraiser

==Steve Ballmer branded Linus Torvalds's talismanic open-source
operating system Linux communist==:
Fifteen years later, in 2016, [Reuters reported him as having softened his position][reuters]. According to a [GitHub blog][gith] at the end of 2018, the company's open source VS Code editor by then
had taken contributions from more developers than any other project,
with a whopping 19,000. And it is a terrific editor.
[reuters]:https://www.reuters.com/article/us-microsoft-ballmer-linux-idUSKCN0WC2RA
[gith]:https://github.blog/2018-11-08-100M-repos

==Tim O'Reilly, a thoughtful denizen of the democratic left==:
For a taste of O'Reilly's political coordinates, there's an
interesting interview with Professor David Runciman at Cambridge
University, discussing the "[WTF economy][wtf]" (and yes, that does stand for
what you think it does).
[wtf]:https://play.acast.com/s/talkingpolitics/timoreillyandthewtfeconom

==Eric S. Raymond . . . an activist of the ornery, gun-rightsy,
\#me-too-bashing libertarian right==:
Where to start here? An amusing *Verge* report on a progressive techy political campaign called The
Great Slate details one of the organization's most successful
fundraising techniques, as follows:
>["I've been torturing Twitter with lurid Eric S. Raymond quotes for years][torture]," says security engineer and
Great Slate activist Thomas Ptacek. "Every time I do, 20 people beg me
to stop.' So Ptacek held his followers hostage: pay up, or the ESR
quotes would keep coming. It's estimated that Ptacek has driven
somewhere around \$30,000, just by threatening to post eye-searing
screencaps."
[torture]:https://www.theverge.com/2018/3/8/17092684/great-slate-fundraising-congressional-campaign

###170
==Mrs Perkins' sin-squelching armor==:
Or "sin-squelching *amour* armor," as Nicholas dubbed it.

###172
==the prodigious "pair programming" team of Jeff Dean and Sanjay
Ghemawat==:
See "[The Friendship That Made Google Huge: Coding together at the same computer, Jeff Dean and Sanjay Ghemawat changed the course of the company—and the Internet][dean]"*, The New Yorker*, December 3, 2018
[dean]:https://www.newyorker.com/magazine/2018/12/10/the-friendship-that-made-google-hu

==Page and his fellow doctoral student business partner Sergey
Brin were the sons of academics==:
Useful accounts of Page and Brin's drift into search are to be found in *The Four: The Hidden DNA of
Amazon, Apple, Facebook, and Google* by Scott Galloway and *World
Without Mind: The Existential Threat of Big Tech,* by Franklin Foer.

###174
==an excoriating report by the US House of Representatives==:
*[Investigation of Competition in Digital Markets][reps]: Majority Staff Report
and Recommendations, Subcommittee on Antitrust, Commercial and
Administrative Law of the Committee on the Judiciary*, published in 2020.
[reps]:https://www.nytimes.com/interactive/2020/10/06/technology/house-antitrust-report-big-tech.html

==a "dearth of startups, declining job creation, falling
demand"==:
The *New York Times* review of Foroohar's *Don't Be Evil*
notes that:
>Big tech lobbyists have helped to bring about an overhaul in
the American patent system, which makes patents harder to secure and
harder to defend—especially for companies without huge legal and
lobbying power. That means that there's less incentive for small tech
businesses to innovate and for venture capitalists to invest in them:
why bother if a tech giant will immediately muscle in on your idea? The
result is a decline in innovation that may prove dangerous to the future
of the American economy. That's not to mention the dearth of startups,
declining job creation, falling demand' and other consequences of the
monopolistic business model.

==Even previous free market fundamentalists==:
See "[Once Tech's Favorite Economist, Now a Thorn in its Side][thorn]," *New York Times*, May 20,
2021.
[thorn]:https://www.nytimes.com/2021/05/20/technology/tech-antitrust-paul-romer.html

==even this minimal consolation is disappearing==:
see *Forbes*, 1 March, 2021, "This Software Giant Declared War On Amazon. Will Other
Open Source Companies Follow?"

###175
==open-source software cast itself like a spell into this gap==:
The neutral terms "FOSS" and "FLOSS" are sometimes used to cover free
*and* open source software.

==Stallman took the "hacker ethic" to heart==:
For more detail, see Levy, *Hackers* (p. 437-9)

###176
=="in some ways I feel I ought to be dead"==:
Difficult as Stallman clearly is, it would take a person with the heart of a . . . well, a
Stalllman, to withhold empathy from the next few sentences he spoke to
Levy in *Hackers* (p. 472):
>"I certainly wished I had killed myself when I was born," he
began, before reconsidering. "In terms of effect on the world, it's
very good that I've lived. And so I guess, if I could go back in time
and prevent my birth, I wouldn't do it. But I sure wish I hadn't had
so much pain."

==By his own account, RMS has spent most of his life in pain==:
Nicholas likens Richard Stallman to Beethoven, a generous analogy that I
like.

###178
==less fanfare than the contemporaneous introduction of small
plastic balls into cans of "draught" Guinness==:
Which won the Queen's Award for Technological Achievement that same year. Internet
schminternet.

==The Linux community seemed to resemble a great babbling
bazaar==:
Eric S. Raymond, *The Cathedral and the Bazaar: Musings on
Linux and Open Source by an Accidental Revolutionary* (p. p21)

==the contemporaneous introduction of small plastic balls into
cans of "draught" Guinness==:
Which, and this is true, won the Queen's Award for Technological Achievement that year (1991.) Internet
schminternet. [*The History of Guinness: Our Story*][balls]
[balls]:https://www.guinness.com/en-my/our-story

###179
==Linux, like the web itself, looked like a utopian revelation==:
Programmers loved Linux then and still do now. The first I heard of it
was from one of the other dads at my kids' Junior School in Brixton,
South London, in 1997 or so. He wore a Lenin beard and round Mao specs
and I used to joke that no matter how politically left a position anyone
in his orbit took on a given issue, he always managed to find one to the
left of it, until, like a schooner sailing off the western edge of a
map, it would end up in the East and seem weirdly conservative. I still
remember the day he came in raving about this new thing called Linux,
which would undermine the corporate overlords at Microsoft and Apple and
return computing to the masses . . .
    And of course I had no idea what he was talking about. The most
enthusiastic early inhabitants of cyberspace and the PC revolution in
the UK were the self-styled "Zippies," or "hippies with computers," of
the club scene: one of the earliest pieces of writing I did for a
national newspaper was about the first public demonstration of the
internet at Megatripolis, the weekly trance-techno night at the Heaven
nightclub in Charing Cross, where the sixties acid guru Timothy Leary,
still banned from entering the UK in person, appeared through the wires
from LA. It was a stilted conversation, because getting and maintaining
a modem connection had taken so long and been so arduous that nobody had
time to consider the content or purpose of the subsequent exchange. Like
many people I knew on that scene, I had my PCs custom built by ravers
associated with sound systems such as The Black Dog and Spiral Tribe, at
a fraction the cost of commercial machines—and with MS-DOS and then
Windows (both possibly pirated) preinstalled. We didn't like Apple,
because their's was a closed system, with expensive proprietorial
software that was hard to modify. Either way, I saw no need for Linux
and thought its leftier-than-thou evangelist crazy. How I wish I'd
listened: he was trying to tell me something interesting, which might
also have alerted me to the wonderland of code. Sigh.

==proof that a better world was possible—even inevitable==:
*Wired* magazine under founding editor Kevin Kelly was comically bullish
in this regard, as witness the strapline from a January 1997 cover story
headed "[The Long Boom: A History of the Future, 1980--2020][boom]," which
elaborated, "We're facing 25 years of prosperity, freedom, and a
better environment for the whole world. You got a problem with that?"
AI and crypto jockeys beware.
[boom]:https://www.wired.com/1997/07/longboom

==the company's present executive vice president of culture and
experience==:
After almost seven years at Stack Overflow, Hanlon moved
to a company called Process Street.

==the New York office of Jay Hanlon==:
Like so much else in the city, Gotham tech has been drifting over the East River into Brooklyn,
but I find Stack Overflow hanging on in Manhattan, working hard to bring
techie quirk to one of the world's least quirky generic
environments—the 28^th^ floor of a midtown office block. "It gets a
little toasty in here," Hanlon grinned as he adjusted a fan by his
desk, noting that when the office fittings rulebook was being dispatched
in a fit of disruption upon the company's arrival, someone wondered why
those square-assed analog jockeys of the past had never noticed you
could fit more rooms into a space if you made them hexagonal, only to
learn the poor dead saps probably had but didn't do it because it turns
out to be a terrible, terrible idea. Now we know.

###181
==The Yahoo Answers problem==:
Hanlon gives an amusing example of how easy it is to fall into this trap.
>Say someone comes to us and says "I got this problem with my code, what do I do?" Great:
we can answer that. And they come back again and say, "Thanks, now
should I do this with Python?" We'd be like, "OK, that's a little
broad, but I guess for your problem, probably Python." And then they
come again and say, "Thanks again, but you know, when I'm coding, my
back hurts, so what's a good chair for programming . . . ?" And
suddenly you've got a discussion on Herman Miller chairs. And
eventually what you get to is "I get sort of hungry when I'm coding,
and I've been making pancakes, but I'm not sure they give me enough
energy, is there a better recipe for pancakes?" Then 'My cat walked
through the pancakes—how do you get syrup out of cat hair?" And
pretty soon you're not a programming site anymore.

==this does not necessarily make oxytocin *moral*==:
like a lot of people, I was enchanted by Paul J. Zak's book *The Moral Molecule:
The New Science of What Makes Us Good or Evil* when it was published in
2013, and still think it's important. The deepening science paints a
more complex and nuanced picture of its actions, however. The science
writer Ed Yong summed up some of the issues in "[The Weak Science Behind
the Wrongly Named Moral Molecule][yong]: No matter what all the articles,
books, and TED talks say, Oxytocin isn't a hug hormone'" as far back
as 2015 in *The Atlantic*.
[yong]:https://www.theatlantic.com/science/archive/2015/11/the-weak-science-of-the-wrongly-named-moral-molecule/415581/

###182
==withering slapdowns==:
Asking your first question *is* terrifying. A part of me would miss this as a rite, in much the way
being served by a polite waiter in a Parisian café would be both
pleasant and little disappointing. Happily, I've never heard of this
happening. Someone has to be responsible for character building across
the general population.
