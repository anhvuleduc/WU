WRITE UP FOR "MARKETING CAMPAIGN" - PATRIOT CTF SEP 2023
-------------------------------------------------------------------------
Difficulty: Hard
Statement: 
Greetings analyst! As you know, our recent attempts to acquire a very lucrative contract failed when our customer decided to go with a Swedish competitor instead. Unfortunately, the SkyTractor-9000 and its munition the VFFR (Very Fast Flying Rock, accurate to within a 1m^2 by 1m^2 zone!) were very expensive to develop and build, and we only ended up building one SkyTractor-9000 . Thankfully, we have a plan to ...convince our customer to reconsider the contract and get more money to build more. This is where you come in.

We need you to find the location of the aircraft in the rightmost part of the photo (the one between 06 and 05). Don't give us latitude and longitude, we need a form of geolocation more precise and reliable than that (that involves using 3 words) for our needs. Try to get your location right on the intersection between the yellow lines in the middle. Our pilot will handle the rest from there. Good luck!

Flag format: PCTF{}
![Plane](https://github.com/anhvuleduc/WU/assets/144676637/fbe16ba1-ce40-4c13-a72b-bac2fad30efb)

Flag: PCTF{poster.reapply.voted} 

APPROACH
---------
From the first observation, I could see that the airport is likely to be an airbase (an airport for military), and the aircrafts are fighter aircrafts.

Also, from the problem statement, I though it seems reasonable that the aircrafts are made by the "Sweden competitor". Additionally, the airbase is placed in a country that purchase these Swedish aircraft (actually during the competition, I looked through Swedish airbase first and then came up with that initiative)

After reverse image searching of the aircraft (I cropped it from the original image and searched on Yandex), I found out that the aircrafts are Saab JAS 39 Gripen, you can see more details here: https://en.wikipedia.org/wiki/Saab_JAS_39_Gripen
Through Wikipedia, I also knew that there are just several countries possessing this aircraft, which are: Sweden, Czech Republic, Hungary, and South Africa)

I started searching through airbases in these countries with Google Earth (from Sweden (actually I should had ruled this out at first) to Czech Republic and end up in Kecskemét Air Base (Hungary))

Now, the work left is quite easy, the form of geolocation mentioned in the statement is 3- word location (which divided the Earth into squares and assigned each square with a corresponding tuple of 3 English word) I found the flag after locating the square on https://what3words.com/factor.boast.vote
