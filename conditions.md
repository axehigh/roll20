### Conditions
Whisper a list of macros to be clicked in chat window. 

```
/w gm &{template:npcaction} {{name=**Condition**}} {{description=
[Blinded](!
#C_blinded)
[Charmed](!
#C_charmed)
[Deafened](!
#C_deafened)}}
```

Need to define "C_Charmed", fex:    
```
&{template:npcatk} {{name=**Charmed**}} {{description=A charmed creature cannot  attack the charmer or target the charmer with harmful a⁠bilities or magical Effects.
The charmer has advantage on any ability check to interact socially with the creature.}}
```