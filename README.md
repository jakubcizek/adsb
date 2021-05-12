## Data z ADS-B přijímače

**planes.json je pole se zaznamy pro jednotliva letadla**

Priklad:

    {"hex": "43EA06", "seen": 8014, "callsigns": ["MABGV"], "category": "A2", "firstseen": 1590136105, "lastseen": 1620087867, "aircraft": "Learjet 45", "registration": "M-ABGV", "airforce": false}

 - **hex:** ICAO 24bit ID (https://www.icao.int/NACC/Documents/eDOCS/Fasid/GRP15Agenda3APXs%20AIC%20para%2024%20bits%20address.pdf)
 - **seen:** pocet detekci od jara 2020
 - **callsigns:** pole s volacimi znaky behem pruletu
 - **category:** kategorie letounu (https://discussions.flightaware.com/t/customizing-aircraft-icons-in-piaware3/18875/2)
 - **firstseen:** unix timestamp prvni detekce
 - **lastseen:** unix timestamp posledni detekce
 - **aircraft:** model letadla
 - **regstration:** registarce/rejstrikova znacka (ceske OK-: https://www.caa.cz/letadlova-technika/letecky-rejstrik/)
 - **airforce:** myslim si, ze se jedna o vojensky/vladni letoun? (analyza volacich znaku a modelu, zatim nekompletni)
