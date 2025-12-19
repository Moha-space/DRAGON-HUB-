# key lib 
```
local KeySystem = loadstring(game:HttpGet("https://raw.githubusercontent.com/Moha-space/DRAGON-HUB-/refs/heads/main/Lib", true))()

```
```
KeySystem.CreateWindow({
    Name = " GUGU GAGA ",
    Size = UDim2.new(0, 500, 0, 360),
    Resizable = false,

    Logo = 1234567890,  -- Your logo asset ID

    Theme = {
        Accent = Color3.fromRGB(138, 43, 226),  -- Purple
        Gradient = {Color3.fromRGB(80, 0, 120), Color3.fromRGB(15, 0, 40)}
    },
```
    ToggleButton = {
        Enabled = true,
        AssetId = 987654321,  -- Custom open button image
    },

    KeyUrl = " LINK TO YOUR KEY ",
    DiscordWebhook = "https://discord.com/api/webhooks/...",

    LoadScript = function()
        loadstring(game:HttpGet("https://your script "))()
        print("Script loaded successfully!")
    end
})
```
