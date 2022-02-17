local OwnerUsers = {
	["15yWhalixz2H"] = true;
}

local WhitelistUsers = {
    ["sbygywdt3"] = true,
	["LICON777"] = true,
	["666X66666666X666"] = true,
}

if OwnerUsers[game.Players.LocalPlayer.Name] or WhitelistUsers[game.Players.LocalPlayer.Name] then
-- Gui to Lua
-- Version: 3.2
-- Gui by Nihilize Script Edited by Whalix();#0265 Inspired in Nihilize

FavoriteColor = Color3.fromRGB(255, 255, 255)

function chatnotify(text)
game.StarterGui:SetCore("ChatMakeSystemMessage", {Text = text; Color = Color3.new(255,255,255); Font = Enum.Font.GothamBlack; FontSize = Enum.FontSize.Size42})
end

Message = {
"Warn:",
"• Gui has Made by Nihilize but Scripts has Edited by Whalix();#0265.",
"• Version Normal.",
"Notices:",
"• (Coming soon) H8X Admin with more 50 commands.",
"• (Coming soon) Settings You put keystrokes (pc only by: Vapin' Cat) and can Change Slots Guns, Color Name (Color Name Too Change Color Gui).",
"*Thanks For Using the Script*",
}

for i,v in pairs(Message) do
chatnotify(v)
end

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Title = Instance.new("TextLabel")
local AntiBring = Instance.new("TextButton")
local BeCriminal = Instance.new("TextButton")
local BeGuardF = Instance.new("TextButton")
local BeGuard = Instance.new("TextButton")
local BeInmate = Instance.new("TextButton")
local BeNeutral = Instance.new("TextButton")
local AntiCrash = Instance.new("TextButton")
local AntiFling = Instance.new("TextButton")
local AntiKickAfk = Instance.new("TextButton")
local AntiShields = Instance.new("TextButton")
local AntiSpamArrests = Instance.new("TextButton")
local AntiStatus = Instance.new("TextButton")
local Settings = Instance.new("TextButton")
local Soon = Instance.new("TextButton")
local Page1 = Instance.new("TextButton")
local AutoClothes = Instance.new("TextButton")
local AutoGuns = Instance.new("TextButton")
local AutoHealth = Instance.new("TextButton")
local AutoInfiniteAmmo = Instance.new("TextButton")
local AutoLock = Instance.new("TextButton")
local AutoRemoveKits = Instance.new("TextButton")
local AutoRespawn = Instance.new("TextButton")
local NoDoors = Instance.new("TextButton")
local BackPage1 = Instance.new("TextButton")
local Page2 = Instance.new("TextButton")
local Armory = Instance.new("TextButton")
local BackNexus = Instance.new("TextButton")
local Cafe = Instance.new("TextButton")
local Cell = Instance.new("TextButton")
local CrimBase = Instance.new("TextButton")
local Gate = Instance.new("TextButton")
local Nexus = Instance.new("TextButton")
local Roof = Instance.new("TextButton")
local Tower = Instance.new("TextButton")
local Yard = Instance.new("TextButton")
local Round = Instance.new("TextButton")
local BackPage2 = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = false
ScreenGui.Name = "H8X"

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderColor3 = FavoriteColor
Frame.BorderSizePixel = 3
Frame.Position = UDim2.new(0.8, 0, 0.1, 0)
Frame.Size = UDim2.new(0, 200, 0, 300)
Frame.BorderMode = "Inset"

Title.Name = "Title"
Title.Parent = Frame
Title.AnchorPoint = Vector2.new(0.5, 0.5)
Title.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Title.BackgroundTransparency = 1.000
Title.BorderColor3 = Color3.fromRGB(0, 0, 0)
Title.Position = UDim2.new(0.5, 0, 0.0700000003, 0)
Title.Size = UDim2.new(0, 180, 0, 50)
Title.Font = Enum.Font.SourceSans
Title.Text = "H8X"
Title.TextColor3 = FavoriteColor
Title.TextScaled = true
Title.TextSize = 24.000
Title.TextWrapped = true

AntiBring.Name = "AntiBring"
AntiBring.Parent = Frame
AntiBring.AnchorPoint = Vector2.new(0.5, 0.5)
AntiBring.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AntiBring.BorderColor3 = FavoriteColor
AntiBring.BorderSizePixel = 2
AntiBring.Position = UDim2.new(0.275000006, 0, 0.200000003, 0)
AntiBring.Size = UDim2.new(0, 73, 0, 32)
AntiBring.Font = Enum.Font.SourceSans
AntiBring.Text = "AntiBring: off"
AntiBring.TextColor3 = FavoriteColor
AntiBring.TextSize = 12.000
AntiBring.TextWrapped = true
AntiBring.BorderMode = "Inset"

BeCriminal.Name = "BeCriminal"
BeCriminal.Parent = Frame
BeCriminal.AnchorPoint = Vector2.new(0.5, 0.5)
BeCriminal.BackgroundColor3 = Color3.fromRGB(96, 0, 1)
BeCriminal.BorderColor3 = FavoriteColor
BeCriminal.BorderSizePixel = 2
BeCriminal.Position = UDim2.new(0.769999981, 0, 0.200000003, 0)
BeCriminal.Size = UDim2.new(0, 20, 0, 32)
BeCriminal.ZIndex = 2
BeCriminal.Font = Enum.Font.SourceSans
BeCriminal.Text = ""
BeCriminal.TextColor3 = FavoriteColor
BeCriminal.TextSize = 25.000
BeCriminal.TextWrapped = true
BeCriminal.BorderMode = "Inset"

BeGuard.Name = "BeGuard"
BeGuard.Parent = Frame
BeGuard.AnchorPoint = Vector2.new(0.5, 0.5)
BeGuard.BackgroundColor3 = Color3.fromRGB(9, 0, 77)
BeGuard.BorderColor3 = FavoriteColor
BeGuard.BorderSizePixel = 2
BeGuard.Position = UDim2.new(0.680000007, 0, 0.174999997, 0)
BeGuard.Size = UDim2.new(0, 20, 0, 17)
BeGuard.SizeConstraint = Enum.SizeConstraint.RelativeXX
BeGuard.ZIndex = 3
BeGuard.Font = Enum.Font.SourceSans
BeGuard.Text = ""
BeGuard.TextColor3 = FavoriteColor
BeGuard.TextSize = 25.000
BeGuard.TextWrapped = true
BeGuard.BorderMode = "Inset"

BeGuardF.Name = "BeGuardF"
BeGuardF.Parent = Frame
BeGuardF.AnchorPoint = Vector2.new(0.5, 0.5)
BeGuardF.BackgroundColor3 = Color3.fromRGB(9, 0, 77)
BeGuardF.BorderColor3 = FavoriteColor
BeGuardF.BorderSizePixel = 2
BeGuardF.Position = UDim2.new(0.680000007, 0, 0.224999994, 0)
BeGuardF.Size = UDim2.new(0, 20, 0, 17)
BeGuardF.SizeConstraint = Enum.SizeConstraint.RelativeXX
BeGuardF.ZIndex = 3
BeGuardF.Font = Enum.Font.SourceSans
BeGuardF.Text = ""
BeGuardF.TextColor3 = FavoriteColor
BeGuardF.TextSize = 25.000
BeGuardF.TextWrapped = true
BeGuardF.BorderMode = "Inset"

