## Roblox Service Doc(s)

### CoreGui

- [ ] **Not Creatable**: You can't create an instance of this class with the **Instance.new** constructor.
- [ ] **Service**: This class is a top-level singleton. Retrive an instance of this class with the **GetService** function.
- [ ] **Not Replicated**: Roblox does not replicate this member across its server-client boundary.


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
[SelectionImageObject](https://create.roblox.com/docs/reference/engine/classes/CoreGui#SelectionImageObject) : GuiObject

- [ ] **Read Parallel**: This property is read-only and is safe to read in unsynchronized threads. Attempting to write to it causes an error.
- [ ] **Roblox Script Security**: This member is accessible only in CoreScripts.

[Version](https://create.roblox.com/docs/reference/engine/classes/CoreGui#Version) : number

- [ ] **Read Only**: This member is read only. Attempting to write to this member causes an error.
- [ ] **Not Replicated**: Roblox does not replicate this member across its server-client boundary.
- [ ] **Read Parallel**: This property is read-only and is safe to read in unsynchronized threads. Attempting to write to it causes an error.

The current version of the CoreGui.
Everytime the CoreGui is majorly
changed, this number is increased.

> #### Methods
[GetGuiObjectsAtPosition](https://create.roblox.com/docs/reference/engine/classes/BasePlayerGui#GetGuiObjectsAtPosition) (x : number, y : number) : Objects

Returns a list of all [`GuiObject`](https://create.roblox.com/docs/reference/engine/classes/GuiObject) instances occupying the given point on the screen.

[SetUserGuiRendering] (enabled : bool, guiAdornee : Instance, faceId : NormalId, horizntalCurvature : float) : null
- [ ] **Roblox Script Security**: This member is accessible only in CoreScripts.

[TakeScreenshot] : null
- [ ] **Roblox Script Security**: This member is accessible only in CoreScripts.

[ToggleRecording] : null
- [ ] **Roblox Script Security**: This member is accessible only in CoreScripts.

> #### Events

[UserGuiRenderingChanged: Event] : (enabled : bool, guiAdornee : Instance, faceId : NormalId, horizntalCurvature : float)
- [ ] **Roblox Script Security**: This member is accessible only in CoreScripts.


### CorePackages

- [ ] **Not Creatable**: You can't create an instance of this class with the **Instance.new** constructor.
- [ ] **Service**: This class is a top-level singleton. Retrive an instance of this class with the **GetService** function.
- [ ] **Not Replicated**: Roblox does not replicate this member across its server-client boundary.


### TextChatService

- [ ] **Not Creatable**: You can't create an instance of this class with the **Instance.new** constructor.
- [ ] **Service**: This class is a top-level singleton. Retrive an instance of this class with the **GetService** function.

A service handling in-experience text
chat, including managing channels,
decorating messages, filtering text,
creating commands, and develeoping
custom chats interfaces.

#### Summary
> #### Properties

[ChatTranslationEnabled](https://create.roblox.com/docs/reference/engine/classes/TextChatService#ChatTranslationEnabled) : bool

- [ ] **Not Replicated**: Roblox does not replicate this member across its server-client boundary.
- [ ] **Read Parallel**: This property is read-only and is safe to read in unsynchronized threads. Attempting to write to it causes an error.
- [ ] **Roblox Script Security**: This member is accessible only in CoreScripts.

[ChatVersion](https://create.roblox.com/docs/reference/engine/classes/TextChatService#ChatVersion) : Enum.ChatVersion

- [ ] **Read Parallel**: This property is read-only and is safe to read in unsynchronized threads. Attempting to write to it causes an error.
- [ ] **Not Accessible Security**: Attempting to access this member in scripts causes an error. You might be able to access this member from Roblox Studio's property window.

Determines whether to fully enable [`TextChatService`](https://create.roblox.com/docs/reference/engine/classes/TextChatService) or revert to the legacy chat system.

[CreateDefaultCommands](https://create.roblox.com/docs/reference/engine/classes/TextChatService#CreateDefaultCommands) : bool

- [ ] **Read Parallel**: This property is read-only and is safe to read in unsynchronized threads. Attempting to write to it causes an error.
- [ ] **Plugin Security**: This member is accessible only through the command bar and plugins only. Attempting to access this member from scripts causes an error.

Determines whether [`TextChatService`](https://create.roblox.com/docs/reference/engine/classes/TextChatService) should create default [`TextChatCommands`](https://create.roblox.com/docs/reference/engine/classes/TextChatCommand).


[CreateDefaultTextChannels](https://create.roblox.com/docs/reference/engine/classes/TextChatService#CreateDefaultTextChannels) : bool

- [ ] **Read Parallel**: This property is read-only and is safe to read in unsynchronized threads. Attempting to write to it causes an error.
- [ ] **Plugin Security**: This member is accessible only through the command bar and plugins only. Attempting to access this member from scripts causes an error.

Determines whether [`TextChatService`](https://create.roblox.com/docs/reference/engine/classes/TextChatService) should create default [`TextChatChannels`](https://create.roblox.com/docs/reference/engine/classes/TextChatChannel).

> #### Methods

[DisplayBubble](https://create.roblox.com/docs/reference/engine/classes/TextChatService#DisplayBubble) (partOrCharacter : Instance, message : string) : null

Displays a chat bubble above the provided
part or player character.

<!-- Continue soon -->
