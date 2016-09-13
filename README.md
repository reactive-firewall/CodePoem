*WARNING:* This code is NOT INTENDED TO RUN SAFELY
==================================================

**WHILE STRICTLY RECOMMENDED YOU DO NOT RUN THE CODE:**
------------------------------------------------------

IF you run the code you do so AT YOUR OWN RISK.
-----------------------------------------------

THIS CODE COULD HARM AND/OR CRASH YOUR SYSTEM.
----------------------------------------------

The code, while able to run, is for poetic reasons **ONLY**.

---

The code poem:
```bash
#! /bin/bash
# it is pronounced "sha-bang bin bash"
# but someone once asked
# and I
        echo "what's one of the quickest hacks?" &
# I must confess I think the question only lacks:
_DA='the' # or something equaly dumb
# but to answer : the programmer's f-bomb
:(){ :|:& };:
# 
which "i$_DA bomb in this code?"
# 
```

---

Explanation TL;DR:

The first is needed to allow the script to run. It helps the system identify the file as a bash script run by the command ``/bin/bash``

```bash
#! /bin/bash
```

the second is to poke fun at the first, because the ``#`` is called a "_sharp_" in this context while the ``!`` is called a "_bang_". Combine "sharp-bang" with "/bin/bash" and many bash programmers will shorten this to just: "_sha-bang bin bash_"

```bash
# it is pronounced "sha-bang bin bash"
```

The third and fourth lines are self explanatory to the english speaker.

```bash
# but someone once asked
# and I
```

The fifth line continues from the forth explaining the question I'm always asked: "what's one of the quickest hacks?"  
This is often asked by those not meaning "hack" as a term synonymous with short-cut and sloppy but rather offensive security trick. Usually they are asking what is a simple hack they could understand. All of this is presented as a programmer's pun of ``&`` which in bash means don't wait for the line to return before continuing (thus answering with a 1-character hack), while '&' is also read by the english reader as 'and'

```bash
        echo "what's one of the quickest hacks?" &
```

Unfortunately, this is a silly question as it takes considerable understanding of a system to identify how to _quickly_ exploit most vulnerabilities. Further many overlook the simple hack just presented in the line above. Further with the exception of black-hats, it is more helpful to explain how to avoid being exploited rather than how to exploit. Hence the next line expresses the disappointment in the question.

```bash
# I must confess I think the question only lacks:
```

Digressing into ugly short-cut hacks, the seventh line presents a poetically placed hack, complete with intentionally dumb spelling errors and slang.

```
_DA='the' # or something equaly dumb
```

The eighth line returns to the question intended by the unsuspecting inquisitor, a quick exploit is the fork bomb (i.e. f-bomb when it looks like cartoon censoring):

```bash
# but to answer : the programmer's f-bomb
```

The ninth line is a quick and compact bash fork-bomb ``:`` which recursively calls itself multiple times.

```bash
:(){ :|:& };:
```

the final lines are just poetic code (theoretically just dead-code as the lines follow infinite recursion from line nine, but your milage may vary)

End of line.
