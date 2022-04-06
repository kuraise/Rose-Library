# Rose Library
The Smartest UI Library

### Sections
* [Loadstring](#Loadstring)
* [About](#About)
* [Features](#Features)
* [Documentation](#Documentation)

### Loadstring
```lua
local customName = loadstring(game:HttpGet('https://raw.githubusercontent.com/kuraise/Rose-Library/main/Source/Source.lua'))
```

### About
Rose Library is a UI library coded by [kura](https://github.com/kuraise) and has many features that no other UI Library has.

### Features
#### 1. Load Color Settings From Http
```lua
local lib = loadstring(game:HttpGet('https://raw.githubusercontent.com/kuraise/Rose-Library/main/Source/Source.lua'))
lib:LoadSettingsFromHTTP('https://site.com/item.json') -- your own github page or site or whatever.
```

#### 2. Load Color Settings From Lua JSON Format
```lua
local lib = loadstring(game:HttpGet('https://raw.githubusercontent.com/kuraise/Rose-Library/main/Source/Source.lua'))
local tb = {
  -- settings soon
}
lib:LoadSettingsFromTable(tb)
```

#### 3. Themes
* Print Themes Names
```lua
local lib = loadstring(game:HttpGet('https://raw.githubusercontent.com/kuraise/Rose-Library/main/Source/Source.lua'))
lib:PrintThemesNames() -- prints the themes names
```

* Modern Theme
```lua
local lib = loadstring(game:HttpGet('https://raw.githubusercontent.com/kuraise/Rose-Library/main/Source/Source.lua'))
lib:LoadTheme('Modern') -- Adds UICorners and UIStroke is bigger
```

* CS:GO Theme
```lua
local lib = loadstring(game:HttpGet('https://raw.githubusercontent.com/kuraise/Rose-Library/main/Source/Source.lua'))
lib:LoadTheme('CS:GO') -- Adds UICorners and UIStroke is bigger
```

### Documentation
**To head to the [documentation](https://github.com/kuraise/Rose-Library/wiki) click where it says 'Documentation' and you will see how to use Rose Library!**
