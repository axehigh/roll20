### Character Information
Prints out player character information.  

```
/w gm &{template:npcaction}  {{name=*Character information*}} {{description=**@{target|character_name}** 
HP: @{target|HP} 
AC: @{target|AC} 
Inspiration: @{target|inspiration}
Alignment: @{target|alignment}
Speed: @{target|speed}
Size: @{target|size}
Passive perveption: @{target|passive_wisdom}

**Saving throws:**
Strength save: @{target|strength_save_bonus}
Dexterity save: @{target|dexterity_save_bonus}
Constitution save: @{target|constitution_save_bonus}
Intelligence save: @{target|intelligence_save_bonus}
Wisdom save: @{target|wisdom_save_bonus}
Charisma save: @{target|charisma_save_bonus}

**Ability scores:**
Strength:@{target|strength}
Dexterity:@{target|dexterity}
Constitution:@{target|constitution}
Intelligence:@{target|intelligence}
Wisdom:@{target|wisdom}
Charisma:@{target|charisma}

**Skills:**
Acrobatics:@{target|Acrobatics_bonus}
Animal handling:@{target|Animal_handling_bonus}
Arcana:@{target|Arcana_bonus}
Athletics:@{target|Athletics_bonus}
Deception:@{target|Deception_bonus}
History:@{target|History_bonus}
Insight:@{target|Insight_bonus}
Intimidation:@{target|Intimidation_bonus}
Investigation:@{target|Investigation_bonus}
Medicine:@{target|Medicine_bonus}
Nature:@{target|Nature_bonus}
Perception:@{target|Perception_bonus}
Performance:@{target|Performance_bonus}
Persuasion:@{target|Persuasion_bonus}
Religion:@{target|Religion_bonus}
Sleight of hand:@{target|Sleight_of_hand_bonus}
Stealth:@{target|Stealth_bonus}
Survival:@{target|Survival_bonus}}}
```