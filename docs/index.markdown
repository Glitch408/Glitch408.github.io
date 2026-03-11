---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: "General Guide"
---

![Player handbook art](/dnd_player_handbook_cover_art.jpg)

[This website](/about/) is a general guide on how to create a DnD character with the 2024 ruleset.

_**Remember**: There are different ways to determine things like ability scores. This website only uses the ones I usually utilize._ 

The first step is to choose a [class](/classes/) and [species](/species/). This tutorial will only go over creating a level 1 charakter. 

### Ability score and modifier
After having decided on who you will be playing, we will roll some `ability scores`. For each of the 6 abilities, you should:
> Take four d6 and drop the lowest roll.  

You can calulate your resulting `ability modifier` of the ability score that you just got with this python code: 

```python
ability_score = int(input('Enter your ability score: '))
ability_modifier = (ability_score-10)//2
print(f'Your ability modifier is: {ability_modifier}')
```
Remember to keep your class in mind when distributing those scores. There is a reason you can't multiclass certain classes if their responding ability score would be under 13.

### Hit points
Next, we will deterine the `Hit points` of our charakter at level 1.

> This is your classes hitpoint die highest number plus your constitution ability modifier

### Armor class
Remember that, if you don't have proficiency with the `armor type`, you have `disadvantage` on any ability check, saving throw, or attack roll that involves Strength or Dexterity, and you can’t cast spells.

The armors `padded`, `scale mail`, `half plate`, `ring mail`, `chain mail`, `splint` and `plate` give you a disadvantage to stealth checks.

These armors are `light` and add your dexterity modifier:
> `no armor` is 10
>
> `Padded` and `leather` armor are 11 
>
> `Studded leather` armor is 12

These armors are `medium` and also add your dexteriry modifier, but this time with a upper limit of 2:
> `Hide` armor is 12
>
> `Chain shirt` armor is 13
>
> `Scale mail` and `breastplate` armor is 14
>
> `Half plate` armor is 15

These are `heavy` and dont add anything:

> `Ring mail` armor is 14 
>
> `Chain mail` armor is 16 strength score of 13 or higher
>
> `Splint` armor is 17 and requires a strength score of 15 or higher
>
> `Plate` armor is 18 and also requires a strenght score of 15 or higher

Giving your character a shield gives them a bonus to their `armor class` plus `2`. 

### Initiative 
> Initative is your dexterity modifier

### Passive perception
> Passive perception is 10 + your perception modifier

The `Speed`, `size`  and `equipment training & proficiencies` are determined by your species. 


