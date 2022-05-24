# ***LetsGrowSmart***
**Indoor Cannabis should not be linked to a 24h day & night cycle**

<br>
but please, read the license first:

```
------------------------------------------------------------------------                 
                           CaCooL 0.1a
               (Care About Carbon OOxide License)
------------------------------------------------------------------------                 

 The licensor expects that his/her/their published knowledge/software/
       hardware could lower the CO2 we leave to our descendants.

                   Do What You Want To Do With It
                     As Long You Care About It!

       There is nothing more important, for the next centuries,
         than to globally share all knowledge and technologies
       especially if it is usable to run our present and future 
                    but with exhausting less CO2.

The licensor just wishes that you "copyleft" all your additional gained
         knowledge/developments/technologies to the world, too!

          You are also free to use all for proprietary stuff...
                 ...then thank you for the CO2 saving!
       But then you are also still a sad major part of the problem!
                 So, get the nonsense out of your brain
              you would been more worth or more important
                than the grand kids of your neighbors!

------------------------------------------------------------------------
Pit Demmer 21-23/05/2022
------------------------------------------------------------------------
```

<br>

## Content

0. **Preambles**

    1. What is it about - try to feel it

1. **Disambiguation**
		
	1. Florin
	2. Day & Night / S_Day & S_Night / Cycles & More
	3. Seedling
	4. Cutting
	5. Clone
	6. Vega
	7. Flower
	8. Indica
	9. Sativa
	10.	Ruderalis / "Automatics"

2. **Timing**

    1. Generic Information
	  2. PreVega
	  3. Vega
  	4. Flower
	  5. Sunrise / Sunset / Clouding
    6. Professional investigation setup

3. **Not that important**

    1. About the initial author
    2. Origin Story

4. **Forgotten And ToDo**
---

<br>

## 0. **Preambles**

<br>

0.1 **What is it about - try to feel it**

The core of ***LetsGrowSmart*** hopefully helps unchaining your mind and technology from the earth given 365 times 24h-Day as something to respect while growing cannabis indoor - 24h are useless at all.  

With practically doing ~5 flower-cycles per year on indoor locations, while knowing that this is far above the max. 2 flowers the nature can do on just a very narrow latitude range - we should get a first feeling that there must be "something" with the plant which can give a "shit" on at least 365. Why not on 24, too?  

But we all also getting kind of daily evidence about the "shit" the plant can give on some of the in nature to expect conditions.  
Day in and day out we magic the indoor-sun within no time on zenith and 12 or 18 hours later, again within no time, we let the "sun" disappear.  
Hey! Come on!  
Even exactly on the equator there is at least a 3/4 hour visible sunrise and sunset but you feel the 1001 changes in temperature and humidity for more than one hour longer   

But a real strange thing seems the switch from the 18:6 to 12:12 timing!  
From one "magic" ON with a 18h burning sun we switch into a 12 hours night instead of 6 hours like the weeks before. And just after that night the sun appears only for 12h from now. Not for 18h like all the weeks before.  
Really?  
Such an magic shift of 6h in the day to night time ratio within just one night? 
On the latitudes where 18:6 and 12:12 exist naturally it takes ~3 months for that shift!  

I hope you got, that the kind we are already switching grow lights on and off has almost nothing to do with the possible conditions a plant has to expect in nature. Please hold your mind as open to tweak around the 24h - as your mind and experience is fine with already tweaking even seasons like a crazy.

<br>

Btw.:  
**The missing sunrise and sunset is a real daily harm to the plants *and the climate* !**  
- Changing the room temperature too fast messes up each time the vapor pressure. Up to that the plant can't "breath" for hours effective! It is also very often part of triggering mould. All lights the same second on/off changes the temperature too fast!   
*Those two effects are more intensive with OldSchool (e.g. HPS) lightning than with LEDs.*  

- Last but not least the plant can not switch the day/night hormones that fast like we switch lamps - each day at least a half hour gets lost at the start of day and even more at the start of night before the plants hormones are out of the worst irritations to get ready to do their specific day and night jobs.  

**But:**
- the rapid 18/6 to 12/12 switch seems not to cause any measurable harm to the plant - even this switch looks related to the natural conditions much stranger.

