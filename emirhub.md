
local Material = loadstring(game:HttpGet("https://raw.githubusercontent.com/Kinlei/MaterialLua/master/Module.lua"))()

local UI = Material.Load({
     Title = "Emir Hub (Baska Update Yok(Emir HUB V2 Geciniz Lutfen)",
     Style = 24,
     SizeX = 500,
     SizeY = 200,
     Theme = "Dark"
})

local Page = UI.New({
    Title = "Welcome To Emir Hub! (Lütfen Emir HUBV2 Geciniz",


})

Page.Button({
    Text = "Prison Life",
    Callback = function()
        





loadstring(game:HttpGet("https://raw.githubusercontent.com/Denverrz/scripts/master/PRISONWARE_v1.3.txt"))();














    end
})
Page.Button({
    Text = "GrubHub (Are You Genius, Infectious Smile, Mow My Lawn 2, Bee Swarm, Prison Life)",
    Callback = function()
        





loadstring(game:HttpGet("https://raw.githubusercontent.com/inceldom/grubhub/main/loader",true))();














    end
})
Page.Button({
    Text = "KAT (Inf Ammo)",
    Callback = function()
        





loadstring(game:HttpGet("https://raw.githubusercontent.com/emirtube11/KAT/main/README.md",true))();














    end
})
Page.Button({
    Text = "Admin Script",
    Callback = function()
        





loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source",true))();














    end
})
Page.Button({
    Text = "Squid Game",
    Callback = function()
        





loadstring(game:HttpGet("https://raw.githubusercontent.com/NocturneMoDz/Squid-Game/main/SCRIPT"))();














    end
})
