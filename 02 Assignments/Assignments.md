---
type: assignment-board
---
# 📋 Assignments
[[04 Resources/Home|← Dashboard]]

Create a note in `02 Assignments/` using [[05 Templates/Assignment Template|Assignment Template]]. Add the real deadline in the note's `due` property and as a Tasks checkbox (`📅 YYYY-MM-DD`) if you want it in both views.

## Open assignments
```dataview
TABLE WITHOUT ID file.link AS Assignment, module AS Module, due AS Due, status AS Status
FROM "02 Assignments"
WHERE type = "assignment" AND status != "submitted" AND status != "completed"
SORT due ASC
```

## Assignment tasks
```tasks
not done
path includes 02 Assignments
sort by due
```
