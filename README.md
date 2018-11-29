# De Nationale Bodem Hackathon

![](https://forum.farmhack.nl/uploads/default/optimized/1X/37c8bad377c83a477daf1946d1f1574b203c8de6_1_690x350.png)

**Datum**: 29 & 30 november

**Locatie**: The Spot, Orion, Wageningen University (Bronland 103 6708 WH Wageningen)

**Forum:** https://forum.farmhack.nl/t/over-de-nationale-bodem-hackathon/134

## Inleiding
**Een gezonde bodem is de basis voor landbouwproductie, waterkwaliteit en voor weerbare ecosystemen.** Boeren zorgen goed voor de bodem, want het is hun grootste kapitaal. Kunnen we de inspanningen voor bodembeheer en de resultaten ervan zichtbaar maken en onderling vergelijken? Zo leren we wat werkt en kunnen we boeren ondersteunen of belonen voor goed beheer.

**Dankzij de digitale revolutie hebben we meer bodemdata dan ooit, en meer mogelijkheden om die data te combineren en integreren.** Dat is nodig ook, want fragmentatie in de data en instrumenten dreigt. Zie daar de context voor deze speciale FarmHack! 

**Deze nationale BodemHack is bedoeld om met de ingrediënten bodem, data en IT tot integrale oplossingen en slimme samenwerking te komen.** Het doel is een integraal instrument ontwikkelen waarmee we de kwaliteit van agrarische bodem- en watersystemen van Nederland in kaart kunnen brengen en tevens de kwaliteit van het beheer kunnen monitoren.  In de ideale situatie is dit instrument betaalbaar, objectief en stimulerend voor degenen die het bodembeheer doen.

## Data 

### WUR 

De [AgroDataCube](http://agrodatacube.wur.nl) "is A Big Open Data collection for Agri-Food Applications". De Cube bevat o.a. de volgende datasets die via een RESTful API te op vragen zijn:
  - Gewasregistratie van Nederland, 2012 – 2018.
  - Dagelijks weer van 50 KNMI meteostations, 01-01-1950 – 28-11-2018.
  - AHN2 data voor Nederland.
  - Per gewasperceel opvraagbaar:
    - AHN2 statistische informatie: count, sum, mean, stddev, min, max.
    - NDVI tijdserie (gemiddelde en standraard afwijking van de NDVI waarde per perceel, ongeveer 50 waarden per jaar), 2013 – 2018.
  - Bodemtypes 1:50.000, bepaald uit intersect van perceel met de Bodemkaart 1:50.000 uit 2014.
  - Info over de 50 KNMI meteostations, incl. locatie.
  - Administratieve grenzen van provincies, gemeente, postcodegebieden uit 2015.
  - Volledige lijst met gewascodes (van de gewasregistratie).
  - Volledige lijst met bodemtypes en bodemcodes (van de bodemkaart 1:50.000).
  - BOFEK (2012) - De informatie in het databestand kan dienen als invoer bij modelberekeningen van water- en stoffentransport in de bodem. Toepassingsschaal: 1 : 50 000 – 1 : 1 000 000
  
 ### Dairy Research Farm De Marke

Tijdens de hackathon zal data beschikbaar zijn van [De Marke](https://www.wur.nl/en/location/De-Marke-1.htm) over 

- [Weersgegevens 1994 - 2015](https://github.com/FarmHackNL/Bodemhack-2018/tree/master/data/De%20Marke/weersgegevens) (CSV)
- N balans per perceel (CSV)
- P balans per perceel (CSV)
- Bodemanalyses (CSV)
- Beregeningsdata - gegevens over de beregeningsregime van de percelen voor de jaren 1994 - 2017 

### Vitens

- [vitens.lizard.net](vitens.lizard.net) - grondwaterkwantiteitsgegevens en de locaties van de meetpunten. **Merk op**: de data in deze portal komt uit een [publike beschikbare API](https://vitens.lizard.net/api/v3/timeseries/?end=1527640000218&min_points=320&start=1464481600218&uuid=e702b82c-af42-47a4-8e12-e23b4e2e8f04). De API kan ook via een [Python wrapper](https://github.com/Vitens/pylizard ) benaderd worden.
- Export uit DATALAB voor februari 2018 - grondwaterkwaliteitsgegevens per puilbuis en pompput (inclusief historie). Zie [data/Vitens/DATALAB documentatie.pptx](https://github.com/FarmHackNL/Bodemhack-2018/raw/master/data/Vitens/DATALAB%20documentatie.pptx) voor een overzicht van de beschikbare gegevens. De dataset wordt tijdens hackathon beschikbaar gemaakt.
- Alle Vitens onttrekkingsputten
- Alle winvergunningen. Let op: niet alle vergunning worden volledig benut worden; de werkelijke onttrekking kan lager zijn.
  
# FarmHack 

[FarmHack](farmhack.nl) mobiliseert coders, creatieven en domeinexperts op vraagstukken van de boer.