BeInmate.Name = "BeInmate"
BeInmate.Parent = Frame
BeInmate.AnchorPoint = Vector2.new(0.5, 0.5)
BeInmate.BackgroundColor3 = Color3.fromRGB(92, 40, 1)
BeInmate.BorderColor3 = FavoriteColor
BeInmate.BorderSizePixel = 2
BeInmate.Position = UDim2.new(0.589999974, 0, 0.200000003, 0)
BeInmate.Size = UDim2.new(0, 20, 0, 32)
BeInmate.ZIndex = 2
BeInmate.Font = Enum.Font.SourceSans
BeInmate.Text = ""
BeInmate.TextColor3 = FavoriteColor
BeInmate.TextSize = 25.000
BeInmate.TextWrapped = true
BeInmate.BorderMode = "Inset"

BeNeutral.Name = "BeNeutral"
BeNeutral.Parent = Frame
BeNeutral.AnchorPoint = Vector2.new(0.5, 0.5)
BeNeutral.BackgroundColor3 = Color3.fromRGB(140, 140, 140)
BeNeutral.BorderColor3 = FavoriteColor
BeNeutral.BorderSizePixel = 2
BeNeutral.Position = UDim2.new(0.860000014, 0, 0.200000003, 0)
BeNeutral.Size = UDim2.new(0, 20, 0, 32)
BeNeutral.ZIndex = 2
BeNeutral.Font = Enum.Font.SourceSans
BeNeutral.Text = ""
BeNeutral.TextColor3 = FavoriteColor
BeNeutral.TextSize = 25.000
BeNeutral.TextWrapped = true
BeNeutral.BorderMode = "Inset"

AntiCrash.Name = "AntiCrash"
AntiCrash.Parent = Frame
AntiCrash.AnchorPoint = Vector2.new(0.5, 0.5)
AntiCrash.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AntiCrash.BorderColor3 = FavoriteColor
AntiCrash.BorderSizePixel = 2
AntiCrash.Position = UDim2.new(0.275000006, 0, 0.340000004, 0)
AntiCrash.Size = UDim2.new(0, 73, 0, 32)
AntiCrash.Font = Enum.Font.SourceSans
AntiCrash.Text = "AntiCrash: off"
AntiCrash.TextColor3 = FavoriteColor
AntiCrash.TextSize = 12.000
AntiCrash.TextWrapped = true
AntiCrash.BorderMode = "Inset"

AntiFling.Name = "AntiFling"
AntiFling.Parent = Frame
AntiFling.AnchorPoint = Vector2.new(0.5, 0.5)
AntiFling.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AntiFling.BorderColor3 = FavoriteColor
AntiFling.BorderSizePixel = 2
AntiFling.Position = UDim2.new(0.725000024, 0, 0.340000004, 0)
AntiFling.Size = UDim2.new(0, 73, 0, 32)
AntiFling.Font = Enum.Font.SourceSans
AntiFling.Text = "AntiFling: off"
AntiFling.TextColor3 = FavoriteColor
AntiFling.TextSize = 12.000
AntiFling.TextWrapped = true
AntiFling.BorderMode = "Inset"

AntiKickAfk.Name = "AntiKickAfk"
AntiKickAfk.Parent = Frame
AntiKickAfk.AnchorPoint = Vector2.new(0.5, 0.5)
AntiKickAfk.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AntiKickAfk.BorderColor3 = FavoriteColor
AntiKickAfk.BorderSizePixel = 2
AntiKickAfk.Position = UDim2.new(0.275000006, 0, 0.479999989, 0)
AntiKickAfk.Size = UDim2.new(0, 73, 0, 32)
AntiKickAfk.Font = Enum.Font.SourceSans
AntiKickAfk.Text = "AntiKickAfk: off"
AntiKickAfk.TextColor3 = FavoriteColor
AntiKickAfk.TextSize = 12.000
AntiKickAfk.TextWrapped = true
AntiKickAfk.BorderMode = "Inset"

AntiShields.Name = "AntiShields"
AntiShields.Parent = Frame
AntiShields.AnchorPoint = Vector2.new(0.5, 0.5)
AntiShields.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AntiShields.BorderColor3 = FavoriteColor
AntiShields.BorderSizePixel = 2
AntiShields.Position = UDim2.new(0.725000024, 0, 0.479999989, 0)
AntiShields.Size = UDim2.new(0, 73, 0, 32)
AntiShields.Font = Enum.Font.SourceSans
AntiShields.Text = "AntiShields: off"
AntiShields.TextColor3 = FavoriteColor
AntiShields.TextSize = 12.000
AntiShields.TextWrapped = true
AntiShields.BorderMode = "Inset"

AntiSpamArrests.Name = "AntiSpamArrests"
AntiSpamArrests.Parent = Frame
AntiSpamArrests.AnchorPoint = Vector2.new(0.5, 0.5)
AntiSpamArrests.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AntiSpamArrests.BorderColor3 = FavoriteColor
AntiSpamArrests.BorderSizePixel = 2
AntiSpamArrests.Position = UDim2.new(0.275000006, 0, 0.620000005, 0)
AntiSpamArrests.Size = UDim2.new(0, 73, 0, 32)
AntiSpamArrests.Font = Enum.Font.SourceSans
AntiSpamArrests.Text = "AntiSpamArrests: off"
AntiSpamArrests.TextColor3 = FavoriteColor
AntiSpamArrests.TextSize = 12.000
AntiSpamArrests.TextWrapped = true
AntiSpamArrests.BorderMode = "Inset"

AntiStatus.Name = "AntiStatus"
AntiStatus.Parent = Frame
AntiStatus.AnchorPoint = Vector2.new(0.5, 0.5)
AntiStatus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AntiStatus.BorderColor3 = FavoriteColor
AntiStatus.BorderSizePixel = 2
AntiStatus.Position = UDim2.new(0.725000024, 0, 0.620000005, 0)
AntiStatus.Size = UDim2.new(0, 73, 0, 32)
AntiStatus.Font = Enum.Font.SourceSans
AntiStatus.Text = "AntiStatus: off"
AntiStatus.TextColor3 = FavoriteColor
AntiStatus.TextSize = 12.000
AntiStatus.TextWrapped = true
AntiStatus.BorderMode = "Inset"

Settings.Name = "Settings"
Settings.Parent = Frame
Settings.AnchorPoint = Vector2.new(0.5, 0.5)
Settings.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Settings.BorderColor3 = FavoriteColor
Settings.BorderSizePixel = 2
Settings.Position = UDim2.new(0.5, 0, 0.75999999, 0)
Settings.Size = UDim2.new(0, 156, 0, 32)
Settings.Font = Enum.Font.SourceSans
Settings.Text = "(Coming Soon)"
Settings.TextColor3 = FavoriteColor
Settings.TextSize = 12.000
Settings.TextWrapped = true
Settings.BorderMode = "Inset"

Soon.Name = "Soon"
Soon.Parent = Frame
Soon.Active = false
Soon.AnchorPoint = Vector2.new(0.5, 0.5)
Soon.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Soon.BorderColor3 = FavoriteColor
Soon.BorderSizePixel = 2
Soon.Position = UDim2.new(0.275000006, 0, 0.899999976, 0)
Soon.Size = UDim2.new(0, 73, 0, 32)
Soon.Font = Enum.Font.SourceSans
Soon.Text = "(Coming Soon)"
Soon.TextColor3 = FavoriteColor
Soon.TextSize = 12.000
Soon.TextWrapped = true
Soon.BorderMode = "Inset"

