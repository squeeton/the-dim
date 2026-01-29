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
>> TABLE maptack AS "Map Tack"
>> FROM "Locations"
>> SORT maptack asc
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
>> SORT file.name DESC
>> LIMIT 10
>> ```
