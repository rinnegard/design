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

För mobil fick dom 68/100 poäng från google pagespeed. Dom skulle kunna förbättra genom att vänta med att ladda in saker som inte används förrän allt nödvändigt har laddats in, så kallad lazy loading. Att använda nyare bildformat skulle också ge tydlig förbättring.

För desktop fick dom 100/100 poäng från google pagespeed. Men om dom skulle vilja förbättra sig även här skulle nyare format hjälpa här också.

[FIGURE src=image/bokus.png?w=300 class="center"]


#### Adlibris

För mobil fick dom 65/100 poäng från google pagespeed. Dom skulle kunna förbättra sig genom att ta bort oanvänd css samt genom att använda lazy loading och nyare bildformat.

För desktop fick dom 93/100 poäng från google pagespeed. Här skulle dom också kunna förbättra sig med att ta bort oanvänd css och genom att använda lazy loading och nyare bildformat.

[FIGURE src=image/adlibris.png?w=300 class="center"]

#### Akademibokhandeln

För mobil fick dom 37/100 poäng från google pagespeed. För att förbättra skulle dom kunna använda lazy loading, nyare bildformat och även komprimera sina text filer.

För desktop fick dom 89/100 poäng från google pagespeed. Här skulle dom också kunna förbättra sig med nyare bildformat och mer komprimering.

[FIGURE src=image/akademibokhandeln.png?w=300 class="center"]


Analys
-----------------------

Alla hade ungefär samma förbättrings åtgärder, det skilde sig lite men för alla var lazy loading och nyare bildformat en stor del av det dom kunde göra för att förbättra sin laddningstid.

Den som presterade bäst i testerna var Bokus följt av Adlibris och sist kom Akademibokhandeln.

Jag tycker att med en laddnings tid på under 1.5s är ungefär den gräns då en webbplats känns snabb. Det var bara Bokus som klarade sig under den gränsen men dom andra var inte allt för långt över så dom kändes ändå inte överdrivet långsamma.