Page1.Name = "Page1"
Page1.Parent = Frame
Page1.Active = false
Page1.AnchorPoint = Vector2.new(0.5, 0.5)
Page1.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Page1.BorderColor3 = FavoriteColor
Page1.BorderSizePixel = 2
Page1.Position = UDim2.new(0.725000024, 0, 0.899999976, 0)
Page1.Size = UDim2.new(0, 73, 0, 32)
Page1.Font = Enum.Font.SourceSans
Page1.Text = "Next Page"
Page1.TextColor3 = FavoriteColor
Page1.TextSize = 12.000
Page1.TextWrapped = true
Page1.BorderMode = "Inset"
Page1.MouseButton1Click:Connect(function()
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiBring.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeCriminal.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeGuard.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeGuardF.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeInmate.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeNeutral.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiCrash.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiFling.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiKickAfk.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiShields.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiSpamArrests.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiStatus.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Settings.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Soon.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Page1.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoClothes.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoGuns.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoHealth.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoInfiniteAmmo.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoLock.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoRemoveKits.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoRespawn.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.NoDoors.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackPage1.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Page2.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Armory.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackNexus.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Cafe.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Cell.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.CrimBase.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Gate.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Nexus.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Roof.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Tower.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Yard.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Round.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackPage2.Visible = false
end)

AutoClothes.Name = "AutoClothes"
AutoClothes.Parent = Frame
AutoClothes.AnchorPoint = Vector2.new(0.5, 0.5)
AutoClothes.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AutoClothes.BorderColor3 = FavoriteColor
AutoClothes.BorderSizePixel = 2
AutoClothes.Position = UDim2.new(0.275000006, 0, 0.200000003, 0)
AutoClothes.Size = UDim2.new(0, 73, 0, 32)
AutoClothes.Font = Enum.Font.SourceSans
AutoClothes.Text = "AutoClothes: off"
AutoClothes.TextColor3 = FavoriteColor
AutoClothes.TextSize = 12.000
AutoClothes.TextWrapped = true
AutoClothes.Visible = false
AutoClothes.BorderMode = "Inset"

AutoGuns.Name = "AutoGuns"
AutoGuns.Parent = Frame
AutoGuns.AnchorPoint = Vector2.new(0.5, 0.5)
AutoGuns.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AutoGuns.BorderColor3 = FavoriteColor
AutoGuns.BorderSizePixel = 2
AutoGuns.Position = UDim2.new(0.725000024, 0, 0.200000003, 0)
AutoGuns.Size = UDim2.new(0, 73, 0, 32)
AutoGuns.Font = Enum.Font.SourceSans
AutoGuns.Text = "AutoGuns: off"
AutoGuns.TextColor3 = FavoriteColor
AutoGuns.TextSize = 12.000
AutoGuns.TextWrapped = true
AutoGuns.Visible = false
AutoGuns.BorderMode = "Inset"

AutoHealth.Name = "AutoHealth"
AutoHealth.Parent = Frame
AutoHealth.AnchorPoint = Vector2.new(0.5, 0.5)
AutoHealth.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AutoHealth.BorderColor3 = FavoriteColor
AutoHealth.BorderSizePixel = 2
AutoHealth.Position = UDim2.new(0.275000006, 0, 0.340000004, 0)
AutoHealth.Size = UDim2.new(0, 73, 0, 32)
AutoHealth.Font = Enum.Font.SourceSans
AutoHealth.Text = "AutoHealth: off"
AutoHealth.TextColor3 = FavoriteColor
AutoHealth.TextSize = 12.000
AutoHealth.TextWrapped = true
AutoHealth.Visible = false
AutoHealth.BorderMode = "Inset"

AutoInfiniteAmmo.Name = "AutoInfiniteAmmo"
AutoInfiniteAmmo.Parent = Frame
AutoInfiniteAmmo.AnchorPoint = Vector2.new(0.5, 0.5)
AutoInfiniteAmmo.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AutoInfiniteAmmo.BorderColor3 = FavoriteColor
AutoInfiniteAmmo.BorderSizePixel = 2
AutoInfiniteAmmo.Position = UDim2.new(0.725000024, 0, 0.340000004, 0)
AutoInfiniteAmmo.Size = UDim2.new(0, 73, 0, 32)
AutoInfiniteAmmo.Font = Enum.Font.SourceSans
AutoInfiniteAmmo.Text = "AutoInfiniteAmmo: off"
AutoInfiniteAmmo.TextColor3 = FavoriteColor
AutoInfiniteAmmo.TextSize = 12.000
AutoInfiniteAmmo.TextWrapped = true
AutoInfiniteAmmo.Visible = false
AutoInfiniteAmmo.BorderMode = "Inset"

AutoLock.Name = "AutoLock"
AutoLock.Parent = Frame
AutoLock.AnchorPoint = Vector2.new(0.5, 0.5)
AutoLock.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AutoLock.BorderColor3 = FavoriteColor
AutoLock.BorderSizePixel = 2
AutoLock.Position = UDim2.new(0.275000006, 0, 0.479999989, 0)
AutoLock.Size = UDim2.new(0, 73, 0, 32)
AutoLock.Font = Enum.Font.SourceSans
AutoLock.Text = "AutoLock: off"
AutoLock.TextColor3 = FavoriteColor
AutoLock.TextSize = 12.000
AutoLock.TextWrapped = true
AutoLock.Visible = false
AutoLock.BorderMode = "Inset"

AutoRemoveKits.Name = "AutoRemoveKits"
AutoRemoveKits.Parent = Frame
AutoRemoveKits.AnchorPoint = Vector2.new(0.5, 0.5)
AutoRemoveKits.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AutoRemoveKits.BorderColor3 = FavoriteColor
AutoRemoveKits.BorderSizePixel = 2
AutoRemoveKits.Position = UDim2.new(0.725000024, 0, 0.479999989, 0)
AutoRemoveKits.Size = UDim2.new(0, 73, 0, 32)
AutoRemoveKits.Font = Enum.Font.SourceSans
AutoRemoveKits.Text = "AutoRemoveKits: off"
AutoRemoveKits.TextColor3 = FavoriteColor
AutoRemoveKits.TextSize = 12.000
AutoRemoveKits.TextWrapped = true
AutoRemoveKits.Visible = false
AutoRemoveKits.BorderMode = "Inset"

AutoRespawn.Name = "AutoRespawn"
AutoRespawn.Parent = Frame
AutoRespawn.AnchorPoint = Vector2.new(0.5, 0.5)
AutoRespawn.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AutoRespawn.BorderColor3 = FavoriteColor
AutoRespawn.BorderSizePixel = 2
AutoRespawn.Position = UDim2.new(0.275000006, 0, 0.620000005, 0)
AutoRespawn.Size = UDim2.new(0, 73, 0, 32)
AutoRespawn.Font = Enum.Font.SourceSans
AutoRespawn.Text = "AutoRespawn: off"
AutoRespawn.TextColor3 = FavoriteColor
AutoRespawn.TextSize = 12.000
AutoRespawn.TextWrapped = true
AutoRespawn.Visible = false
AutoRespawn.BorderMode = "Inset"

NoDoors.Name = "NoDoors"
NoDoors.Parent = Frame
NoDoors.AnchorPoint = Vector2.new(0.5, 0.5)
NoDoors.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
NoDoors.BorderColor3 = FavoriteColor
NoDoors.BorderSizePixel = 2
NoDoors.Position = UDim2.new(0.725000024, 0, 0.620000005, 0)
NoDoors.Size = UDim2.new(0, 73, 0, 32)
NoDoors.Font = Enum.Font.SourceSans
NoDoors.Text = "NoDoors: off"
NoDoors.TextColor3 = FavoriteColor
NoDoors.TextSize = 12.000
NoDoors.TextWrapped = true
NoDoors.Visible = false
NoDoors.BorderMode = "Inset"

