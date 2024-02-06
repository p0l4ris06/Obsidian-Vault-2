tags:
Index: 
## [[Yearly Reviews]]
```dataview
list
FROM #projects/yearly
WHERE file.name != "Project Template"
WHERE completed = null
SORT deadline desc
```
## Monthly Reviews
 > [[Monthly Reviews]]
```dataview
list
FROM #reviews/monthly
WHERE file.name != "Project Template"
WHERE completed = null
SORT deadline desc
```
## Weekly Reviews
> [[Weekly Reviews]]
```dataview
list
FROM #reviews/weekly
WHERE file.name != "Project Template"
WHERE completed = null
SORT deadline desc
```
## Dusty Projects
*These projects may have already bit the dust. I'm just keeping track of them here.*
```dataview
table completed
FROM #projects
WHERE file.name != "Project Template" AND completed != null
SORT completed desc
```
___
# Backlinks
```dataview
list from [[~ Projects]] AND !outgoing([[~ Projects]]) AND !#projects
```
___