## Roblox Service Doc(s)

### CoreGui

- [ ] **Not Creatable** | You can't create an instance of this class with the **Instance.new** constructor.
- [ ] **Service** | This class is a top-level singleton. Retrive an instance of this class with the **GetService** function.
- [ ] **Not Replicated** | Roblox does not replicate this member across its server-client boundary.


The CoreGui is a service used to store
Guis created in-game by Roblox for the
core user interface found in every game
(such as the game menu, the playerlist, the backpack, etc.). It can also be used by
[`Plugins`](https://create.roblox.com/docs/reference/engine/classes/Plugin) in Roblox Studio.


You can use [`StarterGui:SetCoreGuiEnabled()`](https://create.roblox.com/docs/reference/engine/classes/StarterGui#SetCoreGuiEnabled) and 
[`StarterGui:GetCoreGuiEnabled()`](https://create.roblox.com/docs/reference/engine/classes/StarterGui#GetCoreGuiEnabled)
methods in a [`LocalScript`](https://create.roblox.com/docs/reference/engine/classes/LocalScript) to enable
and disable most elements of the
CoreGui. You can also use
[`PlayerGui:SetTopbarTransparency()`](https://create.roblox.com/docs/reference/engine/classes/PlayerGui#SetTopbarTransparency)
to set the transparency of the top bar.

#### Summary
> #### Properties

[SelectionImageObject](https://create.roblox.com/docs/reference/engine/classes/CoreGui#SelectionImageObject)
