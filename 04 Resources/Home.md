

---

## ![📊](https://fonts.gstatic.com/s/e/notoemoji/17.0/1f4ca/72.png) Overview

  

### ![🚨](https://fonts.gstatic.com/s/e/notoemoji/17.0/1f6a8/72.png) Overdue tasks

```tasks

not done

due before today

sort by due

```

  

### ![📅](https://fonts.gstatic.com/s/e/notoemoji/17.0/1f4c5/72.png) Due today

```tasks

not done

due on today

sort by priority

```

  

### ![⏳](https://fonts.gstatic.com/s/e/notoemoji/17.0/23f3/72.png) Coming up — next 7 days

```tasks

not done

due after today

due before in 7 days

sort by due

```

  

---

  

## ![📚](https://fonts.gstatic.com/s/e/notoemoji/17.0/1f4da/72.png) My Modules

  

- [[01 Modules/CMB128 Materials/Materials]]
- [[01 Modules/ELE123 Systems & Control/Systems & Control]]
- [[01 Modules/ELE126 Electrical Fundamentals/Electrical Fundamentals]]
- [[01 Modules/MAC108 Statics & Thermofluids/Statics & Thermofluids]]
- [[01 Modules/MAC111 Aerospace Design/Aerospace Design]]
- [[01 Modules/MPS123 Maths/Maths]] 


  

---

  

## ![📝](https://fonts.gstatic.com/s/e/notoemoji/17.0/1f4dd/72.png) Assignments

  

### Active assignments

  

```dataview

TABLE module AS Module, due AS Deadline, status AS Status

FROM "University/02 - Assignments"

WHERE type = "assignment"

AND status != "submitted"

SORT due ASC

```

  

---

  

## ![🎯](https://fonts.gstatic.com/s/e/notoemoji/17.0/1f3af/72.png) Task Inbox

  

- [00 - Task Inbo]]

  

### Tasks without deadlines

  

```tasks

not done

no due date

sort by path

```

  

---

  

## ![📖](https://fonts.gstatic.com/s/e/notoemoji/17.0/1f4d6/72.png) Recently edited notes

  

```dataview

TABLE file.mtime AS "Last edited", module AS Module

FROM "University/01 - Modules"

WHERE type = "lecture"

SORT file.mtime DESC

LIMIT 7

```

  

---

  

## ![🧠](https://fonts.gstatic.com/s/e/notoemoji/17.0/1f9e0/72.png) Knowledge Hub

  

- [[Concept Index]]

- [[University Brain.canvas]]

- [[Graph View]]

  

---

  

## ![📆](https://fonts.gstatic.com/s/e/notoemoji/17.0/1f4c6/72.png) Daily Planning

  

- [[]]

  

---

  

## ![📌](https://fonts.gstatic.com/s/e/notoemoji/17.0/1f4cc/72.png) Weekly Review

  

- [[Weekly Review]]