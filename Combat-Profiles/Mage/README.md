#**1-60 Mage - Frost & Fire**  
The frost version is in alpha.

###**ROTATIONS:**
**CONSUMABLE:**  
- Drinks health potions when low
- Cast conjure and drink/eat
- Uses managem in combat if low on mana
- Few times use Evocation for mana regain

**BUFFS:**  
- Frost Armor / Ice Armor
- Intellect
- Dampen magic
- Ice barrier before combat and in combat
- Mana Shield if really low on health
- Combustion if not up and out of battle
- Ice Block if low on health  _(frost profile only)_

**PULLING:**  
- Pyroblast if available _(Fire profile only)_
- If not will pull with Frostbolt
- Or else will pull with Fireball _(fire profile only)_

**COMBAT:**  
- Fireball as allways _(fire profile only)_
- Scorch as final blow (sometimes?) _(fire profile only)_
- Scorch later on to stack buff a little. (edit chance or remove if not spec) _(fire profile only)_
- Use blastwave if over 2 enemies, if spec. _(fire profile only)_
- Frost nova, then walk back a little. on 1 or over 2 enemies.
- Sheep if over 1 enemy. will sheep off target with macro.
- Fireblast on cooldown _(less on Frost profile)_
- Wand if out of mana. (autoattack if no wand in the bars)
- Cone of Cold  _(frost profile only)_


###**HOW TO USE:**  
You will need to edit scorch if you think it is spamming and/or you dont have the talent, or if you place the sheep macro another place. Every line you will need to edit are marked and easy to find.

Make the sheep macro and put it in bar 2 slot 9. or edit in profile.  
This will target next target, cast sheep then go back to your last target.

**SHEEP MACRO:**  
/script TargetNearestEnemy();  
/cast Polymorph  
/script TargetLastTarget()  


I use this alternative sheep macro, the one you posted is not working for me at least.

/script TargetNearestEnemy();
/stopcasting
/cast Polymorph  
/emote polymorphs %t.       //this is just to add some roleplay to the macro xD
/script TargetLastTarget()