BackPage1.Name = "BackPage1"
BackPage1.Parent = Frame
BackPage1.AnchorPoint = Vector2.new(0.5, 0.5)
BackPage1.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
BackPage1.BorderColor3 = FavoriteColor
BackPage1.BorderSizePixel = 2
BackPage1.Position = UDim2.new(0.275000006, 0, 0.899999976, 0)
BackPage1.Size = UDim2.new(0, 73, 0, 32)
BackPage1.Font = Enum.Font.SourceSans
BackPage1.Text = "Back Page"
BackPage1.TextColor3 = FavoriteColor
BackPage1.TextSize = 12.000
BackPage1.TextWrapped = true
BackPage1.Visible = false
BackPage1.BorderMode = "Inset"
BackPage1.MouseButton1Click:Connect(function()
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiBring.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeCriminal.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeGuard.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeGuardF.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeInmate.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeNeutral.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiCrash.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiFling.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiKickAfk.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiShields.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiSpamArrests.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiStatus.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Settings.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Soon.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Page1.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoClothes.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoGuns.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoHealth.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoInfiniteAmmo.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoLock.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoRemoveKits.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoRespawn.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.NoDoors.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackPage1.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Page2.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Armory.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackNexus.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Cafe.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Cell.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.CrimBase.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Gate.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Nexus.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Roof.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Tower.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Yard.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Round.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackPage2.Visible = false
end)

Page2.Name = "Page2"
Page2.Parent = Frame
Page2.Active = false
Page2.AnchorPoint = Vector2.new(0.5, 0.5)
Page2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Page2.BorderColor3 = FavoriteColor
Page2.BorderSizePixel = 2
Page2.Position = UDim2.new(0.725000024, 0, 0.899999976, 0)
Page2.Size = UDim2.new(0, 73, 0, 32)
Page2.Font = Enum.Font.SourceSans
Page2.Text = "Next Page"
Page2.TextColor3 = FavoriteColor
Page2.TextSize = 12.000
Page2.TextWrapped = true
Page2.Visible = false
Page2.BorderMode = "Inset"
Page2.MouseButton1Click:Connect(function()
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiBring.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeCriminal.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeGuard.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeGuardF.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeInmate.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeNeutral.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiCrash.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiFling.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiKickAfk.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiShields.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiSpamArrests.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiStatus.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Settings.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Soon.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Page1.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoClothes.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoGuns.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoHealth.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoInfiniteAmmo.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoLock.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoRemoveKits.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoRespawn.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.NoDoors.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackPage1.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Page2.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Armory.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackNexus.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Cafe.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Cell.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.CrimBase.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Gate.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Nexus.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Roof.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Tower.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Yard.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Round.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackPage2.Visible = true
end)

Armory.Name = "Armory"
Armory.Parent = Frame
Armory.AnchorPoint = Vector2.new(0.5, 0.5)
Armory.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Armory.BorderColor3 = FavoriteColor
Armory.BorderSizePixel = 2
Armory.Position = UDim2.new(0.275000006, 0, 0.200000003, 0)
Armory.Size = UDim2.new(0, 73, 0, 32)
Armory.Font = Enum.Font.SourceSans
Armory.Text = "Armory"
Armory.TextColor3 = FavoriteColor
Armory.TextSize = 12.000
Armory.TextWrapped = true
Armory.Visible = false
Armory.BorderMode = "Inset"

BackNexus.Name = "BackNexus"
BackNexus.Parent = Frame
BackNexus.AnchorPoint = Vector2.new(0.5, 0.5)
BackNexus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
BackNexus.BorderColor3 = FavoriteColor
BackNexus.BorderSizePixel = 2
BackNexus.Position = UDim2.new(0.725000024, 0, 0.200000003, 0)
BackNexus.Size = UDim2.new(0, 73, 0, 32)
BackNexus.Font = Enum.Font.SourceSans
BackNexus.Text = "Back Nexus"
BackNexus.TextColor3 = FavoriteColor
BackNexus.TextSize = 12.000
BackNexus.TextWrapped = true
BackNexus.Visible = false
BackNexus.BorderMode = "Inset"

Cafe.Name = "Cafe"
Cafe.Parent = Frame
Cafe.AnchorPoint = Vector2.new(0.5, 0.5)
Cafe.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Cafe.BorderColor3 = FavoriteColor
Cafe.BorderSizePixel = 2
Cafe.Position = UDim2.new(0.275000006, 0, 0.340000004, 0)
Cafe.Size = UDim2.new(0, 73, 0, 32)
Cafe.Font = Enum.Font.SourceSans
Cafe.Text = "Cafetery"
Cafe.TextColor3 = FavoriteColor
Cafe.TextSize = 12.000
Cafe.TextWrapped = true
Cafe.Visible = false
Cafe.BorderMode = "Inset"

Cell.Name = "Cell"
Cell.Parent = Frame
Cell.AnchorPoint = Vector2.new(0.5, 0.5)
Cell.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Cell.BorderColor3 = FavoriteColor
Cell.BorderSizePixel = 2
Cell.Position = UDim2.new(0.725000024, 0, 0.340000004, 0)
Cell.Size = UDim2.new(0, 73, 0, 32)
Cell.Font = Enum.Font.SourceSans
Cell.Text = "Cell"
Cell.TextColor3 = FavoriteColor
Cell.TextSize = 12.000
Cell.TextWrapped = true
Cell.Visible = false
Cell.BorderMode = "Inset"

CrimBase.Name = "CrimBase"
CrimBase.Parent = Frame
CrimBase.AnchorPoint = Vector2.new(0.5, 0.5)
CrimBase.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
CrimBase.BorderColor3 = FavoriteColor
CrimBase.BorderSizePixel = 2
CrimBase.Position = UDim2.new(0.275000006, 0, 0.479999989, 0)
CrimBase.Size = UDim2.new(0, 73, 0, 32)
CrimBase.Font = Enum.Font.SourceSans
CrimBase.Text = "Criminal Base"
CrimBase.TextColor3 = FavoriteColor
CrimBase.TextSize = 12.000
CrimBase.TextWrapped = true
CrimBase.Visible = false
CrimBase.BorderMode = "Inset"

Gate.Name = "Gate"
Gate.Parent = Frame
Gate.AnchorPoint = Vector2.new(0.5, 0.5)
Gate.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Gate.BorderColor3 = FavoriteColor
Gate.BorderSizePixel = 2
Gate.Position = UDim2.new(0.725000024, 0, 0.479999989, 0)
Gate.Size = UDim2.new(0, 73, 0, 32)
Gate.Font = Enum.Font.SourceSans
Gate.Text = "Gate"
Gate.TextColor3 = FavoriteColor
Gate.TextSize = 12.000
Gate.TextWrapped = true
Gate.Visible = false
Gate.BorderMode = "Inset"

Nexus.Name = "Nexus"
Nexus.Parent = Frame
Nexus.AnchorPoint = Vector2.new(0.5, 0.5)
Nexus.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Nexus.BorderColor3 = FavoriteColor
Nexus.BorderSizePixel = 2
Nexus.Position = UDim2.new(0.275000006, 0, 0.620000005, 0)
Nexus.Size = UDim2.new(0, 73, 0, 32)
Nexus.Font = Enum.Font.SourceSans
Nexus.Text = "Nexus"
Nexus.TextColor3 = FavoriteColor
Nexus.TextSize = 12.000
Nexus.TextWrapped = true
Nexus.Visible = false
Nexus.BorderMode = "Inset"

