#### Issue Tracker for the *Dreamstate Project.*

###### The current version of the issue tracker is only used for preliminary bug-mapping. This is to help the development team knowing what to look for and also estimate the required amount of time for specific parts of the development process.



#### What to report:
**Everything.** Keep perfectionism in mind when searching for bugs, all reports are appreciated whether it is minor cosmetic issues or even vague anomalies in the system. If you need some ideas, here is a comprehensive list of issues to be on the lookout for:

|Creatures & Behaviour|Spell Behaviour| Quests   | Scripts     | Script Behaviour| Core |
|------------------|-----------------|---------------|------------|-----------------|----------|
AI Behaviour      | Class Spells    | Conditions     | Boss       | Breakability    | Battleground
Conditions        | Conditions      | Exploitation   | Creature AI| Difficulty      | Freezes
Creature Stats    | Creature Spells | Faulty Behavior| Cosmetic   | Conditions      | Stability
Creature Gossip   | Exploitation    | Money/XP Reward| Game Event | Cosmetic        |
Exploitation      | Misc Spells     | Quest Linking  | Game Object| Exploitation    |
Weapon Equipment  | Proc Effects    | Scripts        | Quest      | Functionality   |
LoS               | Quest Spells    | Spelling Errors| Item       | Lacking Content |
Movement          | Scaling         | Requirements   | RP Event   | Timers          |
RP Event(s)       | Script Effects  |                | Spell      | 
Pathfinding       |                 |                | Dungeon
Placement         | 
Spells / Abilities| 

There are a couple of recurring mentions in the above table, most notably *conditions* and *exploitation*. 

**Conditions:** Actions that should only trigger or become available when certain conditions have been fullfilled, this is common with boss mechanics and spells. Was there actually a condition behind Onyxia's *"Deep Breath"* ability? :)

**Exploitation:** A vague and broad term, the definition we use for exploitation is simply something that can be used for something it is not intended to do. Common examples of exploitation can be: 
- Excessively loading the server by intentionally triggering an accidental loop-hole, such as creature spawns or game objects. 
- Gaining an unfair advantage by using a buff which is only supposed to be used under strictly limited circumstances.
- Tampering with an encounter by disrupting or preventing the original purpose of its mechanics(what is generally considered clever use of game mechanics is an exception).
 


#### How to report:

##### Precautionary measures before submitting a report:

- Ensure that the problem is server-side and not local. Your local *cache*/*WDB* folder stores cosmetic information such as most text assosciated with content in the game, that can be anything from items to creatures. The *WTF* folder stores configuration and interface settings. In rare cases one of the following folders can be the culprit. If you notice a pattern in client freezes or FPS drops it is likely to be server-side and not local.

- Confirm(if possible) that the problem is specific to how it worked during vanilla. There have been significant alterations done to the game content in later expansions. To confirm the issue is not a false negative we would highly encourage and appreciate if you could make prior research before submitting the issue in order to ensure you are not comparing it with how it is supposed to work post-vanilla.

- Check that there doesn't already exist any reports on the same issue, if it does then contribute to the previous report instead. Commenting on a old report will "bump" it, making it visible to the developers and other users again.

##### Submitting the report:

- Familiarize yourself with the labels and utilize them to their fullest potential, this makes it much more convenient for other users and developers to look through them.

- Write a descriptive yet concise explanation of the issue, limit to one bug per report, please try avoid being vague in the description, it is better to be overly detailed.

- If it's a complicated issue or only occurs under limited circumstances, please explain how developers and other testers can recreate this bug. 