---
<br>

		
## 1. **Disambiguation**

1.1	**Florin**

- A mix of plant hormones which tells an adult plant if it's time to flower or to stay in vegetative state.
All Cannabis, but not "Ruderalis" aka "Automatics" starts the production of Florin primary depending on the ratio of day to night time they got within the previous day & night cycles.

<br>

1.2	**Day & Night / S_Day & S_Night / Cycles & More (*S = Smart*)**
		
		
- The "Day" and "Night" taking each one flexible part of 24h.  
Depending on your latitude and the season you will get day to night time ratios in between 00:24 to 24:00.  
Just the guys on the equator can enjoy the whole year from a day to night ratio of 12:12.  
Cannabis (like almost all other "one year plants" too) can naturally procreate on the latitudes between "Spitsbergen" and "Patagonia" - but best natural locations seem much closer to the equator than to Spitsbergen.  

- The "S_Night" is long enough to have a perfect resting time and to (not)(depending on vega/flower) wake up with florin.  
- The "S_Day" is not longer than the plant can do efficient photosynthesis before the need to rest, but also as long/short to (not)(depending on vega/flower) destroy florin.  

*To generate best S_Days & S_Nights in analog or PLC terminology you use a "wiper-function" (analog within a range from at least 3h to 12h). To do sunrise/sunset you use the wiper-function as output for the first lamp and as start point of a command series. All other lamps get attached with an OnDelay+OffDelay combination to the previous lamp:*  

```
Wiper---OnDelay1-OffDelay1---OnDelay2-OffDelay2---\\-OnDelay(n)-OffDelay(n)--
      |                    |                    |                           |
    Lamp1                Lamp2                Lamp3                       Lamp(n)
```

<br>

- A regular week is 7 Days.  
- S_Weeks are flexible with a real duration from 4 to 6 Days.  
        
**The age of a plant depends almost just on the sum of day & night cycles. Independent if the cycles are following the 24h model or a smarter model.**

<br>     
                       
1.3	**Seedling**

- A plant germinated from seed. Those plants need after germination 30-50 Cycles to mature into a state to be able to produce Florin.  
 
<br>

1.4	**Cutting**

- 5cm to 20cm long "tip" of a matured plant branch.

<br>

1.5 **Clone**

- A cutting placed on a position (or inside a "system") to get roots.
		
<br>

1.6 **Vega**

- Succesful rooted cuttings and matured seedlings.

<br>		
		
1.7 **Flower**

- Ex vega plants - from the start of producing florin until the day of harvesting.

<br>
		
1.8	**Sativa**

- Bullshit term for more equatorial and more high altitude influenced genetics. They almost need longer to mature and to flower - when driven within 24h cycles.
		
<br>

1.9	**Indica**

- Bullshit term for less equatorial and more low altitude influenced genetics. They are almost faster in maturing and much faster in flowering within 24h cycles.
		
<br>

1.10	**Ruderalis / "Automatics"**

- In opposition to Sativas and Indicas those Cannabis strains make their decision to start producing florin primary on their age and very independent from the daytime to nighttime ratio.  
***LetsGrowSmart** can't give you actually any proven advice how to speed up those genetics!*

---

<br>

<br>

## 2. Timing

2.1	**Generic Information**

- Relatively independent from being in vega or flower the majority of strains can't do more than 8,5h of high efficient photosynthesis within one cycle of day and night time.  
- But those 8,5h can't get realized within less than 10,5h - 11,5h hours. You have to do time lapse of your grow to find the many 15-30 minutes which sums up to this "lost" 2-3 hours where the plants need some clouds more than direct sun.  
- Also relatively independent from being in vega or flower the majority of strains does absolutely not need more than 4,5h of resting time to get the metabolic night shift done.  
- Just for the optional production of florin you have to add around 1,5h to the least nighttime within a cycle.
- To not destroy the florin during daytime, the daytime can't be much longer than the nighttime. But as longer the nighttime is, as higher the difference between day and night time can be.  

