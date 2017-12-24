Hannes Tautschnig
=================
> _"Sie werden sich noch wundern, was alles gehen wird."_

☏ +43 699 001 02 03
# Primär

~~~~~~~
loop
start
:goto loop
~~~~~~~
Brought to you by the aforementioned person with kind help of:
1. <https://www.markdowntutorial.com>  
Wirkt ganz vernünftig das Tutorial

2. <https://daringfireball.net/projects/markdown>
oder doch in der gleichen Zeile, a wenn ich des Tutorial halt einfach wirklich nicht benutzt hab..

Darfs a kleine Linie sein?  
Just take care not to write directly above the line, 'cause then it'll be intepreted as a 2nd level heading.

---

![Hannes Tautschnig](me/avatar.jpg)

---

I just read header one as well as [Überschrift No. 6](#6-tär) should generally be used _rather_ rarely (Source: [Tutorial von **GitHub**, Lesson 2](https://www.markdowntutorial.com/lesson/2/)). 
Ist aber auch relativ verständlich wenn ich mir so die Darstellung anschaue.

Sekündäre Überschrift
---------------------
Auf `echo hallo` sagt die bash `hallo`

## Eigentlich auch Sekundär
Text
```
# code block
print '3 backticks or'
print 'indent 4 spaces'
``` 
### Links
[a relative link to ma README.md](README.md)  
working nicely!
#### Quartiär
##### Quintär

###### 6-tär

_Text_  
*gleicher Text*  
**ähnlicher Text**  
__theoretisch wieder gleicher Text__

<a name="sprich"></a>
Sprich:
* Ein _ bzw. * entspricht \em{}
* Zwei __ oder ** entsprechen \bf{}
  * Und beides kombiniert schaut überhaupt krass aus: __*SIIIIICK*__ geht aber auch mit 3 _ - ___YO!___

Merke: Double Space  
am Ende der Zeile  
macht einen Umbruch aus!

Lol: Upon comparison of the Eclipse-integrated markdown-renderer and the actual on [GitHub][gh] hosted page, I even noticed a possible flaw/bug inside the Eclipse-part. :D 
Aus **__ und umgekehrt natürlich auch wieder wird in Eclipse nur bold font, auf [GitHub][gh] im Gegensatz stell's des Ganze eigentlich richtig dar: mit den _ als bold und nur die * über Markdown verwandelt.

Und was auch gerade erst aufgefallen ist: In Eclipse werden die Links ziemlich weit oben ohne Probleme als solche erkannt, auf [GitHub][gh] nicht, also zumindest nicht ohne spitze Klammern!

[//]: # (This is a comment inside a bracket)
[//]: # (Shit, meine Coins fallen gerade ins Bodenlose)
[//]: # (Wichtig: Comment _muss_ in runden Klammern sein!)

<!---
This type of comment should be actually rendered inside the
generated HTML output, whereas the above ones should only be visible inside the .md file.
-->

[keybase.io](https://htautsch.keybase.pub/ "Hannes Tautschnig's very own page on keybase.io")

[gh]: https://github.io "GitHub.io"
