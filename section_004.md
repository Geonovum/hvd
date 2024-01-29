# Algemene vereisten HVD {#207C051B}

De technische vereisten die aan de datasets van elk thema worden gesteld, zijn vastgesteld in de <a href='https://eur-lex.europa.eu/legal-content/NL/TXT/HTML/?uri=CELEX:32019L1024' target='_blank'>Open Data richtlijn</a>, de <a href='https://eur-lex.europa.eu/legal-content/NL/TXT/HTML/?uri=CELEX:32023R0138' target='_blank'>Uitvoeringsverordening HVD</a> en in de bijlage van deze uitvoeringsverordening. Op basis van deze documenten zijn in dit hoofdstuk de technische afspraken opgenomen die voor alle thema’s en alle datasets gelden die onder HVD vallen. De vereisten zijn onderverdeeld in vereisten voor de data, vereisten voor de metadata en vereisten voor het beschikbaar stellen.

## Data {#37B269C7}

### Formaat {#120E3368}

Over het formaat waarin de data beschikbaar gesteld dient te worden, staat in de Open Data richtlijn dat dataproviders hun documenten beschikbaar stellen in de reeds bestaande formaten of talen en, indien mogelijk en passend, elektronisch, in formaten die open, machineleesbaar, toegankelijk, vindbaar en herbruikbaar zijn. Daarnaast dient het formaat zo veel mogelijk aan formele open standaarden te voldoen (artikel 5 (1)). <br/>

In de uitvoeringsverordening HVD staat het wat specifieker, namelijk dat het een machineleesbaar formaat dient te zijn dat in de Unie of internationaal erkend is. Ook moet het formaat beantwoorden aan de redelijke behoeften van hergebruikers (artikel 3 (1)).<br/>

In de bijlage van de uitvoeringsverordening wordt bij alle thema’s, met uitzondering van subthema Binnenwateren (van thema Mobiliteit), ook vermeld dat het een open formaat moet zijn. Daarnaast worden in de bijlage bij enkele thema’s specifieke formaten als voorbeelden genoemd. Het is niet verplicht deze specifieke formaten te gebruiken, maar het wordt wel geadviseerd.<br/>

### Licenties {#0A0CAE2E}

Alle datasets worden beschikbaar gesteld onder de voorwaarden van een Creative Commons Public Domain Dedication (CC0) licentie of een Creative Commons BY 4.0-licentie of een gelijkwaardige of minder beperkende open licentie. Dit wordt vermeld in artikel 4, lid 3 van de uitvoeringsverordening. <br/>

## Metadata {#650CD6EF}

De Open Data richtlijn geeft aan dat dataproviders hun data beschikbaar stellen samen met hun metadata en dat de metadata zo veel mogelijk aan formele open standaarden dienen te voldoen (artikel 5, lid 1). <br/>

In de uitvoeringsverordening zijn een aantal aanvullende vereisten voor de metadata beschreven:<br/>
<ul><li>De dataset is in de metadata aangeduid als ‘high value dataset’ (artikel 3, lid 5); </li>
<li>De metadata zijn op internet beschikbaar volgens bestaande normen zoals één register of opendatacatalogus. (bijvoorbeeld NGR of data.overheid.nl) (artikel 5, lid 3a). </li>
</ul>

In de paragraaf Beschikbaar stellen – Overige documentatie is te lezen dat er een aantal documenten en andere informatie beschikbaar gesteld moeten worden. Hieruit kan worden afgeleid dat in de metadata aanvullende informatie opgenomen moet worden zodat deze aanvullende documenten voor gebruikers vindbaar zijn. Hoewel het geen expliciete vereiste is, wordt geadviseerd ook in de metadata op te nemen:<br/>
<ul><li>Contactpunt voor vragen en kwesties in verband met de API; </li>
<li>Een verwijzing naar de verplichte documentatie, zoals gebruiksvoorwaarden, kwaliteit van de service, API documentatie, documentatie van de datasets etc.  <ul><li>In de Europese metadata werkgroep rondom het ontsluiten van HVD (DCAT-AP-HVD), wordt er ook vanuit gegaan dat deze informatie via de metadata ontsloten wordt.</li></ul></li>
</ul>

### Metadata standaarden {#2E19E63B}

