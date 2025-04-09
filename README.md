
# Beer Style Code Convention

This document outlines the convention used to generate compact style codes for beer styles in the BJCP dataset and custom additions like modern IPAs. The codes are used to tag beers with a meaningful identifier based on yeast, region, style group, and optional variants.

---

## Code Format

### Basic Format (4 characters)
```
<Yeast><Region><Group>
```

### Extended Format (5 characters)
```
<Yeast><Region><Group><Variant>
```

---

## Component Definitions

### Yeast Type (1 character)
| Code | Type                   |
|------|------------------------|
| A    | Ale (*S. cerevisiae*)  |
| L    | Lager (*S. pastorianus*) |
| B    | Brettanomyces          |
| K    | Kveik                  |
| M    | Mixed Culture          |
| W    | Wild/Spontaneous       |
| N    | Non-traditional Yeast  |

---

### Region (2 characters)
| Code | Region           |
|------|------------------|
| US   | United States    |
| UK   | United Kingdom   |
| DE   | Germany          |
| BE   | Belgium          |
| NO   | Norway           |
| CZ   | Czech Republic   |
| IE   | Ireland          |
| FR   | France           |
| JP   | Japan            |
| AU   | Australia        |
| PL   | Poland           |
| RU   | Russia           |
| DK   | Denmark          |
| NL   | Netherlands      |
| SE   | Sweden           |
| BR   | Brazil           |
| CA   | Canada           |
| MX   | Mexico           |

---

### Style Group (1 character)
| Code | Group Name                 |
|------|----------------------------|
| L    | Light                      |
| P    | Pale                       |
| D    | Dark                       |
| R    | Roasty                     |
| W    | Wheat                      |
| A    | Amber / Brown              |
| S    | Sour / Tart                |
| F    | Funky / Farmhouse / Wild   |
| C    | Crisp / Lager              |
| H    | Hoppy / IPA-style          |
| M    | Malty / Sweet              |
| B    | Bitter / Dry               |
| T    | Strong / High ABV          |
| V    | Specialty / Fruit / Spice  |
| X    | Undefined / Mixed          |

---

### Variant (Optional 5th character for IPAs and modern substyles)
| Suffix | Meaning           | Examples                  |
|--------|-------------------|---------------------------|
| W      | West Coast        | SoCal IPA, WCIPA          |
| E      | East Coast        | NEIPA (non-hazy)          |
| C      | SoCal West Coast  | SoCal IPA                 |
| H      | Hazy              | Hazy IPA, NEIPA           |
| D      | Dank              | Dank West Coast IPA       |
| B      | Black IPA         | Cascadian Dark Ale        |
| R      | Red IPA           | American Red IPA          |
| T      | Triple IPA        | High ABV IPAs             |
| S      | Session IPA       | Lower ABV hoppy beers     |

---

## Examples

| Style Name         | Code   | Notes                                 |
|--------------------|--------|---------------------------------------|
| American IPA       | AUSH   | Standard IPA, Ale/US/Hoppy            |
| SoCal IPA          | AUSHW  | West Coast IPA                        |
| NEIPA              | AUSHE  | East Coast Hazy IPA                   |
| Red IPA            | AUSHR  | Amber malt body with IPA hopping      |
| Belgian Dubbel     | ABED   | Ale/Belgium/Dark                      |
| German Pilsner     | LDEC   | Lager/Germany/Crisp                   |
| Brett Saison       | BEBF   | Brett/Belgium/Farmhouse               |

---
