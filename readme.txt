=== COMPANION CARRYWEIGHT AND LOOTING REWORK ===

Conflicts : none, fully QoL
Risks : very low risk but needs further testing to be sure

What this addon does :
* Companion loot command now works as intended, it can be used to make them pick or not pick stuff lying around
* Companions don't accept radioactive stuff you give to them unless it has suitable containers. Also if the artefact/attachment(like titanium frame) has a carryweight bonus it will be applied to them(there's a cap on how many based on the available artefact slots
* All NPCs don't carry around raw radioactive artefacts anymore, they'll be automatically put inside lead containers
* Companions will get carryweight bonus from the backpacks you give them, and in case of multiple backpacks they choose only the best one. Exo/nosorog companions don't get the backpack bonus(it can be changed in the script, but why?)
* Companions minimum carryweight will be your game difficulty setting, And they get extra carryweight based on their outfit/visual. And it works with(and highly recommended to use) DNPCAV 
* Story NPCs works slightly different, they accept backpacks/artefact/attachment like the others but their outfit/visual bonus is dependant on an ltx instead. It can changed via gamedata\configs\misc\story_npc_carryweights.ltx
Story NPCs have a default outfit bonus set at 30 kg, but you can override that value by adding a corresponding value to the NPC's section name (example within the ltx, 50kg given to hip)

Installation:
Simple, its a conflict free addon. So just merge with gamedata folder but its highly recommended to use Mod Organizer 2

known bugs and further plans:
none by far, but let me know if you find any. I'm worried if putting artefacts in containers could affect artefact fetch quests.
Also I was trying to rework companion weapon selection based on target and also adding a method to tell your companion which gun to use.
But there seems to be an engine bug so its put on halt
I am open to suggestions as I want to do more stuff on companions

Credits :
Ravenascendant (co-author)