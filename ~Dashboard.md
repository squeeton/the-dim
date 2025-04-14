# Players
```dataview
TABLE perception AS "Passive Perception"
FROM "Characters"
```

> [!column|3 no-title]
>
>>
>> # NPCs
>> ```dataview
>> LIST from "NPCs"
>> ```
>>  
>
>> # Locations
>> ```dataview
>> LIST from "Locations"
>> ```
>
>> # Groups
>> ```dataview
>> LIST from "Groups"
>> ```
>
>> # Things
>> ```dataview
>> LIST from "Things"
>> ```
>
>> # Creatures
>> ```dataview
>> LIST from "Creatures"
>> ```
>
>> # Sessions
>> ```dataview
>> LIST from "~Sessions"
>> LIMIT 10
>> SORT file.name DESC
>> ```
