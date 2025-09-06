---
cssclasses:
  - cards
  - cards-cover
  - table-max
---

```dataview
TABLE WITHOUT id
    embed(link(cover)),
    file.link AS Title,
	"**Prep time:** " + prepTime AS "Prep Time",
	"**Cook time:** " + cookTime AS "Cook Time"
FROM #recipe
WHERE contains(categories, "soup")
```