# VESM2VT - Vor 2020
## Lokaverkefni (35%) - Snúrustýrður bíll með fjarstýringu
Í þessu verkefni áttu að nota Tinkercad til að gera frumgerð af fjarstýrðum bíl og fjarstýringu fyrir hann. Í þessari frumgerð notar þú að vísu snúru til að tengja saman bílinn og fjarstýringuna.

## Efnislisti
- 2 Arduino tölvur
- 2 DC mótorar
- 2 Servo mótorar
- LCD skjár
- Ultrasonic skynjari
- 4 Takkar 
- H-Bridge
- 2 breadboard
- Slatti af snúrum og viðnámum
- Annað sem getur verið gagnlegt að hafa

## Lýsing
Bíllinn og fjarstýringin tala saman með I2C staðlinum.
### Bíllinn
Bíllin notar aðra Arduino tölvuna til að stjórna móturunum. DC mótorarnir eru fyrir afturdekkin og keyra bílinn áfram eða aftur á bak. Nota skal H-Bridge með DC móturunum. Servo mótorarnir sjá um að stýra stefunni á framdekkjunum. Hvað mótorarnir eiga að gera kemur frá fjarstýringunni. Ultrasonic skynjarinn er svo framan á bílnum og hefur það hlutverk stoppa DC mótorana ef bíllinn er innan við 50cm frá einhverju, þessa mælingu þar svo að senda til fjarstýringarinnar.
### Fjarstýringin
Hin Arduino tölvan er notuð sem fjarstýring. Við hana þarf að tengja 4 takka (hægri/vinstri/áfram/bakka). Fjarstýringin er líka með LCD skjá en á honum á að birta fjarlægðina sem er mæld með Ultrasonic skynjaranum á bílnum.
## Verkefnaskil
Haltu utan um verkefnið á github, þar á að vera:
- Dagbók, hvað gerðir þú og hvenær.
- Kóðinn af báðum Arduino tölvunum.
- Hlekkur á Tinkercad teikninguna af rásunum (Muna að gera teikninguna Public).
