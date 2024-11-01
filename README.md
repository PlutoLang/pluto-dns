# pluto-dns

```lua
local dns = require "dns"

local r = new dns.httpresolver()
print(dumpvar(r:query("A", "testrr-1337.soup.do")))
--> {
-->     [1] = {
-->         ["name"] = string(19) "testrr-1337.soup.do",
-->         ["ip"] = string(7) "1.3.3.7",
-->         ["ttl"] = 300,
-->         ["type"] = string(1) "A",
-->     },
--> }

```
