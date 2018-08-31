---
transition: fade-in slide-out
---

## Herencia

```playground
abstract class Animal
  protected abstract def sonido

  def hablar
    puts sonido
  end
end

class Perro < Animal
  protected def sonido
    "¡Guau!"
  end
end

Perro.new.hablar
```

Note:
