---
transition: fade-in slide-out
---

## Módulos

```playground
module Saludador
  def saludar
    puts "¡Hola #{saludado}!"
  end
end

class Copado
  include Saludador
end

Copado.new.saludar
```

Note:
  def saludado
    "a tod@s"
  end
