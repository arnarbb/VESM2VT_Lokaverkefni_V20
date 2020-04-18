# VESM2VT - Vor 2020
## Lokaverkefni (35%) - Snúrustýrður bíll með fjarstýringu
Í þessu verkefni áttu að nota Tinkercad til að gera frumgerð af fjarstýrðum bíl og fjarstýringu fyrir hann. Í þessari frumgerð notar þú að vísu snúru til að tengja saman bílinn og fjarstýringuna.

## Efnislisti
- 2 Arduino tölvur
- 2 DC mótorar
- 2 Servo mótorar
- LCD skjár
- Ultrasonic skynjari
- 4 takkar eða 2 stilliviðnám.
- H-Bridge
- 2 breadboard
- Annað sem getur verið gagnlegt að hafa

## Lýsing
Bíllinn og fjarstýringin tala saman með I2C staðlinum.

### Bíllinn
Bíllin notar aðra Arduino tölvuna til að stjórna móturunum. DC mótorarnir eru fyrir afturdekkin og keyra bílinn áfram eða aftur á bak. Nota skal H-Bridge með DC móturunum. Servo mótorarnir sjá um að stýra stefunni á framdekkjunum. Hvað mótorarnir eiga að gera kemur frá fjarstýringunni. Ultrasonic skynjarinn er svo framan á bílnum og hefur það hlutverk stoppa DC mótorana ef bíllinn er innan við 50cm frá einhverju, þessa mælingu þar svo að senda til fjarstýringarinnar.

### Fjarstýringin
Hin Arduino tölvan er notuð sem fjarstýring. Við hana þarf að tengja 4 takka (hægri/vinstri/áfram/bakka) eða tvö stilliviðnám (hægri/vinstri og áfram/bakka). Fjarstýringin er líka með LCD skjá en á honum á að birta fjarlægðina sem er mæld með Ultrasonic skynjaranum á bílnum.

### Hönnun 
Notaðu TinkerCad og/eða Inkscape til að hanna og útfæra umgjörð fyrir fjarstýringuna og bílinn (e. body). Frjáls útfærsla.

## Verkefnaskil
Haltu utan um verkefnið á github, þar á að vera:
- Dagbók, hvað gerðir þú og hvenær.
- Kóðinn af báðum Arduino tölvunum.
- Hlekkur á Tinkercad teikninguna af rásunum (Muna að gera teikninguna Public).
- [Skjáupptaka](https://screencast-o-matic.com) af virkni í Tinkercad.
- Hönnunarteikningar af bíl og fjarstýringu.

## Námsmat
1. Uppsetning í Tinkercad (Circuits) (20%)
    - 0% Uppsetning stórlega gölluð (t.d. vantar einhverja íhluti) eða hana vantar.
    - 10% Uppsetningin virkar en er ósnyrtileg og erfitt að átta sig á hvað tengist hverju.
    - 20% Uppsetningin er snyrtileg og skýr til aflestrar. Notaðir eru mismunandi litir á víra og skynsamleg notkun á beygjum á þeim.

2. Kóði og virkni (50%)
   - 0% Vantar eða stórlega gallað.
   - 10% Hægt er að stjórna mótorunum frá bílnum.
   - 20% Fjarlægðarmæling send frá bíl til fjarstýringar og birt á LCD.
   - 30% Hægt er að stjórna mótorunum frá fjarstýringunni.
   - 40% Allt virkar en kóði illa settur upp og ruglingslegur.
   - 50% Allt virkar og kóði snyrtilega settur upp með góðum breytunöfnum.

3. 3D hönnun (casing) (30%)
   - 0% Vantar eða stórlega gölluð.
   - 15% Góð hönnun fyrir fjarstýringu og bíl en byggð er á verki annars.
   - 30% Góð hönnun fyrir fjarstýringu og bíl gerð frá grunni.