Following, a few timing advises describing very basic testing scenarios where Indica and Sativa strains will safe work to show their least capabilities within a smarter timing cycle than the common 24h based ones. Some smarter timings are even to realize with 24h based time-switches!

*The "Quality" is a very rough estimation how close this setup is to the best possible setup. How to get closer to the best setup see 2.5.  
But as a homegrower please start with just doing one room/tent your conventional way and a second room/tent with a setup out of the basic smarter ways 2.3 - 2.4.*


<br>
		
2.2 **Pre Vega**

As long the plants try to build roots (the first 14 - 21 cycles) is not a lot metabolic work to do during the night.

| Quality |	std. timers | Sunrise (h) | Day (h) | Sunset (h) | Night (h) | Repetition (h) |
| ------- | ----------- | ------- | --- | ------ | ----- | ---------- |
| 50% | yes | 00:00 | 9,5 | 00:00 | 2,5 | 12:00 |
| 66% | yes | 01:00 | 7,5 | 01:00 | 2,5 | 12:00 |
| 90% | no | 01:00 | 8,5 | 01:00 | 2,5 | 13:00 |

<br>

2.3 **Vega**

| Quality |	std. timers | Sunrise (h) | Day (h) | Sunset (h) | Night (h) | Repetition (h) |
| ------- | ----------- | ------- | --- | ------ | ----- | ---------- |
| 40% | yes | 00:00 | 7,5 | 00:00 | 4,5 | 12:00 |
| 66% | no | 00:00 | 9,5 | 00:00 | 4,5 | 14:00 |
| 80% | no | 01:00 | 8,5 | 01:00 | 4,5 | 15:00 |

<br>

2.4 **Flower**

| Quality |	std. timers | Sunrise (h) | Day (h) | Sunset (h) | Night (h) | Repetition (h) |
| ------- | ----------- | ------- | --- | ------ | ----- | ---------- |
| 25% | yes | 00:00 | 10,5 | 00:00 | 13,5 | 24:00 |
| 33% | yes | 02:00 | 8,5 | 02:00 | 11,5 | 24:00 |
| 66% | no | 01:00 | 8,5 | 01:00 | 9,5 | 20:00 |

<br>

2.5 **Sunrise / Sunset / Clouding**

**To be able to reach out highest "qualities" we must be able to simulate sunrise and sunset in a nice scale!**  
**There is NO way around sunrise and sunset!**  
*Figuring a helpful clouding need many repeated generations of doing time laps after set up the clouding "better" with the results from the previous generation. Totally not worth to investigate in clouding before the best day to night ratios and sunrise/sunset are known!*

**As more lamps you have in as bigger rooms - as more you can reduce the total need of night time and as better you can fill the 8,5h photosynthesis capability without the need to waste too much power and time.**
		
It is tricky to describe the whole system which need to get adjusted to reach out "best qualities" - cause it is
very strain and phenotype depending too. Therefore the examples above are just safe enough to not get frustrated while having the first date with a "new" technology.
- In common it is easier and more realistic to get a regular 11-WeeksToFlowerStrain perfect done within 8 weeks than to reduce a 8-week strain down to 6 weeks.  
*Not the 6 weeks will be the problem but there is a point where the costs of quantity loss are getting greater than the energy and time savings. This happens statistically earlier with "Indica" strains.*

<br>

2.6 **Professional Investigation Setup**

Most important to know first is investigating "florin set and reset sensibility" without using sunrise or sunset. 

| Test No. |	Day (h) | Night (h) | Repetition (h) |
| --- | ----------- | ------------- | ---------------- |
| 1.1 | 12:00 | 12:00 | 24:00 |
| 1.2 | 10:30 | 09:30 | 20:00 |
| 1.3 | 10:30 | 08:30 | 19:00 |
| 1.4 | 10:30 | 07:30 | 18:00

<br>

<br>

With 9 of of 10 strains the next step is to look how the same setup is working but with a 45 minute sunrise and a 75 minute sunset if using "Hot Lamps" (HPS/HMI). Use an equal relationship for "Cold Lamps" (LED/fluorescent tubes).  

