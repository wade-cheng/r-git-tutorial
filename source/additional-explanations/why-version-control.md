# Why Version Control?

We will motivate this answer in the context of code collaboration.

There are some possible solutions to collaborating on code. You can simply email
or message your collaborators with any new code, and they can do so as well when
they make any changes. This has problems because everyone has to make sure to
keep their code updated with what others have sent. People are very liable to
making human errors.

Well, manually keeping track of all collaboration seems like a hassle, so what
if we go to the other extreme? Imagine an RStudio built like Google Docs, where
you can invite collaborators to edit in real time. This is great for ease of
use---all your collaborators can code with no changes to their familiar RStudio
workflows. But consider this scenario: you're tweaking some code to give a graph
axis labels. You've done this a thousand times before. But egads! Somehow,
RStudio complains about some inscutable error... It turns out your coworker was
editing at the same time as you, and some parenthesis was unclosed or something
at the time of you declaring "run all this code." Now what? Should you wait
until they're finished to run your code, and then have them wait while you're
editing?

```{note}
Well, you could both take care to work in your own designated code blocks. Then
any errors would be sandboxed within each block. This actually sounds quite nice
for small scale collaboration with little intermingling. Too bad Posit Cloud's
collaborative editing is locked behind a
[paywall](https://docs.posit.co/cloud/guide/accounts/#beta-features).
```
