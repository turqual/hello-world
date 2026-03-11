# gs-ilvl-lookup

A Simple script to return the Average Item Level (ilvl) of a character in World of Warcraft to a field in a google sheet. 

 * Looks up a WoW character's equipped item level.
 * @param {string} realmSlug  e.g. "area-52"
 * @param {string} characterName  e.g. "thrall"
 * @param {string} region  e.g. "us" or "eu" (default: "us")
 * @return {number} Equipped item level
 * @customfunction

Will need the realmSlug, characterName (including special characters), and the region (either us or eu).

Add `=WOW_ILVL(<NAME>, <REGION>,<REALM>)` in the field on the row that you want to display the iLVL
