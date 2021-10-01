# np-taskbarskill
NoPixel Task Bar Minigame

Usage Example :

```lua
RegisterCommand("minigame", function()
    local finished = exports["taskbarskill"]:taskBar(3700, 1)
    if finished == 100 then 
        print('done')
    end
end)
```

Preview : https://streamable.com/aprkgy
