# RbxLua Scripts
I only update these when I want to. DBR scripts likely don't work anymore.

Loader:

```lua
local branch = "main" -- main = misc scripts, dbr = dead by roblox scripts.
local scriptname = "FTF" -- name of the script, EXCLUDE FILE TYPE.

loadstring(game:HttpGet('https://raw.githubusercontent.com/top4monkeys/luascripts/' .. branch .. '/' .. scriptname .. '.lua'))()
```
