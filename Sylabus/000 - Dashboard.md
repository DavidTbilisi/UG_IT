
## Filtered By Semester
```dataview
table semester, title, status
from "Sylabus" where semester = 1
and contains(status, "todo")

```


## Done
```dataview
table semester
from "Sylabus"
where contains(status, "done")
sort semester
```

## Doing
```dataview
table semester
from "Sylabus"
where contains(status, "doing")
sort semester
```


## Todo ( Mandatory )
```dataview
table title, semester
from "Sylabus" where required = true 
and !contains(status, "done") and !contains(status, "doing")
sort semester asc
```


## Todo (!Mandatory)
```dataview
table title, want
from "Sylabus" where required = false 
and !contains(status, "done") and !contains(status, "doing") and want > 0
sort want desc
```
