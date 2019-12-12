# vote_ss

LES:
Jeg har har satt opp alternativ for gjennomføring av oppgaven rent logisk. 
 
******* Alt 1:
A) Velg Fylke:            Dropdown

B) Velg Kommune:          Dropdown


1.	On load - Les inn fra fil eller fra API direkte til Array(x). Lagre i array etter linje.
2.	Søk gjennom array(x) med en løkke. Print unike fylker 
3.	Bruker velger fylke i printet liste. Valgt verdi lagres i en (ny) variabel(y).
4.	Variabel(y) brukes i nytt søk i array(x). Unike kommuner printes til bruker.
5.	Bruker velger kommune fra listen. Verdi lagres i ny variabel(k). Variabel(K) brukes til å søke etter aktuelle lokasjoner. resultatet printes til bruker.
6.	Bruker ser oversikt over aktuelle stemmelokaler i sin kommune.


******* Alt 2: 
Vil ikke fungere optimalt da postnummer ikke nødvendigvis har et 1-1 med valg-lokaler.
1.	Bruker skriv inn postnummer i inputfelt
2.	Postnummer lagres i variabel(x)
3.	Leser inn tekst eller API i array(a)
4.	Variabel(x) brukes for søk i array(a)
5.	Print ut aktuelle lokasjoner med gitt postnummer til bruker.

