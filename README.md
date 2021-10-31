Naudotos technologijos: Node.js, MongoDB, MySQL, Git, Github Destkop, Heroku, Heroku CLI, Postman API, Javascript, Php, FileZilla.

Duomenų bazė.

1.	Periods: Periods lentelė automatiškai užpildoma nurodytais 15 min intervalais nuo nurodytos starto iki pabaigos datos. Šiai užduoties daliai naudojau php programavimo kalbą. Visas esminis kodas yra ignitis suzipintampe folderyje index.php faile. Taip pat pridedu duomenų bazės failą su užpildytais duomenimis.

2.	Data: Paleidus anksčiau minėtą kodo dalį lentelė data automatiškai užpildoma duomenimis pagal nurodytus reikalavimus, vizualiai dalinį užpildymo bei kodo veikimą galima matyti adresu:
https://ignitisassingment.000webhostapp.com/

a) Nurodytas laikotarpis pilnai užpildytas duomenimis.
b) Panaudota daugiau nei 3 skirtingi point_id.
c) Source laukui priskiriama viena iš dviejų nurodytų galimų reikšmių.
d) Pagal reikalavimus viskas užpildoma randomiškai, naudojamos tik teigiamos reikšmės.

3.	Sql užklausą sumuoja mano pasirinktų Rx ir Rw registrų reikšmes, gautą rezultatą grupuoja pagal period_id ir source laukus. (Užklausos faile “SQL užklausos”). Pridėjau porą papildomų užklausos variantų.

API testavimas.

1)	Nurodyta svetainė yra sandboksinta aplikacija kas reiškia jog jokie pakeitimai neišsaugomi. Manau netikslinga daryti automatinius testus svetainei https://reqres.in/ nes galima tikrinti tik response kodus, o tikro veikimo patikrinti neįmanoma kadangi duomenys niekur nesaugomi. 
2)	Todėl nusprendžiau susikurti savo Rest API naudojant Node.js ir MongoDB (darbui norėjau panaudoti bent porą duomenų bazių ir porą programavimo kalbų), ir parašyti automatinius testus šiai aplikacijai. Vartotojai sukurti pagal regres svetainės pavizdį.
3)	Prie nurodyto patikrinti vartotojo sukūrimo ir visų vartotojų sarašo gavimo nusprendžiau pridėti papildomus testus vartotojo atnaujinimo bei vartotojo ištrinimo kad galėčiau pilnai ištestuoti savo sukurtos API crudo funkcionalumą.
4)	Poros savaičių bėgyje planuoju padaryti frontend vartotojo interface jog būtų galima testuoti betkam per naršyklę nenaudojant API testavimo įrankių.
5)	Visas darbo kodas bei failai https://github.com/Vaidas393/Rest-API-and-API-automation-tests
6)	Išsamus darbo aprašymas bei dokumentacija https://github.com/Vaidas393/Rest-API-and-API-automation-tests/blob/main/README.md

