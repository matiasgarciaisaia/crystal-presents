## Stream-oriented APIs

```playground
class Punto
  def initialize(@x : Int32, @y : Int32)
  end

  def to_s(io)
    io << "(" << @x << ", " << @y << ")"
  end
end

Punto.new(3, 5).to_s
```

Note:

We are not ruby compatible.
