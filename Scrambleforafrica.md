# Introduction

This file contains all the information that is usefull for optaining as many colonies as possible in Victoria II Greater Flavour Mod. It also explains the process in with they are gained, so player can try to prevent their colonization by other nation. For example you can prevent UK from taking Nigeria by conquering just Lagos in the early game and conquer it with free casus beli that you get from Berlin Conference.

# Important topics

## Vaniia/Stock colonization

In GFM almost every colonial province is scripted somewhat and colonization mechanic is mostly used as a last resort, for example if you crippled the Italian or German unification. However, even in that case their colonies (like Cameroon & Eritrea) can still be colonized in scripted action by other countries. Actions almost every time means decision or event, commonly a combination of both.

## Life rating

GFM did micro on LF. This is mostly to block provinces from colonization. The highest LF in 1830 is 48 - for Frankfurt.
Most provinces have 35 LR however. Just like in the base game, by getting inventions you can access those lands to colonize them.

- Prophylaxis against Malaria (in `Medicine`, avaible from 1830): **-5**
- Mission to Civilize (in `State & Goverment`, but avaible only from 1850): **-10**
- 

## Berlin Conference

This is the single most important event in a way for Europeans to dominate the world. It is one of the most important events in the mod.
This event sets a single very important global flag, `berlin_conference` that leads to many events and decions, but most importantly it allows you to use a **uniqe free casus beli against most african natives**.

`Scramble for Africa.txt - 95500`
It can be triggered by a great power nation with a capital in Europe, either being a colonial nation, or owning land in Africa.
Most importantly, they need 3 inventions:
- Prophylaxis against malaria
- Mission to civilize
- Colonial negotiations

The first one is the Medicine tech and is obtainable from the game start (1830).
The second is in State & Goverment, reserchable from 1840, but optainable only after researching 1850' techs.
Last one is the most important, since it is a time bottleneck for the entire event.
It is in the Breech-loaded Rifles (1850 tech), but optainable after researching 1880' techs.
If you are prepared, you will get it it within few months after geting first 1880' tech.

Finally, it has a `MTTH` of 6 months, shorter if your capital is Berlin, increasing chance to be trully Berlin conference.
Otherwise, it is named after capital of nation that got this event. It also gives 25 base prestige.

## The Dark Continent invention

It has a complex requirements, while giving final -5 min life rating. Here it is reqirements:
You CAN NOT get it if you are not a great power with any of those flags:
- congo_master
- historical_congo
- civilizing_congo
- If you have **colonial_reailroading** (it is enabled by deafult):
    - It CAN NOT be discovered after 1895, unless the Congo conference have happened
- If you disabled it:
    - You need 1 more tech or 2 other increasing factors listed below
Now to actually get it, you need any of those techs, but having more of them incrases your chances greatly
- Biologism (1850 tech)
- Military Logistics (1870 tech)
- Steel Streamers (1880 tech)
Other factors also help to get it, but less
- Any great power have that invention
- Your neigthbour have it
At the same scale these factors also can block you from getting it, forcing you to get more of above factors:
- Being at most secondary power
- Having rank worse than 16

## Occupation uncolonized provinces

In 1830 there are many empty provinces. All of them are colonized through decisions, events or a combination of booth.  
They are colonized this way from early game even into the late game.
In 1830 there are 3 uncolonized provinces in the western Sahel, south of Sahara. All of them can be colonized by local countries, but they can find it dificult.

### Gao

### Koro

### Kedugu

# Africa

Africa is in 1830 dominated by *uncivilized* natives, many of them have a very hard time westernizing. This ensures their status until their unprecedented colapse in the **Scrable for Africa**. Worth noting is Egypt that is the most advanced country on the continent, being an Ottoman subject. There are also coming Boer states in the south that are westernized. Finally, there are many growing European coatial colonies dotted all across the continent.

## Algeria
In 1830 it consists of a 4 countries and big swats of uncolonized Sahara to the south. The biggest country is Algiers, that is also overlord of Beylik of Constantine, Ait Abbas and Tuggurt. Additionally, one of Constantine's provinces is in the Tunisia state.
Algeria is conqered by France through many wars and Sahara is taken by anexation of local rebelion + *The Saharan Frontier* decision.
Tags there can be very missleading, here is a table explaining them:

| Tag |Base name|      Real name      |
|-----|---------|---------------------|
|`RGA`| Algiers |       Algiers       |
|`LBY`|  Libya  |Beylik of Constantine|
|`ABA`|Ait Abbas|     Beni Abbas      |
|`TUG`| Tuggurt |      Touggourt      | 
|`ALD`|Aldjazair|      Aldjazair      |

### War for Algiers
`1830_GFM_FRA.txt - france_bullies_algeria`
This is a very simple decision for great power France at peace if Algeria still owns Algiers.
It reqires to be at least **May of any year**, so you can miss it and have to wait to May 1831 to do it.

Algeria relases and breaks aliances with Ait Abbas and Tuggurt and get a feedback event.
Finally, a war is declared upon them with *Punitive Expedition* CB (`treaty_port_casus_belli_no_infamy` exactly).

After France wins, they can take one of two Algerian treaty ports, Oran and Algiers.
`AI` will always chose Algiers since decision for Oran have a check that forbids its taking by `AI` if they do not own Algiers.

> If France does it within 1830-1835 window, all pops from Great Slave Lake will be moved there and given 1% more literacy. This also happens in the setup that `CLN` does at every campain start. This is probably to give Algiers first French settlers along with their slaves.

### Breakup of Algeria
`1830_GFM_FRA.txt - 16151852`
If France have won this war before 1835, they get an event that splits Algeria. They yet again relase their subjects, lose cores, Algeria itself is split into half with Aldjazair. A civil war brokes out, leaving only Touggourt neutral.

> If Algeria wins, they will get research points and can be added into Ottoman SOI
> Algeria do not lose core on Bathnah - probably a mistake, because it has a high (suggesting new new) id

### War for Oran
`1830_GFM_FRA.txt - oran_french_war`
After wining the first war France can easily begin next. They just need to be at peace, hold Algiers and wait untill **1831**.
They will declare war on Algeria with *Punitive Expedition* CB if they still hold Oran. This decision even ignores truce between them.
After taking this treaty port they also gain POPs there, this time from Lake Anthabasca.
> Truce breaking from decisions like that still leads to presige loss and infamy gain

### War fo Ennab
`1830_GFM_FRA.txt - bone_french_war`
Another war that ignores truce. France can do it when at peace while owning Oran from **1832** if `RGA`, `ALD` or `LBY` owns Ennab.
This just declares another Punitive Expedition war against its owner.

