# 📘 `Signal` for roblox.
This module is *specifically* made for custom events in roblox. You can use these in both modules and normal scripts.

To start off, you need to **require** the module. This can be done as following:
`local signal = require(PATH_TO_MODULE_HERE)`lua
Then, we need to initialise a signal. this can be done using `signal.new()`.
```luau
local Jumped = signal.new()
```
*Jumped* is now a **signal**
