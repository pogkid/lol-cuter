-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local BuildABoatForTreasureautofarm = Instance.new("TextButton")
local autofarmdahood = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")
local MADCityautofarmcash = Instance.new("TextButton")
local Madcityautofarmxp = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ResetOnSpawn = false

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(68, 74, 72)
Frame.Position = UDim2.new(0.283084989, 0, 0.296781898, 0)
Frame.Size = UDim2.new(0, 472, 0, 488)
Frame.Active = true
Frame.Draggable = true

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(168, 10, 10)
TextLabel.BorderColor3 = Color3.fromRGB(53, 0, 0)
TextLabel.Position = UDim2.new(0, 0, -0.104821786, 0)
TextLabel.Size = UDim2.new(0, 471, 0, 85)
TextLabel.Font = Enum.Font.SciFi
TextLabel.Text = "Gui Made By / mynameisnew99"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 30.000

BuildABoatForTreasureautofarm.Name = "Build A Boat For Treasure auto farm"
BuildABoatForTreasureautofarm.Parent = Frame
BuildABoatForTreasureautofarm.BackgroundColor3 = Color3.fromRGB(25, 77, 48)
BuildABoatForTreasureautofarm.Position = UDim2.new(0, 0, 0.0735294148, 0)
BuildABoatForTreasureautofarm.Size = UDim2.new(0, 246, 0, 60)
BuildABoatForTreasureautofarm.Font = Enum.Font.SciFi
BuildABoatForTreasureautofarm.Text = "Build A Boat For Treasure"
BuildABoatForTreasureautofarm.TextColor3 = Color3.fromRGB(0, 0, 0)
BuildABoatForTreasureautofarm.TextSize = 20.000
BuildABoatForTreasureautofarm.MouseButton1Down:connect(function()
	local vu = game:GetService("VirtualUser")
	game:GetService("Players").LocalPlayer.Idled:connect(function()
		vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
		wait(1)
		vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
	end)
	game.Players.LocalPlayer.Character.Head:Destroy()
	wait(7)
	spawn(function()
		game:GetService("RunService").Stepped:connect(function()
			game.Players.LocalPlayer.Character:WaitForChild("Humanoid"):ChangeState(11)
		end) end)
	game.Players.LocalPlayer.CharacterAdded:Connect(function()
		Clone = game:GetService("Players").LocalPlayer.Character.LowerTorso.Root:Clone()
		game:GetService("Players").LocalPlayer.Character.LowerTorso.Root:Destroy()
		Clone.Parent = game:GetService("Players").LocalPlayer.Character
	end)
	game.Workspace.Gravity = 0
	local CFrameEnd = CFrame.new(-51.1823959, 80.6168747, -536.437805)
	local Time = 1
	local tween =  game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(Time), {CFrame = CFrameEnd})
	tween:Play()
	tween.Completed:Wait(E)

	local CFrameEnd = CFrame.new(-47.6731682, 66.860466, 8698.90137, 0.999818563, 0.00121844851, -0.0190091729, 8.06243428e-09, 0.997951984, 0.0639670715, 0.0190481842, -0.0639554635, 0.997770965)
	local Time = 33
	local tween =  game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(Time), {CFrame = CFrameEnd})
	tween:Play()
	tween.Completed:Wait(E)
	wait(0.3)
	local CFrameEnd = CFrame.new(-58.6682281, -359.746033, 9489.12891, -0.993616283, 0.0757325292, -0.0836138725, -2.70548408e-05, 0.74101454, 0.671488941, 0.112812653, 0.667204618, -0.736282051)
	local Time = 1
	local tween =  game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(Time), {CFrame = CFrameEnd})
	tween:Play()
	tween.Completed:Wait(E)
	game.Players.LocalPlayer.CharacterAdded:Connect(function()
		repeat
			wait()
		until game.Players.LocalPlayer.Character
		wait(3.3)
		game.Workspace.Gravity = 0
		local CFrameEnd = CFrame.new(-51.1823959, 80.6168747, -536.437805)
		local Time = 1 -- Time in seconds
		local tween =  game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(Time), {CFrame = CFrameEnd})
		tween:Play()
		tween.Completed:Wait(E)

		local CFrameEnd = CFrame.new(-47.6731682, 66.860466, 8698.90137, 0.999818563, 0.00121844851, -0.0190091729, 8.06243428e-09, 0.997951984, 0.0639670715, 0.0190481842, -0.0639554635, 0.997770965)
		local Time = 33
		local tween =  game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(Time), {CFrame = CFrameEnd})
		tween:Play()
		tween.Completed:Wait(E)

		local CFrameEnd = CFrame.new(-58.6682281, -359.746033, 9489.12891, -0.993616283, 0.0757325292, -0.0836138725, -2.70548408e-05, 0.74101454, 0.671488941, 0.112812653, 0.667204618, -0.736282051)
		local Time = 1
		local tween =  game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(Time), {CFrame = CFrameEnd})
		tween:Play()
		tween.Completed:Wait(E)
		game.Workspace.Gravity = 200
	end)
	spawn(function()
		while wait (2) do
			workspace.ClaimRiverResultsGold:FireServer()
		end
	end)
