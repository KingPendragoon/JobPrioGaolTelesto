V1.31-T
***Make sure to reverify party order in trig / FF after Endwalker.*** 

**This version does not use macros thanks to the Telesto plugin**

**Set Up**

You need triggernometry https://github.com/paissaheavyindustries/Triggernometry/releases/latest
You need FFXIV Quick Launcher https://github.com/goatcorp/FFXIVQuickLauncher/releases/latest
You need the plugin Telesto for quick Launcher (instructions on how to install in link) https://github.com/paissaheavyindustries/Telesto

Please make sure that Default party sort is enabled in FF (Tank, Healer, DPS)
![alt text](https://github.com/KingPendragoon/FFXIVJobPrioGaolAutoMarker/blob/main/PartySortInGame.png?raw=true)

In triggernometry it is configured under "Options > Edit Configuration > Final Fantasy XIV" that player list set to `Player First rest by Custom Order`. Then Go through and make sure that your `In Game Role Sort Settings` and your Triggernometry Player List Custom Order match 1 to 1.  ***If they do not then the auto markers will mark the wrong players***


 ![alt text](https://github.com/KingPendragoon/FFXIVJobPrioGaolAutoMarker/blob/main/PartyListTriggerStep1.png?raw=true)
 
 ![alt text](https://github.com/KingPendragoon/FFXIVJobPrioGaolAutoMarker/blob/main/PartyListTriggerStep2.png?raw=true)
 
 ![alt text](https://github.com/KingPendragoon/FFXIVJobPrioGaolAutoMarker/blob/main/PartyListTriggerStep3.png?raw=true)
 
**Testing**
Make sure telesto is on /telesto 

If you would like to test if the triggers work before you go into the fight you will need to make a macro with the following text make sure the line ends with a line break `|`

**You will need an 8 man party in the same instance for the test to work. Don't have a space between these in your macro**

````
/e Titan|2B6C|Rock Throw|88888888|<1>|
/e Titan|2B6C|Rock Throw|88888888|<4>|
/e Titan|2B6C|Rock Throw|88888888|<6>|
````

**Editing**
If you wish to edit the priority list you will need to go into each of the triggers 
Job1Priority-Job3Priority and change the numbers assigned to them there

RPR: 01
  
MNK: 02

DRG: 03
 
NIN: 04 
 
SAM: 05 
 
PLD: 06 
 
WAR: 07 
 
DRK: 08 
 
GNB: 09  

BRD: 10 
 
MCH: 11 
 
DNC: 12 
 
BLM: 13 
 
SMN: 14 
 
RDM: 15 
 
WHM: 16 
 
SCH: 17 
 
AST: 18

SGE: 19
