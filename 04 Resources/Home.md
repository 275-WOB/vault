---
type: dashboard
tags:
  - dashboard
---
# 🏠 Study Dashboard

> [!tip] Start here
> **Capture:** [[00 Inbox/Task Inbox|Task Inbox]] · **Plan:** [[04 Resources/Weekly Review|Weekly Review]] · **Explore:** [[04 Resources/Knowledge Hub|Knowledge Hub]] · **Find:** use **Omnisearch** from the command palette.
>
> For a quick task, use **QuickAdd → Quick Task**. Add a due date like `📅 2026-11-06` to make it appear below.

## 🔴 Overdue
```tasks
not done
due before today
sort by due
limit 30
```

## 🟠 Due today
```tasks
not done
due on today
sort by priority
limit 30
```

## 🗓️ Next 7 days
```tasks
not done
due after today
due before in 7 days
sort by due
limit 35
```

## 🎓 Modules
<<<<<<< HEAD
|                                                                       |                                    |                                                                       |                                   |
| --------------------------------------------------------------------- | ---------------------------------- | --------------------------------------------------------------------- | --------------------------------- |
| 🧱 [[01 Modules/CMB128 Materials/Materials                            | CMB128 · Materials]]               | ⚙️ [[01 Modules/ELE123 Systems & Control/Systems & Control            | ELE123 · Systems & Control]]      |
| ⚡ [[01 Modules/ELE126 Electrical Fundamentals/Electrical Fundamentals | ELE126 · Electrical Fundamentals]] | 🌡️ [[01 Modules/MAC108 Statics & Thermofluids/Statics & Thermofluids | MAC108 · Statics & Thermofluids]] |
| ✈️ [[01 Modules/MAC111 Aerospace Design/Aerospace Design              | MAC111 · Aerospace Design]]        | 📐 [[01 Modules/MPS123 Maths/Maths                                    | MPS123 · Maths]]                  |
=======
| | |
| --- | --- |
| 🧱 [[01 Modules/CMB128 Materials/Materials|CMB128 · Materials]] | ⚙️ [[01 Modules/ELE123 Systems & Control/Systems & Control|ELE123 · Systems & Control]] |
| ⚡ [[01 Modules/ELE126 Electrical Fundamentals/Electrical Fundamentals|ELE126 · Electrical Fundamentals]] | 🌡️ [[01 Modules/MAC108 Statics & Thermofluids/Statics & Thermofluids|MAC108 · Statics & Thermofluids]] |
| ✈️ [[01 Modules/MAC111 Aerospace Design/Aerospace Design|MAC111 · Aerospace Design]] | 📐 [[01 Modules/MPS123 Maths/Maths|MPS123 · Maths]] |
>>>>>>> 0dbbdfeb10f0942ebb657c46e77fbdd5255c820d

## 📌 Assignments
[[02 Assignments/Assignments|Assignment board]] · [[05 Templates/Assignment Template|Assignment template]]

```dataview
TABLE WITHOUT ID file.link AS Assignment, module AS Module, due AS Deadline, status AS Status
FROM "02 Assignments"
WHERE type = "assignment" AND status != "submitted" AND status != "completed"
SORT due ASC
```

## 🎯 Unscheduled tasks
```tasks
not done
no due date
path does not include 05 Templates
limit 25
sort by path
```

## 🕒 Recently changed study notes
```dataview
TABLE WITHOUT ID file.link AS Note, file.mtime AS "Edited"
FROM "01 Modules" OR "03 Revision"
SORT file.mtime DESC
LIMIT 12
```

## 🧠 Learn & connect
- [[04 Resources/Knowledge Hub|Knowledge Hub]] — concepts, visual map, graph ideas and revision
- [[03 Revision/Revision Hub|Revision Hub]] — practice, recall and exam prep
- [[04 Resources/Weekly Review|Weekly Review]] — reset your week
- [[05 Templates/Concept Template|Concept Template]] — build searchable notes alongside handwriting

## 📆 Daily planning
<<<<<<< HEAD
Use **Open today's daily note** in the command palette or select a date in **Calendar**. For a time-blocked day, open **Day Planner**.
=======
Use **Open today's daily note** in the command palette or select a date in **Calendar**. For a time-blocked day, open **Day Planner**.
>>>>>>> 0dbbdfeb10f0942ebb657c46e77fbdd5255c820d
