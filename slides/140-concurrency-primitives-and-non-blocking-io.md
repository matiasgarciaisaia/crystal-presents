## Concurrencia

```playground
require "http/client"
channel = Channel(Int32).new
spawn do
  channel.send(HTTP::Client.get(
    "https://nerdear.la/").body.size)
end
spawn do
  channel.send(HTTP::Client.get(
    "https://crystal-lang.org/").body.size)
end
2.times do
  puts channel.receive
end
```

Note:
TBD: unable to puts channel.receive due to bug in output playground (?)
