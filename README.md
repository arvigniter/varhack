# Description
NoPixel Based VAR hacking minigame

# Acknowledgment
I'm not entirely sure the origin of this code, but shoutout to [sharkiller](https://github.com/sharkiller/nopixel_minigame) for hosting the javascript files on their github. This is simply a repackaging of those files into a Fivem NUI resource.

# Usage
```lua
exports['varhack']:OpenHackingGame(function(success)
    if success then
        print("success")
	else
        print("failed")
	end
end, 2, 3)
```

The first argument in this example represents the number of blocks in the puzzle. The second argument in this example represents the number of seconds that the player will see the exposed numbers, before they are hidden and the puzzle begins. 

##### Qbus.xyz Discord:
[Discord](https://discord.gg/Gec9kBKwcB)