*So, if you are in a hurry you can set up the first 8 tests at the same time.*  
**BUT:**  
- 3 lamps on 3m² in a tent behave in sunrise/sunset less effective than 10 lamps in a 30m² room. Both setups are better than working without sunrise/sunset but in best case they can reach just 20% and 33% of the possible sunrise/sunset efficiency.  
- But if the 30m² gets 30 lamps (same density like the tent) we are close to perfect for this room - just if the room is rather 3m x 10m than 5m x 6m would make the difference if it is rather 99% or 90% perfect.
- Simple: If it's still too dark to read something below the latest starting lamp when the first lamp starts - you are running a nice setup!  

<br>

| Test No. | Sunrise (h) | Day (h) | Sunset (h) | Night (h) | Repetition (h) |
| -------- | ----------- | ----------- | ---------- | ------------- | ---------------- |
| 2.1 | 00:45 | 10:00 | 01:15 | 12:00 | 24:00 |
| 2.2 | 00:45 | 08:30 | 01:15 | 09:30 | 20:00 |
| 2.3 | 00:45 | 08:30 | 01:15 | 08:30 | 19:00 |
| 2.4 | 00:45 | 08:30 | 01:15 | 07:30 | 18:00 |

<br>

<br>

If 1.4 and 2.4 gives both still flowers within a timing better than x.1 we have to dig deeper:  

| Test No. | Sunrise (h) | Day (h) | Sunset (h) | Night (h) | Repetition (h) |
| -------- | ----------- | ----------- | ---------- | ------------- | ---------------- |
| a3.1 | 00:45 | 08:30 | 01:15 | 07:00 | 24:00 |
| a3.2 | 00:45 | 08:30 | 01:15 | 06:30 | 20:00 |
| a3.3 | 00:45 | 09:00 | 01:15 | 07:30 | 19:00 |
| a3.4 | 00:45 | 09:30 | 01:15 | 07:30 | 18:00 |

<br>

<br>

If 1.4 or 2.4 does not flower or time to harvest takes longer than x.1 we raise the daytime from the best out of the 2.x & 3.x setups. In case of 2.1 we have to generate this raise by shorten the sunrise/sunset.  

**From now latest we have to monitor power usage exactly!**  

We're already growing in all setups on a level equal or better than 12:12!  
We almost can't see/feel anymore which setup the most effective might be, cause all setups will differ with the day of harvest by +/- 10 days, every setup will additional differ in the power usage until harvest. Last but not least will the yield also differ:  
*All time two realistic cases possible why the setup with the lowest total weight, or the setup with the highest power usage or the most time taking setup can still be the most efficient one!*

| Test No. | Sunrise (h) | Day (h) | Sunset (h) | Night (h) | Repetition (h) |
| -------- | ----------- | ----------- | ---------- | ------------- | ---------------- |
| b3.1 | 00:30 | 10:30 | 01:00 | 12:00 | 24:00 |
| b3.2 | 00:45 | 09:00 | 01:15 | 09:30 | 20:30 |
| b3.3 | 00:45 | 09:00 | 01:15 | 08:30 | 19:30 |
| -------- | ----------- | ----------- | ---------- | ------------- | ---------------- |
| b3.4 | 00:20 | 11:00 | 00:40 | 12:00 | 24:00 |
| b3.5 | 00:45 | 09:30 | 01:15 | 09:30 | 21:00 |
| b3.6 | 00:45 | 09:30 | 01:15 | 08:30 | 20:00 |
| -------- | ----------- | ----------- | ---------- | ------------- | ---------------- |
| b3.7 | 00:15 | 11:30 | 00:15 | 12:00 | 24:00 |
| b3.8 | 00:45 | 10:30 | 01:15 | 09:30 | 21:30 |
| b3.9 | 00:45 | 10:30 | 01:15 | 08:30 | 21:30 |

Some strains could start to react sensible in setups 3.6 / 3.8 / 3.9.  
Depending on all other parameters we could see a sense in extending sunrise/sunset from the daytime part.

Impossible from now to give further advice without real results - math will tell us more precise whats up and if more practical testing is needed. Normally not!

**But you can count on to never do the full range of setups from above again.**  
*After you once experienced that 24h based flowering setups are all not as effective as most of the 18h to 21h ones.*

