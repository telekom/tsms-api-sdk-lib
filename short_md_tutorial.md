
# Markdown in GitHub Documents

Deutsche Telekom has decided to release some information about its use of **F**ree and **O**pen **S**ource **S**oftware in form of posts provided by its *GitHub* organization [https://github.com/telekom](https://github.com/telekom): Just as other members of the community do, Deutsche Telekom offers software repositories and the specific repository [https://github.com/telekom/telekom.github.io](https://github.com/telekom/telekom.github.io) containing the Jekyll template software for serving blog posts under [https://telekom.github.io](https://telekom.github.io).



# 0.) Inhalt
* [0.) Introduction](#intro)
* [1.) Überschriften](#headers)
* [2.) Absätze](#absaetze)
* [3.) Textauszeichnungen](#textauszeichnung)
* [4.) Listen](#listen)
* [5.) Zitate](#zitate)
* [6.) Coding](#coding)
* [7.) Horizontal Lines](#Lines)
* [8.) Links](#links)



# 1.) <a id="headers"></a>Überschriften

# Überschrift 1
## Überschrift 2
### Überschrift 3

# 2.) <a id="absaetze"></a>Absätze

Dies ist ein deutscher Absatz, mit hinreichend Länge hoffentlich und gutem Zeilenumbruch -  und getestetem zweisprachigem Spellchecking.

This is an English written paragraph, with sufficient length and a fitting line feed - and verified bilingual spell checker

Und hier selbstgesetzter Zeilenumbruch.  
Wird durch zwei Blanks am Ende ausgelöst.  
Klappt.

# 3.) <a id="textauszeichnung"></a>Textauszeichnungen

normal text  
**bold text**  
*italic text*  
***bold and italic Text***

Alternative Notation in unsortierter Liste:
* __bold Text__
* _italic Text_
* ___bold and italic text___

# 4.) <a id="listen"></a>Listen
Verschachtelte Liste

* Level 1
  * Level 1.A
    * Level 1.A.a
  * Level 1.B
* Level 2

Sortierte Liste

1. Level a
   1. Level a.x
   2. Level a.  
      Note: 1.1 does not work
2. Level b

# 5.) <a id="zitate"></a>Zitate

> Dies wird als Zitat wiedergegeben.
>> *Everything* is going according to **plan**.
>
> **Darin sind Formatierungen möglich. Und der Umbruch ist wieder automatisch weich.**

# 6.) <a id="coding"></a>Coding

Codeblocks werden mit 4 Blanks ausgezeichnet:

    if (Zeile 1)
    then
      while(true) do echo $value; done
    else
    fi

Inline `codes` sind über Backticks möglich `AND`. Das Rendern hängt von der Maschine ab.

# 7.) <a id="lines"></a>Horizontal Lines

---
Drei `***` oder `---`
***

# 8.) <a id="links"></a>Links

* nach draußen: `[fodina.de](http://fodina.de "Eine Fundgrube")` = [fodina.de](http://fodina.de "Eine Fundgrube")
* Lokale Bilder: `![Tux, the Linux mascot](markdown-example/tux.png)` = ![Tux, the Linux mascot](markdown-example/tux.png)
* Anchor Links:
  * Anchor: `<a id="anchor-name" />`
  * Anchor-Link: `[Link-Text](#anchor-name)`  
    Note: anchor links only work in texts, interpreted by GitHub markdown viewer, not in normal viewers

<img src="./markdown-example/tux.png" height="124" style="float:right;">Und hier per `<img src="./markdown-example/tux.png" height="124" style="float:right;">` nach rechts in den Blindtext eingebettet *der Tux*: Hallo. Ich bin ein kleiner Blindtext. Und zwar schon so lange ich denken kann. Es war nicht leicht zu verstehen, was es bedeutet, ein blinder Text zu sein: Man ergibt keinen Sinn. Wirklich keinen Sinn. Man wird zusammenhangslos eingeschoben und rumgedreht – und oftmals gar nicht erst gelesen. Aber bin ich allein deshalb ein schlechterer Text als andere? Na gut, ich werde nie in den Bestsellerlisten stehen. Aber andere Texte schaffen das auch nicht. Und darum stört es mich nicht besonders blind zu sein. <a href="./markdown-example/tux.png"><img src="./markdown-example/tux.png" height="124" style="float:left;"></a>Und hier per `<img src="./markdown-example/tux.png" height="124" style="float:left;">` nach links mit Link auf das Bildoriginal nochmal in den Blindtext gerendert *der Tux*. Und sollten Sie diese Zeilen noch immer lesen, so habe ich als kleiner Blindtext etwas geschafft, wovon all die richtigen und wichtigen Texte meist nur träumen.


# 9.) <a id="tables"></a>Tabellen

| 1 | 2 | 3 | 4 | 5 |
|---|---|---|---|---|
| a | ab | abc | abcd | abcde |
| xyz | xy | x | xy | xyz |
| a | b | c | d | e |
