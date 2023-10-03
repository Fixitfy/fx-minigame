# FX-Minigame
Task Bar Minigame

Usage Example :

```lua
RegisterCommand("minigame", function()
    local finished = exports["fx-minigame"]:taskBar(3700, 1)
    if finished == 100 then 
        print('done')
    end
end)
```