Algemeen geldt dus dat data voorzien dient te worden van metadata, dat de metadata zo veel mogelijk aan formele open standaarden dient te voldoen en dat de metadata op internet beschikbaar wordt gemaakt volgens bestaande normen. <br/>

Voor het beschrijven van ruimtelijke data en dataservices wordt op dit moment het <a href='https://docs.geostandaarden.nl/md/mdprofiel-iso19115/' target='_blank'>Nederlands metadata profiel op ISO 19115 voor geografie versie 2.1.0</a> en het <a href='https://docs.geostandaarden.nl/md/mdprofiel-iso19119/' target='_blank'>Nederlands metadata profiel op ISO 19119 voor services versie 2.1.0</a> toegepast.<br/>

Ten behoeve van de Europese INSPIRE regelgeving is ook een metadata profiel opgesteld. De vereisten uit het INSPIRE profiel zijn opgenomen in deze Nederlandse profielen zodat, door te voldoen aan het Nederlandse profiel, tevens aan de Europese INSPIRE vereisten voldaan kan worden.<br/>

Beide profielen staan op de <a href='https://forumstandaardisatie.nl/open-standaarden/' target='_blank'>Pas-toe-of-leg-uit-lijst</a> van het College Standaardisatie.<br/>

Voor ruimtelijke data en dataservices die conform deze metadata profielen de datasets en services (API’s) beschrijven, kunnen hiermee voldoen aan vereisten rondom metadata uit de <a href='https://eur-lex.europa.eu/legal-content/NL/TXT/HTML/?uri=CELEX:32023R0138' target='_blank'>Uitvoeringsverordening HVD</a>. Daarvoor is het wel noodzakelijk de specifieke extra informatie voor HVD ook in de metadata wordt opgenomen. Het gaat in ieder geval om de aanduiding van ‘high value dataset’ en daarnaast om onder andere contactinformatie en de verwijzing naar verplichte documentatie. Dit kan in bestaande metadata-elementen opgenomen worden, hiervoor is een wijziging van de Nederlandse metadata profielen niet direct noodzakelijk. Op termijn is dit voor een betere aansluiting op DCAT wellicht wel wenselijk (zie ook <a href='#409368F9'>Beschrijven van de HVD specifieke metadata in ISO 19115</a>).<br/>

De metadata kan voor andere domeinen conform andere bestaande normen (standaarden en profielen) beschikbaar worden gemaakt. Als er geen gangbare, domein specifieke metadata standaard is, kan de metadata aangemaakt worden conform DCAT-AP-NL.

### Standaard voor het uitwisselen van metadata tussen metadata portalen {#65FBDE9D}

In Europa is het applicatie profiel (<A href='https://semiceu.github.io/DCAT-AP/releases/3.0.0/' target='_blank'>DCAT-AP</a>) ontwikkeld op de internationale DCAT standaard, voor het uitwisselen van metadata tussen Europese dataportalen. De transformatie van INSPIRE metadata conform het Nederlands profiel op ISO 19115 naar DCAT, wordt uitgevoerd op catalog/dataportaal niveau. Individuele beheerders van metadata hoeven hier geen actie op te ondernemen. Dit geldt ook voor de metadata conform het Nederlands profiel op ISO 19119.<br/>

Er is voor het geo-domein en het statistische-domein op Europees niveau ook een applicatie profiel gemaakt, waarmee het mogelijk wordt om de domein specifieke metadata, zoals de ISO 19115 metadata voor ruimtelijke data, te transformeren naar het generieke DCAT-AP. Voor het uitwisselen van de HVD specifieke metadata is een extensie op DCAT-AP gemaakt, <a href='https://semiceu.github.io/DCAT-AP/releases/2.2.0-hvd/' target='_blank'>DCAT-AP-HVD</a>, zodat daarmee ook aan de vereisten vanuit de uitvoeringsverordening voor hoogwaardige datasets kan worden voldaan. Een update van geoDCAT-AP, waarin ook de transformatie van ISO metadata naar DCAT-AP-HVD is vastgelegd, is momenteel nog niet beschikbaar.<br/>

### DCAT-AP-NL {#6E5518C4}

