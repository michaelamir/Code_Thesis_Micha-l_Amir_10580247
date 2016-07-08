 <!-- Run with 
 pandoc hoe_een_slim_gebruik_van_de_voorkeursdrempel_vrouwen_de_meerderheid_in_het_parlement_bezorgd.md --smart --standalone --bibliography Thesis\ LaTeX/literature.bib >ESB.html

and you get all refs correct and nice html! 

of pandoc hoe_een_slim_gebruik_van_de_voorkeursdrempel_vrouwen_de_meerderheid_in_het_parlement_bezorgd.md --smart --standalone --bibliography Thesis\ LaTeX/literature.bib -o ESB.pdf
 voor een mooie pdf
 
--> 

## Hoe een slim gebruik van de voorkeursdrempel vrouwen de meerderheid in het parlement bezorgt

#### Draft voor ESB

* Michael Amir, Maarten Marx
* Universiteit van Amsterdam

<hr/>


### Introductie
We laten zien dat vrouwen, maar ook andere bevolkingsgroepen, <!-- Moeten we het niet alleen betrekken op vrouwen en dan later bij de strategieën vermelden dat het voor andere bevolkingsgroepen ook is toegepast in de scriptie en linken naar de scriptie--> bij de parlementsverkiezingen in 2012 op eenvoudige wijze 80% van alle zetels in het parlement hadden kunnen bemachtigen zonder dat &eacute;&eacute;n vrouw op een andere partij had hoeven stemmen.
Zij moeten hierbij slim gebruik maken van de voorkeursdrempel, die de ordening op de kandidatenlijst _overruled_.
Deze resultaten zijn robuust: ze gelden  ook voor andere bevolkingsgroepen <!-- in het verlengde van de vorige comment: we zouden hier kunnen zeggen dat de strategieën op allerlei bevolkingsgroepen zouden kunnen worden toegepast en dan er 3 andere bevolkingsgroepn in de scriptie zijn getest..--> en ook wanneer slechts een beperkt deel van de vrouwen meedoet.
De enige manier om dit resultaat af te wenden is dat mannen dezelfde strategie gaan toepassen.
We kunnen de dan resulterende stemming op &eacute;&eacute;n partij modelleren als een strategisch spel met twee spelers.
Dit spel heeft een uniek Nash equilibrium waarbij de bereikte man/vrouw zetelverdeling gelijk is aan de man/vrouw stemmers verdeling.


### Hoe de Kamer er na de verkiezingen in 2012 ook uit had kunnen zien.

We leggen de werking van de strategi&euml;en uit met vrouwen maar hebben de uitkomsten ook berekend voor allochtonen, senioren en "provincialen", zie Tabel 1.
De zetelverdeling in het Nederlandse kiessysteem is, afgezien van de methode voor het verdelen van de reststemmen, erg eenvoudig.
De kiesdeler _d_ is gelijk aan  het aantal uitgebrachte stemmen gedeeld door 150 (het aantal zetels in de Tweede Kamer).
Het aantal zetels dat een partij ontvangt is gelijk aan het aantal ontvangen stemmen gedeeld door de kiesdeler.
<!--Welke kandidaten op die zetels gaan zitten is afhankelijk van 1) de plaats van de kandidaten op de lijst en 2) het aantal voorkeurstemmen die de kandidaat  ontvangen heeft.-->
Bij het verdelen van de zetels aan de kandidaten wordt er, conform de kieswet [@kieswetje], eerst gekeken naar het aantal stemmen dat een kandidaat heeft ontvangen. Vervolgens wordt er pas gekeken naar de plaats op de kandidatenlijst. Een kandidaat die aan de voorkeursdrempel voldoet krijgt zodoende de voorkeur boven een kandidaat die hoger genoteerd staat maar niet aan de voorkeursdrempel voldoet.

 
Hoe dit kan uitpakken voor mannen en vrouwen kunnen we laten zien met een simpel voorbeeld:

