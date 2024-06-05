# The_Delta_Timeline
## [[Souls]]
```dataview
TABLE 
	file.etags AS "Tags" 
FROM 
	[[Souls]]
WHERE
	file.name != "README"
```
## [[Races]]
```dataview
TABLE 
	file.etags AS "Tags" 
FROM 
	[[Races]]
WHERE 
	file.name != "README"
```
## [[Locations]]
```dataview
TABLE 
	file.etags AS "Tags" 
FROM 
	[[Locations]]
WHERE 
	file.name != "README"
```
## [[Characters]]
```dataview
TABLE
	file.etags AS "Tags" 
FROM
	[[Characters]]
WHERE 
	file.name != "README"
```

## Orphaned
```dataview
LIST 
FROM 
	[[]] and !outgoing([[]]) 
```