---

<br>

## 3. Not That Important

<br>

3.1 **About the initial author** 
		
Born in 1967 - growing Cannabis since the early 80s. Three kids and actually seven grandchildren.  

Educated toolmaker + media-designer (software & print) and instructor for youth and adults inside the German "DualEducationSystem.  
But most jobs in life were initially supposed to be industrial engineering with a slight focus on Soft- and Hardware development over the mechanical constructing - but finally was this never enough and I got a kind of a walking library and toolbox for everyone in need - but principally free just to do what I thought makes the most sense. I had to deep learn a lot technologies and machinery. The time I spent on work I added in privacy to really learn all the things on a rock solid level. With fun! I have to say thanks to every single company I got educated or worked for since I left school in 1985.
				
All ***CannaParts*** projects will soon get their repositories on Github.
		
The "brands" ***CannaControl***, ***CannaClocky***, ***LetsGrow***, ***CannaParts*** are used by me since up to 30 years.
		
I am publishing this at a point I went bankrupt and into debts caused by much too long financially and physically supporting a ~~medical cannabis~~ investment scam project in Denmark - shit happens.
The left tragedy is that the debts are that hard to handle, that I can't support and maintain the ***LetsGrowSmart*** and other ***CannaParts*** projects the way I should.
		
If you are a rich guy and you want to help speeding up to save up to 20% - 33% of the CO2 exhausted by cannabis indoor grows...
...**please let me know** !

<br>

<br>

3.2 **Origin Story**

When my first seed germinated in 1981 there was no internet, no books, no friends - just my mother: "You can do this in your room but not in the garden - AND YOU HAVE TO STAY AWAY FROM THE SCENE!"  
I was good and it took nearly 5 years until I touched the 1st time the scene and hash.  

It also took me under this accepted isolation two and a half years to get my first (trash)flower done. And to be honest, it was more an "accident" that I had for long enough a working day to night ratio running!  
But I interpreted the accident right and had already made at least 10 flowered grows when I heard the first time about indoor growing would be done in the US too and they would use 18:6 / 12:12 day to night ratios.  

I was that time using day to night ratios around 13:11 to 14:10 but with (too) heavy sunrise, sunset and clouding + rain + storm - I even collected all kinds of spiders and bugs of the season - cause I could not imagine at all that a full synthetic environment could reach out something - I was 14-15 during this "zero clue" but "endless interest" times!  

Close to 10 years later a friend was massive struggling with the crazy flowering behavior of Haze in the early 90s.  
As a joke I said: "This taste is absolutely worth to say good bye to the earth and to search for a lift to a faster rotating planet".
My friend didn't got the joke and I had to explain. While explaining it felt totally not like a joke anymore.  

As a first proof of concept we scaled down all times by 50% on some vega plants (it probably was a 8,5:3,5 day:night ratio)  
After they really survived their first week we made "party".  
One more week and we got totally crazy - cause all 12h cycled plants were at least as good looking as the 24h based ones.  

So, if the plant can perfectly do vega on a double fast rotating planet... why not flower too?

YES... but:  
Even that flower is possible on 12h repetitions, I only know one reason to do - as part of the fastest way to get the gender of "regular" seedlings - but even in this case, the speeded vega is saving same or more time than the time gained by speeding up the flower.  

Latest from 2000 then I had vega and flower on many different strains with nearly all possible repetitions from 12h to 36h in a one hour resolution done. 

From 2018 to 2021 in Denmark under legal conditions, endless growing space, a perfect lab and some very cool scientists on board we looked professional into many effects I was able to handle but without a real clue why the plants reactions are like they are.  
It all was almost about a delayed/stressed/suppressed Metabolism and/or suppressed/wrong Hormones. Sunrise/sunset are the key elements to keep tweaked plants happy! The common tweak to magic sun on zenith within no time is the dumbest and most energy wasting, but working, tweaks you can do.

---

<br>

## 4. Forgotten & ToDo

- instead of messing up a harvest while "accidentally" on holiday, we can stretch the flower easily nearly as hard as we can compress.  

- cheap weed - just waving multiple sunrise to sunset - like clouding.