Roof.Name = "Roof"
Roof.Parent = Frame
Roof.AnchorPoint = Vector2.new(0.5, 0.5)
Roof.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Roof.BorderColor3 = FavoriteColor
Roof.BorderSizePixel = 2
Roof.Position = UDim2.new(0.725000024, 0, 0.620000005, 0)
Roof.Size = UDim2.new(0, 73, 0, 32)
Roof.Font = Enum.Font.SourceSans
Roof.Text = "Roof"
Roof.TextColor3 = FavoriteColor
Roof.TextSize = 12.000
Roof.TextWrapped = true
Roof.Visible = false
Roof.BorderMode = "Inset"

Tower.Name = "Tower"
Tower.Parent = Frame
Tower.AnchorPoint = Vector2.new(0.5, 0.5)
Tower.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Tower.BorderColor3 = FavoriteColor
Tower.BorderSizePixel = 2
Tower.Position = UDim2.new(0.275000006, 0, 0.75999999, 0)
Tower.Size = UDim2.new(0, 73, 0, 32)
Tower.Font = Enum.Font.SourceSans
Tower.Text = "Tower"
Tower.TextColor3 = FavoriteColor
Tower.TextSize = 12.000
Tower.TextWrapped = true
Tower.Visible = false
Tower.BorderMode = "Inset"

Yard.Name = "Yard"
Yard.Parent = Frame
Yard.AnchorPoint = Vector2.new(0.5, 0.5)
Yard.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Yard.BorderColor3 = FavoriteColor
Yard.BorderSizePixel = 2
Yard.Position = UDim2.new(0.725000024, 0, 0.75999999, 0)
Yard.Size = UDim2.new(0, 73, 0, 32)
Yard.Font = Enum.Font.SourceSans
Yard.Text = "Yard"
Yard.TextColor3 = FavoriteColor
Yard.TextSize = 12.000
Yard.TextWrapped = true
Yard.Visible = false
Yard.BorderMode = "Inset"

BackPage2.Name = "BackPage2"
BackPage2.Parent = Frame
BackPage2.AnchorPoint = Vector2.new(0.5, 0.5)
BackPage2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
BackPage2.BorderColor3 = FavoriteColor
BackPage2.BorderSizePixel = 2
BackPage2.Position = UDim2.new(0.275000006, 0, 0.899999976, 0)
BackPage2.Size = UDim2.new(0, 73, 0, 32)
BackPage2.Font = Enum.Font.SourceSans
BackPage2.Text = "Back Page"
BackPage2.TextColor3 = FavoriteColor
BackPage2.TextSize = 12.000
BackPage2.TextWrapped = true
BackPage2.Visible = false
BackPage2.BorderMode = "Inset"
BackPage2.MouseButton1Click:Connect(function()
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiBring.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeCriminal.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeGuard.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeGuardF.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeInmate.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeNeutral.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiCrash.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiFling.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiKickAfk.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiShields.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiSpamArrests.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiStatus.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Settings.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Soon.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Page1.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoClothes.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoGuns.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoHealth.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoInfiniteAmmo.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoLock.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoRemoveKits.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoRespawn.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.NoDoors.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackPage1.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Page2.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Armory.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackNexus.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Cafe.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Cell.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.CrimBase.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Gate.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Nexus.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Roof.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Tower.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Yard.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Round.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackPage2.Visible = false
end)

Round.Name = "Round"
Round.Parent = Frame
Round.AnchorPoint = Vector2.new(0.5, 0.5)
Round.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Round.BorderColor3 = FavoriteColor
Round.BorderSizePixel = 2
Round.Position = UDim2.new(0.725000024, 0, 0.899999976, 0)
Round.Size = UDim2.new(0, 73, 0, 32)
Round.Font = Enum.Font.SourceSans
Round.Text = "1v1"
Round.TextColor3 = FavoriteColor
Round.TextSize = 12.000
Round.TextWrapped = true
Round.Visible = false
Round.BorderMode = "Inset"

