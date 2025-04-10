
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

### Style Group (2 Numbers)

Randomly assigned
