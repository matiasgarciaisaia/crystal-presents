---
transition: fade-in slide-out
---

## Colecciones

```playground
[1,2,3,4]
	.map { |x| x * 3 }
	.select { |x| x.odd? }
```

Note:
(1..4)

.select(&.odd?)
