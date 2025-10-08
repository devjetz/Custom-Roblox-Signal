# 📘 `Signal` for roblox.
This module is *specifically* made for custom events in roblox. You can use these in both modules and normal scripts. Best part? You can use this freely without needing to give credits at all. I do appreciate it though, but claiming you made it is **not** allowed.

To start off, you need to **require** the module. This can be done as following:
`local signal = require(PATH_TO_MODULE_HERE)`
Then, we need to initialise a signal. this can be done using `signal.new()`.
```luau
local Jumped = signal.new()
```
*Jumped* is now a **signal**. To fire this signal, you will need to type `signal:Fire()`. This will trigger any script with `signal:Connect` in them.
