
## DCS World - Hold Item List

Hold Item List: A list of specific work orders that are deferred because a required part, piece of equipment, or system is missing or inoperable although a limitation might be associated with the HIL record.
Put in simple terms: DCS_HIL lets you check current status/airworthyness of your DCS aircraft before you hop in or start planning your next mission. It's the way it's done in real life.

**Why?**
because in my opinion it is preferable to know your options during planning time, i.e. what works and to what extent, instead of having to find out the hard way: over the target area after 1.5 h mission time (or trail & error).

**Is it realistic?**
in some way even "bugs" are. real life aircraft often have small defects that dont require immediate grounding. Flight & maintenance crews use the manufacturer's documentation to assess, if and under which conditions an aircraft is airworthy, before flight.

**How is this different from a bug list?**
a bug list features all things that remain to be corrected, f.ex. graphical issues/missing sounds, and things that are not in line with the real counterpart, whether or not those things are impeding functionality. Also the HIL presents relevant defects more systematically than the bugs sections in ED's forums.

**What should go into the HIL?**
only bugs that would prevent a specific task to be performed as expected, or features that are completely broken/missing. Also a workaround, if available.
**Reference: official game manual or Chuck's guides** (i think there is no point in browsing through real life docs, and listing everything that's missing in the game).

**How could this be done?**
obviously this can only be achieved as a group effort. Github is a good starting point, because of its accessibility, but this project could move to another platform in the future.

### Formatting Rules ###
main categories (Flight Control System, Weapon System, etc.) are always listed and labeled either/or
| **unrestricted** |**`RESTRICTED`**|
| --- | --- |

sub-category items (Speedbrake, AIM-120C, etc.) are only listed, if restricted (workaround available) or inoperative (completely unusable or missing feature), and labeled as follows
|**`RESTRICTED`**|**`INOP`**|
|--- | --- |

Sorting: 
- categories by priority, see template below
- items alphabetically; except for weapon system: air-air weapons first, alphabetically, air-ground weapons next, also alphabetically

### Template ###
use this as example or to copy/paste items and labels into the HIL

| **Flight Control System** | **`RESTRICTED`** ||||
| --- | --- | --- | --- | --- |
| *Item* | *Restriction* | *Description / Workaround* | *Date* | *Name* |
| Example | **`INOP`** | very very long description and even longer workaround 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 1234567890 | 2021-11-24 | HILOK |

| **Performance** | **unrestricted** ||||
| --- | --- | --- | --- | --- |
| *Item* | *Restriction* | *Description / Workaround* | *Date* | *Name* |
| Take-Off | --- | --- | --- | --- |
| Landing | --- | --- | --- | --- |
| Range | --- | --- | --- | --- |
| Air Air Refueling | --- | --- | --- | --- |
| Cold Weather Opertaion | --- | --- | --- | --- |
| Night Operation | --- | --- | --- | --- |
| VSTOL | --- | --- | --- | --- |
| Carrier Operation | --- | --- | --- | --- |

| **Navigation** | **unrestricted** ||||
| --- | --- | --- | --- | --- |
| *Item* | *Restriction* | *Description / Workaround* | *Date* | *Name* |
| ADF | --- | --- | --- | --- |
| DME | --- | --- | --- | --- |
| ILS | --- | --- | --- | --- |
| TACAN | --- | --- | --- | --- |
| Terrain Following | --- | --- | --- | --- |
| VOR | --- | --- | --- | --- |

| **Communication** | **unrestricted** ||||
| --- | --- | --- | --- | --- |
| *Item* | *Restriction* | *Description / Workaround* | *Date* | *Name* |
| Datalink | --- | --- | --- | --- |
| VHF | --- | --- | --- | --- |
| UHF | --- | --- | --- | --- |

| **Defensive System** | **unrestricted** ||||
| --- | --- | --- | --- | --- |
| *Item* | *Restriction* | *Description / Workaround* | *Date* | *Name* |
| --- | --- | --- | --- | --- |

| **Targeting System** | **unrestricted** ||||
| --- | --- | --- | --- | --- |
| *Item* | *Restriction* | *Description / Workaround* | *Date* | *Name* |
| --- | --- | --- | --- | --- |

| **Weapon System** | **`RESTRICTED`** ||||
| --- | --- | --- | --- | --- |
| *Item* | *Restriction* | *Description / Workaround* | *Date* | *Name* |
| Gun | --- | --- | --- | --- |
| AIM-7F | --- | --- | --- | --- |
| AIM-7M | --- | --- | --- | --- |
| AIM-7MH | --- | --- | --- | --- |
| AIM-9L | --- | --- | --- | --- |
| AIM-9M | --- | --- | --- | --- |
| AIM-9X | --- | --- | --- | --- |
| AIM-120C | --- | --- | --- | --- |
| AIM-120B | --- | --- | --- | --- |
| CAP-9M | --- | --- | --- | --- |
| AGM-62 | --- | --- | --- | --- |
| AGM-65E | --- | --- | --- | --- |
| AGM-65F | --- | --- | --- | --- |
| AGM-84D | --- | --- | --- | --- |
| AGM-84E | --- | --- | --- | --- |
| AGM-88C | --- | --- | --- | --- |
| AGM-154A | --- | --- | --- | --- |
| AGM-154C | --- | --- | --- | --- |
| BDU-33 | --- | --- | --- | --- |
| CBU-99 | --- | --- | --- | --- |
| GBU-12 | --- | --- | --- | --- |
| GBU-16 | --- | --- | --- | --- |
| GBU-10 | --- | --- | --- | --- |
| GBU-38 | --- | --- | --- | --- |
| GBU-32 | --- | --- | --- | --- |
| GBU-31 | --- | --- | --- | --- |
| Mk. 5 | --- | --- | --- | --- |
| Mk. 20 | --- | --- | --- | --- |
| Mk. 71 | --- | --- | --- | --- |
| Mk. 82 | --- | --- | --- | --- |
| Mk. 82Y | --- | --- | --- | --- |
| Mk. 83 | --- | --- | --- | --- |
| Mk. 84 | --- | --- | --- | --- |
| Mk. 151 | --- | --- | --- | --- |

- EOF
