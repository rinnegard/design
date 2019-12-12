Laddningstid Rapport
=======================

I den här rapporten analyserar jag flera olika webbplatsers laddningstid.

Urval
-----------------------

Jag valde 3st webbplatser som säljer böcker online. Jag ville jämföra webbplatser som hade lika funktion så jag valde att kolla på 3st onlinebutiker. Just dom här är dom 3 största svenska onlinebutikerna som säljer böcker. [Bokus](https://www.bokus.com/), [Akademibokhandeln](https://www.akademibokhandeln.se/) och [Adlibris](https://www.adlibris.com/)

Metod
-----------------------
Jag använde [Google PageSpeed](https://developers.google.com/speed/pagespeed/insights/) och devtools för webbläsaren för att undersöka sidorna.


Resultat
-----------------------
[Spreadsheet](https://docs.google.com/spreadsheets/d/1fQwdmAou7xoXZbzxnre8L3Z_4enE6V4ptQpOavICgr0/edit?usp=sharing)



####  Bokus

Bokus fick väldigt bra betyg för desktop men för mobil skulle dom kunna förbättra sig genom att använda lazy loading och använda nyare bildformat.

[FIGURE src=image/bokus.png?w=300 class="center"]


#### Akademibokhandeln

Akademibokhandeln fick dåligt betyg på mobil och bra betyg på desktop. På båda skulle dom kunna förbättra med lazy loading, nyare bildformat och komprimera text filer.
[FIGURE src=image/akademibokhandeln.png?w=300 class="center"]


#### Adlibris

Adlibris fick bra betyg för desktop men lite sämre för mobil som dom skulle kunna förbättra genom att ta bort oanvänd css och använda lazy loading och nyare bildformat samt använda sig av preload.

[FIGURE src=image/adlibris.png?w=300 class="center"]


Analys
-----------------------

Alla hade ungefär samma förbättrings åtgärder, det skilde sig lite men för alla var lazy loading och nyare bildformat en stor del.

Den som presterade bäst i testerna var Bokus följt av Adlibris och sist kom Akademibokhandeln.

Jag tycker att med en laddnings tid på under 1.5s är ungefär den gräns då en webbplats känns snabb. Det var bara Bokus som klarade sig under den gränsen men dom andra var inte allt för långt över så dom kändes ändå inte överdrivet långsamma.
