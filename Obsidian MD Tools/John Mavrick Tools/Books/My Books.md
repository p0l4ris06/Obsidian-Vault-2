 # My Books
## Progress
### Not Started 🟥
```dataview
table started, finished, rating
from #i/books AND #📥/🟥
sort finished desc
```
### Reading 🟧 
```dataview
table started, finished, rating
from #i/books AND #📥/🟧 
sort finished desc
```
### Note Organization 🟨
```dataview
table started, finished, rating
from #i/books AND #📥/🟨 
sort finished desc
```
### Finished 🟩 
```dataview
table started, finished, rating
from #i/books AND #📥/🟩 
sort finished desc
```
## All Books
```dataview
table started, finished, rating
from #i/books and !templates
sort finished desc
```
### Sorted By Rating
```dataview
table started, finished, rating
from #i/books and !"templates"
sort rating desc, finished desc
```
