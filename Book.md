---
cssclasses:
  - cards
  - cards-cover
  - table-max
---

```dataview
table without id
  embed(link(cover)),
  file.link as Title,
  "**Prep time:** " + prepTime as "Prep Time",
  "**Cook time:** " + cookTime as "Cook Time"
from #recipe and -"Extras"
```


