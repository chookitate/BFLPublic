# Investigation - svmnaldo_alt
## Raw Proof & Explanation
---

These files contain the raw data which led us to the conclusion that svmnaldo_alt is VPNing. Most of the information in the JSON files is irrelevant, except for the CountryCode, SystemLocale, and TimezoneName attributes, found near the bottom. We collect the data collected in these json files for everyone, and it is how our Valkyrie system functions.

`baseline.json` - This is the "baseline" client settings and locale information for svmnaldo_alt. Captured on November 22, 2026 at 7:22 PM GMT. Note that SystemLocale, and TimezoneName are en-gb and GMT respectively, showing that he uses his system in British English, with the british timezone. 

`00 November 18th Bosnia join.json` - This is the first country descrepancy observed. This was captured at *November 18, 2026 at 10:24 PM*, with "CountryRegion" now showing "BA" (Bosnia) instead of "HR" (Croatia) as observed less than an hour earlier in `00 November 18th Croatia join adjacent.json`, captured at *November 18, 2026 at 9:18 PM* . This is not definitive proof, due to the proximity of the two countries, however, it does explain the behaviour seen later on.

`01 November 2nd United Kingdom join.json` - The first join from the United Kingdom, captured at *November 2, 2026 at 4:56 PM*. Just minutes later, at *November 2, 2026 at 5:17 PM*, he is seen joining from Croatia, as evidenced in `01 November 2nd Croatia join adjacent.json`.

`02 October 31st United Kingdom join.json` - The second join from the United Kingdom, captured at *October 31, 2026 at 2:50 AM*. Again, 1 hour prior, on a join at *October 31, 2026 at 1:40 AM*, he was in Croatia, as evidenced in `02 October 31st Croatia join adjacent.json`..