Een Nederlands applicatie profiel op DCAT is in ontwikkeling. Hierin wordt op basis van het Europese DCAT-AP, specifiekere afspraken gemaakt die beter aansluiten op de situatie in Nederland. Dit profiel gaat gebruikt worden voor de uitwisseling van metadata tussen Europese en Nederlandse data portalen. In een aantal domeinen en bijbehorende portalen wordt DCAT als standaard gebruikt om de metadata in vast te leggen. Daar kan het Nederlandse profiel ook gebruikt gaan worden zodat de metadata die wordt vastgelegd beter aansluit bij de Nederlandse wensen en eisen op dit gebied.<br/>

### Beschrijven van de HVD specifieke metadata in ISO 19115 (INSPIRE) {#409368F9}

Ruimtelijke data en dataservices (API’s) waarvan de metadata wordt beschreven conform het Nederlands metadata profiel op ISO 19115 voor geografie versie 2.1.0 en het  Nederlands metadata profiel op ISO 19119 voor services versie 2.1.0 kunnen hiermee voldoen aan vereisten rondom metadata uit de Uitvoeringsverordening HVD. Het is dan wel noodzakelijk dat de specifieke extra informatie voor HVD ook in de metadata wordt opgenomen. Het gaat daarbij in ieder geval om de aanduiding van ‘high value dataset’ en daarnaast onder andere om contactinformatie en de verwijzing naar verplichte documentatie.<br/>

Een update van een Europees afgestemd geoDCAT-AP, waarin ook de transformatie van ISO metadata naar DCAT-AP-HVD is vastgelegd, is momenteel nog niet beschikbaar. Het is mogelijk dat daarin van andere ISO metadata elementen uitgegaan gaat worden om HVD vereisten in DCAT te ontsluiten. Zolang de gevraagde informatie in de juiste DCAT elementen ontsloten wordt, zal dit niet tot problemen leiden.<br/>
<br/>

<B><I>De aanduiding 'high value dataset'</i></B>

Vooralsnog lijkt het opnemen van de aanduiding ‘high value dataset’ en het aangeven van het HVD thema in het metadata element trefwoord te voldoen.<br/>

Voor de aanduiding ‘high value dataset' moet daarvoor de ELI `http://data.europa.eu/eli/reg_impl/2023/138/oj` opgenomen worden.<br/>

Het trefwoord voor het HVD thema moet een waarde zijn uit <a href='https://op.europa.eu/en/web/eu-vocabularies/dataset/-/resource?uri=http://publications.europa.eu/resource/dataset/high-value-dataset-category' target='_blank'>https://op.europa.eu/en/web/eu-vocabularies/dataset/-/resource?uri=http://publications.europa.eu/resource/dataset/high-value-dataset-category</a>.

Dit kan als volgt worden opgenomen in de metadata:
<code>
<pre class="xml">
<span style='color: #000080;'>
&lt;gmd:MD_Keywords&gt;
  &lt;gmd:keyword&gt;
    &lt;gmx:Anchor xlink:href="http://data.europa.eu/eli/reg_impl/2023/138/oj"&gt;HVD&lt;/gmx:Anchor&gt;
  &lt;/gmd:keyword&gt;
&lt;/gmd:MD_Keywords&gt;
&lt;gmd:MD_Keywords&gt;
  &lt;gmd:keyword&gt;
    &lt;gmx:Anchor xlink:href="https://op.europa.eu/web/eu-vocabularies/concept/-/resource?uri=http://data.europa.eu/bna/c_dd313021"&gt; Aardobservatie en milieu&lt;/gmx:Anchor&gt;
  &lt;/gmd:keyword&gt;
  &lt;gmd:thesaurusName&gt;
    &lt;gmd:CI_Citation&gt;
      &lt;gmd:title&gt;
        &lt;gmx:Anchor xlink:href="http://publications.europa.eu/resource/dataset/high-value-dataset-category"&gt;High-value dataset categories &lt;/gmx:Anchor&gt;&gt;
      &lt;/gmd:title&gt;
      &lt;gmd:date&gt;
        &lt;gmd:CI_Date&gt;
          &lt;gmd:date&gt;
            &lt;gco:Date&gt;2023-09-27&lt;/gco:Date&gt;
          &lt;/gmd:date&gt;
          &lt;gmd:dateType&gt;
            &lt;gmd:CI_DateTypeCode codeList="http://standards.iso.org/ittf/PubliclyAvailableStandards/ISO_19139_Schemas/resources/Codelist/ML_gmxCodelists.xml#CI_DateTypeCode"codeListValue="publication"&gt;publication&lt;/gmd:CI_DateTypeCode&gt;
          &lt;/gmd:dateType&gt;
        &lt;/gmd:CI_Date&gt;
      &lt;/gmd:date&gt;
    &lt;/gmd:CI_Citation&gt;
  &lt;/gmd:thesaurusName&gt;
