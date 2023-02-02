# p1monitor-kwartiervermogen
Toepassing voor het real-time berekenen en weergeven van de kwartiervermogens in het elektriciteitsverbruik, gebruik makend van de P1monitor van ZTATZ

## Waarom deze toepassing?

De huidige versie van de P1monitor (20221105) van ZTATZ geeft al bepaalde vermogensinformatie weer uit de digitale/slimme meter.
Het ogenblikkelijk of 'actuele' vermogen vind je op 'main-2.php', linkse kolom en op 'e-verbuik.php', linkse kolom.
Daarnaast vind je ook het maximaal vermogen (vermogenespiek) dat vandaag werd genoteerd en ook het tijdstip waarop dit voorkwam (zie onder 'vandaag' op 'main-2.php', laatste twee vermeldingen).
Wat voor Vlaanderen (België) ontbreekt, is een overzicht van de kwartiervermogens.

Een woordje uitleg:

Sinds 1 januari 2023 geldt in Vlaanderen een nieuw distributienettarief, dat grotendeels is gebaseerd op het vermogen dat aan de meter werd geleverd, verder 'capaciteitstarief' genoemd. Het capaciteitstarief wordt aangerekend op basis van een ‘gemiddelde maandpiek’ (kW). Deze maandpiek is wel niet de piek zoals nu dagelijks aangegeven door de P1monitor, maar een zogenaamde kwartiervermogenspiek. Voor de aanrekening van het capaciteitstarief wordt immers gekeken naar het GEMIDDELDE vermogen op kwartierbasis (ofwel ‘kwartiervermogen’). De absolute piek is dus niet van belang. Het aansluitingsvermogen en het type aansluiting (een- of driefasig) heeft in Vlaanderen ook geen enkele impact op het te betalen capaciteitstarief. Het verbruik (in kWh) wordt natuurlijk ook nog aangerekend, maar werd op 1 januari 2023 drastisch verlaagd.

Elke maand wordt een 'hoogste' kwartiervermogen vastgesteld. Van deze maandpieken wordt dan het gemiddelde genomen over de laatste 12 maanden om het (jaarlijkse) capaciteitstarief van de netbeheerder vast te stellen. Er wordt voor elke maand wel een minimum van 2,5 kW aangerekend. De kostprijs per kW is geoon lineair. Er is dus een maandelijkse minimale kost overeenkomend met een vermogenpiek van 2,5 kW verschuldigd.

Meer informatie is te vinden op de website van de Vlaamse Energieregulator VREG (zie https://www.vreg.be/nl/nieuwe-nettarieven).

De hier vermelde toepassing zorgt ervoor dat kwartiervermogens worden opgeslagen en kunnen worden uitgelezen.

Deze toepassing is dus een add-on bij de P1monitor van ZTATZ die je daarom eerst moet downloaden en installeren (zie https://www.ztatz.nl/ )
