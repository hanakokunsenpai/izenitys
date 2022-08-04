local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Deviisonwho?", "Ocean")
local Tab = Window:NewTab("The Mimic")
local Section = Tab:NewSection("KTollT")

Section:NewButton("KTollT", "The Mimic", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/KTollT/KTollT/main/README.md'))()
end)

Section:NewButton("KTollT Arceus X", "The Mimic", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/KTollT/NewGUI/main/README.md'))()
end)

Section:NewButton("Limited", "The Mimic", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/KTollT/Limited/main/README.md'))()
end)

Section:NewButton("Limited Two", "The Mimic", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/KTollT/LimitedTwo/main/README.md'))()
end)

Section:NewButton("Lantern", "The Mimic", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/KTollT/Lantern/main/README.md'))()
end)

local Section = Tab:NewSection("POOM HUB")

Section:NewButton("April Fools", "The Mimic", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/poisklmpoikslms901i234/ScriptAutoFarmMimicPoomHubLimited/main/.Lua"))()
end)

Section:NewButton("The Mimic Book II", "The Mimic", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/poisklmpoikslms901i234/ScriptTheMimicPoomHubBookIIFirst/main/.Lua"))()
end)

Section:NewButton("Halloween Trials", "The Mimic", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/poisklmpoikslms901i234/POOMHUBHalloweenScript/main/.Lua"))()
end)

Section:NewButton("Revamp I", "The Mimic", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/poisklmpoikslms901i234/TheMimicBook1RevampScript/main/.Lua"))()
end)

local Section = Tab:NewSection("XVAS")

Section:NewButton("Book I", "The Mimic", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/XITHHUB/SCRIPT/main/README.md"))()
end)

Section:NewButton("Book II", "The Mimic", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/XITHHUB/TheMimic/main/README.md"))()
end)

Section:NewButton("Jigoku", "The Mimic", function()
    function Tp(X, Y, Z)
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(X, Y, Z)
end
if game.PlaceId == 7618863566 then
    Tp(604.8139038085938, 11.90846061706543, 1079.7760009765625)
    wait(7)
    Tp(637.9722900390625, 11.74887752532959, 910.3511962890625)
    for i, v in pairs(game:GetService("Workspace"):GetDescendants()) do
        if v.ClassName == "ProximityPrompt" and v.Parent.Name == "Orb" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame * CFrame.new(0, -5, 0)
            wait(.2)
            fireproximityprompt(v, 1)
        end
    end
else
    for i, v in pairs(Game.Players:GetChildren()) do
        if v.Name ~= "owner.Name" then
            Game:GetService("TeleportService"):Teleport(7618863566, v.Character)
        end
    end
end

end)

local Section = Tab:NewSection("Noob Hub")

Section:NewButton("The Mimic", "The Mimic", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/koio08199za/THEMIMIC/main/NOOBHUB.Lua"))()
end)

local Tab = Window:NewTab("Yokai")
local Section = Tab:NewSection("Coming Soon...")

local Tab = Window:NewTab("Creepypasta")
local Section = Tab:NewSection("Herererererererere")
Section:NewButton("Xester", "The Mimic", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/1p9gSWK4'))()
end)

Section:NewButton("Vereus", "The Mimic", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/1p9gSWK4'))()
end)

Section:NewButton("Master Of Elements", "The Mimic", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/jiPHd64z'))()
end)

Section:NewButton("Shrike The Dice God", "The Mimic", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/L9s88W5u'))()
end)

Section:NewButton("Executioner Brutallus", "The Mimic", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/1p9gSWK4'))()
end)


local Tab = Window:NewTab("Others")
local Section = Tab:NewSection("Others")

Section:NewButton("Infinite Yield", "FE Admin Commands", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

Section:NewButton("Fullbright", "Makes The Map Brighter", function()
    local Light = game:GetService("Lighting")

function dofullbright()
Light.Ambient = Color3.new(1, 1, 1)
Light.ColorShift_Bottom = Color3.new(1, 1, 1)
Light.ColorShift_Top = Color3.new(1, 1, 1)
end

dofullbright()

Light.LightingChanged:Connect(dofullbright)
end)

Section:NewKeybind("Toggle UI", "KeybindInfo", Enum.KeyCode.F, function()
	Library:ToggleUI()
end)


local Tab = Window:NewTab("Credits")
local Section = Tab:NewSection("Made By amane, and the rightful owners!")