end)

autofarmdahood.Name = "auto farm da hood"
autofarmdahood.Parent = Frame
autofarmdahood.BackgroundColor3 = Color3.fromRGB(25, 77, 48)
autofarmdahood.Position = UDim2.new(0.525423706, 0, 0.0737496391, 0)
autofarmdahood.Size = UDim2.new(0, 224, 0, 60)
autofarmdahood.Font = Enum.Font.SciFi
autofarmdahood.Text = "autofarm da hood"
autofarmdahood.TextColor3 = Color3.fromRGB(0, 0, 0)
autofarmdahood.TextSize = 25.000
autofarmdahood.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/rapnz/scripts/master/DaHoodFarm.lua"))()
end)

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(168, 10, 10)
TextLabel_2.Position = UDim2.new(0, 0, 0.825819671, 0)
TextLabel_2.Size = UDim2.new(0, 471, 0, 85)
TextLabel_2.Font = Enum.Font.SciFi
TextLabel_2.Text = "AUTO FARM GUI/version 0.1"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 30.000


MADCityautofarmcash.Name = "MAD City auto farm cash"
MADCityautofarmcash.Parent = Frame
MADCityautofarmcash.BackgroundColor3 = Color3.fromRGB(25, 77, 48)
MADCityautofarmcash.Position = UDim2.new(0, 0, 0.196480229, 0)
MADCityautofarmcash.Size = UDim2.new(0, 246, 0, 60)
MADCityautofarmcash.Font = Enum.Font.SciFi
MADCityautofarmcash.Text = "Mad city auto farm cash"
MADCityautofarmcash.TextColor3 = Color3.fromRGB(0, 0, 0)
MADCityautofarmcash.TextSize = 20.000
MADCityautofarmcash.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Eazvy/Mad-City-Advanced-Autofarm/main/Autofarm.lua"))()
end)

Madcityautofarmxp.Name = "Mad city auto farm xp"
Madcityautofarmxp.Parent = Frame
Madcityautofarmxp.BackgroundColor3 = Color3.fromRGB(25, 77, 48)
Madcityautofarmxp.Position = UDim2.new(0.525423706, 0, 0.196700454, 0)
Madcityautofarmxp.Size = UDim2.new(0, 224, 0, 60)
Madcityautofarmxp.Font = Enum.Font.SciFi
Madcityautofarmxp.Text = "Mad city auto farm xp"
Madcityautofarmxp.TextColor3 = Color3.fromRGB(0, 0, 0)
Madcityautofarmxp.TextSize = 25.000
Madcityautofarmxp.MouseButton1Down:connect(function()
	game:GetService("ReplicatedStorage").RemoteFunction:InvokeServer("SetTeam", "Police")
	wait(.75)
	game:GetService("RunService").RenderStepped:Connect(function()
		for i,v in pairs(game:GetService("Players").LocalPlayer.Backpack:GetChildren()) do
			if v.Name == "Handcuffs" then v.Parent = game:GetService("Players").LocalPlayer.Character
			end
		end
		game:GetService("ReplicatedStorage").Event:FireServer("Eject", game:GetService("Players").LocalPlayer)
	end)
end)
