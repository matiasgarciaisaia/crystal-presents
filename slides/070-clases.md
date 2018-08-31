---
transition: fade-in slide-out
---

## Clases

```playground
class Saludador
  @nombre : String

  def initialize(nombre)
    @nombre = nombre
  end

  def saludar
    puts "¡Hola #{@nombre}!"
  end
end

Saludador.new("nerdos").saludar
```

Note:
