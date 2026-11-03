---
type: hub
tags:
  - knowledge
---
# 🧠 Knowledge Hub
[[04 Resources/Home|← Dashboard]] · [[03 Revision/Revision Hub|Revision Hub]]

> [!abstract] Build a useful graph
> Obsidian's **Graph view** and **Local graph** are built in. A graph only becomes useful when you connect related concepts using `[[wiki links]]`. Handwriting images are preserved, but their contents aren't automatically indexed as text.

## 🗺️ Visual knowledge map
Open [[04 Resources/University Knowledge Map.canvas|University Knowledge Map]] for an editable Canvas overview of all six modules, the dashboard, and revision. Add concept cards and connect them as you study.

## 🧭 Explore by module
- [[01 Modules/CMB128 Materials/Materials|Materials]] · [[01 Modules/ELE123 Systems & Control/Systems & Control|Systems & Control]]
- [[01 Modules/ELE126 Electrical Fundamentals/Electrical Fundamentals|Electrical Fundamentals]] · [[01 Modules/MAC108 Statics & Thermofluids/Statics & Thermofluids|Statics & Thermofluids]]
- [[01 Modules/MAC111 Aerospace Design/Aerospace Design|Aerospace Design]] · [[01 Modules/MPS123 Maths/Maths|Maths]]

## 🔎 All concept notes
Create notes from [[05 Templates/Concept Template|Concept Template]] and tag them `#concept`.

```dataview
TABLE WITHOUT ID file.link AS Concept, module AS Module, file.mtime AS Updated
FROM #concept
SORT file.mtime DESC
```

## 🗃️ Revision questions and learning
- [[03 Revision/Revision Hub|Revision Hub]]
- **Spaced Repetition** is installed: add `#flashcards` and `Question::Answer` on a note to create review cards.
- For handwritten lectures, add a short text **Summary**, **Key concepts**, and **Related** links beneath the drawing.

## 🕸️ Graph view tips
1. Run **Graph view: Open graph view** from the command palette.
2. For a topic-sized graph, open its note and run **Open local graph**.
3. Make connections in your notes: `[[Differentiation]]`, `[[Drag]]`, `[[RLC Circuits]]`.
4. In graph filters, exclude `path:"05 Templates"` and `path:"04 Resources"` if you want a study-only graph. Adjust graph filters to your needs.

## 📚 Recently edited study material
```dataview
LIST
FROM "01 Modules" OR "03 Revision"
SORT file.mtime DESC
LIMIT 15
```
