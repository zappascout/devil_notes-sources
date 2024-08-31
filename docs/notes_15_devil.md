#**CHAPTER 15**
##**"A Codemy of Errors"**
###p. 302
==Such a function might look as follows in Sonic Pi/Ruby==:
For anyone interested in going a little deeper, here is the Sonic Pi/Ruby
code explained:
```ruby
define :playseq do \|notes, durations\|

notes.zip(durations).each do \|n,d\|

play n

sleep d

end

end
```
In the first line we define the function "playseq" and initialize it (i.e. *activate it*)
with a "do" call. The words "notes" and "durations" appear between
goalposts at the end of this line to tell the Ruby interpreter (and us)
to expect values for these two parameters whenever the function is
called—in other words, *these are the things we will be working with*.
Now (line two) we take notes from an as yet unspecified "notes" array
and zip() them to corresponding durations from a "durations" array,
appending the ".each" method to tell Sonic Pi we want to step through
each note-duration pair in sequence: between goalposts at the end of
this line, we inform the interpreter we will be referring to individual
items in the "notes" array as "n" and in the "durations" array as "d".
Finally, in lines three and four we tell Sonic Pi to play each note (n)
with the duration (d) we've just zipped to it. The ".each" method in the
previous line ensures this happens for each pair of items consecutively
until there are none left to play. Functions such as this are sometimes
referred to as "subroutines" or "procedures"—and you can see why.

For the record, something similar in Python would look like the below,
substituting a print function for play and sleep commands, which
obviously have no use in a non-musical language. This function will zip
notes to intended durations then print each pair in sequence, within the *for* loop.
```python
def playseq(notes, durations):

lead_bass = zip(notes, durations)

for full_note in lead_bass:

    print(full_note)
```
###303
==Ruby code is handsome, I think==:
Its creator, Yukihiro Matsumoto (or "Matz" to Rubyites) claims to have been motivated by twin
dislikes of Perl, which "had the smell of a toy language," and Python,
which he considered an object-oriented paradigm imposter. see The Ruby
Language FAQ, [*What is the History of Ruby?*][toy] Intriguingly, in an [ACM
Turing Award lecture from 2003][kay], Alan Kay, generally regarded as the
creator of Object Oriented Programming, appears to feel that his idea
has never been completely realized, presumably even by Ruby.
[toy]:https://www.ruby-lang.org/en/documentation/faq/1/
[kay]:https://www.youtube.com/watch?v=ymF94cFfzUQ&list=PLn0nrSd4xjjYCkOxtYqozyDuwt-4sC2L6&index=16

###304
==the opening of whose *Tenebrae Responsoria* comprises eight of
the most beautiful bars of music I have ever heard==:
Especially as sung by The Hilliard Ensemble on their ECM album *Tenebrae*. This has long
been a go-to album for mornings when I'm writing. For anyone interested,
others that flavored this book were Brian Eno's *Top Boy* soundtrack,
along with his "thinking music" records *Reflections* and *Lux*, plus
his and brother Roger's lush *Mixing Colors*; Plaid's *Reachy Prints*;
Autechre's *Sign*; The Hilliard Ensemble's Bach/Webern mashup,
*Ricercar*; John Coltrane's *Live at the Village Vanguard*; Charles
Mingus's *Mingus Ah Um* and *The Black Saint and the Sinner Lady*; Vijay
Iyer's *Break Stuff*; Nils Frahm's *All Melody*. Would these therefore
enhance the reading of the book they flavored? I'd be interested to know
the results of any experiments in this regard!

==its own discrete coding environment==:
Typically this is known as an *Integrated Development* Environment, or IDE, basically an editor
with bells on, that can only be used with its own domain specific language (DSL.)

###308
==Consult venv documentation and watch helpful YouTube tutorial==:
[This one][corey] from an estimable collection by Corey Shafer.
[corey]:https://www.youtube.com/user/schafer5

###312
==what I like about Atom==:
Alas, Atom is also doomed. In 2022 GitHub announced it would no longer develop or support it—one
thing new coders have to get used to is their favorite tools being
deemed obsolete by the people who made them. Atom's fate was probably
sealed by the wild success of the brilliant VS Code editor, which is
also open source and maintained by Microsoft (GitHub is owned by
Microsoft.)