* Stel de kiesdeler is 60.000 stemmen (in het vervolg schrijven we 60K), en de voorkeursdrempel is dus 15K. Stel een partij krijgt 800K stemmen, 50-50 van mannen en vrouwen. De lijsttrekker van deze partij is een man, en er staan 20 vrouwen op de lijst. 
* We gaan er van uit dat alle mannen op de lijsttrekker stemmen en de vrouwen willekeurig op een vrouw op de lijst. 
*  Dit betekent dat de lijsttrekker 400K stemmen krijgt, en elke vrouw 400K gedeeld door 20 is ruwweg 20K stemmen. Dus de lijsttrekker en alle vrouwen komen boven de voorkeursdremplel uit.
*  De partij krijgt minimaal 13 zetels, en in dit geval zijn dat er dus 1 man en 12 vrouwen.
*  Als de kandidatenlijst om en om een man en een vrouw had gehad en iedereen had "normaal" (op de bovenste man of vrouw) gekozen waren er dus 7 mannen en 6 vrouwen in de Kamer gekomen.
<!-- Ik heb het gedeelte hierboven een klein beetje aangepast maar misschien is deze passage in de comment hieronder ook geschikt? de passage komt rechtstreeks uit de scriptie-->
<!--Bij het verdelen van de zetels aan de kandidaten wordt er, conform de kieswet [@kieswetje], eerst gekeken naar het aantal stemmen die een kandidaat heeft ontvangen. Vervolgens wordt er pas gekeken naar de plaats op de kandidatenlijst. Een kandidaat die aan de voorkeursdrempel voldoet krijgt zodoende de voorkeur boven een kandidaat die hoger genoteerd staat maar niet aan de voorkeursdrempel voldoet.--> 

 

<!-- ik snap niet helemaal naar welk voorbeeld hier wordt gerefereerd-->

#### Als vrouwen  slim op vrouwen stemmen

Vrouwen, maar ook allochtonen zijn geneigd om op vrouwen (allochtonen) te stemmen [@van2012tweede].
<!-- referentie uit de scriptie: @article{van2012tweede,
  title={Tweede orde personalisering; Voorkeurstemmen in Nederland},
  author={Van Holsteyn, J and Andeweg, R},
  journal={Res Publica},
  volume={54},
  number={2},
  pages={163--191},
  year={2012}
}. -->
We hebben twee scenarios doorgerekend voor de Tweede Kamerverkiezingen in 2012 waarbij

<!-- Hier zijn de strategieën omgedraaid.. wat voor het artikel ook wel beter is denk ik-->
* iedereen stemt op de partij waar ze al op stemden
* alle mannen op dezelfde kandidaat als ze al deden
* alle vrouwen stemmen 
	* in scenario **S1** op een willekeurige vrouw op de lijst van hun partij;
	* en in scenario  **S2** op een willekeurige vrouw uit de eerste _N_  vrouwen op de lijst van hun partij.

waarbij _N_ zo is uitgekiend om maximaal veel rendement ( = vrouwen in de Kamer) te halen.
De precieze _N_ is eenvoudig uit te rekenen uit het aantal vrouwen op de lijst, het aantal verwachte zetels van de partij volgens de laatste peiling en het percentage vrouwelijke kiezers op de partij. <!-- in de scriptie is dit strategie 1 top N toch? Het percentage vrouwelijke kiezers was voor 2012 niet nodig voor het uitrekenen van de N. Voor de N was alleen het aantal vrouwen op de kandidantenlijst benodigd en het het aantal te verwachten zetels volgens de peiling. Het verwachte percentage vrouwelijke kiezers hadden we voor elke partij op 50-50 gezet omdat we dat niet konden weten. Daarom deden we op basis daarvan een 'voorspelling' om te kijken hoe verwacht zou worden dat de stemmen verdeeld zouden zijn bij 100% deelname. De uiteindelijk percentage vrouwelijke kiezers op een partij is gebruikt om verolgens de 'voorspelling'  te testen en de hoe de daadwerkelijke stemmen verdeeld hadden kunnen zijn. Het stukje in de comment hieronder is een beschrijving van het bepalen van N -->
<!-- De eerste _N_ vrouwen wordt voor elke partij als volgt bepaald: als de partij een gelijk of hoger aantal vrouwen op de kandidatenlijst had staan dan het aantal zetels dat voor de partij volgens de peiling werd verwacht is _N_ voor deze partij gelijk aan het aantal zetels volgens de peiling. Als de partij minder vrouwen op de kandidatenlijst had staan dan het volgens de peiling verwachte aantal zetels, is _N_ gelijk aan het totaal aantal vrouwen op de kandidatenlijst-->
Het resultaat is samen met dat voor  de allochtonen, senioren en "provincialen" weergegeven in Tabel 1.



