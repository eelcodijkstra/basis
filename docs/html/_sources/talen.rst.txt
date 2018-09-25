Talen en grammatica's
=====================

Een taal bestaat een verzameling *zinnen*.
Dit geldt zowel voor een natuurlijke taal zoals het Nederlands, als voor een programmeertaal.
Het aantal zinnen in een taal is erg groot; dit kan zelfs oneindig zijn.
Het is handig als je een *beknopte beschrijving* van een taal hebt die aangeeft wat de geldige zinnen in de taal zijn,
en wat is de betekenis daarvan is.
In het geval van programmeertalen is zo'n beschijving zelfs essentieel:
het moet zowel voor de menselijke gebruikers van de taal als voor de computer volstrekt duidelijk zijn wat een geldig programma is,
en wat een geldig programma betekent.

Een beschrijving van een natuurlijke taal als het Nederlands is lastig:
je hebt hiervoor tenminste een woordenboek nodig met alle woorden en een grammatica (syntax).
En daarnaast nog een grote verzameling van vaste uitdrukkingen, spreekwoorden en gezegdes,
en lijsten met uitzonderingen.

Een beschrijving van een programmeertaal kan veel beknopter:
het aantal woorden is erg beperkt, de regels zijn (naar verhouding) eenvoudig, en er zijn
(als de taal goed ontworpen is) weinig speciale gevallen en uitzonderingen.
Maar omdat een programmeertaal vaak een historie heeft, waarin soms onhandige keuzes gemaakt zijn,
heb je ook in programmeertalen te maken met uitzonderingen en speciale gevallen.

Geldig versus correct
---------------------

Een zin is een reeks woorden en andere symbolen zoals leestekens.
Maar niet elke reeks woorden en leestekens is een geldige Nederlandse zin.
Een geldige zin in het Nederlands is een zin die grammaticaal klopt.
Je begrijpt dan wat de betekenis van die zin is.

De zin "*maan kaas*" is geen geldige Nederlandse zin.
Het is een on-zin: je kunt hier geen betekenis aan toekennen.

Aan een geldige zin kun je een betekenis toekennen.
Maar die betekenis kan best onzin zijn, zoals in "*De maan is van kaas.*"
In een fantasieverhaal zou zo'n zin nog kunnen,
maar in een "serieuze" tekst probeer je zinnen te gebruiken waarvan de betekenis geen onzin is.

Op eenzelfde manier is een *geldig programma* een programma waarvan de computer weet hoe dit uitgevoerd moet worden.
Maar daarmee hoeft het geen *correct programma* te zijn: het kan een foutief antwoord geven.
Als je een sorteerprogramma maakt, dan moet je er niet alleen voor zorgen dat dit door de computer uitgevoerd kan worden.
Je moet er ook voor zorgen dat deze uitvoering altijd het bedoelde resultaat geeft: een gesorteerde versie van de input.

.. rubric:: Opdracht

* geef een voorbeeld van een Nederlandse on-zin: een opeenvolging van woorden die geen goede Nederlandse zin vormt.
* geef een voorbeeld van een geldige Nederlandse zin waarvan de betekenis onzin is.

Structuur
---------

Zoals eerder gezegd: een zin is een reeks woorden en leestekens - maar niet elke reeks is een geldige zin in een bepaalde taal.
Door middel van een grammatica (syntax) van een taal beschrijven we welke reeksen geldige zinnen in die taal zijn.
Een grammatica bevat *regels* om de structuur van geldige zinnen te beschrijven.

Dit geldt zowel voor natuurlijke talen als voor programmeertalen.

Een grammatica beschrijft bovendien de *structuur* van een zin:
uit welke onderdelen bestaat deze zin, en wat is de relatie tussen deze onderdelen?

De structuur van een zin hangt nauw samen met de betekenis van deze zin.
Dezelfde woorden in een andere structuur geeft een andere betekenis.

  Dit is ook de reden waarom je op school leert de structuur van Nederlandse zinnen te *ontleden*:
  je kunt dan de verschillende onderdelen van een zin benoemen,
  en daarmee de rol van die onderdelen in de betekenis begrijpen.

  Bij het vak Nederlands gebruik je vaak twee soorten ontleden: *taalkundig* en *redekundig* ontleden.
  Bij taalkundig ontleden beschrijf je de *woordsoort* van de woorden,
  bijvoorbeeld: `de` - lidwoord, `grote` - bijvoeglijk naamwoord, `hond`  - zelfstandig naamwoord.
  Bij *redekundig ontleden* gaat het om de *rol* van de verschillende onderdelen in een zin:
  bijvoorbeeld in `de grote hond bijt de kat` is `de grote hond` het onderwerp,
  `bijt` het gezegde, en `de kat` het lijdend voorwerp.

