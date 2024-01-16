# Introductie {#06C37D5F}

In de Europese Open Data Richtlijn (EU) 2019/1024 wijst de Europese Commissie een lijst met thematische categorieën van hoogwaardige datasets (de ‘High Value Datasets’ (HVD)) aan. Hoofddoel van de HVD is om ervoor te zorgen dat overheidsgegevens met een groot sociaaleconomisch potentieel bij minimale wettelijke en technische beperkingen kosteloos beschikbaar worden gesteld voor hergebruik. Op 21 december 2022 is de Uitvoeringsverordening HVD besloten die wettelijke verplichtingen oplegt betreffende de high value datasets.<br/>

Geonovum ondersteunt het Ministerie van Binnenlandse Zaken en Koninkrijksrelaties en de Nederlandse dataproviders bij de invoering van HVD in Nederland.<br/>

Deze handreiking HVD is een handreiking met informatie om te voldoen aan de (technische) HVD-verplichtingen. Deze HVD-handreiking is bedoeld voor de HVD-dataproviders, die datasets voor HVD ontsluiten. Voor meer algemene informatie over HVD verwijzen we graag naar de <a href='https://docs.geostandaarden.nl/eu/handreiking-EU-informatie/#high-value-data-lijst' target='_blank'>HVD paragraaf</a> in de <a href='https://docs.geostandaarden.nl/eu/handreiking-EU-informatie/' target='_blank'>Handreiking EU informatie m.b.t. digitale en data-strategie</a>.<br/>

De opbouw van de HVD-handreiking is gebaseerd op de verschillende processtappen die de dataproviders doorlopen. <br/>

## Doelgroep {#10AF0A77}

Deze HVD-handreiking bedient meerdere doelgroepen, maar richt zich in eerste instantie op partijen die verantwoordelijk zijn voor de uitvoering van HVD. Daarnaast is de informatie ook relevant voor andere partijen die aan slag gaan met HVD. Het belangrijkste doel van deze handreiking is om het werkproces inzichtelijk te maken en kennis hierover op een overzichtelijke manier ter beschikking te stellen.<br/>

### Uitvoerders {#4814E9DB}

Onder partijen die verantwoordelijk zijn voor de uitvoering verstaan wij die personen en organisaties die praktisch en technisch met HVD aan de slag gaan. Dat gaat hier concreet om de Nederlandse dataproviders. Zij zullen de processtappen uitvoeren die nodig zijn om te voldoen aan de uitvoeringsverordening HVD. Ook zijn zij verantwoordelijk voor het publiceren van de metadata en aanvullende documentatie en het ontsluiten van de data via API’s. Dit kan door verschillende personen binnen een organisatie uitgevoerd worden, zoals data-beheerders, applicatie-specialisten, dba’ers van ruimtelijke databases en ICT'ers.<br/>

### Beleidsmakers {#21BEA824}

De handreiking is daarmee momenteel meer technisch dan organisatorisch ingestoken. Ook beleidmakers en managers krijgen met HVD te maken. Zij zullen ook praktisch met HVD aan de slag gaan, maar op een andere manier dan de technische beheerders, GIS-specialisten en ICT'ers. Toch kan het verhelderend zijn de handreiking te lezen om een idee te krijgen van het type werk, dat voor HVD moet worden uitgevoerd.<br/>

## Processtappen {#6E27898C}

Het HVD-implementatieproces is, na het aanmerken van de dataprovider en het vervolgens inrichten van de eigen organisatie, opgedeeld in drie technische stappen:<br/>

<ul><li><a href='#37B269C7'>Data</a></li>
<li><a href='#650CD6EF'>Metadata</a></li>
<li><a href='#37E1B35B'>Beschikbaar stellen</a>
  <ul><li>API</li>
  <li>Bulkdownload</li>
  <li>Overige documentatie</li></ul>
</li>
</ul>

