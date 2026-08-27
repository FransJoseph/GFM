# Victoria II Grater Flavour Mod colonization encyclopedia

This file contains all the information that is useful for obtaining as many colonies as possible in Victoria II Greater Flavour Mod. It also explains the process in with they are gained, so player can try to prevent their colonization by other nation. For example you can prevent UK from taking Nigeria by conquering just Lagos in the early game and conquer it with free casus belli that you get from Berlin Conference.

## Dictionary

Here is a small dictionary to help you understand some of the terms and abbreviations used in this encyclopedia.

GFM - Greater Flavour Mod
GP - Great Power
SP - Secondary Power
SoI - Sphere of Influence
CB - Casus Belli
LR - Life rating
SC - Supply Consumption
WE - War Exhaustion
`MTTH` - Mean time to happen, events use it to determine how long it takes to happen
Independent - Not a puppet, but can be in someone SoI
Base prestige - Prestige from events to be modified by *prestige gain* modifier
`colonial_railroading` (or similar looking) - in-game name for flag, decision or event (but events have numbers instead)
`Yakutat.txt` - game/mod file in with said thing is written
`GER` (or similar) - Country `tag`. Every country have a unique one (few short living countries are used as other country, retaining the same tag)
France - French like country not specifying exact tag, like `BOR` or `FRA`
Germany - German like country not specifying exact tag, like `NGF`, `GER` or rarely `SGF`
UK - United Kingdom
USA - United States of America
45k+ (and similar) - *at least 45 thousand pounds*

## Important topics

### Colonial railroading

At every campaign start you get a chain of setup events. One of them asks you for *colonial railroading*. This is a setting that does exactly what is says - it leads countries to their historical colonies, and block others from taking the region. It is **enabled by default**, but can be disabled in that setup. Most decisions and events cited here can only appear if it is enabled. Every of them is labeled under being a `colonial_railroading`.

### Vanilla/Stock colonization & Life Rating

In GFM almost every colonial province is scripted and colonization mechanic is mostly used as a last resort, for example if you crippled the Italian or German unification. However, even in that case their colonies (like Cameroon & Eritrea) can still be colonized in scripted action by other countries.

GFM did micro on LR. This is mostly to block provinces from colonization rather that represent real conditions there. Thats why when you get them through decisions or events you get LR there. The highest LR in 1830 is 48 - for Frankfurt.
Most provinces have 35 LR. Just like in the base game, by getting inventions you can colonize provinces that have a lower LR. Note that some provinces have LR of just 5 or even 1. They can never be colonized through that mechanic alone.  
Here is the list of inventions that do decrease minimum LR in GFM:

- Prophylaxis against Malaria (in `Medicine`, available from 1830): -5, 30 minimum in total
- Mission to Civilize (in `State & Government`, but available only from 1850): -10, 20 minimum in total
- Colonial Negotiations (in `Breech-loaded Riffles`, but available from 1880): -5, 15 minimum in total
- The Dark Continent (in `Revolution & Counterrevolution`, but available from 1895): -5, 10 minimum in total

#### The Dark Continent invention

It has a complex requirements, while giving final -5 min life rating. Here it is requirements:

You **CAN NOT** get it if you are not a great power with any of those flags:

- `congo_master`
- `historical_congo`
- `civilizing_congo`
- If you have `colonial_railroading`
  - It CAN NOT be discovered after 1895, unless the Congo conference have happened
- If you disabled it:
  - You need 1 more tech or 2 other increasing factors listed below

Now to actually get it, you need any of those techs, but having more of them increases your chances greatly:

- `Biologism` (1850 tech)
- `Military Logistics` (1870 tech)
- `Steel Streamers` (1880 tech)
  Other factors also help to get it, but less
- Any great power have that invention
- Your neighbor have it

At the same scale these factors also can block you from getting it, forcing you to get more of above factors:

- Being at most secondary power
- Having rank worse than 16

___

### Colonial nation status

Every country can be categorized by its colonial status. There are however a few quirks there. That status is important since being one allows to make many colonial actions, but also increases supply consumption.

First, all uncivilized nations are non-colonial since they can not have colonial states. Second, you can actually have many of those and never be a colonial nation. To actually became one, you need to met a set of requirements:

- You **can not** have a capital in modern day Australia, New Zealand, Morocco, Algeria, Libya, Egypt or Sudan
- A colonial state in any of those regions: Africa, Australia, New Zealand, Oceania, or some part of Asia, more specific:
  - Indochina, Siam, Burma (including Andaman Islands), Yunnan state, Philippines or Indonesia and its surroundings

Most importantly, American colonies like in the Caribbeans (Sweden case), in India or in the Middle East do not make you a colonial nation.

> NOTE: You can be a colonial nation for example as Zulu (probably a mistake) since continent *Africa* is actually just North Africa, the rest is West Africa, East Africa, etc.

___

### Colonial policies/reforms

Those reforms works rather like policies and are called like that in the game interface. There are 4 of them:

- Settlement
- Indirect rule
- Civilizing mission
- Non-colonial Nation

If you are not a colonial nation, you are forced to have *Non-colonial Nation* reform. Note that uncivilized nations do not have it, since they have westernization reforms instead. If you became a colonial nation, you are forced to have 1 of 3 remaining instead. You will also get an event allowing you to take any of those for free. They work otherwise as a normal political reforms, allowing you to take one step at a time into lower tiers, or rollback them into higher tiers.

#### Detailed description

**Settlement** -

**Indirect rule** -

**Civilizing mission** - It is the most *liberal* one of them all. It is blocked for countries with `islamic_law` and enabled only after `berlin_conference` or for `theocratic_government` countries.

Like all of them it increases the need for bureaucrats in the same scale. The greatest bonus here is education efficiency +10% and +10% assimilation rate. Additionally it gives 5% culture research and 0.1

**Non-colonial Nation** - Despite being a place holder for the other nations, it can be beneficial. That is because it gives -5% SC and gives +5% research on military techs, in exchange for -5% on naval techs, with is nothing to complain about. Additionally, since being a colonial nation gives extra 10% SC, this is instant jump of +15% when you become a colonial nation.

### Berlin Conference

It is one of the most important events in the mod, allowing European countries to dominate the world.
It sets a single very important global flag, `berlin_conference` that leads to many events and decisions, but most importantly it allows you to use a **unique free casus belli against most african natives**. Every event and decision cited here also is categorized if it requires it or not, just like `colonial_railroading`.

`Scramble for Africa.txt - 95500`
It can be triggered by a great power nation with a capital in Europe, either being a colonial nation, or owning land in Africa.
Most importantly, they need 3 inventions:

- Prophylaxis against Malaria
- Mission to Civilize
- Colonial Negotiations

The first one is the Medicine tech and is obtainable from the game start (1830).
The second is in State & Government, available from 1840, but obtainable only after researching 1850' techs.
Last one is the most important, since it is a time bottleneck for the entire event.
It is in the Breech-loaded Rifles (1850 tech), but obtainable after researching 1870' techs.
If you are prepared, you will get it it within few months after getting first 1870' tech.

Finally, it has a `MTTH` of 6 months, shorter if your capital is Berlin, increasing chance to be truly Berlin conference.
Otherwise, it is named after capital of nation that got this event. It also gives 25 base prestige.

> Note: The Conference have historically happened in 1884 - many years later than will happen in any campaign.

### Colonial related casus belli

They are key for taking colonies, as for example *Scramble for Africa* casus belli can be used to conquer most african natives without taking any infamy.
Due to GFM complexity, there are quite a few of them. Due to technical limitations, many have 2 similar versions, one to take state and other for annexation.

#### Scramble for Africa - Demand State/Annex

They are CB's that represent European justification for annexing african natives.
They cannot be justified, but are enabled by default. *You just need to fulfill many requirements* to get them.
First one is to take a state and second to annex nation if they have just one state left.
Since the second one have a few extra requirements the first one - Demand State, will be explained first.

> Note: they are named `annex_africa` & `annex_africa_full` in the files.

##### Scramble for Africa - Demand State

It has EU4 aggressive expansion icon.
What you need to enable it?