### War for Bougie with Ait Abbas
`1830_GFM_FRA.txt - bougie_french_war`
It works literally the same. France just declares a war on them if `ABA` own Bougie. They again just need to hold Algiers and wait untill **1833**.

### Battle of Macta - conqest of Algeria
`1830_GFM_FRA.txt - 17051919`
It trigers for France owning any Algerian core in short time window: **May-December 1835**. It declares another war on Algeria and Aldjazair with *Establish Protectorate* CB, again ignoring potential truce.
> As player you can also chose to not declare these wars in that event, losing prestige

### French settlement in Algeria
`1830_GFM_FRA.txt - fund_french_settlement_in_algeria` & `1830_GFM_FRA.txt - 160518542`
This easy decision gives France coresponding event that has 3 options, neighter costing anything. The first increases French settled POPs, gives them some cash and increases size their slaves POPs, the second omits that slaves part and the third reduces prestige. There is no `AI` weighting there as in entire file.

### Conqest of Beylik of Constantine
`Algerian_War.txt - 372382`

### Rebelion - anexation of remaining states
`Algerian_War.txt - 37240`
___

## Indian Ocean Teritory

This state is in 1830 owned by UK and France, with exception of Comoros & Mayotte.
First one is uncolonized, second is an unciv OPM - Mahori Sultanate.

They are quickly annexed by France by uniqe `colonial_railroading` decision: `France.txt - annex_mayotte`.
France needs to be a great power at peace with `Medicine` technology that they get fairly early. Mahori Sultanate must be `AI` and Comoros must be empty.

> Probably the only way to get them before France is to conqer Mahori, since **its 1 infamy max** and colonize Comoros by hand since they have 30 life rating, enabling colonization after geting just `Prophylaxis against Malaria`.

___

## Namibia

### Walvis Bay & Penguin Islands
`Colonial railroading` `berlin_conference` event (`MTH` of 1 day) - `BoerWar.txt - 98260`

