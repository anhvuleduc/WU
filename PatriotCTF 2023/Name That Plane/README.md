WRITE UP FOR "MARKETING CAMPAIGN" - PATRIOT CTF SEP 2023
---------
Difficulty: Hard

Problem Statement: 

Time to identify some planes. I'd like you to identify the aircraft in the zoomed in picture and the airport it was photographed at.

The name of the plane should include its number ex: If your plane is the Siebel Si 201: Siebel_Si_201

An IATA code for an airport looks like this: Name: Ronald Reagan Washington National Airport IATA Code: DCA

Flag Format: PCTF{NameOfPlane_IATAcodeForAirport}

![airport](https://github.com/anhvuleduc/WU/assets/144676637/baae73ac-9a9d-4ef6-85f4-ae6ba2892297)
![Plane](https://github.com/anhvuleduc/WU/assets/144676637/0c4f2006-a130-47b8-9fbf-5c140eb576e8)

Flag: PCTF{Cessna_208_Caravan_HEA}

MY APPROACH
---
At first sight, I could see that the airport is likely to be an airbase (an airport for military), also it seems to be somewhere like a desert.

After several reverse searches, the two countries that popped up in my engine the most are United States (Area 51) and Afghanistan (Bagram Airfield)

I actually got stucked because the US has too much airbase to brute-force, so I bought a hint (15 points, the problem's point was 480 so I think it is a reasonable compensation)

So hint was: "Try looking in the graveyard of empires"

"The graveyard of empires" refers to Afghanistan (you can see more on Google), so I started to look at Afghanistan. I used this list to scan through all airports on Google Earth: https://en.wikipedia.org/wiki/List_of_airports_in_Afghanistan

(Actually, scanning an airport took about just 1-2 min, you just need to memorize significant features of the initial photograph. For me, these features are: A black line on the middle of the road, a white roofted house with 3 helicopters on 3 corners, ...)

Luckily, when I looked at Herat airbase, I found the exact same place as the photograph. The IATA code of Herat airbase is HEA.

The work left is identify the aircraft. On Google Earth, I zoomed into the aircraft and had a closer view of it. Then, by finding the list of aircrafts of Afghanistan: https://en.wikipedia.org/wiki/List_of_Afghan_Air_Force_aircraft, my teammate found Cessna 208B (seems like its official name is Cessna 208 Caravan)