</span></pre></code>
<br/>

<B><I>Contactinformatie</I></B>

De contactinformatie voor vragen over de API kan in de metadata elementen behorende bij “Verantwoordelijke organisatie bron” worden opgenomen. Gebrui daarbij als rol: pointOfContact. Het wordt aanbevolen dat contactinformatie de vorm heeft van een (persistent) e-mailadres, bijvoorbeeld servicedesk@xxx.nl, of een link naar een contactformulier op een webpagina, bijvoorbeeld om contact op te nemen met een servicedesk.<br/>
<br/>

<B><I>De gebruiksvoorwaarden</I></B>

De licentie kan zoals gebruikelijk worden opgenomen bij het element “juridische toegangsrestricties” in de metadata. Deze moet echter wel een Creative Commons Public Domain Dedication (CC0) licentie of een Creative Commons BY 4.0-licentie of een gelijkwaardige of minder beperkende open licentie zijn.<br/>
<br/>

<B><I>Documentatie van de dataset</I></B> 

Bij diverse HVD thema’s wordt gevraagd om de online documentatie van de datasets waarin ten minste de gegevensstructuur en -semantiek is opgenomen. De link naar deze documentatie kan, zoals al gebruikelijk is, in de metadata opgenomen worden bij het element “specificatie” met bijbehorende conformiteitsindicatie.<br/>
<br/>

<B><I>De kwaliteit van de dienstverlening</I></B>

Voor de API moet de kwaliteit van de dienstverlening, wat betreft de prestaties, de capaciteit en de beschikbaarheid worden gepubliceerd. In het Nederlands profiel op ISO 19119 zijn daar specifieke metadata elementen voor. DCAT kent deze niet, daar wordt voor deze informatie uitgegaan van een document, waarin deze informatie is opgenomen. Een optie is om de kwaliteit van de dienstverlening als “Algemene beschrijving herkomst” op te nemen in de ISO metadata. Dit is een metadata element waarin ook kwaliteitsinformatie kan worden opgenomen. Dit element is echter nog niet opgenomen in het Nederlands metadata profiel op ISO 19119, maar heeft als voordeel dat het eenduidig is te transformeren naar DCAT. Het opnemen in het element “specificatie” met bijbehorende conformiteitsindicatie, heeft een nadeel dat dit niet eenduidig te transformeren is naar DCAT.<br/> 

Het document met deze specificatie van de kwaliteit van de service zal wel apart online gepubliceerd moeten worden zodat deze direct toegankelijk is. Deze werkwijze sluit ook aan bij de opmerking in DCAT-AP-HVD dat kwaliteitsinformatie over de service wordt gezien als onderdeel van de generieke documentatie van een service.<br/>
<br/>

<B><I>API documentatie</I></B>

Voor de API moet de documentatie over de API zelf gepubliceerd worden. Deze documentatie geeft specifieke details over het endpoint. Dit komt overeen met wat er vastgelegd wordt in een capabilities document van een WFS of de open API specificatie op een OGC: API features. De link naar deze documentatie wordt in de metadata gelegd in het element URL.<br/>
<br/>

<B><I>Overige metadata</I></B>

Als er voor de HVD data van verschillende generalisatieniveaus,  granulariteit, actualiseringsfrequentie en – termijnen, tijdreeksen en updatefrequentie wordt gevraagd te leveren, is het ook van belang deze specifieke informatie in de metadata op te nemen in de daarvoor aanwezige metadata elementen. Net als distributie formaat is dit relevante informatie, maar geen verplicht metadata element.

## Beschikbaar stellen {#37E1B35B}

### API {#289E9E05}