Rank 16+ country owning both Cape Town AND Springbok (O'okiep) while target provinces are empty with 10k to pay.
Probably Easter Egg or mistake, all pops are moved from Walvis Ridge ocean province into Penguin Islands.

> You can do this decision with ease if you took Cape Town. Otherwise you will have to take infamy to take them

### Germany takes Namibian core - Luderitz Expedition

`FlavourModAfrica.txt - luderitz_expedition` `colonial_railroading` decision

3 mainland Southern Namibian provinces needs to be empty & Dithakong, Tsabong and Walvis Bay cannot be empty
Country needs to be a German-like state owning Bremen or Wilhelmshaven (read code for more details)
Is at least 1880/81/82, depending on techs and if GER is doing that
Have `Nationalism & Imperialism`, 2MLN+ POPs, be 16+ rank, cannot be pacifistic and have <5 war exhaustion.
Player also needs 55+ ships and 50k to pay.

> If you do not prevent German unification from including Bremen & Wilhelmshaven (Oldenburg sells it to Prussia), you can really only take those ports for Infamy or devastate them at war until you will colonize Namibia thanks to `The Dark Continent`

## Rhodesia

## Cameroon

### Adamawa expands
`decisions/Yakutat.txt - conquest_south_wafrica`
This decisions allows any country owning specified provinces to expand southwards since 1840.
In this case, Adamawa takes Ngundere & Gembu

### Ambass Bay - temporary colonized by UK
`decisions/Yakutat.txt - colonize_ambasbay`

`Colonial railroading` decision avaible for the UK if said province is empty or owned by a uncivilized AI
They need to be a great power at peace, not disarmed, with Nationalism & Imperialism tech and 20+ ships.
In short, province will be renamed and given to the UK. It will happen in 1850+ because of techs.

### Begining as the German colony
`decisions/FlavourMod_Africa.txt - german_west_africa`

Colonial railroading decision avaible from 1880 to Germany, GCF, or "North German state".
They need to be a great power monarchy, have prophylaxis_against_malaria, mission_to_civilize, steel_steamers techs and colonial_negotiations invention.
They also need 2mln+ POPs, not be disarmed, at least 3 ports, less than 5 war exhaustion and cannot be pacifistic.
Finally, player also needs 75 001 funds and 55 ships
Deido province needs to be empty or owned by an uncivilized AI

Germany then gets 2 infamy, southern Cameroon is transfered to temporary tag and some provinces are renamed.
Fusab and Ambass Bay owners (if any) are asked in events for the transfer of said provinces. Their AI will always agree.
If UK player will contest, Germany will get a casus beli on them,
but AI Germany will be chill agains UK player that resisted transfer, not taking said casus beli.
Finally, all provinces are transfered from temporary tag to Germany and German player additionally pays 75k.

### Expansion to Adamawa state
`decisions/FlavourMod_Africa.txt - take_kamerun_interior`

Its 1882 and previous decision was taken (so only Germany can do this one).
Any of Adamawan STATE provinces is owned by uncivilized AI and Germany owns Fusab and Bangante

If UK owns Wukari and uncivilized Adamawa owns Yola and Dumboa, UK gets those from them. If Wukari is owned by Sokoto, they will get these instead.
Owner of Adamawa STATE is then asked for transfer (AI will never contest, otherwise Germany gets casus beli).
If they agree, Adamawa STATE is transfered to Germany throught temporary tag.
There is also misspeel with province id but it looks like it does not affect the decision.

### Expansion to Marva state
`take_entenschnabel`

Technicly colonial_railroading decision avaible to country that took german_west_africa decision (basicly only Germany).
It is at most May any year from 1884, country needs to own Garwa and any province of that state needs to be owned by an uncivilized AI.

It instantly transfers uncivilized AI provinces from that state, ones owned by a civilized nation will be transfered through
event that AI will never contest. Otherwise Germany gets a casus beli.
Disclaimer: it is impossible to even be taken if A WHOLE STATE IS NOT owned by an uncivilized AI.

## Togo

Togo can be colonized by most european countries by just one `colonial_railroading` decision (`FlavourModAfrica.txt - claim_togoland`), however German `AI` have easier route to it.

Lome is empty or owned by uncivilized AI
**`RUS` and `TUR` cannot do it**, nation needs to have a capital in the Europe and `berlin_conference` has happened

Since so many counties can do this decision, it is important to prioritise this one, here is its requirements:

Country cannot be pacifistic, have <5 war e. and have 3+ ports,
Next there are 3 ways to do it, a case for colonial nation, one for vice versa and third for German AI doing this decision:
- Germany:
`GER` or `NGF` `AI` just needs to literary exist
- Otherwise:
2MLN+ POPs, be a great power, revolution_n_counterrevolution
- If already colonial nation:
steel_steamers and blue_and_brown_water_schools techs and 30+ ships
- If not:
naval_statistics or blue_and_brown_water_schools tech and 50+ ships

In short, if AI formed Germany (Prussia will always form it even without any other nation), probably the only easy way to get Togo is to keep German war exhausion high.

If finally done, Togo is given and if civilized country owns any part of it, they will be asked to transfer it. AI will never contest, otherwise claimer will get a casus beli.

## Liberia

### Independence and early colonization
Liberia begins as uncivilized American OPM subject. Event `FlavourMod_USA - 441266` trigered in **1847** relases it and gives it Teysa and Tabu provinces.
As USA player, you can also play as it or annex Liberia with those extra provinces.
Whatever happens with these event, Liberia is still in US influence or annexed.

### Expansion
In short, `Liberia.txt - 441277` event will easily triger in 1874 (`LIB` player can speed this up?),
it will give Liberia its modern borders and one extra province in every direction.
This is fairly complex event, its resoults may give Liberia more provinces?

## Ivory Coast

### First colony - Fort Nemours (Aboisso)
`Colonial railroading` decision - `Sitka.txt - fort_nemours` can be taken by great power France since 1840 (1843 automaticly) if they are at peace.
France gains it and province name is changed. If some nation owned Aboisso earlier (few tags are listed), it is stil taken and bad event is given to the loser.

### Mainland Conquest
`Colonial railroading` decision `FlavourModArfica.txt - ivory_coast_conquest` can be made by almost any contry - you can take that oportunity.

It must be at least 1875, country needs to own Fort Nemours, have 2MLN+ POPs, be 16+ rank, have nationalism_n_imperialism tech, have 50k to spend,
be independent, not disarmed, at peace and Sassandra and Subre needs to be empty.
If you are not **FRA tag**, you need to wait until 1882. AI France can get this without spending 50k.

This decision gives in short every empty province in Windward Coast state plus Man province.
Disclaimer: Liberia can take Tabu and Guiglo earlier and they will not be given.
Names of 2 provinces are changed and war is declared against Wattara and Baule to annex them, but only if they are uncivilized AI outside of anyone SOI.
For some reason BZD is also a target.
Defending countries gets a casus beli against France, making it impossible to intervine on their side as a great power.

Search Plig in `events/Yakutat.txt`

## Senegal

### African minors actions

Bundu starts with a war of conqest against Wolof, while being weaker country.

### The Occupation of Seju
Yakutat.txt - sedhiou_conquest decision gives Seju province. It is not fixed to France.
It is avaible to civilized country at peace, owning Dakar OR Kahone OR Ziguinchor while Sejuand and Bigona are empty.
However, to actually do this decision, you need to own Dakar or Velingara. **It can be made since 1836 in months September-December**.

### The plan of 1854
Yakutat.txt - plan_of_1854 is a decision avaible to FRA or BOR tags owning St Louis, that do not own Babae or Xhouma.
France also needs to be at peace and not disarmed. **It is avaible well, from 1854**.

**It gives 4 infamy, but only to a player**, declares war with unique casus beli on any uncivilized country owning Babae, Xhouma, Mataam, Bakel, Kaedi, Bulibani or Xaayi.
Enforcing this casus beli on a country annexes it, but only provinces specified in decision are taken. 
Defending nations gets a buff and a casus beli, making intervention as a great power impossible.

### Maba Diakhou Ba's Jihads
Yakutat.txt - 184825379
**Event in a short time window: March-December 1861**, that happens to animist owner of Kunghol.

It spawns Badibu in Kunghol. NOTE: It is a modified tag from kurdish Ottoman subject. Ottomans annex them in 1848, leaving this tag free to use.

Thanks to Yakutat.txt - launch_jihads_diakhou decision they made in **1865** they send ultimatum to Wolof, Saloum and Sine. Wolof converts to islam, while the rest reject the ultimatum.
Due to this, war is delared on them.

### Claim the Kayor Coast
This is a decision (Yakutat.txt - dakar_stlouis_railroad) is not restricted to France. You need to be a civilized country being at peace and not disarmed, owning St Louis and Dakar, while Kayor owns Mbul.
**AI can take it from 1863, while player from 1855** while having nationalism_n_imperialism and medicine techs.

It instantly gives you Mbul with 2 raiload lvs and declares war of conquest on Kayor for the **cost of 1 infamy**.
Since Kayor gets a casus beli, it is impossible to intervine.

### Appointment of Louis Briere - conqest
FlavourModAfrica.txt - appoint_louis_briere **colonial railroading** decision is avaible to great power France **from 1865**. Kedugu and Sitakili must be owned by France or by uncyvilized nation.
France must have 2MLN+ POPs, cannot be disarmed, be a colonial nation, have nationalism_n_imperialism and raider_group_doctrine techs, 3+ ports, and less than 5 war e.
Player also needs 45+ ships on top of that.

**It gives 5 infamy**, declares war of conqest on Kedugu owner and gives a casus beli of conqest on Orungu.
Defender gains casus beli, making intervention impossible, but against Orungu France gains just a casus beli, so intervention is possible.
It can be possible to lose that casus beli since Tenda can easily be a subject of Futa Jallon.
Note: AI will accept it even while having over 22 infamy, going over limit due to error in the code.

### Big invasion
FRAFlavor.txt - 37241 event. It can happen **from 1870** to a great power France at peace owning Dakar, Mbul and St Louis.
Jaxaaw, Kahone and Kunghol owner/s must be uncivilized, AI, or France, so if european AI got it it can still trigger.

It has 2 options, but only first is interesting.
**It gives 3 infamy** then, if **conolial_railroading** is not disabled and AI Trarza is not in any SOI and with no truce with France, it gives 500 influence over it, instantly adding it to SOI.
War is declared upon Sine, Saloum, Toro Imanate and Wolof if there are not truce with them. Read code for more details, since some of them may not be a target.
For some reason Bayazid is again listed there, but event works fine.
Same can be said about The Toro Immanate and Wolof, that should you should get a casus beli against, but it again does look like to work.
It is probably due to complex casus beli system giving *establish_protectorate_casus_belli* but it cannot be used why you have Nationalism & Imperialism tech, making it useless.

Theoriticly it is possible to prevent France from taking this option, if they have large infamy. They also theoreticly would take it even over infamy limit.
Note: Appointment of new Senegal Governor is not necesary for it, despite being directly linked historicly.

### The Ocupation of Bignona
Yakutat.txt - fogni_conquest decision is not limited to France. It gives Bignona.
You need to be civilized, own Seju or Soma province, Bigona must be empty, additionally, you need to own Dakar or Velingara and Seju cannot be empty.
Finally, you need to **own Velingara while having colonial_negotiations invention or just wait until 1883**.

### Border exchange
Velingara can be echanged for Kansala throught border exchange. Read another paragraph for details.

##  Guinea

Guinea have a few unciv nations and uncolonized provinces. It will be dominated by Jallom Immanate before the Scrable for Africa.

### African states actions

#### Creation of Kabadugu
In 1848, right after BZD tag is annexed by the Ottomans, they are spawned as Kabadugu in Odiene with Sinko province.
Kong that lost provinces to it also gets Man province.

#### Wattara Gwiriko conflicts
These countries ends up in war set by events, potentially by Gwiriko's secession. Events:
`Yakutat.txt - 184900011 18490002`

#### Jallon Immamate Conqests
Jallon declares a war against Tenda in **1856** to subjugate them (`Yakutat.txt - invade_tenda`).

- `events/Yakutat.txt - 184900211`
If previous decision was taken, after wining war with Tenda, the *Treaty of Yimbering* happens. It has additional reqirements but it does not matter really.
It gives Jallon Yimbering and colonizes Sangaredi and gives 5 prestige. It has `MTTH` of just 1 day.

- `decisions/Yakutat.txt - invade_kaabu`
After that Jallon can easily make next decision, to puppet Gabu for **3 infamy**.
Gabu gets an event for some army stats and adds humilate casus beli, making intervention impossible.

- `events/Yakutat.txt - 18490021`
After losing the war, Gabu can get an event, but it probably will never trigger due to reqirements.
Gabu is then annexed by Jallon, and they can get Boffa?

- `events/Yakutat.txt - 18482479`
This event would allow anexation of Gabu, but it requires Jallon to be civilized.

- `decisions/Yakutat.txt - unite_with_tooro`
This decision allows **non AI** Jallon Immanate to annex peacefully Tooro Immanate.
Vice versa can be done if you play Tooro Immamate.

- `decisions/Yakutat.txt - denianke_happens`
Is is a player only decision giving Jallon Immanate many provinces

- `decisions/Yakutat.txt - no_more_fula_jihad`
Another player only decision avaible to 3 countries in the region
It annexes TOU if it is a vasal and gives many cores in the region.

Later, a coalition of muslim countries can form against new coalition of animist countries.
> Subjects makes later Scrable harder, but it is the best to let it all happen

### Colonization of Boffa
`Yakutat.txt - colonize_boffa` is a `colonial_railroading` decision to colonize Boffa.
It is only avaible to `FRA` or `BOR` tags owning Dakar. They need to be at peace and not disarmed.
**AI can do it since 1851, player instead needs `Nationalism & Imperialism`**.
> You cannot exploit it. It is better to conqer all of Senegal from France in one war

### Coastline conqest
`FlavourModAfrica.txt - conquer_conakry` is another `colonial_railraoading` decision.
It is avaible **from 1870** to a great power France while Dubreka is empty.
They need to be at peace and not disarmed with `Nationalism & Imperialism`.
Player also needs 45+ ships.

**It gives 1.5 infamy**, gives Sangaredi and Dubreka and gives casus beli onto uncivilized AI owner of Forekariah.
That casus beli however may not appear?
`AI` will not do it while it is at 20+ infamy.

##  Gambia

Gambia as a colony consists of Bathurst, Soma and Basse. UK starts with first province.

### Colonisation of Soma
Soma can be colonized by `Yakutat.txt - upper_gambia_british` by UK **since 1875** if they are at peace and not disarmed when owning Bathburst.
Soma and Basse can be gained through border exchange. Read the section below.
> You cannot exploit it

> The final province, Basse can be gained through border exchange - read next paragraph

## Senegal-Gambia border treaty
`FlavourModAfrica.txt - senegal_gambia_border_treaty` is a `berlin_conference` decision fixing borders in the region.
> If other colonial powers got colonies there, you can *recover* them thanks to this decision

### Requirements
You must be a great power at peace with `Nationalism & Imperialism`, owning one of those provinces:
- Bignona
- Velingara
- Kansala
- Seju  

You can not however own Bissau, Ziguinchor or Cacheu - Portuguese posesions. You also cannot have a truce with Bissau owner - them.
> If left to itself it will happen shortly after France colonize Bignona **in 1870**

### Effects
Finally, events can be given to other colonizers in the region:
- Bissau owner gets an offer that `AI` will always accept, otherwise giving a casus beli.
- If you own Basse and `ENG` owns Soma, they will also participate in the negotiations

#### Deal with Bissau owner
They get Kansala from you otherwise from `AI` nation that owns it or will colonize it.
In exchange, you get all of their provinces they may have in Lower Guinea state and Gambia state provinces that belongs to Senegal colony, including Ziguinchor that is a Portuguesse posesion in 1830.

If `FRA` or `BOR` neightbours any of those countries, they will declare war of coquest on them:
- Susu
- Wolof
- The Tooro Immanate
- The Jallon Immanate

> This event has a seceond option that `AI` will never take. It gives booth sides *Place in the Sun* CB

> There is also a feedback event just informing you about the outcome

You will get an event telling you about their decision. If they accepted the deal, you will also colonize Bignona if you do not own it already.

#### Deal with United Kingdom
In exchange for Soma and Basse that you may own (otherwise they will colonize/get them from `AI` owning it), they will also give you every province they might own in Lower Guinea and Gambia states, excluding Gambia proper, but this time also 4 southern provinces in the Djolof state. They also lose 400 influence over local `tags`, giving you free way to conqer them throught previous event.

> UK needs to own Soma in a first place to participate in this negotiations

> United Kingdom `AI` will always accept this proposition, otherwise both sides gets *Place in the Sun* CB

## Gabon

`events/Yakutat.txt - 18482374`
Add influence over them - WIP

### The conqest of Orungu
`FlavourModAfrica.txt - appoint_louis_briere` described in Senegal section also gives conqest casus beli against Orungu

___

## Mali
`Yakutat.txt - massina_conquer_segu`

___

## Madagascar

Madagascar in 1830 consist of Imerina that holds most of the island, its subject Boina and small nation of Antankarana. In the south there are 2 uncolonized provinces. France also owns a small island on the coast, that will be the key to Madagascar colonization.
> Imerina is one of few countries that cannot be a target of Scramble for Afrca cb. You can still get them up to `berlin_conference` through SOI event

### Imerina decisions

#### Cores on surrounding islands
**Non AI** Imerina can get cores on surrounding islands throught `decisions/Sitka.txt - Claim_MAD`.
> If you will ever play it you can use it to gain extra CP from naval bases

#### Boina annexation
`decisions/Yakutat.txt - annex_boina`
Imerina anexes its Boina subject in **1836**.
Decision description missleads that it leads to war with them.
> It is the best to let it happen. Otherwise you have an extra war to do

#### Colonization of the south
`decisions/Yakutat.txt - claim_madagascar_lowdesert`
Ampanihy & Ihosy can be taken by any nation owning Tananarive at peace since **1838**. Comonly, Imerina will do it.
> Let it happen. You do not lose anything

#### Cores in Antankarana
`decisions/Yakutat.txt - the_antankarana_question`
It grants cores to Imerina in all Antankaranan cores (Antomboko and Nosy Be) if Antankarana still exists.
It can be easily done from **1841**, but have a few other requirements.

### The Lambert Charter
`decisions/FlavourMod_Africa.txt - the_lambert_charter`
A decision avaible to great power France with `State & Goverment` tech (avaible from **1840**).
Imerina needs to be at peace and be in their SOI or not it any SOI at all.
It gives France 400 influence over them, instantly ading them to their SOI.

> It also reduces influence of great power having Imerina in SOI by 150, but this will do nothing since they cannot be in SOI of other powers to begin with

> Get Imerina to your SOI before that, that way it will be easiest, you will block them from doing this decision Remember however that they can do this decision instantly if you lose Imerina from SOI

### Nosy Be colony & influence over Antankarana
`decisions/Yakutat.txt - colonize_nosy_be`
Decision avaible to France owning Ile Sainte-Marie (island at the Madagascar coast) at 16+ rank, at peace, independent and not disarmed.
They also needs 100+ relation with Antankarana owning Nosy Be or just wait until **1840**.

France gets Nosy Be from them and they can contest it throught event, but AI will never do it.

`events/Yakutat.txt - 18482357`
In **April of 1840** just after previous decision, Antankarana gets another event.
They there can take anti colonial position, but AI will never do that.
Instead owner of Nosy Be will get 400 influence and relations with them and get an event.

In that event Nosy Be owner will gain them as a subject or break any ties with them.
AI will always take the first option.
With that Antankarana will lose a core on Nosy Be and Imerina will get it instead.
This is because their cores makes borders of future Madagascar colony.

If any counry takes Nosy Be from France, Antankarana will become a subject of Nosy Be new owner throught `events/Yakutat.txt - 18482358`.
They alse can be annexed throught for for free or made free if a player wishes. AI wiil do neither of those.
> You may prevent this by taking Ile Sainte-Marie from Frace, but it costs infamy. SOI is still the only efficient way to get Madagascar. However, you will not get all Madagacar this way

### Subjectification of Imerina
`decisions/FlavourMod_Africa - end_the_merina_monarchy`
This is a `berlin_conference` decision avaible **untill 1900** for great power owner of Ile Sainte-Marie
with `Nationalism & Imperialism`, `Mission to civilize`, capital in Europe and naval base that have Imerina in SOI.
Imerina needs to be an uncivilized nation that is not a subject and at peace.
You also need a province in Africa, but Ile Sainte-Marie that you need in a first place should fit.

It declares a war with Imerina to puppet them and annexes Antankarana if they are a subject of nation clicking this decision.
It does not give any infamy, but AI will not do it if at 23+ infamy.
> If you missed this event, it is the last chance to get Imerina. Add them to SOI.

### Reorganisation of Madagascar
`events/Yakutat.txt - 18482516`
After Imerina becomes a subject of a country that did previous decision **before 1900**
(so basicly after earlier war), this event trigers for their overlord with MTTM of 1 day.

It gives 50k and transfers 3 provinces that colonizer should have already in the Madagascar to Imerina.
It also gives `colony_exemption` flag to Imerina, preventing their annexation from having them in SOI alone.
> Their fate is set, you can only try prevent France from geting them

### Anexation of Imerina
`events/Yakutat.txt - 18482517`
It can trigger to country that got the previous event **from 1895**
with a MTTH of 1 month while Imerina is their subject.

It relases Imerina free and declares a war to annex them. Imerina adds just a status quo casus beli.
Since this event do not check for SOI over Imerina and they do not add other casus belis,
(all of their cores sould belong to them in that date, disalloving retake core cb) a great power intervention is possible.

This event have a second option that AI will never take. It relases Imerina
and once again allows to annex them throught SOI alone.
> Since Scramble for Africa cb does not work on them and neighter SOI annexation from now, they can only be annexed the hard way

### Rebelion
`events/Sitka.txt - 123490`
From **1904**, a rebelion will happen to `FRA` controlled Madagascar.
Rebels add a casus beli, disallowing intervention.
A player can chose to play as the rebels.

>There is a **disabled** event `SAFFlavor.txt - 1500000` connected to sale of Madagascar.

# Antarctic and subantarctic islands

## Bouvet Island
It is one of few provinces with just 1 life rating. Due to this it cannot be colonized normally.
Stitka.txt - bouvet_island
It can be seized by Norway or Scandinavia from 1900 that have Oil Driven Ships tech (avaible from **1919**).
However after that UK gets an event where it can take it for **0.1 infamy**. AI have 10% chance to do it, and this action cannot be contested.

> Poland can get a core there, probably a mistake in the code. It is also temporary used in one event as a buffer province.

## Prince Edward Islands
It is one of few provinces with just 1 life rating. Due to this it cannot be colonized normally.
`Sitka.txt - prince_edward_islands`
You need to be a civilized couuntry with Umtata or have a subject owning it, while said islands are empty.
Next there are two ways to take them:
- Have Mass Politics tech (reseachable from 1900)
- Be a Boer primary culture with Naval Logistics tech if it is after 1900

Both results in province being taken within a few months from **1900**.
Boer RPA can get a core there. This is also true for non `AI` Imerina.

> If you really want them, you need to conqer Umtata, or just take all of South Africa at once since they belong to that state

## Kergulen Island
`Sitka.txt - 123562`
This `colonial_railroading` event `with MTTH` of 3 months that gives this island. It requires:
Being a France since **1893** while said island is empty.

It also changes its name and gives coal there instead of fish.
This coal however is shortly after in 1895 changed back to fish.

Non `AI` Imerina can also get a core there.

> It is theoreticly possible to colonize it normally after geting `The Dark Continent`, otherwise you have to conqer it. It is a part of Austalian Victoria state

# Mix

## Flavour Ferdinandea Island
`1830_GFM_FRA.txt - 17051920` & `1830_GFM_FRA.txt - 16051921`
Island that quickly sinks, but you can claim it and disfavour other countries thanks to it!

# Colonial related casus belis

They are key for taking colonies, as for example *Scramble for Africa* casus beli can be used to conqer most african natives without taking any infamy.
Due to GFM complexity, there are quite a few of them. Many have 2 similar versions, one to take state and other for annexation.

## Scramble for Africa - Demand State/Annex
They are CB's that represent European justification for anexing african natives.
They cannot be justified, but are enabled by deafult. *You just need to fulfill many reqirements* to get them.
As you can see there are two of them, they are very similar. First one is to take a state and second to annex nation if they have just one state left.
Since the second one have a few axtra reqirements the first one - Demand State, will be explained firt.
Note: they are `named annex_africa` & `annex_africa_full` in the files.

### Scramble for Africa - Demand State
It has EU4 aggressive expansion icon.
What you need to enable it?
- Berlin conference has happened (it can happen from 1880, read other paragraph for details)
- Have a capital in Europe
- **You can't be `RUS` or `TUR`**
- Be a westernized (civilized) nation
- `Have Nationalism & Imperialims`
- Be a colonial nation (have a colonial state but ones in America and Sibieria does not count, you cannot be an African or Australia/New Zealand nation)
- Ban slavery
- You are not a nation that called the Congo conference (basicly Belgium), since you get Congo for free, but nothing else.
> Note: `punitive_effects` blocks you usinng it unless you are already at war with target nation
> Note: `POR` `AI` cannot use it, unless you disabled `colonial_railraoading`

What countries can be conquered with it?
Nation that fullfills all of those:
- Have a capital in Africa
- It is `AI` controlled
- Is uncivilized
- Have more than 1 state
- You neightbor it by land or you and target have sea access or you are already at war with them as a player
- It is not your subject
- This is not a post colonial country (basicly ones that were already taken)
- **It is NOT any of those nations: Morocco, Aldjazair, Tripoli, Cyrenaica, Liberia, Ethiopia, Madagascar/Imerina or Egypt**

___

### Scramble for Africa - Annex
It has EU4 overextension icon.
It has the same reqirements as the previous one but some extra:
- Target have only 1 state
- **You cannot have `claimed_africa` country flag** (see explanation below)
- Target cannot have any Ethiopian culture as their primary one (but ETH tag is not forbiden directly this time)
These reqirements can be baypassed if you are already at war with the target nation:
    - If you do not neighbour target nation you will need to have 5+ ships
    - You need to have at least 1 army with 2+ brigades
> It does not technicly require to be a westernized nation but it would be impossible to get `Nationalism & Imperialims` otherwise
> This casus beli can be used on Madagascar/Imerina & Egypt but they start the game with more than 1 state, making that allowance rather useless

> Because Scramble for Africa - Annex cb is limited to how often you can use it, you can only annex one state countries every 120 days, while the first cb does not have that limitation - meainig you can even annex big countries quicker.

### Demand Concession (Berlin Conference)
It has standard *place in the sun cb* icon. Its name in the files: `demand_concession_BC_casus_belli`.

### `claimed_africa` flag limit explanation
This flag exists to disallow spam of certain casus belis. It is added to country that forces
another one to accept specyfic wargoals or adds said war goals to wars.

Casus belis that are blocked by this flag:
- Scramble for Africa - Annex
- Colonial Conquest
- Imperialism - Annex
Note: they are called `annex_africa_full`, `colonial_conquest` & `colonial_conquest_full` in files.

Actions that gives that flag:
- When you add *Scramble for Africa - Annex* (Demand State does not count here) casus beli as a **aditional war goal** or you enforce it on some nation,
you will get it for 120 days.
- Enforcing *Colonial Conquest* cb on other nation for 1-5 years at random
- Doing the same with *Imperialism - Annex* cb for the same amount of time
Note: the last cb description wrongly states that it will always be 5 years.

`demand_concession_BC_casus_belli`
`demand_concession_NI_casus_belli`
`demand_concession_casus_belli`
`demand_concession_casus_belli_no_infamy`

`establish_protectorate_BC_casus_belli`
`establish_protectorate_NI_casus_belli`
`establish_protectorate_casus_belli`
`establish_protectorate_casus_belli_no_infamy`

`colonial_conquest`
`colonial_conquest_full`

`claim_colonial_region`
`claim_colonial_region_full`

`colonial_reconquest_cb`

`claim_holy_land`

# WIP

## South Africa

> Disclaimer: Dithakong is in the Bechuanaland section

### Set-up for Boers

`events/1830_GFM_ENG.txt id: 18351836` # The Great Trek

If there is at least 1834, but before 1845
Country with banned slavery and owns both Cape Town & Port Elizabeth (UK bans it with slavery_abolition_act_ENG (1830_GFM_ENG decision), preventable?)

Gets an event that set-ups global flag `great_boer_trek` enabling Boer republics and associated events and decisions to begin and giving cores to future Boer states

This also begins the existance of prototype Oranje, see below section

Many events and decisions also checks for lacking of flag `boer_accepted`. It is only gained through `decisions/NET.txt id: embrace_the_boer`

------------------------------------------------------------------

### Oranje (Voortrekkers)

events/1830_GFM_ENG id: 183518362
Said event gives an event for uncivilized owner of Botshabelo that forces creation of independent Voortrekkers (Oranje) from that province
Uk gains 600 influence over it, instantly adding it to its sphere of influence
There is also second option doing the same, but allowing to play as them.

The founding of Winburg (events/BoerWar.txt id: 98215)

It is 1836-1889, but no later than September in these years
Civilized country owning Cape Town that do not have country flag boer_accepted
Is not SAF or VLK
Voortrekkers (Oranje) own Botshabelo
Qwa-Qwa belongs to uncivilized nation at peace or to a nation geting the event (but only if it do not aslo own Botshabelo)

Then country gets an event (with MTTH of 1 day) in which:

SAF gets boer as an accepted culture and primary culture of whoever gets this event
Whatever uncivilized tag owns Qwa-Qwa gives it to Oranje through another event (AI tags never contest that in said event) (id: 98216)
Oranje becomes a puppet of a nation that got this event (it can declare independence with event: 18482420 but AI will never do this)
This event also tries to change infuence over Oranje from UK to whoever owns Cape town, but it do not work?

There is a decision that is possible to take while having Voortrekkers as a subject: decisions/Boer War.txt id: orange_river_convention
It also requires Voortrekkers to be at peace and can be only made from 1854 onwards but before 1860

This relases Potchefstroom and changes their goverment type, which renames them to Oranje and gives them 98231 event that
gives influnce over them to a nation that clicked this decision (in contrast to similar sand_river_convention)
There is a second option in event that Oranje AI would never take, giving casus beli against Oranje

Temporaraly anexation of Oranje by Transvaal

If Transvaal exists and is at peace while Oranje is also at peace and have prov_gov_liberal goverment type and Oranje is in the same influence as Transvaal or in no one
Then they can click a decision from 1844 onwards: decisions/Yakutat.txt id: unite_with_potchefstroom

This decision gives Transvaal maaaaany early techs, and anexes Oranje for Transvaal, while changing Transvaal goverment to prov_gov_conservative.
This also sets global flag unite_with_potchefstroom, which will be important later.
There are special cases if player plays one of this countries, making it player friendly, while overal effect is the same.

decisions/Yakutat.txt id: warden_line

If UK controlls Cape Town while Oranje do not exists with global flag unite_with_potchefstroom
They can click a decision when at peace from 1848 onwards

This decision transfers Oranje core provinces from subjects of country that clicked this decision to Oranje
If owner/s of this provinces are not subjects of said country, they will get an event 18482307. Oranje also gains Phuthaditjhaba (again) as a core

This event asks owners of Oranje cores to give them to Oranje. If not, they will face a war. AI will always agree.
This also changes Oranje goverment type to colonial_company, changing their name to Transorangia and flag to union jack themed

-----------------------------------------------------------------

Nothern Cape (O'okiep, Emthanjeni and Hantam)

`events/BoerWar.txt id - 98261` #The Northern Cape Colony

UK/SAF event at year 1840 with some MTTH, must be at peace and own Cape Town, at least one of said provinces must be empty

Target country gets O'okiep, Emthanjeni and Hantam (in that order) if they are not already colonized

-----------------------------------------------------------------

### Natalia & Zulu

`events/BoerWar.txt id: 98205` #Invasion of the Laagers

has_global_flag = great_boer_trek
It is at least 1838
It is (or at least?) November
Zulu own KwaDukuza
Owner of Cape Town do not have flag boer_accepted

`MTTH` = { days = 1 }

Zulu AI relase Natalia from said province and Emnambithi (Zulu player can contest it with a war)
Owner of Cape Town gets an event (id: 98207) where AI selects to make them a puppet and give them Durban if it belongs to it

Then a country at peace with all great powers and capital in Europe that have Cape Town with Natalia as a puppet (Natalia must be at peace)
NOT = { has_country_flag = boer_accepted }

Gets an event (id: 98210) with MTTH of a few years in with AI always deciding to annex Natalia, AI Natalia will always accept it through another event

-------------------------------------------------------------------

Anexation of Zulu:
UK or South Africa at peace from 1878 onwards
Neightbouring uncivilized Zulu with less than 2 states and no truce

Gets an event allowing them to declare war on Zulu with establish protectorate casus beli. AI would do this if they have a infamy reserve.

-------------------------------------------------------------------

Transvaal (Potchefstroom Republic)
`events/BoerWar.txt id: 98220`

Requirements:

It is at least 1837
IT is (at least?) August
It is before 1890
Civilized country owning Cape Town
Do not have a country flag boer_accepted
Is not SAF or VLK
Oranje exists and Transvaal do not
Do not own all Transvaal core provinces + Ga-Seleka + Mashashane at the same time (+ 1 province in South America xD)
Marothodi belongs to uncivilized nation at peace or to a nation geting the event

Then country gets an event with MTTH of 1 day in which:

SAF = {
        primary_culture = british
        add_accepted_culture = boer
    }

If country geting the event own any of said provinces, it will give them to Potchefstroom, which is temporary created in uncolonized Saan province

This triggers 2 events:

`184824202` - for Potchefstroom
It asks them if they want to declare independence or not (AI will always stay loyal in this event)

Event for Mthwakazi (events/Yakutat.txt id: 18482305), that sets up Potchefstroom Republic, for example making it a puppet of a nation that got original 98220 event
Asks Mthwakazi for contest of it (AI will never do this)
(3rd option allows to play as Potchefstroom Republic) and triggers another 2 events:

`events/Yakutat.txt id: 184823053` - for the owner of Ga-Seleka
It asks for action against their incursion into Ga-Seleka (AI will never oppose it), then event 184823055 triggers for Mthwakazi as a response,
giving them said province and giving their old provinces to Potchefstroom and aslo uncolonizing Saan province from them (by changing life rating?)

events/African Uncivs.txt id: 95517 - for Potchefstroom after ~120 days (MTTH)
Basicly another double event triger and 3 prestige, this delay allows Mthwakazi migration to work without issues and look smoothly

events/African Uncivs.txt id: 95518 - for Mthwakazi
Mthwakazi moves from Ga-Seleka (giving it (back) to gaMangwato) to southern Zimbabwe, + anexing OPM in Tomotha province
Rozvi, which loses said Zimbabwe provinces also loses 2 western provinces to baTawana
Mthwakazi also gains powerfull military buff without expiration date

events/African Uncivs.txt id: 95517324 - for Rozvi Empire
Event without AI decision weights, but it looks like AI selects option to lose 1 core and prestige
another option would give them military buff and declare war on Mthwakazi

There is a decision that is possible to take while having Potchefstroom as a subject: decisions/Boer War.txt id: sand_river_convention
It also requires Potchefstroom to be at peace and can be only made from 1852 onwards but before 1858

This relases Potchefstroom and gives them 98230 event that changes their goverment type, which renames Potchefstroom to Transvaal
It also gives influnce over them to UK (whoever clicked this decision, UK or someone else) (in contrast to similar orange_river_convention)
There is a second option in event that Transvaal AI would never take, giving casus beli against Transvaal

Mashishing (decisions/Yakutat.txt id: lydenburg_occupy)

Availbe to Boer primary culture nation owning Kwaneng while baPedi owns Mashishing
Country must be at peace and fullfill one of these:

It is at least 1850 and at least March (2nd month in files)
Have Nationalism & Imperialism tech
State & Goverment tech with at least 50 001 money and at least 100 relation with baPedi

After clicking it, Transvaal gets Mashishing, as AI will never refuse to their demand/proposal
There are 2 ways to finalise this, booth looks the same,
but if Transvaal bought province, baPedi gains techs (not money as event says). Taking it by having Nationalism & Imperialism tech will not create that resoults

The Sekhukhune Wars (Transvaal conquers of Tky-Gariep state/baPedi tribe) (events/Yakutat.txt id: 18482309)

There is at least 1874 but before 1878, while Transvaal owns Kwaneng and baPedi owns Mbombela (MTTH = 1 day)

Out of 3 options AI will chose 1st one and very rarely 2.
Booth of these will give Transvaal cores on rest of the state (except Mbabane and eMkhondo)
First option also resoults in a war of conquest between Transvaal and baPedi

Ga-Seleka goes to Transvaal (events 18482313 and 184823131 from events/Yakutat.txt)

In short between 1852 and 1855 there is an event for baMangwato that spawns event for Transvaal. These events gives Ga-Seleka to Transvaal.

Nkomazi is given to Transvaal (events 18494562 and 184945621 from events/Yakutat.txt)

In short, if some non-african country owning Nkomazi without owning Mbombela, while colonial_railroading is not disabled,
it gets an event that allows to give this province to owner of Mbabane, losing 1 infamy in a proces (AI will always select this option)
The second option do nothing

Second event just seceds province to the Mbombela owner

The colonization of Saan by Transvaal (events/Yakutat.txt id: 18482589)

In short, by by pretty much power projection, Transvaal can get Saan quicker or faster (read details in event)
There is another option, just wait unil neightboring Dithakong is colonized. Event have MTTH of 1 day

WIP

Witwatersrand Goldrush (1886)

In short, if Transvaal is independent and not in any sphere of influence, after geting this gold rush,
neightboring great power can (AI will always) get a casus beli to add it to its sphere, but not to make them a puppet

--------------------------------------------------------------------------------------------------------------

Xhosa

Great power UK (or South Africa)
That neightbour Xhosa
Is at peace and have no truce with them

Gets an event in which they declare war on Xhosa to add them to sphere
This event will fire a few (3?) times

treaty_of_umtata decision

In short, a country that owns Cape Town and was at war with Xhosa can kick them out of their sphere of influence and get 2 of their 3 provinces for 1 infamy. AI will always do this

Anexation of Xhosa

Great power UK (or South Africa)
That neightbour Xhosa
Is at peace and with no truce with them
OR = {
        check_variable = {
            which = xhosa_conflict
            value = 3
        }
        has_global_flag = berlin_conference
    }

Gets an event in which at 90% AI will annex them through war or 10% to gain extra influence and relations with Xhosa

--------------------------------------------------------------------------------------------------------------

The Northern Cape Colony (2-3 provinces)

UK or South Africa at peace owning Cape Town from 1840 onwards when any of the target province is empty (player also needs 10k)

Event giving target provinces for 10k

If someone else owns these provinces, UK have a decision if owning Cape Town to get a casus beli on that country. UK will also leave aliance with said country

--------------------------------------------------------------------------------------------------------------

Griekwastad/Kimberley

`events/Boer War.txt id: 98262` - Diamonds Discovered in Kimberley

Civilized nation owning Hantam from 1867 onwards, while Griekwastad do not produce gems and is owned by uncivilized nation or Griqua (MTTH = 1 day)

Griekwastad is renamed to Kimberley and its RGO changes to gems

If Mpondo owns Kokstad/Shayilanga, it wiil get event: events/Yakutat.txt id: 18490065, asking them if they allow Griekwastad to move into Kokstad/Shayilanga (AI wiil always accept)
This will remove all Griqua cores and make this provinces cores of South Africa, then give Griqua core in Kokstad/Shayilanga and give them 184900651 event
Another event: 184900653 is given to owner of Hantam

184900651 event will move Griqua POPs, change them to republic and make them a subject of UK, if they own any provinces listed in the event? (Lake Nyasa is one of them xD)

184900653 event will give Kimberley to nation that got this event, with Philippolis if Griqua also owns it

--------------------------------------------------------------------------------------------------------------

Transvaal & Oranje + Natalia (Uk anex them)

Boer War

A series of events, but in short:

Uk at peace and have no truce with Transvaal
Neightbouring Transvaal
Transvaal is not a subject and in peace
It is at least 1896
South Africa AND Zulu does not exists

Event in with Uk declares war (AI will not do it if going over infamy limit, always otherwise) on (if any of them exists) Transvaal, Oranje and Natalia to annex them
Some countries can contest this, joining the war on boer side, resoulting in event chain after victory, resoults include boer helper losing all provinces in South Africa
To win that war on the boer side, boer primary culture country needs to occupy Cape Town for at least 120 days

appeal_to_the_british decision

If any of these 3 countries are getting bad at war (while not being in the sphere of UK influence or a war with UK) with anyone except Zulu or any other of these 3 countries
UK gets an event that allows them to get 200 influence over them or get a casus beli on them
Chance for the first is 35-70% or maybe even 100%

--------------------------------------------------------------------------------------------------------------

The fate of Basotho and Suazi

Basotho from 1860 onwards or Suazi after Berlin Conference can make a decision to ask for protection

The target country needs to:
Be a great power outside of Africa and own Cape Town that neightbour them
Basotho/Suazi cannot be in the sphere of influence of other country (can be in that of target country) and cannot be a puppet and must be at peace

Through an event target country makes them a puppet, target country gets all of their provinces, evcept for the capital,
changes their religion to its faith, gains influence over them and relations

Target country AI will rarely refuse
Note: from that point they cannot be a target for Scramble for Africa casus beli

--------------------------------------------------------------------------------------------------------------

reorganize_south_africa

Decision that requires ownership of Cape Town, being at peace and having Nationalism & Imperialism tech while South Africa do not exists

It makes South Africa of your primary culture, adds boer as their accepted culture
South Africa also loses its cores in South Africa that you do not own
This decision do not relase them

--------------------------------------------------------------------------------------------------------------
## Bechuanaland

`bechuanaland_protectorate` `colonial_railroading` decision

Country needs to:

Have Nationalism & Imperialism tech
Have Machineguns tech or it is at least 1885
Can not be disarmed or a subject
Be at peace with all great powers
Own both Cape Town and Kimberley

All target provinces (except for Dithakong and Luhonono) needs to be empty or owned by AI controlled uncivilized nation(s)

All target provinces will be granted to target nation, but Luhonono only if it is empty

Tip: Dithakong is the province needed to discover Australopithecus Africanus

Tip: bamangwato_chungus decision allows local nation to take those empty provinces if they conquer all non empty Bechuanaland provinces,
so this decision would not work, but they can be easily conquered later instead

--------------------------------------------------------------------------------------------------------------

Luhonono can be bought from non African country thanks to buy_caprivi_strip decision

Requirements:

Is civilized and at peace
Hereroland state is fully owned, except for Luhonono
Target country is independent and have no truce with proposing country
Have 100k or is AI

Then target country gets an event in which it makes the deal, or denies
The better the relations, the better the chance for the deal with AI and vice versa
If target is in the sphere of the proposer, the chance is very good even with the worst relations