local States_AntiBring = false
local States_AntiCrash = false
local States_AntiFling = false
local States_AntiKickAfk = false
local States_AntiShields = false
local States_AntiSpamArrests = false
local States_AntiStatus = false
local States_IsInSettings = false
local States_AutoClothes = false
local States_AutoGuns = false
local States_AutoHealth = false
local States_AutoInfiniteAmmo = false
local States_AutoLock = false
local States_AutoRemoveKits = false
local States_AutoRespawn = false
local States_NoDoors = false
local GamePass = game.MarketplaceService:UserOwnsGamePassAsync(tonumber((game.Players.LocalPlayer.CharacterAppearance):split('=')[#((game.Players.LocalPlayer.CharacterAppearance):split('='))]), 96651)

function Kill(Player)
pcall(function()
workspace.Remote.ItemHandler:InvokeServer(workspace.Prison_ITEMS.giver["Remington 870"].ITEMPICKUP)
local MyTeam = game.Players.LocalPlayer.TeamColor.Name
if Player.TeamColor.Name == game.Players.LocalPlayer.TeamColor.Name then
local savedcf = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame
local savedcamcf = workspace.CurrentCamera.CFrame
workspace.Remote.loadchar:InvokeServer(nil, BrickColor.random().Name)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = savedcf
workspace.CurrentCamera.CFrame = savedcamcf
workspace.Remote.ItemHandler:InvokeServer(workspace.Prison_ITEMS.giver["Remington 870"].ITEMPICKUP)
end

local Gun = game.Players.LocalPlayer.Character:FindFirstChild("Remington 870") or game.Players.LocalPlayer.Backpack:FindFirstChild("Remington 870")
for i,v in pairs(Player) do
local FireEvent = {
[1] = {
["RayObject"] = Ray.new(Vector3.new(), Vector3.new()), 
["Distance"] = 0, 
["Cframe"] = CFrame.new(), 
["Hit"] = workspace[v.Name].Head
}, [2] = {
["RayObject"] = Ray.new(Vector3.new(), Vector3.new()), 
["Distance"] = 0, 
["Cframe"] = CFrame.new(), 
["Hit"] = workspace[v.Name].Head
}, [3] = {
["RayObject"] = Ray.new(Vector3.new(), Vector3.new()), 
["Distance"] = 0, 
["Cframe"] = CFrame.new(), 
["Hit"] = workspace[v.Name].Head
}, [4] = {
["RayObject"] = Ray.new(Vector3.new(), Vector3.new()), 
["Distance"] = 0, 
["Cframe"] = CFrame.new(), 
["Hit"] = workspace[v.Name].Head
}, [5] = {
["RayObject"] = Ray.new(Vector3.new(), Vector3.new()), 
["Distance"] = 0, 
["Cframe"] = CFrame.new(), 
["Hit"] = workspace[v.Name].Head
}, [6] = {
["RayObject"] = Ray.new(Vector3.new(), Vector3.new()), 
["Distance"] = 0, 
["Cframe"] = CFrame.new(), 
["Hit"] = workspace[v.Name].Head
}, [7] = {
["RayObject"] = Ray.new(Vector3.new(), Vector3.new()), 
["Distance"] = 0, 
["Cframe"] = CFrame.new(), 
["Hit"] = workspace[v.Name].Head
}, [8] = {
["RayObject"] = Ray.new(Vector3.new(), Vector3.new()), 
["Distance"] = 0, 
["Cframe"] = CFrame.new(), 
["Hit"] = workspace[v.Name].Head
}
}
end
game:GetService("ReplicatedStorage").ShootEvent:FireServer(FireEvent, Gun)
end)
end

function GetCorrectRootPartCFrame()
local x, y, z = game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame:ToOrientation()
return CFrame.new(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame.X, game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame.Y, game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame.Z) * CFrame.fromOrientation(x, y, z)
end

function GetCorrectCameraCFrame()
local x, y, z = game:GetService("Workspace").CurrentCamera.CFrame:ToOrientation()
return CFrame.new(game:GetService("Workspace").CurrentCamera.CFrame.X, game:GetService("Workspace").CurrentCamera.CFrame.Y, game:GetService("Workspace").CurrentCamera.CFrame.Z) * CFrame.fromOrientation(x, y, z)
end

local HumanoidRootPartLastCFrame = GetCorrectRootPartCFrame()
local CurrentCameraLastCFrame = GetCorrectCameraCFrame()

function SaveCFrame()
CurrentCameraLastCFrame = GetCorrectCameraCFrame()
HumanoidRootPartLastCFrame = GetCorrectRootPartCFrame()
end

function LoadCFrame()
for i = 1, 2 do
wait()
if game.Players.LocalPlayer.Character.Humanoid.Sit then
game.Players.LocalPlayer.Character.Humanoid.Sit = false
end
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = HumanoidRootPartLastCFrame
game:GetService("Workspace").CurrentCamera.CFrame = CurrentCameraLastCFrame
end
end

function LoadCharacter(Color)
local Color = Color or nil
game:GetService("Workspace").Remote.loadchar:InvokeServer(nil, Color)
end

function FireTeam(Brickcolor)
game:GetService("Workspace").Remote.TeamEvent:FireServer(Brickcolor)
end

AntiBring.MouseButton1Click:Connect(function()
if States_AntiBring == false then
States_AntiBring = true
AntiBring.Text = "AntiBring: on"
elseif States_AntiBring == true then
States_AntiBring = false
AntiBring.Text = "AntiBring: off"
end
end)

BeCriminal.MouseButton1Down:connect(function()
SaveCFrame()
LoadCharacter(BrickColor.new("Really red").Name)
LoadCFrame()
end)

BeGuard.MouseButton1Down:connect(function()
FireTeam("Bright blue")
end)

BeGuardF.MouseButton1Down:connect(function()
SaveCFrame()
LoadCharacter(BrickColor.new("Bright blue").Name)
LoadCFrame()
end)

BeInmate.MouseButton1Down:connect(function()
FireTeam("Bright orange")
end)

BeNeutral.MouseButton1Down:connect(function()
FireTeam("Medium stone grey")
end)

AntiCrash.MouseButton1Click:Connect(function()
if States_AntiCrash == false then
States_AntiCrash = true
AntiCrash.Text = "AntiCrash: on"
elseif States_AntiCrash == true then
States_AntiCrash = false
AntiCrash.Text = "AntiCrash: off"
end
end)

AntiFling.MouseButton1Click:Connect(function()
if States_AntiFling == false then
States_AntiFling = true
AntiFling.Text = "AntiFling: on"
elseif States_AntiFling == true then
States_AntiFling = false
AntiFling.Text = "AntiFling: off"
end
end)

AntiKickAfk.MouseButton1Click:Connect(function()
if States_AntiKickAfk == false then
States_AntiKickAfk = true
AntiKickAfk.Text = "AntiKickAfk: on"
elseif States_AntiKickAfk == true then
States_AntiKickAfk = false
AntiKickAfk.Text = "AntiKickAfk: off"
end
end)

AntiShields.MouseButton1Click:Connect(function()
if States_AntiShields == false then
States_AntiShields = true
AntiShields.Text = "AntiShields: on"
elseif States_AntiShields == true then
States_AntiShields = false
AntiShields.Text = "AntiShields: off"
end
end)

AntiSpamArrests.MouseButton1Click:Connect(function()
if States_AntiSpamArrests == false then
States_AntiSpamArrests = true
AntiSpamArrests.Text = "AntiSpamArrests: on"
elseif States_AntiSpamArrests == true then
States_AntiSpamArrests = false
AntiSpamArrests.Text = "AntiSpamArrests: off"
end
end)

AntiStatus.MouseButton1Click:Connect(function()
if States_AntiStatus == false then
States_AntiStatus = true
AntiStatus.Text = "AntiStatus: on"
elseif States_AntiStatus == true then
States_AntiStatus = false
AntiStatus.Text = "AntiStatus: off"
end
end)

--[[
Settings.MouseButton1Click:Connect(function()
if States_IsInSettings == false then
States_IsInSettings = true
Settings.Text = "(Coming soon)"
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiBring.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeCriminal.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeGuard.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeGuardF.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeInmate.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeNeutral.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiCrash.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiFling.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiKickAfk.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiShields.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiSpamArrests.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiStatus.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Soon.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Page1.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoClothes.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoGuns.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoHealth.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoInfiniteAmmo.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoLock.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoRemoveKits.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoRespawn.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.NoDoors.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackPage1.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Page2.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Armory.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackNexus.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Cafe.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Cell.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.CrimBase.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Gate.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Nexus.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Roof.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Tower.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Yard.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Round.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackPage2.Visible = false
elseif States_IsInSettings == true then
States_IsInSettings = false
Settings.Text = "Settings"
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiBring.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeCriminal.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeGuard.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeGuardF.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeInmate.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BeNeutral.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiCrash.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiFling.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiKickAfk.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiShields.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiSpamArrests.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AntiStatus.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Soon.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Page1.Visible = true
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoClothes.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoGuns.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoHealth.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoInfiniteAmmo.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoLock.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoRemoveKits.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.AutoRespawn.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.NoDoors.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackPage1.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Page2.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Armory.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackNexus.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Cafe.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Cell.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.CrimBase.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Gate.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Nexus.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Roof.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Tower.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Yard.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.Round.Visible = false
game.Players.LocalPlayer:WaitForChild("PlayerGui").H8X.Frame.BackPage2.Visible = false
end
end)
]]--

AutoClothes.MouseButton1Click:Connect(function()
if States_AutoClothes == false then
States_AutoClothes = true
AutoClothes.Text = "AutoClothes: on"
elseif States_AutoClothes == true then
States_AutoClothes = false
AutoClothes.Text = "AutoClothes: off"
end
end)

AutoGuns.MouseButton1Click:Connect(function()
if States_AutoGuns == false then
States_AutoGuns = true
AutoGuns.Text = "AutoGuns: on"
elseif States_AutoGuns == true then
States_AutoGuns = false
AutoGuns.Text = "AutoGuns: off"
end
end)

AutoHealth.MouseButton1Click:Connect(function()
if States_AutoHealth == false then
States_AutoHealth = true
AutoHealth.Text = "AutoHealth: on"
elseif States_AutoHealth == true then
States_AutoHealth = false
AutoHealth.Text = "AutoHealth: off"
end
end)

AutoInfiniteAmmo.MouseButton1Click:Connect(function()
if States_AutoInfiniteAmmo == false then
States_AutoInfiniteAmmo = true
AutoInfiniteAmmo.Text = "AutoInfiniteAmmo: on"
elseif States_AutoInfiniteAmmo == true then
States_AutoInfiniteAmmo = false
AutoInfiniteAmmo.Text = "AutoInfiniteAmmo: off"
end
end)

AutoLock.MouseButton1Click:Connect(function()
if States_AutoLock == false then
States_AutoLock = true
AutoLock.Text = "AutoLock: on"
elseif States_AutoLock == true then
States_AutoLock = false
AutoLock.Text = "AutoLock: off"
end
end)

AutoRemoveKits.MouseButton1Click:Connect(function()
if States_AutoRemoveKits == false then
States_AutoRemoveKits = true
AutoRemoveKits.Text = "AutoRemoveKits: on"
elseif States_AutoRemoveKits == true then
States_AutoRemoveKits = false
AutoRemoveKits.Text = "AutoRemoveKits: off"
end
end)

AutoRespawn.MouseButton1Click:Connect(function()
if States_AutoRespawn == false then
States_AutoRespawn = true
AutoRespawn.Text = "AutoRespawn: on"
elseif States_AutoRespawn == true then
States_AutoRespawn = false
AutoRespawn.Text = "AutoRespawn: off"
end
end)

NoDoors.MouseButton1Click:Connect(function()
if States_NoDoors == false then
States_NoDoors = true
NoDoors.Text = "NoDoors: on"
workspace.Doors.Parent = game.Lighting
workspace.Prison_Cellblock.doors.Parent = game.Lighting
elseif States_NoDoors == true then
States_NoDoors = false
NoDoors.Text = "NoDoors: off"
game.Lighting.Doors.Parent = workspace
game.Lighting.doors.Parent = workspace.Prison_Cellblock
end
end)

Armory.MouseButton1Click:Connect(function()
if game.Players.LocalPlayer.Character.Humanoid.Sit then
game.Players.LocalPlayer.Character.Humanoid.Sit = false
end
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(792.8857421875, 102.78999328613, 2250.7065429688)
end)

BackNexus.MouseButton1Click:Connect(function()
if game.Players.LocalPlayer.Character.Humanoid.Sit then
game.Players.LocalPlayer.Character.Humanoid.Sit = false
end
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(978.74920654297, 99.990005493164, 2341.8315429688)
end)

Cafe.MouseButton1Click:Connect(function()
if game.Players.LocalPlayer.Character.Humanoid.Sit then
game.Players.LocalPlayer.Character.Humanoid.Sit = false
end
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(874.12316894531, 99.989959716797, 2251.3356933594)
end)

Cell.MouseButton1Click:Connect(function()
if game.Players.LocalPlayer.Character.Humanoid.Sit then
game.Players.LocalPlayer.Character.Humanoid.Sit = false
end
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(933.19299316406, 114.79006195068, 2500.8937988281)
end)

CrimBase.MouseButton1Click:Connect(function()
if game.Players.LocalPlayer.Character.Humanoid.Sit then
game.Players.LocalPlayer.Character.Humanoid.Sit = false
end
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-942.98992919922, 94.128784179688, 2056.1499023438)
end)

Gate.MouseButton1Click:Connect(function()
if game.Players.LocalPlayer.Character.Humanoid.Sit then
game.Players.LocalPlayer.Character.Humanoid.Sit = false
end
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(504.37423706055, 102.03991699219, 2242.4948730469)
end)

Nexus.MouseButton1Click:Connect(function()
if game.Players.LocalPlayer.Character.Humanoid.Sit then
game.Players.LocalPlayer.Character.Humanoid.Sit = false
end
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(872.7822265625, 99.990005493164, 2387.4567871094)
end)

Roof.MouseButton1Click:Connect(function()
if game.Players.LocalPlayer.Character.Humanoid.Sit then
game.Players.LocalPlayer.Character.Humanoid.Sit = false
end
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(924.82531738281, 138.46385192871, 2458.8420410156)
end)

Tower.MouseButton1Click:Connect(function()
if game.Players.LocalPlayer.Character.Humanoid.Sit then
game.Players.LocalPlayer.Character.Humanoid.Sit = false
end
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(822.69244384766, 130.03994750977, 2588.4006347656)
end)

Yard.MouseButton1Click:Connect(function()
if game.Players.LocalPlayer.Character.Humanoid.Sit then
game.Players.LocalPlayer.Character.Humanoid.Sit = false
end
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(793.51580810547, 98.18994140625, 2546.2531738281)
end)

Round.MouseButton1Click:Connect(function()
if game.Players.LocalPlayer.Character.Humanoid.Sit then
game.Players.LocalPlayer.Character.Humanoid.Sit = false
end
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-338.030426, 64.572464, 1812.73853)
end)

local Emojis = {"😀","😃","😄","😁","😆","😅","🤣","😂","🙂","🙃","😉","😊","😇","🥰","😍","🤩","😘","😗","☺","😚","😙","😋","😛","😜","🤪","😝","🤑","🤗","🤭","🤫","🤔","🤐","🤨","😐","😑","😶","😏","😒","🙄","😬","🤥","😌","😔","😪","🤤","😴","😷","🤒","🤕","🤢","🤮","🤧","🥵","🥶","🥴","😵","🤯","🤠","🥳","😎","🤓","🧐","😕","😟","🙁","☹","😮","😯","😲","😳","🥺","😦","😧","😨","😰","😥","😢","😭","😱","😖","😣","😞","😓","😩","🥱","😤","😡","😠","🤬","😈","👿","💀","☠","💩","🤡","👹","👺","👻","👽","👾","🤖"}
local Letters = {"A","B","C","D","E","F","G","H","I","J","K","L","M","N","O","P","Q","R","S","T","U","V","W","X","Y","Z"}


local SuperRandom = {math.random(1, #Emojis),math.random(1, #Letters)}

local WordKey = math.random(1, #SuperRandom)..math.random(1, #SuperRandom)..math.random(1, #SuperRandom)..math.random(1, #SuperRandom)..math.random(1, #SuperRandom)..math.random(1, #SuperRandom)..math.random(1, #SuperRandom)..math.random(1, #SuperRandom)..math.random(1, #SuperRandom)..math.random(1, #SuperRandom)

game:GetService("Players").LocalPlayer.CharacterAdded:Connect(function(NewChar)
if AntiBring then
workspace.FallenPartsDestroyHeight = math.huge-math.huge
for i,v in pairs(game.Players.LocalPlayer:WaitForChild("Backpack", 2):GetChildren()) do
local GunsValid = Instance.new("Part")
GunsValid.Parent = v
GunsValid.Name = WordKey

NewChar.ChildAdded:Connect(function(NewTool)
if not NewTool:FindFirstChild(WordKey) then
NewTool:Destroy()
end
end)
end
end
end)

spawn(function()
while wait() do
pcall(function()
if States_AntiCrash then
for i, v in pairs(game.Players:GetPlayers()) do
if v:FindFirstChild("PlayerScripts") and v.PlayerScripts:FindFirstChild("ClientGunReplicator").Disabled == false then
v.PlayerScripts.ClientGunReplicator.Disabled = true
end
if v.Character and v.Character.Head:FindFirstChild("handcuffedGui") and #v.Character.Head:FindFirstChild("handcuffedGui") > 2 then
if v == game.Players.LocalPlayer then
game.Players.LocalPlayer.Character.Humanoid.Health = 0
end
Kill(v)
end
end
else
for i, v in pairs(game.Players:GetPlayers()) do
if v:FindFirstChild("PlayerScripts") and v.PlayerScripts:FindFirstChild("ClientGunReplicator").Disabled == false then
v.PlayerScripts.ClientGunReplicator.Disabled = false
end
end
end
end)
end
end)

game:GetService("RunService").Stepped:Connect(function()
if States_AntiFling then
local plr = game.Players
local me = plr.LocalPlayer
for i,v in pairs(plr:GetPlayers()) do
if v ~= me then
local char = v.Character
if char then
for _,p in pairs(char:GetChildren()) do
pcall(function()
p.CanCollide = false
if p:FindFirstChild("Handle") then
p.Handle.CanCollide = false
end
end)
end
end
end
end
end
end)

game.Players.LocalPlayer.Idled:connect(function()
if States_AntiKickAfk then
game.VirtualUser:CaptureController()
game.VirtualUser:ClickButton2(Vector2.new())
end
end)

spawn(function()
while wait() do
pcall(function()
if States_AntiShields then
for i,v in pairs(game.Players:GetPlayers()) do
if v ~= game.Players.LocalPlayer then
for i2,v2 in pairs(v.Character:GetChildren()) do
if v2:FindFirstChild("ShieldFolder") then
v2:FindFirstChild("ShieldFolder"):Destroy()
end
if v2:FindFirstChild("Riot Shield") then
v2:FindFirstChild("Riot Shield"):Destroy()
end
end
end
end
end
end)
end
end)

spawn(function()
while wait() do
pcall(function()
if States_AntiSpamArrests then
if game.Players.LocalPlayer.TeamColor.Name == "Really red" or game.Players.LocalPlayer.Character.Head:FindFirstChild("handcuffedGui") then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(888, 100, 2388)
LoadCharacter(BrickColor.random().Name)
end
end
end)
end
end)

spawn(function()
while wait() do
pcall(function()
if States_AntiStatus then
game.Players.LocalPlayer:WaitForChild("Status"):WaitForChild("isHostile").Value = false
game.Players.LocalPlayer:WaitForChild("Status"):WaitForChild("toollsEquiped").Value = false
game.Players.LocalPlayer:WaitForChild("Status"):WaitForChild("isBadGuard").Value = false
game.Players.LocalPlayer:WaitForChild("Status"):WaitForChild("isArrested").Value = false
game.Players.LocalPlayer:WaitForChild("Status"):WaitForChild("innocentKills").Value = false
game.Players.LocalPlayer:WaitForChild("Status"):WaitForChild("playerCell").Value = false
end
end)
end
end)

game:GetService("RunService").RenderStepped:Connect(function()
if States_AutoGuns then
local Backpack = game:GetService("Players").LocalPlayer:WaitForChild("Backpack")
if not Backpack:FindFirstChild("M4A1") then
if Gamepass then
game:GetService("Workspace").Remote.ItemHandler:InvokeServer(game:GetService("Workspace").Prison_ITEMS.giver:FindFirstChild("M4A1").ITEMPICKUP)
end
end
wait(0.1)
if not Backpack:FindFirstChild("Remington 870") then
game:GetService("Workspace").Remote.ItemHandler:InvokeServer(game:GetService("Workspace").Prison_ITEMS.giver:FindFirstChild("Remington 870").ITEMPICKUP)
end
wait(0.1)
if not Backpack:FindFirstChild("AK-47") then
game:GetService("Workspace").Remote.ItemHandler:InvokeServer(game:GetService("Workspace").Prison_ITEMS.giver:FindFirstChild("AK-47").ITEMPICKUP)
end
wait(0.1)
if not Backpack:FindFirstChild("M9") then
game:GetService("Workspace").Remote.ItemHandler:InvokeServer(game:GetService("Workspace").Prison_ITEMS.giver:FindFirstChild("M9").ITEMPICKUP)
end
end
end)

local OldHealth = game:GetService("Players").LocalPlayer.Character.Humanoid.Health

spawn(function()
while wait() do
pcall(function()
if States_AutoHealth then
OldHealth = game:GetService("Players").LocalPlayer.Character.Humanoid.Health
wait(2)
if game:GetService("Players").LocalPlayer.Character.Humanoid.Health < OldHealth then
SaveCFrame()
LoadCharacter(BrickColor.random().Name)
LoadCFrame()
end
end
end)
end
end)

game:GetService("RunService").RenderStepped:Connect(function()
if States_AutoInfiniteAmmo then
for i,v in pairs(game:GetService("Players").LocalPlayer.Character:GetChildren()) do
if v:IsA("Tool") then
game:GetService("ReplicatedStorage").ReloadEvent:FireServer(v)
end
end
wait(1.5)
for i, v in next, debug.getregistry() do
if type(v) == "table" then
if v.Bullets then
v.CurrentAmmo = math.huge
v.MaxAmmo = math.huge
end
end
end
end
end)

spawn(function()
while wait() do
pcall(function()
if States_AutoLock then
if game:GetService("Players").LocalPlayer.Character and game.Players.LocalPlayer.Character.Humanoid then
game:GetService("Players").LocalPlayer.Character.Humanoid.WalkSpeed = 24
end
if game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:FindFirstChild("ClientInputHandler") then
game.Players.LocalPlayer.Character:FindFirstChild("ClientInputHandler"):Destroy()
end
game.StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.All, true)
end
end)
end
end)

spawn(function()
while wait() do
pcall(function()
if States_AutoRemoveKits then
local Kit1 = game.Players.LocalPlayer.Backpack:FindFirstChild("Taser") or game.Players.LocalPlayer.Character:FindFirstChild("Taser")
if Kit1 then
Kit1:Destroy()
end
local Kit2 = game.Players.LocalPlayer.Backpack:FindFirstChild("Handcuffs") or game.Players.LocalPlayer.Character:FindFirstChild("Handcuffs")
if Kit2 then
Kit2:Destroy()
end
end
end)
end
end)

spawn(function()
while wait() do
pcall(function()
if States_AutoRespawn then
if game.Players.LocalPlayer.Character.Humanoid.Health < 30 then
if States_AutoClothes then
if game.Players.LocalPlayer.TeamColor.Name == "Bright orange" then
SaveCFrame()
LoadCharacter(BrickColor.new("White").Name)
LoadCFrame()
FireTeam("Bright orange")
elseif game.Players.LocalPlayer.TeamColor.Name == "Bright blue" then
SaveCFrame()
LoadCharacter(BrickColor.new("White").Name)
LoadCFrame()
FireTeam("Bright blue")
end
else
if game.Players.LocalPlayer.TeamColor.Name == "Medium stone grey" then
SaveCFrame()
LoadCharacter(BrickColor.new("White").Name)
LoadCFrame()
FireTeam("Medium stone grey")
else
SaveCFrame()
LoadCharacter()
LoadCFrame()
end
end
end
end
end)
end
end)

function dragify(Frame)
dragToggle = nil
dragSpeed = 100000 -- You can edit this.
dragInput = nil
dragStart = nil
dragPos = nil

function updateInput(input)
Delta = input.Position - dragStart
Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
game:GetService("TweenService"):Create(Frame, TweenInfo.new(0), {Position = Position}):Play()
end

Frame.InputBegan:Connect(function(input)
if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then
dragToggle = true
dragStart = input.Position
startPos = Frame.Position
input.Changed:Connect(function()
if (input.UserInputState == Enum.UserInputState.End) then
dragToggle = false
end
end)
end
end)

Frame.InputChanged:Connect(function(input)
if (input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch) then
dragInput = input
end
end)

game:GetService("UserInputService").InputChanged:Connect(function(input)
if (input == dragInput and dragToggle) then
updateInput(input)
end
end)
end

dragify(Frame)
else
game.Players.LocalPlayer:Kick("Not Whitelisted.")
end