Zowel in de Open Data richtlijn (artikel 5, lid 8) als in de uitvoeringsverordening (artikel 3, lid 1) staat dat de datasets die onder HVD vallen, via een Application Programming interface (API) beschikbaar gesteld moeten worden. Een API is in Open Data richtlijn gedefinieerd als "een set functies, procedures, definities en protocollen voor communicatie tussen machines en de naadloze uitwisseling van data." Er is geen technische verordening voor de functionaliteit en techniek voor API’s opgesteld. Er wordt dus geen ‘technische’ keuze of API stijl voor API’s voorgeschreven. Voor de thema’s geodata, aardobservatie en milieu en mobiliteit is aangegeven dat het gaat om een API “zoals direct access download services op basis van Richtlijn 2007/2/EG” (INSPIRE). De INSPIRE direct access download service implementatie maakt het mogelijk om slechts een deel van de dataset door eigen selecties te downloaden. INSPIRE dataproviders met HVD datasets kunnen de INSPIRE ‘network services’ op de volgende wijze inzetten voor de HVD: <br/>
<table style='width: 290pt;'><caption></caption>
<colgroup><col id='col1' style='width: 76%;'>
<col id='col2' style='width: 24%;'>
</colgroup>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #A8D08D; border-left: 0.5pt solid #A8D08D; border-bottom: 0.5pt solid #A8D08D; border-right: 0.5pt solid #A8D08D; background-color: #70AD47;'>INSPIRE ‘network service’<br/>
</td>
<td align='center' style='border-top: 0.5pt solid #A8D08D; border-left: 0.5pt solid #A8D08D; border-bottom: 0.5pt solid #A8D08D; border-right: 0.5pt solid #A8D08D; background-color: #70AD47;'>HVD API<br/>
</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #A8D08D; border-left: 0.5pt solid #A8D08D; border-bottom: 0.5pt solid #A8D08D; border-right: 0.5pt solid #A8D08D; background-color: none;'>OGC Web Services: WFS, WCS, SOS<br/>
</td>
<td align='center' style='border-top: 0.5pt solid #A8D08D; border-left: 0.5pt solid #A8D08D; border-bottom: 0.5pt solid #A8D08D; border-right: 0.5pt solid #A8D08D; background-color: none;'><span style='color: #3C3C3C;'>X</span><br/>
</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #A8D08D; border-left: 0.5pt solid #A8D08D; border-bottom: 0.5pt solid #A8D08D; border-right: 0.5pt solid #A8D08D; background-color: none;'>OGC API: STA, API Features<br/>
</td>
<td align='center' style='border-top: 0.5pt solid #A8D08D; border-left: 0.5pt solid #A8D08D; border-bottom: 0.5pt solid #A8D08D; border-right: 0.5pt solid #A8D08D; background-color: none;'><span style='color: #3C3C3C;'>X</span><br/>
</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #A8D08D; border-left: 0.5pt solid #A8D08D; border-bottom: 0.5pt solid #A8D08D; border-right: 0.5pt solid #A8D08D; background-color: none;'>Atom feeds<br/>
</td>
<td align='center' style='border-top: 0.5pt solid #A8D08D; border-left: 0.5pt solid #A8D08D; border-bottom: 0.5pt solid #A8D08D; border-right: 0.5pt solid #A8D08D; background-color: none;'></td>
</tr>
</tbody>
</table>

De internationale standaarden voor INSPIRE API's zijn door het OGC opgesteld. Deze eerste generatie OWS standaarden, zoals WFS, WCS en SOS, zijn gebaseerd op RPC en XML. Deze standaarden zijn nog steeds geldig en in gebruik, maar worden gaandeweg vervangen door de nieuwe generatie. Deze nieuwe generatie, de OGC API’s, zijn gebaseerd op algemene Web architectuur, i.e. REST. In de algemene Web architectuur wordt ook de <a href='https://docs.geostandaarden.nl/api/API-Strategie/' target='_blank'>Nederlandse API strategie</a> van de overheid toegepast.<br/>

Kortom, datasets ontsloten via INSPIRE ‘direct access download services’, kunnen eveneens als HVD API’s worden ingezet. Er zijn geen voorgeschreven technische implementatieregels vanuit ODD en HVD, maar wel een verwachting dat API’s  meegroeien met de redelijke wensen van hergebruikers. Om te voldoen aan de behoefte van hergebruikers is het advies om het gebruik van REST API’s conform de Nederlandse API strategie en conform de OGC API standaarden zoals STA en OGC API Features (INSPIRE Good Practises) te implementeren en stimuleren. Deze nieuwe generatie API's zijn voor een veel breder publiek toegankelijk voor hergebruik. Daarnaast is het advies om de brede Europese ontwikkelingen op het gebied van API implementatie te volgen en te zorgen dat de Nederlandse API belangen worden gewaarborgd.  