| Bevolkingsgroep | Strategie S1 | Strategie S2 |
|-----------------|-------------|-------------|
| Vrouwen         | 116         | 121         |
| Allochtonen     | 34          | 34          |
| Ouderen         | 84          | 89          |
| Provincialen    | 131         | 138         |

[Tabel 1: Aantal zetels in de Tweede Kamer na de verkiezingen in 2012 per bevolkingsgroep als alle stemmers uit die bevolkingsgroep de strategie volgen.]


<!-- De tabel is ook veranders. Eerst stratgegie willekeurig en daarna stragtegie top N--> 

We zien een gigantische toename van het aantal vrouwen in de Kamer. Het feit dat het er geen 150 zijn is als volgt te verklaren: voor elke partij is er minstens 1 man, daarnaast zijn er partijen die niet genoeg vrouwen hadden om al hun vrouwelijke stemmen optimal te verdelen (SGP, PVV, VVD en SP). Ten slotte kwam er 1 man (Pieter Omzigt) op voorkeurstemmen de Kamer in.

 
<!-- De verklaring hieronder is wat te lang denk. Op kleine aanpassingen na komt het direct uit de scriptie. En het gaat alleen over strategie 2(stategie 1 in de scriptie)-->  
<!--De SGP had helemaal geen vrouwelijke kandidaten op de kandidatenlijst staan en de PVV, de SP en de VVD zouden volgens de peiling meer zetels gaan ontvangen dan dat zij vrouwelijke kandidaten op de kandidatenlijsten hadden staan. Zodoende komt het totaal aantal vrouwelijke kandidaten dat volgens de peiling in de Tweede Kamer gekozen had kunnen worden uit op 127.
De reden dat er 121 vrouwen in de Tweede Kamer zouden hebben plaatsgenomen na uitvoering van strategie 2 ligt ten grondslag aan een aantal factoren: het merendeel van de partijen hadden een mannelijke kandidaat als lijsttrekker en deze lijsttrekkers ontvingen de meeste stemmen in vergelijking met alle andere kandidaten van dezelfde partij. Hierdoor zou er bij de 50PLUS, de ChristenUnie en de SP één vrouwelijke kandidaat af zijn gevallen. Daarnaast had de SP minder zetels behaald bij de einduitslag dan dat zij volgens de peiling zouden gaan ontvangen. Hierdoor zou ook bij de SP nog een vrouwelijke kandidaat af zijn gevallen. Ook de Partij voor de Dieren ontving minder zetels bij de einduitslag dan zij volgens de peiling zouden gaan ontvangen en, ondanks het feit dat zij een vrouwelijke lijsttrekker hadden in de persoon van Marianne Thieme, zou dit geresulteerd hebben in één afgevallen vrouwelijke kandidaat. Bij het CDA had een mannelijke kandidaat in de persoon van Pieter Omtzigt meer stemmen ontvangen dan de vrouwelijke kandidaten zouden hebben ontvangen. Hierdoor viel bij het CDA een vrouwelijke kandidaat af. Dit komt op een totaal van zes afgevallen vrouwelijke kandidaten, oftewel een totaal van (127 􀀀 6 = ) 121 vrouwen in de Tweede Kamer na uitvoering van strategie 2.-->

