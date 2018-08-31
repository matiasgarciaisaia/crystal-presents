---
transition: fade-in slide-out
---

## Generics

```playground
class Caja(T)
  getter contenido
  def initialize(@contenido : T)
  end
end

caja = Caja(String).new("foo")
caja.contenido

otra_caja = Caja(Int32).new(42)
otra_caja.contenido
```

Note:
