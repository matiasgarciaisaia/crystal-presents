---
transition: fade-in slide-out
---

## Sobrecarga de métodos

```playground
1 + 3
"hola" + " nerds"

def doble(a)
  a + a
end

doble(2)
doble("nom")
```

Note:
def doble(a : String)
  "#{a}, #{a}"
end