In <a href='#207C051B'>hoofdstuk 4</a> is informatie over de afzonderlijke stappen die voor alle thema’s en datasets gelden beschreven. In de hoofdstukken daarna zijn dezelfde stappen beschreven met specifieke informatie die alleen geldt voor de respectievelijke thema’s. Per dataset moeten daarom de stappen doorlopen worden uit hoofdstuk 4 plus de stappen uit het betreffende hoofdstuk.<br/>

Bij het publiceren van de uitvoeringsverordening HVD is geen rekening gehouden met processtappen die een technisch data-beheerder of geo-informatie specialist moet ondernemen om de data conform HVD te ontsluiten. Deze handreiking helpt de dataproviders om het werkproces inzichtelijk te maken. In <a href='#2831FFFB'>hoofdstuk 12</a> is een checklist opgenomen van alle stappen die een dataprovider dient te doorlopen om een dataset inclusief services en documentatie te publiceren conform HVD vereisten.

## Deadlines {#55C1B036}

Op 21 december 2022 is de Uitvoeringsverordening tot vaststelling van een lijst met specifieke high value datasets en de regelingen voor publicatie en hergebruik van die gegevens besloten. Deze uitvoeringsverordening heeft de kracht van wet ongeacht de omzetting van de Open Data richtlijn in de Nederlandse Wet Hergebruik van Overheidsinformatie. De wettelijke verplichtingen van de high value datasets staan daarmee volledig op zichzelf. De eisen in de uitvoeringsverordening HVD moeten uiterlijk per 9 juni 2024 door iedere lidstaat vervuld zijn. <br/>

Het ministerie van Binnenlandse zaken stelt een gefaseerde aanpak voor, zie <a href='#3280DEA1'>Nederlandse ambitie HVD</a>.

## Bronnen {#6A547147}

Achtergrond, doelen, vereisten en overige informatie over de HVD is te vinden in de onderstaande, door de EU gepubliceerde documenten:<br/>
<br/>
<ul><li><a href='https://eur-lex.europa.eu/legal-content/NL/TXT/HTML/?uri=CELEX:32019L1024' target='_blank'>EU Open Data richtlijn (ODD)</a></li>
<li><a href='https://eur-lex.europa.eu/legal-content/NL/TXT/HTML/?uri=CELEX:32023R0138' target='_blank'>Uitvoeringsverordening tot vaststelling van een lijst met specifieke hoogwaardige datasets en de regelingen voor publicatie en hergebruik van die gegevens</a></li>
<li>Algemene <a href='https://data.europa.eu/nl' target='_blank'>website van de EU over open data</a></li>
</ul>

## Over deze handreiking {#375880A5}

### HVD is nog steeds in beweging {#3567F8EA}

HVD is nog steeds in beweging. Dat betekent dat nog niet alles over HVD gezegd is. Als er aanpassingen zijn, dan wordt deze handreiking daarop aangepast.<br/>

Verwacht hier echter niet alles over HVD. De insteek is om <i>die</i> informatie te verstrekken die nodig is om data volgens de uitvoeringsverordening HVD beschikbaar te kunnen stellen. De meest complete bron van informatie is de uitvoeringsverordening zelf. <br/>

Het detail van de handreiking slaat het software-niveau over; het is geen <i>how to</i> die uitlegt hoe je in specifieke software bepaalde functionaliteit oproept, of uitvoert. Wel reikt de handreiking principes of mechanismen aan.

### HVD Helpdesk {#2BBF3ADD}

We proberen via deze handreiking zoveel mogelijk informatie over HVD te delen. Heb je toch nog een vraag over HVD, stuur dan een e-mail naar <a href='mailto:HVD@geonovum.nl' target='_blank'>HVD@geonovum.nl</a>.<br/>

In de Handreiking EU Informatie m.b.t. digitale en data-strategie is zoals al eerder aangegeven algemene informatie over <a href='https://docs.geostandaarden.nl/eu/handreiking-EU-informatie/#high-value-data-lijst' target='_blank'>HVD</a> te vinden.

