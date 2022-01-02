-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local pressittogetcoins = Instance.new("TextButton")
local pressittogetlevel = Instance.new("TextButton")
local MADEBYMYNAMEISNEW99 = Instance.new("TextLabel")
local DestructionSimulatorgui = Instance.new("TextLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ResetOnSpawn = false

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(76, 76, 76)
Frame.Position = UDim2.new(0.400423735, 0, 0.14302741, 0)
Frame.Size = UDim2.new(0, 431, 0, 541)
Frame.Active = true
Frame.Draggable = true

pressittogetcoins.Name = "press it to get coins"
pressittogetcoins.Parent = Frame
pressittogetcoins.BackgroundColor3 = Color3.fromRGB(32, 108, 0)
pressittogetcoins.Position = UDim2.new(0, 0, 0.112754159, 0)
pressittogetcoins.Size = UDim2.new(0, 431, 0, 88)
pressittogetcoins.Font = Enum.Font.SciFi
pressittogetcoins.Text = "press it to get coins"
pressittogetcoins.TextColor3 = Color3.fromRGB(0, 0, 0)
pressittogetcoins.TextSize = 50.000
pressittogetcoins.TextWrapped = true
pressittogetcoins.MouseButton1Down:connect(function()
	game:GetService("ReplicatedStorage").Remotes.generateBoost:FireServer("Coins", 480, 99999999)
end)

pressittogetlevel.Name = "press it to get level"
pressittogetlevel.Parent = Frame
pressittogetlevel.BackgroundColor3 = Color3.fromRGB(32, 108, 0)
pressittogetlevel.Position = UDim2.new(0, 0, 0.722735703, 0)
pressittogetlevel.Size = UDim2.new(0, 431, 0, 88)
pressittogetlevel.Font = Enum.Font.SciFi
pressittogetlevel.Text = "press it to get level"
pressittogetlevel.TextColor3 = Color3.fromRGB(0, 0, 0)
pressittogetlevel.TextSize = 50.000
pressittogetlevel.TextWrapped = true
pressittogetlevel.MouseButton1Down:connect(function()
	game:GetService("ReplicatedStorage").Remotes.generateBoost:FireServer("Levels", 480, 10)

end)

MADEBYMYNAMEISNEW99.Name = "MADE BY/MYNAMEISNEW99"
MADEBYMYNAMEISNEW99.Parent = Frame
MADEBYMYNAMEISNEW99.BackgroundColor3 = Color3.fromRGB(97, 4, 4)
MADEBYMYNAMEISNEW99.Position = UDim2.new(-0.0011715591, 0, -0.00109935552, 0)
MADEBYMYNAMEISNEW99.Size = UDim2.new(0, 431, 0, 61)
MADEBYMYNAMEISNEW99.Font = Enum.Font.SourceSans
MADEBYMYNAMEISNEW99.Text = "MADE BY/MYNAMEISNEW99"
MADEBYMYNAMEISNEW99.TextColor3 = Color3.fromRGB(0, 0, 0)
MADEBYMYNAMEISNEW99.TextSize = 30.000

DestructionSimulatorgui.Name = "Destruction Simulator gui"
DestructionSimulatorgui.Parent = Frame
DestructionSimulatorgui.BackgroundColor3 = Color3.fromRGB(97, 4, 4)
DestructionSimulatorgui.Position = UDim2.new(-0.0011715591, 0, 0.886574984, 0)
DestructionSimulatorgui.Size = UDim2.new(0, 431, 0, 61)
DestructionSimulatorgui.Font = Enum.Font.SourceSans
DestructionSimulatorgui.Text = "Destruction Simulator gui"
DestructionSimulatorgui.TextColor3 = Color3.fromRGB(0, 0, 0)
DestructionSimulatorgui.TextSize = 30.000
