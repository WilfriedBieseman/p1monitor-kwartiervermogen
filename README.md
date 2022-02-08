# p1monitor-kwartiervermogen
Toepassing voor het berekenen en weergeven van de kwartiervermogens in het elektriciteitsverbruik bij gebruik van de P1monitor van ZTATZ

## Waarom deze toepassing?

De huidige versie van de P1monitor (201909) geeft al bepaalde informatie weer over vermogengegevens uit de digitale/slimme meter.
Het ogenblikkelijk of 'actuele' vermogen vind je op 'main-2.php', linkse kolom en op 'e-verbuik.php', linkse kolom.
Daarnaast vind je ook het maximaal vermogen (vermogenespiek) dat vandaag werd genoteerd en ook het tijdstip waarop dit voor kwam (zie onder 'vandaag' op 'main-2.php', laatste twee vermeldingen).
Wat voor Vlaanderen (België) ontbreekt, is een overzicht van de kwartiervermogens.

Een woordje uitleg:

Vanaf juli 2022 geldt in Vlaanderen een nieuw distributienettarief, dat grotendeels zal gebaseerd zijn op het vermogen dat aan de meter werd geleverd, verder 'capaciteitstarief' genoemd. Het capaciteitstarief zal worden aangerekend op basis van een ‘gemiddelde maandpiek’ (kW). Deze maandpiek is wel niet de piek zoals nu dagelijks aangegeven door de P1monitor, maar een zogenaamde kwartiervermogenspiek. Voor de aanrekening van het capaciteitstarief wordt immers gekeken naar het GEMIDDELDE vermogen op kwartierbasis (ofwel ‘kwartiervermogen’). De absolute piek is dus niet van belang. Het aansluitingsvermogen en het type aansluiting (een- of driefasig) zal in Vlaanderen ook geen enkele impact hebben op het te betalen capaciteitstarief.

Elke maand wordt een 'hoogste' kwartiervermogen vastgesteld. Van deze maandpieken wordt opnieuw een gemiddelde genomen over de laatste 12 maanden om het (jaarlijkse) capaciteitstarief van de netbeheerder vast te stellen. Op deze manier hebben toevallige vermogenspieken of toevallig hoge kwartierpieken slechts weinig invloed op de te betalen vergoeding voor het netgebruik. Wie in een bepaald jaar sytematisch hoge pieken vraagt over verschillende tijdsperioden van een kwartier, betaalt daarentegen wel een hoog nettarief.

Meer informatie is te vinden op de website van de Vlaamse Energieregulator VREG (https://www.vreg.be/nl/faq --> 'nettarieven').

De hier vermelde toepassing zorgt ervoor dat kwartiervermogens worden opgeslagen en kunnen worden uitgelezen.

Deze toepassing is dus een add-on bij de P1monitor van ZTATZ die je daarom eerst moet downloaden en installeren (zie https://www.ztatz.nl/ )