### Bulkdownload {#420E7103}

Uitzonderingen daargelaten moeten veel van de datasets naast via een API ook als bulkdownload beschikbaar worden gesteld. Bulksdownload wordt in de uitvoeringsverordening gedefinieerd als: “een functie die het mogelijk maakt een volledige dataset in een of meer pakketten te downloaden.”<br/>

INSPIRE dataproviders met HVD datasets kunnen de INSPIRE ‘network services’ op de volgende wijze inzetten voor de HVD: <br/>
<table style='width: 320pt;'><caption></caption>
<colgroup><col id='col1' style='width: 67%;'>
<col id='col2' style='width: 33%;'>
</colgroup>
<tbody valign='top'><tr><td align='left' style='border-top: 0.5pt solid #A8D08D; border-left: 0.5pt solid #A8D08D; border-bottom: 0.5pt solid #A8D08D; border-right: 0.5pt solid #A8D08D; background-color: #70AD47;'>INSPIRE ‘network service’<br/>
</td>
<td align='center' style='border-top: 0.5pt solid #A8D08D; border-left: 0.5pt solid #A8D08D; border-bottom: 0.5pt solid #A8D08D; border-right: 0.5pt solid #A8D08D; background-color: #70AD47;'>HVD Bulkdownload<br/>
</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #A8D08D; border-left: 0.5pt solid #A8D08D; border-bottom: 0.5pt solid #A8D08D; border-right: 0.5pt solid #A8D08D; background-color: none;'>OGC Web Services: WFS, WCS, SOS<br/>
</td>
<td align='center' style='border-top: 0.5pt solid #A8D08D; border-left: 0.5pt solid #A8D08D; border-bottom: 0.5pt solid #A8D08D; border-right: 0.5pt solid #A8D08D; background-color: none;'>X<br/>
</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #A8D08D; border-left: 0.5pt solid #A8D08D; border-bottom: 0.5pt solid #A8D08D; border-right: 0.5pt solid #A8D08D; background-color: none;'>OGC API: STA, API Features<br/>
</td>
<td align='center' style='border-top: 0.5pt solid #A8D08D; border-left: 0.5pt solid #A8D08D; border-bottom: 0.5pt solid #A8D08D; border-right: 0.5pt solid #A8D08D; background-color: none;'>X<br/>
</td>
</tr>
<tr><td align='left' style='border-top: 0.5pt solid #A8D08D; border-left: 0.5pt solid #A8D08D; border-bottom: 0.5pt solid #A8D08D; border-right: 0.5pt solid #A8D08D; background-color: none;'>Atom feeds<br/>
</td>
<td align='center' style='border-top: 0.5pt solid #A8D08D; border-left: 0.5pt solid #A8D08D; border-bottom: 0.5pt solid #A8D08D; border-right: 0.5pt solid #A8D08D; background-color: none;'>X<br/>
</td>
</tr>
</tbody>
</table>

### Overige documentatie {#41325C33}

In de uitvoeringsverordening is beschreven dat ten behoeve van hergebruik verschillende documentatie beschikbaar gesteld dient te worden.<br/>
<ul><li>Naast de API zelf moeten de gebruiksvoorwaarden van de API worden vastgesteld en worden gepubliceerd in een open, voor de mens en machineleesbaar formaat (artikel 3, lid 2).</li>
<li><span style='color: #000000;'>De criteria inzake de kwaliteit van de dienstverlening moet eveneens worden vastgesteld en gepubliceerd. Het betreft hier de prestaties, de capaciteit en de beschikbaarheid van de services (</span>artikel 3, lid 2)<span style='color: #000000;'>. </span></li>
<li>Tenslotte wordt ook de API documentatie gepubliceerd in een open, voor de mens en machineleesbaar formaat dat in de Unie of internationaal erkend is (artikel 3, lid 3).</li>
</ul>

### Contactpunt {#14E940CF}

Alle dataproviders die over high value datasets beschikken, wijzen een contactpunt aan voor vragen en kwesties in verband met de API. Dit heeft als doel de beschikbaarheid en het onderhoud van de API te waarborgen en draagt uiteindelijk bij aan de vlotte en doeltreffende publicatie van de datasets (uitvoeringsverordening artikel 3, lid 4). Het advies is hiervoor een helpdesk-punt te gebruiken.

