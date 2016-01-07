## Empire Builder
MP modification for Battle for Wesnoth in which you can build your own empire. You are able to construct various buildings here (some of them can be even upgraded), they will produce some resources for you, allow you to train units or research  technologies/upgrades. To perform certain actions, you will need a higher noble title. To upgrade your title, you have to acquire certain score (by constructing/upgrading buildings and training units) and pay a certain amount of gold.

### Progress on features
* noble titles -  70%
* diplomacy    -   0%
* buildings    - 100%
* resources    -  75%
* research     -  95%

### TODO list
* add a few more upgrades for units
* allow trading between players
* code diplomacy
* complete factions (The Cult is missing healers, Drakes worker and mages)
* add some scenarios for this era

### Custom eras
All mechanics of this add-on are done via MP modification so it is possible (in theory) to play it with various eras. However, many features require special settings so they have to be defined by the era. The era has to define event set_faction which is called every time a side is initialized (be it player or computer controlled). In this event you have to define units which the side will use. You can also define images for some buildings and default name for leader. For real examples, see files in folder factions.