* http://wp.digischool.nl/nederlands/home/taalkundig-ontleden-woordsoorten/
* http://wp.digischool.nl/nederlands/home/ontleden-redekundig-taalkundig/

Samengestelde vormen
--------------------

Een woord of een leesteken kun je zien als een enkelvoudige vorm.
Er zijn verschillende soorten enkelvoudige vormen.
In een natuurlijke taal heb je bijvoorbeeld zelfstandige naamwoorden, lidwoorden, werkwoorden,
voorzetsels, voegwoorden, punten, komma's, enz.
In een programmeertaal heb je getallen, namen voor variabelen en functies, symbolen als ``;`` en ``,`` enz.

Daarnaast heb je manieren nodig om samengestelde vormen te maken.
In een natuurlijke taal heb je daarvoor de opeenvolging (volgorde) van de woorden, en bijvoorbeeld voegwoorden en leestekens.
In een programmeertaal heb je daarvoor bijvoorbeeld opeenvolging (``;``), keuze (``if``),
herhaling (``for``, ``while``), en functies.
De regels in de grammatica beschrijven hoe je deze samengestelde vormen maakt uit de enkelvoudige vormen.

Syntaxdiagrammen
----------------

De symbolen die in de zinnen van een taal kunnen voorkomen noemen we de *eindsymbolen* van die taal.
Een verzameling symbolen noemen we ook wel een *alfabet*.

De syntaxregels van die taal beschrijven hoe we deze eindsymbolen kunnen combineren tot geldige zinnen.
regels van de

De regels van een grammatica, waarmee we beschrijven wat geldige zinnen zijn,
kunnen we op verschillende manieren beschrijven.
Een *syntaxdiagram* is een grafische notatie voor syntaxregels.

* een syntaxdiagram beschrijft een taal - alle zinnen in die taal, en de structuur van deze zinnen;
* vb: eenvoudige "natuurlijke" taal, subset van Nederlands
* vb: eenvoudige programmeertaal

.. todo::

  * Overeenkomst/verschil tussen eindige automaat en syntaxdiagram?

Een syntaxdiagram bestaat uit een aantal *regels*.
Elke regel bestaat uit een diagram dat gelabeld is met een hulpsymbool.
Je kunt dit hulpsymbool beschouwen als de naam van die regel.
Dit hulpsymbool staat ook voor alle *zinsvormen* die met die regel gemaakt kunnen worden.
Een *zinsvorm* is een reeks die bestaat uit eindsymbolen en hulpmsymbolen.

Aan de ene kant is het lastig om zonder namen (hulpsymbolen) de structuur te beschrijven.
Aan de andere kant geven deze namen vaak een hint voor de betekenis.

Mogelijke opdrachten
--------------------

.. todo::

  Opdrachten uitwerken. De opdrachten kunnen van de vorm zijn:

    * gegeven een syntaxdiagram, genereer 3 verschillende zinnen
    * gegeven een syntaxdiagram en een zin, ga na of deze zin element van de taal is
    * gegeven een syntaxdiagram en een zin, maak een ontleedboom

Opmerkingen
-----------

.. todo::

  Uitwerken van deze opmerkingen.

    * we hebben hier ook weer te maken met *vorm* en *betekenis*
    * niet alle vormen zijn "geldige vormen"
    * alleen van geldige vormen kunnen we de betekenis bepalen
    * deze betekenis hangt samen met de structuur van de vorm: de manier waarop de delen samengevoegd zijn.
    * een zin is een opeenvolging van woorden; niet alleen de woorden zelf maar ook de volgorde van de woorden bepaalt de betekenis.
    * onder deze volgorde ligt een structuur. Een zin bestaat uit onderdelen die een bepaalde verhouding tot elkaar hebben, en die in de zin een bepaalde rol spelen.
    * een ander voorbeeld van een soort grammatica is wat we zien bij "blokjestalen" - zoals Scratch.
      Ook daar komen we recursieve structuren tegen, bijvoorbeeld voor expressies.
    * gebruik van boekje van Jan Lepeltak (De Taalkist)


Voorbeeld: Expr
---------------

We geven hier een voorbeeld van een eenvoudige expressietaal.

.. figure:: talen/expr.png
   :width: 200 px
   :align: center

   Expr-regel

Een expressie (``Expr``) is een reeks termen verbonden door `+` of ``-`` operatoren.
Voorbeelden van Expr zijn dan: ``Term``, ``Term - Term``, ``Term + Term + Term``, enz.