#### Wat als niet iedereen meedoet?
Hierboven gingen we uit van 100% participatie door vrouwen. Dit is niet heel realistisch. Figuur 1 zet de participatiegraad uit tegen de vrouwelijke zetelwinst. Bij 50% participatie halen de vrouwen met strategie 2 al bijna een twee derde meerderheid (62.6%). <!-- Misschien ook voor S1(S2 in scriptie) doen. En misschien niet 40% doen maar 50% want dan is het percentage vrouwen in de kamer 62,6%-->

 



<img src="http://i.imgur.com/AwNMJM0.png">
[Figuur 1: Het aantal zetels behaald door vrouwen in de Tweede Kamer bj de verkiezingen van 2012 als een bepaald percentage vrouwen zich commiteerde aan strategie 1 (groen) of strategie 2 (blauw).]

### Mannen doen ook mee: een speltheoretische interpretatie.


Hoe eenvoudig het "misbruik maken" van de voorkeursdrempel ook is, het lijkt geen stabiele situatie: als de complementaire groep de verwachte uitkomst niet zint kunnen ze besluiten dezelfde strategie toe te passen.
We kunnen de resulterende stemming op &eacute;&eacute;n partij modelleren als een strategisch spel met twee spelers (de 2 groepen) die hun stemmen verdelen over hun voorkeurskandidaten.
Hoe de coordinatie binnen een groep plaatsvindt is niet triviaal, maar dat laten we hier buiten beschouwing.


Een paar <!-- wordt met 'een paar' bedoeld dat dat zowel M als V een strategie uitvoeren en op de hoogte zijn van elkaars strategie?--> strategie&euml;n _(M,V)_ is een _Nash equilibrium_ als geen van de spelers baat heeft bij het veranderen van strategie gegeven de strategie van de ander: beide strategie&euml;n zijn _best responses_ op elkaar.
Hiermee is de volgende stelling eenvoudig te bewijzen:

**Stelling**
Gegeven is een willekeurige voorkeursdrempel. 
Laat _0<=p<=1_ en stel dat een partij _Z_ zetels verwacht op basis van _S_ stemmen en _pS_ mannelijke (en dus _(1-p)S_ vrouwelijke) stemmen. 
Alle Nash equilibria zijn gegeven door de volgende paren strategieën:

* De mannen verdelen hun stemmen gelijk  over _pZ_ kandidaten en de vrouwen net zo over _(1-p)Z_ kandidaten.

**Direct gevolg van de stelling**

1. In een Nash equilibrium ontvangt elke kandidaat die gekozen wordt evenveel stemmen als de kiesdeler.
2. Het aantal zetels per groep is recht evenredig aan het aantal stemmers per groep.


### Aanbevelingen

De stelling laat zien dat de voorkeursdrempel in de evenwichtstoestand totaal geen rol speelt.
Wij zien dit als genoeg bewijs om voor te stellen om die af te schaffen.
De tweede aanbeveling komt voort uit de toch ietwat vreemde constructie om verplicht op &eacute;&eacute;n kandidaat te stemmen terwijl veel mensen eigenlijk op een partij stemmen. <!--**REF NEEDED**.--> Net als in Belgi&euml; zou men kunnen denken aan een stem op de partij gecombineerd met een stem op een kandidaat. <!-- Mischien iets meer over dit Belgisch kiessysteem en hoe de stemmen dan wegen-->

