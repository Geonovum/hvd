# Monitoring en rapportage {#04CFC1BA}
De implementatie van High Value Datasets (HVD) stopt niet bij het publiceren van datasets. Ook na publicatie is het belangrijk om te controleren of de datasets vindbaar, toegankelijk en bruikbaar blijven en voldoen aan de toepasselijke HVD-vereisten.  
## Doel van de monitoring
Monitoring is bedoeld om inzicht te krijgen in de mate waarin aangemerkte HVD-datasets daadwerkelijk beschikbaar zijn en blijven voldoen aan de vereisten van de [HVD-uitvoeringsverordening (EU) 2023/138](https://eur-lex.europa.eu/legal-content/NL/TXT/?uri=CELEX:32023R0138).
Daarbij wordt onder andere gekeken naar:
- Vindbaarheid in nationale en Europese dataportalen;
- Beschikbaarheid en kwaliteit van metadata;
- Correcte aanduiding als HVD, inclusief categorie en subcategorie;
- Beschikbaarheid via API's en, waar vereist, bulkdownload;
- Beschikbaarheid in machineleesbare formaten;
- Toepasselijke licenties en hergebruikvoorwaarden;
- Actualiteit van documentatie en contactinformatie.
## Doorlopende monitoring
Dataproviders zijn verantwoordelijk voor het beschikbaar houden van hun datasets en de bijbehorende voorzieningen. Het is daarom belangrijk om periodiek te controleren of de datasets, metadata en ontsluitingsdiensten nog correct functioneren.

Een dataset kan correct zijn aangemerkt als HVD, maar toch ontbreken in de Europese monitoring wanneer de metadata niet correct wordt geoogst of niet voldoet aan het toepasselijke [DCAT-AP HVD-profiel](https://semiceu.github.io/DCAT-AP/releases/3.0.1-hvd/).

Bij periodieke controles zijn de volgende punten relevant:

1. **Metadatakwaliteit:** Beschikbaarheid en validiteit van de metadata volgens de toepasselijke metadatastandaarden en het [DCAT-AP HVD-profiel](https://semiceu.github.io/DCAT-AP/releases/3.0.1-hvd/);

2. **HVD-classificatie:** Correcte aanduiding van de toepasselijke HVD-categorie en de meest specifieke subcategorie volgens [DCAT-AP HVD 3.0.1](https://semiceu.github.io/DCAT-AP/releases/3.0.1-hvd/);

3. **Databeschikbaarheid:** Beschikbaarheid en toegankelijkheid van de distributies volgens de [HVD-uitvoeringsverordening (EU) 2023/138](https://eur-lex.europa.eu/legal-content/NL/TXT/?uri=CELEX:32023R0138);

4. **Nationale vindbaarheid:** Controleren of de HVD-datasets vindbaar zijn in het [Nationaal Georegister (NGR)](https://www.nationaalgeoregister.nl/), voor zover van toepassing, om na te gaan of zij correct zijn opgenomen in de nationale ontsluitingsketen richting het Europese dataportaal;

5. **Europese vindbaarheid:** Controleren of de datasets als HVD vindbaar zijn via de [HVD-zoekfunctie van het Europese dataportaal](https://data.europa.eu/data/datasets?is_hvd=true&locale=en) en het [High-value Dataset Dashboard](https://data.europa.eu/en/hvd-dashboard);

6. **Technische toegankelijkheid:** Werking en beschikbaarheid van API's en, waar vereist, bulkdownload volgens de [HVD-uitvoeringsverordening (EU) 2023/138](https://eur-lex.europa.eu/legal-content/NL/TXT/?uri=CELEX:32023R0138), inclusief de bijbehorende Quality of Service-documentatie en servicevereisten;

7. **Documentatie en voorwaarden:** Actualiteit van licenties, gebruiksvoorwaarden, documentatie en contactgegevens volgens de toepasselijke vereisten en het [DCAT-AP HVD-profiel](https://semiceu.github.io/DCAT-AP/releases/3.0.1-hvd/);

8. **Administratieve registratie:** Controleren of de eigen HVD-datasets correct en actueel zijn opgenomen in het [nationale aanmerkingsregister](https://www.aanmerking.nl/aanmerkingsregister), inclusief verwijzingen naar de bijbehorende metadata.

## Europese monitoring
Op Europees niveau wordt de beschikbaarheid van HVD-datasets gevolgd via het Europese dataportaal [data.europa.eu](https://data.europa.eu/).
Het [High-value Dataset Dashboard](https://data.europa.eu/en/hvd-dashboard) biedt onder andere inzicht in:

- Het aantal beschikbare HVD-datasets per lidstaat;
- De verdeling over HVD-categorieën en subcategorieën;
- De kwaliteit van de metadata;
- De beschikbare dataformaten;
- De catalogi waarin HVD-datasets zijn opgenomen.

Het dashboard kan worden gebruikt om de Europese vindbaarheid van datasets te controleren en mogelijke ontbrekende datasets of metadataproblemen te signaleren.

Daarnaast biedt het [HVD Reporting Tool](https://data.europa.eu/apps/hvd-reporting-tool/index.html) (bètaversie) inzicht in de HVD-rapportage en controles op metadata, distributies en API's.
De aanwezigheid van een dataset op het Europese dataportaal betekent niet automatisch dat deze aan alle juridische en technische HVD-vereisten voldoet.

## Tweejaarlijkse rapportage
Op grond van [artikel 5 van de HVD-uitvoeringsverordening (EU) 2023/138](https://eur-lex.europa.eu/legal-content/NL/TXT/?uri=CELEX:32023R0138) rapporteren de EU-lidstaten iedere twee jaar over de uitvoering ervan. De eerste rapportage vond plaats in februari 2025. De volgende rapportage is voorzien voor februari 2027.
Op Europees niveau wordt gewerkt aan een meer geautomatiseerde rapportage op basis van metadata die via het Europese dataportaal wordt verzameld.
De Europese specificatie [DCAT-AP HVD 3.0.1](https://semiceu.github.io/DCAT-AP/releases/3.0.1-hvd/) beschrijft hoe HVD-metadata de verplichte rapportage ondersteunt, onder andere in paragraaf 11.9 over rapportage.
Voor de rapportage in 2027 is het uitgangspunt dat alleen datasets die correct worden geoogst en voldoen aan de toepasselijke DCAT-AP HVD-vereisten, kunnen worden meegenomen in de geautomatiseerde rapportage.
Dit maakt correcte metadata, harvesting en Europese vindbaarheid belangrijk voor zowel de implementatie als de rapportage over HVD.

## Verantwoordelijkheden
Bij de monitoring en rapportage zijn verschillende partijen betrokken:

**Dataproviders**
Zorgen voor de beschikbaarheid en actualiteit van datasets, metadata, API's, bulkdownload en bijbehorende documentatie. Zij controleren periodiek of de voorzieningen correct werken.
**Beheerders van broncatalogi**
Zorgen voor de correcte opname en doorgifte van metadata richting nationale catalogi.
**Nationale coördinatie**
Ondersteunt het overzicht van aangemerkte HVD-datasets, de voortgang van de implementatie en het signaleren van ontbrekende of niet-vindbare datasets.
**Europees dataportaal**
Verzamelt metadata via harvesting en ondersteunt de Europese vindbaarheid en monitoring van HVD-datasets.
**Verantwoordelijke autoriteiten van de lidstaat**
Dragen zorg voor de formele rapportage aan de Europese Commissie.

De precieze inrichting van de monitoring en de verdeling van operationele taken kunnen verder worden uitgewerkt naarmate de Europese en nationale werkwijzen zich ontwikkelen.
