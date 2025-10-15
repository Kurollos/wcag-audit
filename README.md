# WCAG Audit 

Doe een WCAG audit op een bestaande website uit je eigen omgeving en rapporteer daarover.

De instructies van deze opdracht staan in [INSTRUCTIONS](https://github.com/fdnd-task/wcag-audit/blob/main/docs/INSTRUCTIONS.md).


## Titel Website

Welke website heb je getest? Beschrijf de website en voeg een screenshot toe.
Saint Morris Argentijnse Restaurant.
![IMG_6825](https://github.com/user-attachments/assets/02ff8789-fbc8-4efd-b393-e30997689b46)

Toon een screenshot van het Lighthouse Accessibility testresultaat.
![IMG_6821 (1)](https://github.com/user-attachments/assets/d504c3b3-6bb2-45bf-85de-4b390cfe828a)

Schrijf een samenvatting van de testbevindingen, en link naar je Wiki voor de volledige documentatie.
Samenvatting van testbevindingen – Accessibility Review

Tijdens de accessibility-test van de website zijn zowel automatische als handmatige controles uitgevoerd, inclusief toetsenbordnavigatie en screen reader tests met NVDA. Hieronder volgt een overzicht van de belangrijkste bevindingen:

1. Lighthouse Accessibility Audit
De automatische audit vond enkele aandachtspunten zoals ontbrekende alt-teksten bij afbeeldingen, onvoldoende kleurcontrast op bepaalde knoppen en gemiste labels bij formulieren.
Over het algemeen scoorde de website redelijk goed, maar er zijn kleine verbeterpunten die de toegankelijkheid voor screen reader-gebruikers kunnen vergroten.

2. Interactieve elementen

De meeste knoppen en links zijn toegankelijk via toetsenbord (Tab en Shift + Tab), en de focusindicatoren zijn zichtbaar.
Sommige interactieve elementen missen duidelijke labels of beschrijvingen, waardoor het voor screen reader-gebruikers niet altijd duidelijk is wat het element doet.
Formuliervelden hebben grotendeels correcte labels, maar bij enkele velden ontbreekt een gekoppeld label of ARIA-omschrijving.

3. Headings

De koppenstructuur is grotendeels logisch en hiërarchisch opgebouwd (h1 → h2 → h3), wat de navigatie via NVDA vergemakkelijkt.
Er zijn enkele kleine inconsistenties waarbij een headingniveau wordt overgeslagen, wat de leesbaarheid voor screen reader-gebruikers enigszins kan beïnvloeden.

4. Landmarks

Semantische HTML5-landmarks zoals header, nav, main en footer worden correct gebruikt en herkend door NVDA.
Navigatie tussen landmarks is logisch en intuïtief.
Sommige ARIA-rollen kunnen worden verbeterd of toegevoegd om extra duidelijkheid te geven bij dynamische content.

5. Handmatige toetsenbord- en screen reader checks

Alle primaire functies zijn bereikbaar zonder muis.
Dynamische updates zoals popups of modals worden in veel gevallen correct aangekondigd, maar sommige live-regions kunnen beter worden voorzien van aria-live om automatisch voorgelezen te worden.
Foutmeldingen bij formulieren worden gedeeltelijk voorgelezen; sommige meldingen missen een duidelijke focus of aankondiging.

Conclusie

De website is grotendeels toegankelijk voor gebruikers met een screen reader en toetsenbord, maar er zijn enkele verbeterpunten:
Toevoegen van ontbrekende alt-teksten en labels bij interactieve elementen.
Controleren van heading-hiërarchie om overgeslagen niveaus te corrigeren.
Verbeteren van live-regions en ARIA-rollen bij dynamische content.
Over het geheel genomen kan de gebruikerservaring voor mensen met een visuele beperking met relatief kleine aanpassingen significant verbeteren.

De Wiki Linkje https://github.com/Kurollos/wcag-audit/wiki
https://saint-morris.nl/

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
