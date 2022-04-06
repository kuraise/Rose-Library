# Rose Library
The Smartest UI Library

### Loadstring
```lua
local customName = loadstring(game:HttpGet('lib.com'))
```

### About
Rose Library is a ui library coded by [kura](https://github.com/kuraise) and has many features that no other UI Library has.

### Features
#### 1. Load Color Settings From Http
```lua
local lib = loadstring(game:HttpGet('https://site.com/script.lua'))
lib:LoadSettingsFromHTTP('https://site.com/item.json')
```

#### 2. Load Color Settings From Lua JSON Format
```lua
local lib = loadstring(game:HttpGet('https://site.com/script.lua'))
local tb = {
  -- settings soon
}
lib:LoadSettingsFromTable(tb)
```

#### 3. Themes
* Print Themes Names
```lua
local lib = loadstring(game:HttpGet('https://site.com/script.lua'))
lib:PrintThemesNames() -- prints the themes names
```

* Modern Theme
```lua
local lib = loadstring(game:HttpGet('https://site.com/script.lua'))
lib:LoadTheme('Modern') -- Adds UICorners and UIStroke is bigger
```

* CS:GO Theme
```lua
local lib = loadstring(game:HttpGet('https://site.com/script.lua'))
lib:LoadTheme('CS:GO') -- Adds UICorners and UIStroke is bigger
```

### Documentation
**To head to the [documentation](https://github.com/kuraise/Rose-Library/wiki) click where it says 'Documentation' and you will see how to use Rose Library!**
