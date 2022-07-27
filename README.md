# DexV4
not mine, its the dex explorer v4, but with some improvements

# Loader
```lua
local file = "dexV4.lua" -- cache file name (workspace folder)
local url = "https://raw.githubusercontent.com/loglizzy/dexV4/main/source.lua"

local raw = isfile and isfile(file) and readfile(file)
raw = raw or game:HttpGet(url)

if isfile then
    task.spawn(writefile, file, game:HttpGet(url))
end

loadstring(raw)()

```
![image](https://user-images.githubusercontent.com/72479668/134221104-95ef1ac5-4b10-4d90-82d6-0b41cc151885.png)

## Features

* Faster Loading `thread loading`
* Almost Indetectable `uses protect_gui, getconnections, random instances, hided in roblox gui`
* Copy Path `copies the selected instance path`
* View Script `allows you to see the selected script source code`
* Copy Script Source `copies the selected script source`
* Require Module `shows the require(module) response`

* Cascate effect `script viewer windows are positioned in a cascate pattern`
* Resizable Windows `the windows are also all resizable`

![image](https://user-images.githubusercontent.com/72479668/134221588-5a6290fb-3b5d-42c1-95a9-26f7809e9029.png)

## Aditional changes (raging shit)
* Removed Properties window close button
* Removed Dragging from all the windows
* Didn't used the same shit syntax highlight as dex v3 (script viewer)