De laatste aanbeveling is revolutionairder. 
De Nash equilibrium strategie werkt alleen goed als kiezers netjes hun stemmen over de kandidaten verdelen.
We hebben dat gesimuleerd door kiezers willekeurig te laten kiezen, maar het is bekend dat het maken van een willekeurige keuze zeer lastig is voor mensen [@schulz2012analysing]. 
<!-- 3 referenties uti de scriptie: @article{schulz2012analysing,
  title={Analysing humanly generated random number sequences: a pattern-based approach},
  author={Schulz, Marc-Andr{\'e} and Schmalbach, Barbara and Brugger, Peter and Witt, Karsten},
  journal={PloS one},
  volume={7},
  number={7},
  pages={e41531},
  year={2012},
  publisher={Public Library of Science}
}

@article{bar1991perception,
  title={The perception of randomness},
  author={Bar-Hillel, Maya and Wagenaar, Willem A},
  journal={Advances in applied mathematics},
  volume={12},
  number={4},
  pages={428--454},
  year={1991},
  publisher={Elsevier}
}

@article{neuringer1986can,
  title={Can people behave" randomly?": The role of feedback.},
  author={Neuringer, Allen},
  journal={Journal of Experimental psychology: general},
  volume={115},
  number={1},
  pages={62},
  year={1986},
  publisher={American Psychological Association}
}-->
Om dit probleem op te lossen zijn er simpele hulpmiddelen in de vorm van een app te bedenken maar dit lijken toch schijnoplossingen. <!-- schijnoplossingen omdat de voorkeursdrempel nogsteeds kan worden uitgebuit?-->
Veel simpeler is om niet alleen een _partij-stemvakje_ te hebben maar ook een vaakje voor een stem op een man  en een   vakje voor een stem op een vrouw.   <!-- kunnen we hier niet beter enkel een stemvakje voor geslachten voorstellen? aangezien het geslacht er toch al op staat, vrouwen degene zijn die het meeste op eigen groep stemmen en Minister Bussemaker campange begonnen is om meer vrouwen aan topfunctie te helpen.. of wat voor reden dan ook die positief is voor vrouwen. Vrouwen (geslachten) lijkt mij het meest neutraal en tevens het meest haalbaar-->
<!--In het geval van mannen en vrouwen krijgen we dan dus een man en een vrouwvakje. -->
De stemmen daarop worden van boven naar beneden op de lijst verdeeld over de mannen en vrouwen totdat een kandidaat de kiesdeler haalt.
Dit simpele systeem heeft dus hetzelfe effect als de meeste natuurlijke Nash strategie, namelijk om de stemmen over de bovenste top _pZ_ en _(1-p)Z_ kandidaten te verdelen.

Lastig is natuurlijk dat binnen _no time_ misschien wel elke minderheid z'n eigen aparte paar vakjes claimt.<!-- dit lijkt me goede kritische toevoeging op de vorige comment over alleen geslachtsvakje.--> 

### Verantwoording
Dit stuk is gebaseerd op de  Bachelor scriptie Informatiekunde van Michael Amir, verdedigd  aan de Universiteit van Amsterdam. De complete scriptie staat op <http://...>
<!-- deze hoop ik vanmiddag up de loaden naar de uva bieb en dan kan die link hier neergezet worden-->

 
### Referenties
 
<!-- @online{kieswetje,
  author = {BZ and Koninkrijksrelaties},
  title = {Kieswet artikel H2},
  year = 2016,
  url = {http://wetten.overheid.nl/BWBR0004627/2016-01-01},
  urldate = {2016-03-19}
}

 @article{van2012tweede,
  title={Tweede orde personalisering; Voorkeurstemmen in Nederland},
  author={Van Holsteyn, J and Andeweg, R},
  journal={Res Publica},
  volume={54},
  number={2},
  pages={163--191},
  year={2012}
}

@article{schulz2012analysing,
  title={Analysing humanly generated random number sequences: a pattern-based approach},
  author={Schulz, Marc-Andr{\'e} and Schmalbach, Barbara and Brugger, Peter and Witt, Karsten},
  journal={PloS one},
  volume={7},
  number={7},
  pages={e41531},
  year={2012},
  publisher={Public Library of Science}
  -->