- Berlin conference has happened (beginning of the 1880')
- Have a capital in Europe
- **You can't be `RUS` or `TUR`**
- Be a westernized (civilized) nation
- `Have Nationalism & Imperialism`
- Be a colonial nation (explained in the other paragraph)
- Ban slavery
- You are not a nation that successfully called the Congo conference (basically Belgium)

> Note: `punitive_effects` blocks you using it unless you are already at war with target nation
> Note: `POR` `AI` cannot use it, unless you disabled `colonial_railroading`

What countries can be conquered with it?
Nation that fulfills all of those:

- Have a capital in Africa
- It is `AI` controlled
- Is uncivilized
- Have more than 1 state
- You neighbor it by land or you and target have sea access or you are already at war with them as a player
- It is not your subject
- This is not a post colonial country (basically ones that were already taken)
- **It is NOT any of those nations: Morocco, Aldjazair, Tripoli, Cyrenaica, Liberia, Ethiopia, Madagascar/Imerina or Egypt**

___

##### Scramble for Africa - Annex

It has EU4 overextension icon.
It has the same requirements as the previous one but some extra:

- Target have only 1 state
- **You cannot have `claimed_africa` country flag** (see explanation below)
- Target cannot have any Ethiopian culture as their primary one (but ETH tag is not forbidden directly this time)

These requirements can be bypassed if you are already at war with the target nation:

- If you do not neighbor target nation you will need to have 5+ ships
- You need to have at least 1 army with 2+ brigades

> It looks like this CB **can be used** by congo conference caller
> It does not technically require to be a westernized nation but it would be impossible to get `Nationalism & Imperialism` otherwise
> This casus belli can be used on Madagascar/Imerina & Egypt but they start the game with more than 1 state, making that allowance rather useless
> Because Scramble for Africa - Annex cb is limited to how often you can use it, you can only annex one state countries every 120 days, while the first cb does not have that limitation - meaning you can even annex big countries quicker.

#### Demand Concession (Berlin Conference)

It has standard *place in the sun cb* icon. Its name in the files: `demand_concession_BC_casus_belli`.

#### `claimed_africa` flag limit explanation

This flag exists to disallow spam of certain casus belli. It is added to country that forces
another one to accept specific war goals or adds said war goals to wars.

Casus belli that are blocked by this flag:

- Scramble for Africa - Annex
- Colonial Conquest
- Imperialism - Annex
  Note: they are called `annex_africa_full`, `colonial_conquest` & `colonial_conquest_full` in files.

Actions that gives that flag:

- When you add *Scramble for Africa - Annex* (Demand State does not count here) casus belli as a **additional war goal** or you enforce it on some nation,
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

### Annexation through Sphere of Influence

After the Berlin Conference, most African natives can be annexed also through SoI. **It costs some infamy**, but can be the only way of annexation. Ethiopia is a good example of it.

This process consists of an event chain:

1. Event must pop-up in a nation that is a candidate for annexation, where it can accept, or deny annexation
2. Great power gets an event where it can decide to annex that country **for 2 infamy**, or not, **losing 1 infamy**. If African nation denied it, GP can declare a war on them with free CB, or let it be

How the first event (`Scramble for Africa.txt - 95505`) is triggered:

- Berlin Conference has happened
- It is independent, uncivilized country with a capital in Africa at peace
- It is not a country that was refused annexation that way by colonial power before or post colonial country
- Its sphere leader neighbors it or booth countries have sea access
  - Russia however cannot do this through sea
- Sphere leader have a capital in Europe, `Nationalism & Imperialism` technology, is at peace, not disarmed, not pacifistic and without rebels
- **`AI`** cannot annex those countries that way: **Cyrenaica**, **Aussa**, **Algeria**, **Algiers**, **Harar**, **Ethiopia** or **Darfur**
  - Ottoman **`AI`** additionally cannot annex **Morocco** this way

> This rather broad trigger allows you to annex countries like Ethiopia, Senussi, Morocco or even Liberia!
> Note: This event can trigger to a player
> Note: `CYR` is labeled 2 times in the `OR` code bracket

This event has a `MTTH` of 4 months, but can happen earlier or later depending on some circumstances:

- Egypt, Tunisia or Morocco triggers it 100x times as fast, so in ~1.2 day
  - For The Ottomans however Egypt takes 5x that time (~6 days)
- Ethiopia takes 10x that time (~40 months or over 3 years)
- Zanzibar takes 10x time up to 1890, because of unique flag after its formation: `delay_unciv_annexation`
- It triggers 1000x times as fast for Bilad as-Siba having `triggerfasttamazight` flag (1 day)
- Base time for all cases is halved from 1890 (~2 months)
- It is halved again since 1900 (~1 month)

Finally, the candidate for annexation is presented with 2 options:

- Accept annexation
- Deny it

`AI` will respond to both options with 50% chance at base.
However, if it has less than 3 armies (3 stacks of min 2 regiments) it will always accept it.
Otherwise, if target country has any of those (it stacks), it will likely deny:

- At least 50% westernization progress
- More than 2 states
- It is Ethiopia
- It is Bilad as-Siba having `triggerfasttamazight` flag

If annexation was accepted, SoI owner gets an event: `Scramble for Africa.txt - 95506`

It gives 2 options, where first makes a status quo, **reducing infamy by 1**. It also locks annexation of it that way, event if other GP adds it to its SoI. Second annex target country **for 2 infamy**.

If the annexation was denied however, SoI owner gets event `Scramble for Africa.txt - 95507` instead.

GP loses them from SoI, all other GPs also loses 100 influence over them. In the event itself GP can let them be for 25 prestige, `AI` will rarely do that. Otherwise, GP declares a war to annex them.

### Occupation of empty provinces

In 1830 there are huge swats of empty provinces. All of them are colonized through decisions, events or a combination of booth.
They are colonized this way from early game even into the late game by multi-use decisions.
They give you provinces deeper into the hinterlands if you own corresponding frontier provinces.
Most of them can be still be taken through vanilla colonization, but provinces with less than 10 LR cannot be.

#### Map

On the map, I added a special folder dedicated to expansion like that. I painted frontier provinces in green. Provinces you can get are painted in yellow. Arrows shows an order in with they are given if you own a province in with said arrow begins. They can create a whole chain, with is taken all at once. If expansion requires some province/s to be already taken, it is shown in red. In some cases, there are more than one set of *frontier provinces*. In that case, they are colored in lime or arrows shows one of the sets.

#### Sahara

It is by far the largest area that can be colonized that way. It can be taken by multi use decision ``...

#### Sahel

In 1830 there are 3 empty provinces in the western Sahel, south of Sahara. All of them can be colonized by local countries, but they can find it difficult. They are:

- Gao
- Koro
- Kedugu

#### Sagokope

It is the only empty province in Ghana. It can be taken by an event: `Yakutat.txt - 18482535` by any nation that owns required provinces. You can see that on the map. It is most likely to be taken in the **early 1850's** by UK when they bought Accra from Denmark, since they take Krobo from Ashanti in the beginning of the game.

#### Togo & neighboring lands

Togo is a special case, where all provinces belonging to a colony is taken by once without any *frontier province*. It is described in its dedicated chapter.

However, there is an additional event (`Yakutat.txt - 18482536`) allowing you to take all empty provinces between Ghana and Nigeria that is a typical *expansion* event. It requires to take 3 provinces around it. Since its only a only a set of provinces, local natives can also take them, for a much better looking map.

> Tip: Since one of the requirements is true in 1830 - empty provinces in the Togo-Benin border you can easily do it after conquering Ashanti and Dahomey. The whole event is however blocked in the moment that Togo is colonized.

#### Ethiopia & Somalia

### Tags recycling

In GFM for ??? reasons some country tags are recycled. This can cause big confusions. Here is a list of them:

|  Tag  | First name |      Second name      |        Third name        |
| ----- | ---------- | --------------------- | ------------------------ |
| `BZD` |  Bayazid   |       Kabadugu        |            -             |
| `BTL` |   Bitlis   |        Badibu         |            -             |
| `CAR` |   Rafai    |    Rabih az-Zubayr    | Central African Republic |
| `EQG` |   Waalo    |         Benga         |    Equatorial Guinea     |

## Africa

`uncivilizedFlavor.txt - conquest_of_the_south`

Africa is in 1830 dominated by *uncivilized* natives, many of them have a very hard time westernizing. This ensures their status until their unprecedented collapse in the **Scramble for Africa**. Worth noting is Egypt that is the most advanced country on the continent, being an Ottoman subject. There are also coming Boer states in the south that are westernized. Finally, there are many growing European coastal colonies dotted all across the continent.

## French Conquests in the Scrabble for Africa

France have historically conquered huge swats of land in western Africa. For that big of a task, for both `AI` and French player, there is a `colonial_railroading` decision declaring war or annexing countries in SoI in the Western Africa with exception of ones in Nigeria, Ashanti and Sierra Leone. There are also a set of decisions helping France with conquest of modern day Chad and Central Africa.

`FlavourMod_Africa.txt - ai_french_west_africa`  
Requirements:

- Berlin Conference has happened
- Great power have a capital in Paris and french as a primary culture (its an incarnation of France)
- Country is not disarmed, own Aboisso and St Louis
- Country is at peace with the following nations:
  - Germany (`GER` or `GCF`)
  - United Kingdom (`ENG`)
  - Italy (`ITA`)
  - Austria-Hungary (`KUK`)
  - Russia (`RUS`)
  - Japan (`JAP`)
  - USA (`USA`)
  - Belgium (`BEL`)
  - Netherlands (`NET`)
  - Spain (`SPA`)
  - Ottoman Empire (`TUR`)

Effects:

- If Gobir is a subject of `AI` Sokoto, it is released
- Uncivilized `AI` countries in the Western Africa (except ones in Nigeria, Ghana and Sierra Leone) that are not a part of **any** SoI gets an event in with France declares a war of conquest upon them (`AI` adds status quo CB, still allowing GP intervention)
- If `ALD` meets those conditions (while being in another part of Africa by itself) war will also be declared upon them
- The same set of countries (except `ALD`) but in the French SoI gets a different event in with they are directly annexed **for 0 infamy**!
- If `AI` does this decision, they **lose 15 infamy**, and get some steam transports

> Note: Using or prohibiting use of this decision can be very powerful, especially since annexation CB for Scramble can not be spammed  
> Note: Declaring wars through decisions and events still gives penalties for truce breaking, good relations etc, be careful  
> Note: Despite `ASH` being blocked in the code, they are still a target of war. Following that, countries like ... in the Western Sahara is also a target of war. Some countries in Nigeria can also be one.

### Western Chad

`FlavourMod_Africa.txt - french_bagirmi` is a `colonial_railroading`, `berlin_conference` decision available to an incarnation of France that is a great power while not disarmed and neighboring Chad or Kanem-Bornu owning its provinces.

It annexes Chad or takes it from Kanem-Bornu if they own their provinces.

### Conquest of Eastern Chad

`FlavourMod_Africa.txt - france_wadai` is a `colonial_railroading`, `berlin_conference` decision available to an incarnation of France that is a great power while not disarmed. Eventually, instead of France this can be any other civilized country with a capital in Europe since 1907.

It declares a war of conquest upon Wadai.

### Rabih az-Zubayr Empire

`Yakutat.txt - join_rabih_azzubayr` is a decision creating historical empire created by adventurer from Egypt. For simplicity is is just formed by a local nation.

Requirements:

- Its Rafai
  - or Azande is a player if Rafai no longer exists
- Have 50%+ westernization progress or is westernized
  - `AI` can bay pass that from 1876
- Owns Bangasu and Zemio or is `AI`

Effects:

- Goverment type is changed to `absolute_empire`, changing country name to *Rabih az-Zubayr* by doing so (`tag` `CAR` stays the same)
- 10 prestige is given
- Soldiers POPs size is tripled
- 5 regiments are given
- If the country is uncivilized (almost certain), a few reforms and techs are given
- If the country was not Rafai (so Azande), tag is changed to `CAR`
- 4 empty provinces are given (5th is their in 1830)
- Cores are given

**Northern Expansion**  
`Yakutat.txt - rabih_azzubayr` is a decision available to Rabih az-Zubayr that simplifying, owns all non empty cores. It gives many cores in the region.

### Conquest of Central Africa

`FlavourMod_Africa.txt - france_rabih` is a decision with almost the same requirements as the previous French ones. It similarly declares a war of conquest, but this time upon Rabih az-Zubayr (or rather just `CAR`).

## Algeria

In 1830 it consists of a 4 countries and big swats of empty Sahara to the south. The biggest country is Algiers, that is also overlord of Beylik of Constantine, Ait Abbas and Touggourt. Additionally, one of Constantine's provinces is in the Tunisia state.
Algeria is conquered by France through many wars and Sahara is taken by annexation of local rebellion + *The Saharan Frontier* decision.

Tags there can be very misleading, here is a table explaining them:

| Tag   | Base name | In-game name          |
| ----- | --------- | --------------------- |
| `RGA` | Algiers   | Algiers               |
| `LBY` | Libya     | Beylik of Constantine |
| `ABA` | Ait Abbas | Beni Abbas            |
| `TUG` | Tuggurt   | Touggourt             |
| `ALD` | Aldjazair | Algeria               |

### War for Algiers

`1830_GFM_FRA.txt - france_bullies_algeria`
This is a very simple decision for great power France at peace if Algeria still owns Algiers.
It requires to be at least **May of any year**, so you can miss it and have to wait to May 1831 to do it.

Algeria releases and breaks alliances with Ait Abbas and Touggourt and get a feedback event.
Finally, a war is declared upon them with *Punitive Expedition* CB (`treaty_port_casus_belli_no_infamy` exactly).

After France wins, they can take one of two Algerian treaty ports, Oran and Algiers.
`AI` will always chose Algiers since decision for Oran have a check that forbids its taking by `AI` if they do not own Algiers.

> If France does it within 1830-1835 window, all pops from Great Slave Lake will be moved there and given 1% more literacy. This also happens in the setup that `CLN` does at every campaign start. This is probably to give Algiers first French settlers along with their slaves.

### Breakup of Algeria

`1830_GFM_FRA.txt - 16151852`
If France have won this war before 1835, they get an event that splits Algeria. They yet again release their subjects, lose cores, Algiers itself is split into half with Algeria. A civil war breaks out, leaving only Touggourt neutral.

> If Algeria wins, they will get research points and can be added into Ottoman SOI
> Algeria do not lose core on Batnah - probably a mistake, because it has a high (suggesting new new) id

### War for Oran

`1830_GFM_FRA.txt - oran_french_war`
After wining the first war France can easily begin next. They just need to be at peace, hold Algiers and wait until **1831**.
They will declare war on Algeria with *Punitive Expedition* CB if they still hold Oran. This decision even ignores truce between them.
After taking this treaty port they also gain POPs there, this time from Lake Athabasca.

> Truce breaking from decisions like that still leads to prestige loss and infamy gain

### War fo Ennab

`1830_GFM_FRA.txt - bone_french_war`
Another war that ignores truce. France can do it when at peace while owning Oran from **1832** if `RGA`, `ALD` or `LBY` owns Ennab.
This just declares another Punitive Expedition war against its owner.

### War for Bougie with Ait Abbas

`1830_GFM_FRA.txt - bougie_french_war`
It works literally the same. France just declares a war on them if `ABA` own Bougie. They again just need to hold Algiers and wait until **1833**.

### Battle of Macta - conquest of Algeria

`1830_GFM_FRA.txt - 17051919`
It triggers for France owning any Algerian core in short time window: **May-December 1835**. It declares another war on Algiers and Algeria with *Establish Protectorate* CB, again ignoring potential truce.

> As player you can also chose to not declare these wars in that event, losing prestige

### French settlement in Algeria

`1830_GFM_FRA.txt - fund_french_settlement_in_algeria` & `1830_GFM_FRA.txt - 160518542`
This easy decision gives France corresponding event that has 3 options, neither costing anything. The first increases French settled POPs, gives them some cash and increases size their slaves POPs, the second omits that slaves part and the third reduces prestige. There is no `AI` weighting there as in entire file.

### Conquest of Beylik of Constantine

`Algerian_War.txt - 372382`

### Rebellion - annexation of remaining states

`Algerian_War.txt - 37240`

## Benin/Dahomey

Dahomey colony - modern day country of Benin - in 1830 a state belonging to 4 nations, 2 of them have a capital there - Dahomey and Borgu. They are separated by empty land. Benin is scripted to be colonized by France.

### Partition of Egba

`Yakutat.txt - pact_for_abeokuta`
Decision allowing Dahomey to partition Egba with Ijebu in 1850-54 time window for **5 infamy**.

> Thanks to it there is one nation less to conquer in the 1880's

Type: -  
Requirements:

- Be independent Dahomey at peace owning Abomey (thats their capital)
- Ijebu owns Eko (also their capital)
- Egba owns booth of their starting provinces
- Its before 1855
- Have 200 relation with Ijebu (`AI` can omit that **from 1850**)

Effects: A war with `cut_down_to_size_no_infamy` CB is declared upon Egba **for 5 infamy**, Egba adds humiliate CB and event chain starts.

In short, If all participants are `AI` controlled, Ijebu joins the war and UK stays neutral, making an easy war for the attackers.

If they win the war, and no one got on their way otherwise, an event - `Yakutat.txt - 184824102` happens.
It gives Abenkuta to Ijebu and Ketu to Dahomey and ensures they still have slavery, giving them that reform.

Here is a graph depicting full event chain:

```text
[Decision to partition Egba]
           ↓            
[Join the war - Ijebu]
↳ (Do not join - 0% chance) → [Ijebu rejects deal - Dahomey]
|                             ↳ (Stop the war - 0% chance)
|                             ↳ (Declare war on Ijebu - 100% chance)
|
↳ (Join) → [Egba calls UK]
           ↳ (Stand alone - 10% chance) ----------------------→ [Dahomey victory]
           ↳ (Ask UK to join - 90% chance)
                  ↓
           [UK answers to Egba]
           ↳ (Ignore them - 100% chance) ---------------------→ [Dahomey victory]
           ↳ (Send ultimatum and add them to SoI - 0% chance)
                     ↓
           [UK Ultimatum - Dahomey]
           ↳ (Reject Ultimatum - 90% chance) → [UK responds to rejected ultimatum]
           |                                   ↳ (Blockade them - 90% chance) -------------------→ [UK naval blockade - Dahomey]
           |                                   ↳ (Do nothing - 10% chance)                         ↳ (Ignore blockade - 10% chance) → [UK acknowledge that]
           ↳ (Accept Ultimatum - 10% chance)                 ↓                                     ↳ (Surrender - 90% chance)
                            |                    [UK do not intervene - Egba]                                   ↓
                            ↓                    [UK do not intervene - Dahomey]                     [Dahomey accepts ultimatum - UK]
             [Dahomey accepts ultimatum - UK]                  ↓                                     [Dahomey accepts ultimatum - Egba]
             [Dahomey accepts ultimatum - Egba]        [Dahomey victory]                             [Dahomey accepts ultimatum - Ijebu]
             [Dahomey accepts ultimatum - Ijebu]
```

#### References

- Decision to partition Egba - `pact_for_abeokuta`
- Join the war - Ijebu - `18482410`
- Ijebu rejects deal - Dahomey - `184824101`
- Dahomey victory - `184824102`
- Egba calls UK - `184824103`
- UK answers to Egba - `184824104`
- UK Ultimatum - Dahomey - `184824105` - also gives them 100 influence over Dahomey
- Dahomey accepts ultimatum - UK - `184824106`
- Dahomey accepts ultimatum - Egba `184824107`
- Dahomey accepts ultimatum - Ijebu - `184824108`
- UK responds to rejected ultimatum - `184824109`
- UK do not intervene - Egba - `184824110`
- UK do not intervene - Dahomey - `184824111`
- UK naval blockade - Dahomey - `184824112`
- UK acknowledge that - `184824113`

> Note: It worked in test like if `AI` would be able to take decisions with `factor = 0` somehow
> Note: UK does not declare war directly at any point in the event chain.

### Concessions to France

`FlavourMod_Africa.txt - cotonou_concession`  
It allows France to take Wyida and add Dahomey to their SoI **from ~1855** for **0.5 infamy**.

> You can prevent France from doing that by adding Dahomey to your SoI

Type: `colonial_railroading`
Requirements:

- Be a great power French primary culture with 2 MNL+ POPs (be an incarnation of France)
- Have `Nationalism & Imperialism` & `Raider Group Doctrine`
- Wyida is owned by an uncivilized `AI` that cannot be in SoI of other nation
- Don't be disarmed
- Neither pacifistic
- Less than 5 war exhaustion
- Have 45+ ships and 45k+ funds (actually 45001) to pay (`AI` omits that)

Effects: Wyida is bought from Dahomey for 45k and they are added to SoI (300 influence) of decision executor

### Conquest of the east

`Yakutat.txt - finish_off_dahomey`
Type: `colonial_railroading`, `berlin_conference`
Requirements:

- Own Wyida, while Dahomey own Abomey
- Be independent great power (is otherwise possible?) that is not disarmed
- Be at peace (this can be bypassed from 1883)

Effects: Dahomey get empty province of Chauru, and Ketu if they failed to take it earlier and you declare a war of conquest upon them.
You also declare a war upon Borgu, with `demand_concession_capital` or `annex_africa_full` CB, depending on their extend.

> Note that this decision can be done by almost any nation. It also ignores sphere leader of the Dahomey.
> Dahomey add a CB to retake core, making intervention mechanic useless there.

### Conquest of the west

`Yakutat.txt - 18482534`
> This event is just a mean to extend the reach of **any** Dahomey colonizer
Type: `colonial_railroading`
Requirements:

- Own Abomey & Wyida while Dahomey no longer exists (basically conquer Dahomey)
- **Its 1875 or later**
- Be a colonial nation (this is a weak check to filter out African nations)

Effect: You get 4 provinces in Dahomey state: Idaasha, Maho, Materi and Chauru that if they are empty or owned by an uncivilized nation.

> Berlin Conference happens in the beginning of 1880's, meaning that it can be done **instantly after conquering Dahomey**.

## Belgian Congo

Congo (the bigger - Belgian one) colony has a complex scripts allowing it to be taken by Belgium (eventually other secondary like power) with approval from great powers in the Congo Conference. This is one of the most beneficial colonies, with wast supply of rubber and other resources and big population.

### 1830 in future Belgian Congo

Borders of this future colony are so wast and abstract that it shatters many native African countries. The coast belongs to two countries, then there are a few countries in the interior, but half of the colony consist of empty jungle provinces in the center. Colony also cuts in half two Central African countries in the north and Rwanda to the east.

### The Congo Conference

This conference can be called by `colonial_railroading` decision by Belgium (or `BNF`) or eventually other secondary like power to take over wast Congo colony while having limited colonial possibilities, thanks to approval by Great Powers, forbidding them from taking that colony. By doing so they can weaken colonial rivals, because no one will take it.

> Note: For simplicity, in this chapter, the country that calls the Congo Conference will be called *Belgium*, since they do it in wast majority of campaigns, despite its formable and other minor European powers also having access to it.  
> Note: Taking Congo that way forbids you from using *Scramble for Africa* CB, severely reducing your potential at gaining other colonies in Africa. It is also generally restricted to minor European countries.

`BEL.txt - international_african_association`

Requirements:

- Berlin Conference has happened (early 1870's) and its at least 1870 (useless check?)
- Country have a capital in Europe
- Have a naval base
- At least 6 cities (provinces?) and at least 2 states
- Its independent monarchy at peace
- It is not any of those countries: `TUR`, `RUS`, `SAR`, `SIC`
- Have 1MLN+ POPs
- Have 16+ rank or is `BEL` or `BNF`
- Abolished slavery
Then country have to fulfill at least one set of those requirements:
- Set one (10 infamy):
  - Have less than 10 infamy
  - Do not have any subjects
  - Do not have any colonial province
  - Have `Blue and Brown Water Schools` (1875) technology
- Set two (2.5 infamy)
  - Less than 2.5 infamy
  - Do not have any province in Africa (but other colonies **are allowed**)
  - Have `Naval Logistics` (1870) technology
  - It is at least 1885
- Set three (0.25 infamy)
  - Have less than 0.25 infamy
  - Do not have any province in Africa (but other colonies **are NOT allowed**)
  - Do not have any colonial province
  - Have `Raider Group Doctrine` (1855) technology
  - It is at least 1886
- Set four (Belgium)
  - It is `BEL` or `BNF`
  - Have less than 12.5 infamy
  - Do not have any province in Africa (but other colonies **are NOT allowed**)
  - Do not have any colonial province
  - Have `Raider Group Doctrine` (1855) technology
  - It is at least 1884
  - `colonial_railroading` is enabled

> Note: One of the sets is identical as the other but has a smaller infamy tolerance. Due to this, it was skipped.  
> Note: `colonial_railroading` is checked to even show this decision, so its placement in Belgium set requirements is useless.

Effects:

All Great Powers in Europe, excluding `TUR`, `RUS` and Belgium gets an event in with they can vote to agree or deny demands stated in the conference.

`Congo.txt - 955182`

There are 3 options:

- Vote for Belgium
- Vote against Belgium
- Abstain from voting

1. Gives 25 influence and 25 relation Belgium (`AI` base 75%, 2x if have Belgium in SoI or at 150+ relation, 1.1x if at 100+ relation, 5x if `BEL` or `BNF` called the conference, 0.7x if at -50 relation, 0.4x if at -100 relation)
2. Gives -25 influence and -25 relation with Belgium (`AI` base 20%, 0.1x if have Belgium in SoI or at 150+ relation, 1.25x if at -50 relation, 1.5x if at -100 relation)
3. Nothing happens (`AI` 5%)

> Note: In this time period there should be around 4-6 countries allowed to vote.
> If `BEL` or `BNF` called the conference and there are no big player involvements, they have little chances to lose this voting.
> Since Belgium have big favours if they called the Conference, the worst chances they can get look like this: 1: ~71% 2: ~25% 3: ~3%

When *votes are counted* another event happens in with Belgium claims Congo:

`Congo.txt - 4778710`

Event triggers if Belgium received at least 4 votes *for* or at lest 3 votes *for* while there are less than 3 votes *against*.

This gives event to Belgium to claim Congo if any westernized nation is owning Boma or Kinkoki or Lemba. There, they ask them to transfer Congo to them through another event.

`Congo.txt - 4778711`

Congo current colonizer gets 2 options there:

- Sell Congo to Belgium
- Stay at Congo against Belgium

1. Congo is sold for 100k, (see map for actual provinces that are sold) you get 25 prestige and **lose 3 infamy** (`AI` 100%)
2. **3 infamy** is given, 25 prestige taken, every European GP lose 250 relation with you and get cut down to size CB against you. In response you get the same CB against Belgium, and lose 400 influence and relations with it. (`AI` 0%)

> This means that in order to vote conference to fail, you need to force at least 3 votes *against* and up to 3 *for*, or just less than 3 votes *for*. You can occupy European GPs to oblivion, making non-Europeans countries GPs since only European GPs can vote.
> Congo is transferred in the next event, this just asks its owner

If Belgium took Congo (may there be an exploit?) and if votes are still for it (this is double checking?), another event happens, where Congo is colonized by Belgium.

`Congo.txt - 955183`

Congo is colonized by Belgium and any country that voted for it, transfers their provinces to it. Other countries are given ultimatum to do it instead.
Colony consists of a westernized subject with its master religion, Belgium gets `Indirect Rule` reform/colonial policy, despite potentially not owning any colony directly.

WIP

## Ghana

### Ghana in 1830

Colony of Ghana consist of 2 states: Gold coast at the south and Lower Volta in the north. In 1830, the north is dominated by tiny natives, the center by Ashanti and the coast by 3 European colonies.
Those belong to UK, The Netherlands & Denmark. North of them there is also another native tag, Fante that is in the UK's SoI and alliance. They also have a Union Jack as part of their flag.

### The Anglo-Ashanti Treaty

`1830_GFM_ENG.txt - anglo_ashanti_treaty` It is a decision available since **1831** to `ENG` at peace owning Cape Coast while Ashanti and Fante exists.
It gives Ashanti a treaty event: `1830_GFM_ENG.txt - 16051835`. There, Ashanti can accept it, giving them Krobo (`AI` 100%) or deny, giving UK another event.
Whatever happens, UK gets respond event. If Ashanti denied, they can declare a war to take it (`AI` 100%), or let it be.

### The sell of Accra

Denmark (or Denmark-Norway) sells Accra to Cape Coast owner in the early 1850's. **Potentially, it can give colonies like Ghana, Togo?, Senegal?, Benin and Ivory Coast** from Accra owner to Gold Coast province owner.

`DEN.txt - selling_danish_ghana`  
Requirements:

- It is at least 1850
- It has `State & Goverment` technology
- Its Denmark or Denmark-Norway with Danish as primary culture
- Owns Accra
- It is not a great power
- It is independent and at peace
- It does not own any of Fante starting provinces or `colonial_railroading` is disabled
- Cape Coast owner:
  - Is civilized
  - Ruing party is not reactionary, communist or fascist
  - Have at least 0 relation with this country
  - Is independent or a puppet of that country
  - Have at least 35 001 funds

Finally, Cape Coast owner gets an event in with they can deny it (AI 0%) or accept.
If accepted, the following provinces will be transferred: Accra and all provinces that seller may own in the following colonies: Ghana, Togo?, Senegal?, Benin and Ivory Coast for 55k (seller always gets its money but `AI` do not pay anything). Seller also loses 200 influence and relations with Ashanti.

### Bond of 1844

This is a decision available from **1844** to `ENG`, making Fante their subject.

`Yakutat.txt - bond_of_1844`  
Requirements:

- It is `ENG` at peace and not disarmed owning Cape Coast, Accra or Sekondi
- Fante is an independent nation, have no truce with a country making this decision and at least -100 relation with them

2 prestige is given and an event chain begins:

`Yakutat.txt - 18490031` - Fante agrees or not on treaty, if they agree (`AI` 100%), `ENG` gets the next event:
`18490031` - Where `ENG` can alter the treaty (`AI` 100%) or not. Fante gets another event for **0.5 infamy** (`AI` do not get it):
`184900313` - Where Fante becomes their subject.

Alternatively if player is involved, Fante can oppose the treaty, giving `ENG` event where they can let if be, **losing 0.5 infamy**, or subjecting them through war for **2 infamy**. Fante adds humiliate CB, making no use to intervention mechanic.

### Sogakope

Sogakope is the only empty province in Ghana. It can be taken in expansion like event, described in the expansion section.

### Annexation of Fante

It looks like Fante do not have a dedicated annexation script. So it is probably annexed through SoI chain event, since they are UK subject in their SoI - hard material to overcome.

### Gold Coast Treaty

`ENG.txt - gold_coast_treaty` is a decision allowing Gold Coast owner (generally UK) to take Sekondi through treaty with the Dutch or `BNF`. You also agree to lose 200 influence over Indonesian countries. **Potentially, it can give colonies like Ghana, Togo?, Senegal?, Benin and Ivory Coast** from Sekondi owner to Gold Coast province owner.

Requirements:

- **Suez Canal is enabled**
- **You** own Cape Coast as a great power at peace and have 10k+
- It is 1900 or Aceh (country in Sumatra) no longer exists
- You are not `NET` or `BNF`
- `NET` or `BNF`:
  - Is at peace
  - Own Sekondi and Batavia
  - If you disabled `colonial_railroading`, then that decision is blocked if they expanded their colony there

> This decision can be done by almost any country owning Cape Coast!
> `AI` will never do this decision while having a truce or less than -50 relation with Sekondi owner.

Finally, this decision takes your 10k and gives Sekondi owner an event: `ENGFlavor.txt - 36960`. There, receiver have 2 options.

If the treaty is accepted, Sekondi is transferred and relation is improved by 100. Then, the response event happens to country that did the original decision.

It gives 100 influence over seller (if it is not a GP), +50 relation, Sekondi and all provinces that seller may own in the following colonies: Ghana, Togo?, Senegal?, Benin and Ivory Coast.
You also lose 200 influence and all alliances with Indonesian minors.

If the treaty is rejected, then you will get a different event, giving your 10k back.
You can decide to let it be, losing 10 prestige or **for 2 infamy**, get a temporary core on Sekondi and humiliate CB, allowing you to take Sekondi through war.
You also lose 100 influence, alliance and relation with country that rejected the treaty. `AI` do not have any weights attached to this event.

> `AI` will always accept the treaty if it is a subject of the proposer or in its SoI. Otherwise, relations, having alliance or `AI` being in other GP SoI have an impact on its decision there.

### Annexation of Ashanti

`FlavourMod_Africa.txt - fourth_ashanti_war`

This is a big `colonial_railroading` decision for the final takeover of Ghana by `ENG`. Due to this, Ashanti is given the rest of non-westernized Ghana.

Requirements:

- It is a great power `ENG` owning Cape Coast or Accra or Sekondi while not disarmed and with `Colonial Negotiations`
  - If player does it there are extra requirements: have 95+ ships, `Blue & Brown Water Schools` and own Krobo
- It is at least 1875
- Uncivilized Ashanti is `AI` controlled, at peace and neighbors `ENG`

> `AI` can hold Cape Coast and wait until 1881 if it failed to take Krobo instead

Effects:

- All of future Ghana colony becomes a core of `GHN` (plus 2 Gyman provinces outside of Ghana)
- Local natives gives their land in Lower Volta state to Ashanti
- A safety check runs to secure both countries from truce breaking and similar infamy/prestige related penalties
- Ashanti declares a humiliation CB war on UK that gets conquest CB on them (making intervention mechanic useless there)

> Note: War will not be declared if there is a truce between UK and Ashanti

## Eritrea

## Indian Ocean Territory

This state is in 1830 owned by UK and France, with exception of Comoros & Mayotte.
First one is empty, second is an uncivilized OPM - Mahori Sultanate.

They are quickly annexed by France by unique `colonial_railroading` decision: `France.txt - annex_mayotte`.
France needs to be a great power at peace with `Medicine` technology that they get fairly early. Mahori Sultanate must be `AI` and Comoros must be empty.

> Probably the only way to get them before France is to conger Mahori, since **its 1 infamy max** and colonize Comoros by hand since they have 30 life rating, enabling colonization after getting just `Prophylaxis against Malaria`.

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

`Colonial railroading` decision available for the UK if said province is empty or owned by a uncivilized AI
They need to be a great power at peace, not disarmed, with Nationalism & Imperialism tech and 20+ ships.
In short, province will be renamed and given to the UK. It will happen in 1850+ because of techs.

### Beginning as the German colony

`decisions/FlavourMod_Africa.txt - german_west_africa`

Colonial railroading decision available from 1880 to Germany, GCF, or "North German state".
They need to be a great power monarchy, have prophylaxis_against_malaria, mission_to_civilize, steel_steamers techs and colonial_negotiations invention.
They also need 2mln+ POPs, not be disarmed, at least 3 ports, less than 5 war exhaustion and cannot be pacifistic.
Finally, player also needs 75 001 funds and 55 ships
Deido province needs to be empty or owned by an uncivilized AI

Germany then gets 2 infamy, southern Cameroon is transferred to temporary tag and some provinces are renamed.
Fusab and Ambass Bay owners (if any) are asked in events for the transfer of said provinces. Their AI will always agree.
If UK player will contest, Germany will get a casus beli on them,
but AI Germany will be chill against UK player that resisted transfer, not taking said casus beli.
Finally, all provinces are transferred from temporary tag to Germany and German player additionally pays 75k.

### Expansion to Adamawa state

`decisions/FlavourMod_Africa.txt - take_kamerun_interior`

Its 1882 and previous decision was taken (so only Germany can do this one).
Any of Adamawan STATE provinces is owned by uncivilized AI and Germany owns Fusab and Bangante

If UK owns Wukari and uncivilized Adamawa owns Yola and Dumboa, UK gets those from them. If Wukari is owned by Sokoto, they will get these instead.
Owner of Adamawa STATE is then asked for transfer (AI will never contest, otherwise Germany gets casus beli).
If they agree, Adamawa STATE is transferred to Germany through temporary tag.
There is also error with province id but it looks like it does not affect the decision.

### Expansion to Marva state

`take_entenschnabel`

technically colonial_railroading decision available to country that took german_west_africa decision (basically only Germany).
It is at most May any year from 1884, country needs to own Garwa and any province of that state needs to be owned by an uncivilized AI.

It instantly transfers uncivilized AI provinces from that state, ones owned by a civilized nation will be transferred through
event that AI will never contest. Otherwise Germany gets a casus beli.
Disclaimer: it is impossible to even be taken if A WHOLE STATE IS NOT owned by an uncivilized AI.

## Togo

Togo can be colonized by most european countries by just one `colonial_railroading` decision (`FlavourModAfrica.txt - claim_togoland`), however German `AI` have easier route to it.

Lome is empty or owned by uncivilized AI
**`RUS` and `TUR` cannot do it**, nation needs to have a capital in the Europe and `berlin_conference` has happened

Since so many counties can do this decision, it is important to prioritize this one, here is its requirements:

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

In short, if AI formed Germany (Prussia will always form it even without any other nation), probably the only easy way to get Togo is to keep German war exhaustion high.

If finally done, Togo is given and if civilized country owns any part of it, they will be asked to transfer it. AI will never contest, otherwise claimer will get a casus beli.

> Tip: There is an expansion like event that gives all of Togo and surrounding empty provinces. It is described in its section in the expansion chapter. You will need to own a province in Ghana and 2 in Dahomey however. It can even be taken by natives.

## Liberia

### Independence and early colonization

Liberia begins as uncivilized American OPM subject. Event `FlavourMod_USA - 441266` triggered in **1847** releases it and gives it Teysa and Tabu provinces.
As USA player, you can also play as it or annex Liberia with those extra provinces.
Whatever happens with these event, Liberia is still in US influence or annexed.

### Expansion

In short, `Liberia.txt - 441277` event will easily trigger in 1874 (`LIB` player can speed this up?),
it will give Liberia its modern borders and one extra province in every direction.
This is fairly complex event, its results may give Liberia more provinces?

## Ivory Coast

### First colony - Fort Nemours (Aboisso)

`Colonial railroading` decision - `Sitka.txt - fort_nemours` can be taken by great power France since 1840 (1843 automatically) if they are at peace.
France gains it and province name is changed. If some nation owned Aboisso earlier (few tags are listed), it is still taken and bad event is given to the loser.

### Mainland Conquest

`Colonial railroading` decision `FlavourModAfrica.txt - ivory_coast_conquest` can be made by almost any country - you can take that opportunity.

It must be at least 1875, country needs to own Fort Nemours, have 2MLN+ POPs, be 16+ rank, have `Nationalism & Imperialism` and 50k to spend, be independent, not disarmed, at peace and Sassandra and Subre needs to be empty.
If you are not `FRA`, you need to wait until 1882. `AI` France can get this without spending 50k.

This decision gives in short every empty province in Windward Coast state plus Man province.

> Disclaimer: Liberia can take Tabu and Guiglo earlier and they will not be given.

Names of 2 provinces are changed and war is declared against Wattara and Baule to annex them, but only if they are uncivilized `AI` outside of anyone SoI.

For some reason `BZD` is also a target.
Defending countries gets a casus beli against France, making it impossible to intervene on their side as a great power.

Search Plig in `events/Yakutat.txt`

## Senegal

### African minors actions

Bundu starts with a war of conquest against Wolof, while being weaker country.

### The Occupation of Seju

`Yakutat.txt - sedhiou_conquest` decision gives Seju province. It is not fixed to France.
It is available to civilized country at peace, owning Dakar OR Kahone OR Ziguinchor while Sejuand and Bigona are empty.
However, to actually do this decision, you need to own Dakar or Velingara. **It can be made since 1836 in months September-December**.

### Trarza-Waalo relations

`Yakutat.txt - trarza_waalo_relations` is a decision allowing them to create alliance in 1845.

### The plan of 1854

`Yakutat.txt - plan_of_1854` is a decision available to FRA or BOR tags owning St Louis, that do not own Babae or Xhouma.
France also needs to be at peace and not disarmed. **It is available well, from 1854**.

**It gives 4 infamy, but only to a player**, declares war with unique casus belli on any uncivilized country owning Babae, Xhouma, Mataam, Bakel, Kaedi, Bulibani or Xaayi.
Enforcing this casus beli on a country annexes it, but only provinces specified in decision are taken.
Defending nations gets a buff and a casus beli, making intervention as a great power impossible.

> Note: Annexation of Waalo paves the way for its repperance in the Equatorial Guinea. It is primarly used as that country with `tag`: `EQG`.

### Maba Diakhou Ba's Jihads

`Yakutat.txt - 184825379`
**Event in a short time window: March-December 1861**, that happens to animist owner of Kunghol.

It spawns Badibu in Kunghol. NOTE: It is a modified tag from kurdish Ottoman subject. Ottomans annex them in 1848, leaving this tag free to use.

Thanks to Yakutat.txt - launch_jihads_diakhou decision they made in **1865** they send ultimatum to Wolof, Saloum and Sine. Wolof converts to islam, while the rest reject the ultimatum.
Due to this, war is declared on them.

### Claim the Kayor Coast

This is a decision (`Yakutat.txt - dakar_stlouis_railroad`) is not restricted to France. You need to be a civilized country being at peace and not disarmed, owning St Louis and Dakar, while Kayor owns Mbul.
**AI can take it from 1863, while player from 1855** while having nationalism_n_imperialism and medicine techs.

It instantly gives you Mbul with 2 railroad lvs and declares war of conquest on Kayor for the **cost of 1 infamy**.
Since Kayor gets a casus beli, it is impossible to intervene.

### Appointment of Louis Briere - conquest

`FlavourModAfrica.txt - appoint_louis_briere` **colonial railroading** decision is available to great power France **from 1865**. Kedugu and Sitakili must be owned by France or by uncivilized nation.
France must have 2MLN+ POPs, cannot be disarmed, be a colonial nation, have nationalism_n_imperialism and raider_group_doctrine techs, 3+ ports, and less than 5 war e.
Player also needs 45+ ships on top of that.

**It gives 5 infamy**, declares war of conquest on Kedugu owner and gives a casus beli of congest on Orungu.
Defender gains casus beli, making intervention impossible, but against Orungu France gains just a casus beli, so intervention is possible.
It can be possible to lose that casus beli since Tenda can easily be a subject of Futa Jallon.
Note: AI will accept it even while having over 22 infamy, going over limit due to error in the code.

### Big invasion

`FRAFlavor.txt - 37241 event`. It can happen **from 1870** to a great power France at peace owning Dakar, Mbul and St Louis.
Jaxaaw, Kahone and Kunghol owner/s must be uncivilized, AI, or France, so if european AI got it it can still trigger.

It has 2 options, but only first is interesting.
**It gives 3 infamy** then, if **colonial_railroading** is not disabled and AI Trarza is not in any SOI and with no truce with France, it gives 500 influence over it, instantly adding it to SOI.
War is declared upon Sine, Saloum, Toro Immanate and Wolof if there are not truce with them. Read code for more details, since some of them may not be a target.
For some reason Bayazid is again listed there, but event works fine.
Same can be said about The Toro Immanate and Wolof, that should you should get a casus beli against, but it again does look like to work.
It is probably due to complex casus beli system giving *establish_protectorate_casus_belli* but it cannot be used why you have Nationalism & Imperialism tech, making it useless.

Theoretically it is possible to prevent France from taking this option, if they have large infamy. They also would take it even over infamy limit.
Note: Appointment of new Senegal Governor is not necessary for it, despite being directly linked in history.

### The Occupation of Bignona

`Yakutat.txt - fogni_conquest` decision is not limited to France. It gives Bignona.
You need to be civilized, own Seju or Soma province, Bignona must be empty, additionally, you need to own Dakar or Velingara and Seju cannot be empty.
Finally, you need to **own Velingara while having colonial_negotiations invention or just wait until 1883**.

### Border exchange

Velingara can be exchanged for Kansala through border exchange. Read another paragraph for details.

## Guinea

Guinea have a few uncivilized nations and empty provinces. It will be dominated by Jallon Immanate before the Scramble for Africa.

### African states actions

#### Creation of Kabadugu

In 1848, right after BZD tag is annexed by the Ottomans, they are spawned as Kabadugu in Odiene with Sinko province.
Kong that lost provinces to it also gets Man province.

#### Wattara Gwiriko conflicts

These countries ends up in war set by events, potentially by Gwiriko's secession. Events:
`Yakutat.txt - 184900011 18490002`

#### Jallon Imamate Conquests

Jallon declares a war against Tenda in **1856** to subjugate them (`Yakutat.txt - invade_tenda`).

- `events/Yakutat.txt - 184900211`
  If previous decision was taken, after wining war with Tenda, the *Treaty of Yimbering* happens. It has additional reqirements but it does not matter really.
  It gives Jallon Yimbering and colonizes Sangaredi and gives 5 prestige. It has `MTTH` of just 1 day.
- `decisions/Yakutat.txt - invade_kaabu`
  After that Jallon can easily make next decision, to puppet Gabu for **3 infamy**.
  Gabu gets an event for some army stats and adds humiliate casus beli, making intervention impossible.
- `events/Yakutat.txt - 18490021`
  After losing the war, Gabu can get an event, but it probably will never trigger due to requirements.
  Gabu is then annexed by Jallon, and they can get Boffa?
- `events/Yakutat.txt - 18482479`
  This event would allow annexation of Gabu, but it requires Jallon to be civilized.
- `decisions/Yakutat.txt - unite_with_tooro`
  This decision allows **non AI** Jallon Immanate to annex peacefully Tooro Immanate.
  Vice versa can be done if you play Tooro Imamate.
- `decisions/Yakutat.txt - denianke_happens`
  Is is a player only decision giving Jallon Immanate many provinces
- `decisions/Yakutat.txt - no_more_fula_jihad`
  Another player only decision available to 3 countries in the region
  It annexes TOU if it is a vassal and gives many cores in the region.

Later, a coalition of muslim countries can form against new coalition of animist countries.

> Subjects makes later Scrabble harder, but it is the best to let it all happen

### Colonization of Boffa

`Yakutat.txt - colonize_boffa` is a `colonial_railroading` decision to colonize Boffa.
It is only available to `FRA` or `BOR` tags owning Dakar. They need to be at peace and not disarmed.
**AI can do it since 1851, player instead needs `Nationalism & Imperialism`**.

> You cannot exploit it. It is better to conquer all of Senegal from France in one war

### Coastline conquest

`FlavourModAfrica.txt - conquer_conakry` is another `colonial_railroading` decision.
It is available **from 1870** to a great power France while Dubreka is empty.
They need to be at peace and not disarmed with `Nationalism & Imperialism`.
Player also needs 45+ ships.

**It gives 1.5 infamy**, gives Sangaredi and Dubreka and gives casus beli onto uncivilized AI owner of Forekariah.
That casus beli however may not appear?
`AI` will not do it while it is at 20+ infamy.

## Gambia

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

You can not however own Bissau, Ziguinchor or Cacheu - Portuguese possessions. You also cannot have a truce with Bissau owner - them.

> If left to itself it will happen shortly after France colonize Bignona **in 1870**

### Effects

Finally, events can be given to other colonizers in the region:

- Bissau owner gets an offer that `AI` will always accept, otherwise giving a casus beli.
- If you own Basse and `ENG` owns Soma, they will also participate in the negotiations

#### Deal with Bissau owner

They get Kansala from you otherwise from `AI` nation that owns it or will colonize it.
In exchange, you get all of their provinces they may have in Lower Guinea state and Gambia state provinces that belongs to Senegal colony, including Ziguinchor that is a Portuguese possessions in 1830.

If `FRA` or `BOR` neighbors any of those countries, they will declare war of conquest on them:

- Susu
- Wolof
- The Tooro Immanate
- The Jallon Immanate

> This event has a second option that `AI` will never take. It gives booth sides *Place in the Sun* CB
> There is also a feedback event just informing you about the outcome

You will get an event telling you about their decision. If they accepted the deal, you will also colonize Bignona if you do not own it already.

#### Deal with United Kingdom

In exchange for Soma and Basse that you may own (otherwise they will colonize/get them from `AI` owning it), they will also give you every province they might own in Lower Guinea and Gambia states, excluding Gambia proper, but this time also 4 southern provinces in the Djolof state. They also lose 400 influence over local `tags`, giving you free way to conquer them through previous event.

> UK needs to own Soma in a first place to participate in this negotiations
> United Kingdom `AI` will always accept this proposition, otherwise both sides gets *Place in the Sun* CB

## Gabon

`events/Yakutat.txt - 18482374`
Add influence over them - WIP

### The conquest of Orungu

`FlavourModAfrica.txt - appoint_louis_briere` described in Senegal section also gives conquest casus beli against Orungu

___

## Mali

`Yakutat.txt - massina_conquer_segu`

## Madagascar

Madagascar in 1830 consist of Imerina that holds most of the island, its subject Boina and small nation of Antankarana. In the south there are 2 empty provinces. France also owns a small island on the coast, that will be the key to Madagascar colonization.

> Imerina is one of few countries that cannot be a target of Scramble for Africa cb. You can still get them up to `berlin_conference` through SOI event

### Imerina decisions

#### Cores on surrounding islands

**Non AI** Imerina can get cores on surrounding islands through `decisions/Sitka.txt - Claim_MAD`.

> If you will ever play it you can use it to gain extra CP from naval bases

#### Boina annexation

`decisions/Yakutat.txt - annex_boina`
Imerina annexes its Boina subject in **1836**.
Decision description misleads that it leads to war with them.

> It is the best to let it happen. Otherwise you have an extra war to do

#### Colonization of the south

`decisions/Yakutat.txt - claim_madagascar_lowdesert`
Ampanihy & Ihosy can be taken by any nation owning Tananarive at peace since **1838**. Commonly, Imerina will do it.

> Let it happen. You do not lose anything

#### Cores in Antankarana

`decisions/Yakutat.txt - the_antankarana_question`
It grants cores to Imerina in all Antankaranan cores (Antomboko and Nosy Be) if Antankarana still exists.
It can be easily done from **1841**, but have a few other requirements.

### The Lambert Charter

`decisions/FlavourMod_Africa.txt - the_lambert_charter`
A decision available to great power France with `State & Goverment` tech (available from **1840**).
Imerina needs to be at peace and be in their SOI or not it any SOI at all.
It gives France 400 influence over them, instantly adding them to their SOI.

> It also reduces influence of great power having Imerina in SOI by 150, but this will do nothing since they cannot be in SOI of other powers to begin with
> Get Imerina to your SOI before that, that way it will be easiest, you will block them from doing this decision Remember however that they can do this decision instantly if you lose Imerina from SOI

### Nosy Be colony & influence over Antankarana

`decisions/Yakutat.txt - colonize_nosy_be`
Decision available to France owning Ile Sainte-Marie (island at the Madagascar coast) at 16+ rank, at peace, independent and not disarmed.
They also needs 100+ relation with Antankarana owning Nosy Be or just wait until **1840**.

France gets Nosy Be from them and they can contest it through event, but AI will never do it.

`events/Yakutat.txt - 18482357`
In **April of 1840** just after previous decision, Antankarana gets another event.
They there can take anti colonial position, but AI will never do that.
Instead owner of Nosy Be will get 400 influence and relations with them and get an event.

In that event Nosy Be owner will gain them as a subject or break any ties with them.
AI will always take the first option.
With that Antankarana will lose a core on Nosy Be and Imerina will get it instead.
This is because their cores makes borders of future Madagascar colony.

If any country takes Nosy Be from France, Antankarana will become a subject of Nosy Be new owner through `events/Yakutat.txt - 18482358`.
They else can be annexed through for for free or made free if a player wishes. AI will do neither of those.

> You may prevent this by taking Ile Sainte-Marie from France, but it costs infamy. SOI is still the only efficient way to get Madagascar. However, you will not get all Madagascar this way

### Puppet of Imerina

`decisions/FlavourMod_Africa - end_the_merina_monarchy`
This is a `berlin_conference` decision available **untill 1900** for great power owner of Ile Sainte-Marie
with `Nationalism & Imperialism`, `Mission to civilize`, capital in Europe and naval base that have Imerina in SOI.
Imerina needs to be an uncivilized nation that is not a subject and at peace.
You also need a province in Africa, but Ile Sainte-Marie that you need in a first place should fit.

It declares a war with Imerina to puppet them and annexes Antankarana if they are a subject of nation clicking this decision.
It does not give any infamy, but AI will not do it if at 23+ infamy.

> If you missed this event, it is the last chance to get Imerina. Add them to SOI.

### Reorganization of Madagascar

`events/Yakutat.txt - 18482516`
After Imerina becomes a subject of a country that did previous decision **before 1900**
(so basically after earlier war), this event triggers for their overlord with MTTH of 1 day.

It gives 50k and transfers 3 provinces that colonizer should have already in the Madagascar to Imerina.
It also gives `colony_exemption` flag to Imerina, preventing their annexation from having them in SOI alone.

> Their fate is set, you can only try prevent France from getting them

### Annexation of Imerina

`events/Yakutat.txt - 18482517`
It can trigger to country that got the previous event **from 1895**
with a MTTH of 1 month while Imerina is their subject.

It releases Imerina free and declares a war to annex them. Imerina adds just a status quo casus beli.
Since this event do not check for SOI over Imerina and they do not add other casus belli,
(all of their cores should belong to them in that date, disallowing retake core cb) a great power intervention is possible.

This event have a second option that AI will never take. It releases Imerina
and once again allows to annex them through SOI alone.

> Since Scramble for Africa cb does not work on them and neither SOI annexation from now, they can only be annexed the hard way

### Rebellion

`events/Sitka.txt - 123490`
From **1904**, a rebellion will happen to `FRA` controlled Madagascar.
Rebels add a casus beli, disallowing intervention.
A player can chose to play as the rebels.

> There is a **disabled** event `SAFFlavor.txt - 1500000` connected to sale of Madagascar.

## Equatorial Guinea

### 1830 in future Equatorial Guinea

In 1830, this state consist of UK leased from Spain Fernando Po island, Portuguesse Sao Tome e Principe and 2 empty provinces in the mainland Africa. Portuguesse colony is an etirely different one, despite being just a one province.

### End of Fernando Po lease

`SPA.txt - colonization_of_fernando_po` is a decision allowing Spain to end lease to the island.

It is avaible to `SPA` or `SPC` at peace while `ENG` owns Fernando Po and do not have a truce with it.
If you are a player, you need `Nationalism & Imperialism`, `AI` can also just wait untill **1855**.

> There is a useles check preventing `EIC` from seing this decision

It gives `ENG` an event: `Sitka.txt - 1239508` with 3 options:

- Return the island (`AI` 0%)
- Attempt to purchase it (`AI` 100%)
- Ingore them (`AI` 0%)

1. Transfers Fernando Po to Spain, and all english culture POPs from it to London
2. Spanish `AI` will alwasys refuse, otherwise UK can keep the island for 60k. You will transfer Fernando Po just as you would take option 1. If UK will still refuse to handel the island, the same event as if you would took option 3 will trigger
3. **For 1 infamy** you can keep the island, giving Spain a casus beli against you

> If `AI` is in controll of both nations, Fernando Po is transfered peacefuly to Spain

### Coastial provinces

After taking Fernando Po, Spain or `SPC` can get coastial subject through `colonial_railroading` event `Yakutat.txt - 18482430` that triggers in **March of 1858**.

> Note: This would create a subject Benga that hava a tag `EQG` - the same as Waalo (Senegal) that is annexed by France in 1854

If a player took this decision, a subject Benga is created in Evinayong and Mitembie.
If Waalo still exists, provinces are given directly.
If `AI` took this decision, provinces are always given directly.

### Inland colonization and border adjustments

`SPA.txt - treaty_of_bata`

If previous events went right, after Germany (or any other westernized nation) colonizes Cameroon (Kribi to be exact), this decision can be taken by Spain if they are at peace and have `Nationalism & Imperialism`.

Effects:

- Spain annexes Benga if they are their subject
- Kribi owner gets an event `SPAFlavor.txt - 90141`
- Gabon owner (if westernized) or European country that have Orungu in its SoI will get an event `Yakutat.txt - 18482429`

1. If istead of Benga, Spain got their provinces directly, nothing happens
2. If country agres, Aconibe is given to Spain and country that got this event **loses 1 infamy** and gets 75 relation with Spain (`AI` 70% - if between 2 AIs or countries have 50+ relation, its 100%). If no deal is achived, that country gets colonial CB on Spain for **2 infamy** (`AI` 30%, 60% if realtion is below -50, 0% if stated as above). Then, Spain gets the response event in with they can let it be for -5 prestige (`AI` 100%) or declare a war over it, with defender geting humiliate CB (`AI` 0%).
3. Gabon owner (if westernized) or European country that have Orungu in its SoI will get Mitembie from Spain. There is no other option to pick.

## Bouvet Island

It is one of few provinces with just 1 life rating. Due to this it cannot be colonized normally.
Stitka.txt - bouvet_island
It can be seized by Norway or Scandinavia from 1900 that have Oil Driven Ships tech (available from **1919**).
However after that UK gets an event where it can take it for **0.1 infamy**. AI have 10% chance to do it, and this action cannot be contested.

> Poland can get a core there, probably a mistake in the code. It is also temporary used in one event as a buffer province.

## Prince Edward Islands

It is one of few provinces with just 1 life rating. Due to this it cannot be colonized normally.
`Sitka.txt - prince_edward_islands`
You need to be a civilized country with Umtata or have a subject owning it, while said islands are empty.
Next there are two ways to take them:

- Have Mass Politics tech (available from 1900)
- Be a Boer primary culture with Naval Logistics tech if it is after 1900

Both results in province being taken within a few months from **1900**.
Boer RPA can get a core there. This is also true for non `AI` Imerina.

> If you really want them, you need to conquer Umtata, or just take all of South Africa at once since they belong to that state

## Kergulen Island

`Sitka.txt - 123562`
This `colonial_railroading` event `with MTTH` of 3 months that gives this island. It requires:
Being a France since **1893** while said island is empty.

It also changes its name and gives coal there instead of fish.
This coal however is shortly after in 1895 changed back to fish.

Non `AI` Imerina can also get a core there.

> It is theoretically possible to colonize it normally after getting `The Dark Continent`, otherwise you have to conquer it. It is a part of Australian Victoria state

## Mix

### Flavour Ferdinandea Island

`1830_GFM_FRA.txt - 17051920` & `1830_GFM_FRA.txt - 16051921`
Island that quickly sinks, but you can claim it and temporary disfavor other countries thanks to it!

## South Africa

> Disclaimer: Dithakong is in the Bechuanaland section

### Set-up for Boers

`events/1830_GFM_ENG.txt id: 18351836` # The Great Trek

If there is at least 1834, but before 1845
Country with banned slavery and owns both Cape Town & Port Elizabeth (UK bans it with slavery_abolition_act_ENG (1830_GFM_ENG decision), preventable?)

Gets an event that set-ups global flag `great_boer_trek` enabling Boer republics and associated events and decisions to begin and giving cores to future Boer states

This also begins the existance of prototype Oranje, see below section

Many events and decisions also checks for lacking of flag `boer_accepted`. It is only gained through `decisions/NET.txt id: embrace_the_boer`

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
Then they can click a decision from 1844 onwards: `Yakutat.txt - unite_with_potchefstroom`

This decision gives Transvaal maaaaany early techs, and anexes Oranje for Transvaal, while changing Transvaal goverment to prov_gov_conservative.
This also sets global flag unite_with_potchefstroom, which will be important later.
There are special cases if player plays one of this countries, making it player friendly, while overal effect is the same.

`Yakutat.txt - warden_line`

If UK controlls Cape Town while Oranje do not exists with global flag unite_with_potchefstroom
They can click a decision when at peace from 1848 onwards

This decision transfers Oranje core provinces from subjects of country that clicked this decision to Oranje
If owner/s of this provinces are not subjects of said country, they will get an event 18482307. Oranje also gains Phuthaditjhaba (again) as a core

This event asks owners of Oranje cores to give them to Oranje. If not, they will face a war. AI will always agree.
This also changes Oranje goverment type to colonial_company, changing their name to Transorangia and flag to union jack themed

Nothern Cape (O'okiep, Emthanjeni and Hantam)

`events/BoerWar.txt id - 98261` #The Northern Cape Colony

UK/SAF event at year 1840 with some MTTH, must be at peace and own Cape Town, at least one of said provinces must be empty

Target country gets O'okiep, Emthanjeni and Hantam (in that order) if they are not already colonized

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

Anexation of Zulu:
UK or South Africa at peace from 1878 onwards
Neightbouring uncivilized Zulu with less than 2 states and no truce

Gets an event allowing them to declare war on Zulu with establish protectorate casus beli. AI would do this if they have a infamy reserve.

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

If country geting the event own any of said provinces, it will give them to Potchefstroom, which is temporary created in empty Saan province

This triggers 2 events:

`184824202` - for Potchefstroom
It asks them if they want to declare independence or not (AI will always stay loyal in this event)

Event for Mthwakazi (events/Yakutat.txt id: 18482305), that sets up Potchefstroom Republic, for example making it a puppet of a nation that got original 98220 event
Asks Mthwakazi for contest of it (AI will never do this)
(3rd option allows to play as Potchefstroom Republic) and triggers another 2 events:

`events/Yakutat.txt id: 184823053` - for the owner of Ga-Seleka
It asks for action against their incursion into Ga-Seleka (AI will never oppose it), then event 184823055 triggers for Mthwakazi as a response,
giving them said province and giving their old provinces to Potchefstroom and aslo uncolonizing Saan province from them (by changing life rating?)

events/African uncivilizeds.txt id: 95517 - for Potchefstroom after ~120 days (MTTH)
Basicly another double event triger and 3 prestige, this delay allows Mthwakazi migration to work without issues and look smoothly

events/African uncivilizeds.txt id: 95518 - for Mthwakazi
Mthwakazi moves from Ga-Seleka (giving it (back) to gaMangwato) to southern Zimbabwe, + anexing OPM in Tomotha province
Rozvi, which loses said Zimbabwe provinces also loses 2 western provinces to baTawana
Mthwakazi also gains powerfull military buff without expiration date

events/African uncivilizeds.txt id: 95517324 - for Rozvi Empire
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

The Northern Cape Colony (2-3 provinces)

UK or South Africa at peace owning Cape Town from 1840 onwards when any of the target province is empty (player also needs 10k)

Event giving target provinces for 10k

If someone else owns these provinces, UK have a decision if owning Cape Town to get a casus beli on that country. UK will also leave aliance with said country

Griekwastad/Kimberley

`events/Boer War.txt id: 98262` - Diamonds Discovered in Kimberley

Civilized nation owning Hantam from 1867 onwards, while Griekwastad do not produce gems and is owned by uncivilized nation or Griqua (MTTH = 1 day)

Griekwastad is renamed to Kimberley and its RGO changes to gems

If Mpondo owns Kokstad/Shayilanga, it wiil get event: events/Yakutat.txt id: 18490065, asking them if they allow Griekwastad to move into Kokstad/Shayilanga (AI wiil always accept)
This will remove all Griqua cores and make this provinces cores of South Africa, then give Griqua core in Kokstad/Shayilanga and give them 184900651 event
Another event: 184900653 is given to owner of Hantam

184900651 event will move Griqua POPs, change them to republic and make them a subject of UK, if they own any provinces listed in the event? (Lake Nyasa is one of them xD)

184900653 event will give Kimberley to nation that got this event, with Philippolis if Griqua also owns it

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

The fate of Basotho and Suazi

Basotho from 1860 onwards or Suazi after Berlin Conference can make a decision to ask for protection

The target country needs to:
Be a great power outside of Africa and own Cape Town that neightbour them
Basotho/Suazi cannot be in the sphere of influence of other country (can be in that of target country) and cannot be a puppet and must be at peace

Through an event target country makes them a puppet, target country gets all of their provinces, evcept for the capital,
changes their religion to its faith, gains influence over them and relations

Target country AI will rarely refuse
Note: from that point they cannot be a target for Scramble for Africa casus beli

reorganize_south_africa

Decision that requires ownership of Cape Town, being at peace and having Nationalism & Imperialism tech while South Africa do not exists

It makes South Africa of your primary culture, adds boer as their accepted culture
South Africa also loses its cores in South Africa that you do not own
This decision do not relase them

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

Luhonono can be bought from non African country thanks to buy_caprivi_strip decision

Requirements:

Is civilized and at peace
Hereroland state is fully owned, except for Luhonono
Target country is independent and have no truce with proposing country
Have 100k or is AI

Then target country gets an event in which it makes the deal, or denies
The better the relations, the better the chance for the deal with AI and vice versa
If target is in the sphere of the proposer, the chance is very good even with the worst relations