.. figure:: talen/term.png
   :width: 200 px
   :align: center

   Term-regel

Een term (`Term`) is een reeks factoren verbonden door ``*`` of ``/`` operatoren.
Voorbeelden van Term zijn dan: ``Factor``, ``Factor * Factor``, ``Factor * Factor / Factor``, enz.

.. figure:: talen/factor.png
   :width: 300 px
   :align: center

   Factor-regel

Een factor (`Factor`) is een getal (`Number`), een variabele (`Variable`), of een `Expr` tussen haakjes.
Voorbeelden van `Factor` zijn dan `Number`, `(Expr)`.

Je kunt uit een zinsvorm (met hulpsymbolen) een *zin* (met alleen eindsymbolen) door alle hulpsymbolen hierin te vervangen door hun "expansie" volgens de regel van dat hulpsymbool. Als je dat dat voor stap doet, zoals hieronder, spreken we ook wel van een *afleiding*.

**Voorbeeld**:

.. code-block:: none

  Expr ->
  Term + Term ->
  Factor + Term ->
  Factor + Factor * Factor ->
  Number + Factor * Factor ->
  Number + Number * Factor ->
  Number + Number * Variable

Voorbeeld: HTML-lijsten
-----------------------

In HTML heb je twee mogelijke vormen van opsomming: een ongeordende lijst (`ul`) en de geordende lijst (`ol`).
De eerste resulteert meestal in een lijst met "bullets", de tweede in een genummerde lijst.

We geven hieronder de syntaxdiagrammen voor deze opsommingen.

.. figure:: talen/orderedlist.png
   :width: 350 px
   :align: center

   OrderedList-regel

Een geordende lijst (OrderedList) bestaat uit het haakjespaar ``<ol> ... </ol>``, met daartussen 0 of meer ListItems.
Een lijst met ListItems kan leeg zijn: in dat geval heb je alleen de haakjes ``<ol> </ol>``.

.. figure:: talen/unorderedlist.png
   :width: 350 px
   :align: center

   UnorderedList-regel

Een ongeordende lijst (UnorderedList)  bestaat uit het haakjespaar ``<ul> ... </ul>`` met daartussen 0 of meer ListItems.

.. figure:: talen/listitem.png
   :width: 300 px
   :align: center

   ListItem-regel

Een ListItem bestaat uit het haakjespaar ``<li> ... </li>`` met daartussen een Item.

.. figure:: talen/item.png
   :width: 250 px
   :align: center

   Item-regel

Een Item is een OrderedList, of een UnorderedList, of een OtherItem.
Een voorbeeld van een OtherItem is een "normale" tekst.

Merk op dat een Item ook weer een OrderedList of UnorderedList kan zijn:
dit betekent dat we deze deelstructuren kunnen *nesten*,
bijvoorbeeld een geordende lijst als element in een geordende lijst.

Een voorbeeld van een ongeordende lijst:

.. code-block:: html

  <ul>
    <li> huisje </li>
    <li> boompje </li>
    <li> beestje </li>
  </ul>

Dit resulteert dan in:

* huisje
* boompje
* beestje

**Opdracht**: geef een aantal voorbeelden van een UnorderedList.
Geef tenminste één voorbeeld van *nesting*, waarbij je een lijst binnen een lijst gebruikt.

Laat van één voorbeeld zien hoe je dit kunt afleiden via de syntaxdiagrammen.

**Opdracht**: demonstreer deze voorbeelden in een HTML-pagina.

Voorbeeld: Nederlands
---------------------

.. todo::

  Voorbeeld van syntaxdiagrammen voor eenvoudige Nederlandse zinnen.

  (En mogelijk: voorbeeld van een Haiku-generator?)

Ontleedbomen
------------

We kunnen de afleiding van een zin met behulp van de syntaxregels ook op een grafische manier weergeven,
in de vorm van een boom.
We spreken dan van een *ontleedboom*.
Zo'n ontleedboom laat de structuur van een zin zien.
Bovendien kun je deze gebruiken om de betekenis van de zin duidelijk te maken.

Programma voor het tekenen van ontleedbomen: http://mshang.ca/syntree/

In het voorbeeld hieronder zie je de ontleedboom van de eerder gegeven afleiding.
Aan de hand van deze ontleedboom kunnen we de betekenis van de expressie - dat wil zeggen, de expressie uitrekenen.
Je ziet hier aan de boom dat "vermenigvuldigen voor optellen gaat": dit is in de syntaxdiagrammen vastgelegd.

.. figure:: talen/exprtree.png
   :width: 350 px
   :align: center

   Ontleedboom voor een Expr
