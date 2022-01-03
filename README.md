-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local autofarmdahood = Instance.new("TextButton")
local BuildABoatForTreasureautofarm = Instance.new("TextButton")
local MADCityautofarmcash = Instance.new("TextButton")
local Madcityautofarmxp = Instance.new("TextButton")
local skywarsautofarmcoins = Instance.new("TextButton")
local ImpossibleGlassBridgeSquidGameautowinfarm = Instance.new("TextButton")
local Frame_2 = Instance.new("Frame")
local AUTOFARMGUI1 = Instance.new("TextButton")
local DestructionSimulatorgui = Instance.new("TextButton")
local kickoffautogoal = Instance.new("TextButton")
local MillionaireEmpireTycoonINFINITEMONEYANDREBIRTH = Instance.new("TextButton")
local ZombieRushautofarm = Instance.new("TextButton")
local ExpeditionAntarcticaautofarmcoin = Instance.new("TextButton")
local CreaturesofSonariaautofarmbell = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ResetOnSpawn = false

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(61, 60, 58)
Frame.Position = UDim2.new(0.343220383, 0, 0.153754473, 0)
Frame.Size = UDim2.new(0, 499, 0, 513)
Frame.Active = true
Frame.Draggable = true


TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(144, 0, 0)
TextLabel.Position = UDim2.new(-0.202003986, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 601, 0, 57)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "MADE BY/MYNAMEISNEW99"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 30.000

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(144, 0, 0)
TextLabel_2.Position = UDim2.new(-0.202003986, 0, 0.888888896, 0)
TextLabel_2.Size = UDim2.new(0, 600, 0, 57)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "AUTO FARM GUI/VERISON 0.1"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 30.000

autofarmdahood.Name = "auto farm da hood"
autofarmdahood.Parent = Frame
autofarmdahood.BackgroundColor3 = Color3.fromRGB(13, 94, 23)
autofarmdahood.Position = UDim2.new(0, 0, 0.111111112, 0)
autofarmdahood.Size = UDim2.new(0, 246, 0, 50)
autofarmdahood.Font = Enum.Font.SciFi
autofarmdahood.Text = "auto farm da hood"
autofarmdahood.TextColor3 = Color3.fromRGB(0, 0, 0)
autofarmdahood.TextSize = 30.000
autofarmdahood.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/rapnz/scripts/master/DaHoodFarm.lua"))()
end)

BuildABoatForTreasureautofarm.Name = "Build A Boat For Treasure auto farm"
BuildABoatForTreasureautofarm.Parent = Frame
BuildABoatForTreasureautofarm.BackgroundColor3 = Color3.fromRGB(13, 94, 23)
BuildABoatForTreasureautofarm.Position = UDim2.new(0.492000014, 0, 0.111111112, 0)
BuildABoatForTreasureautofarm.Size = UDim2.new(0, 254, 0, 50)
BuildABoatForTreasureautofarm.Font = Enum.Font.SciFi
BuildABoatForTreasureautofarm.Text = "Build A Boat For Treasure auto farm"
BuildABoatForTreasureautofarm.TextColor3 = Color3.fromRGB(0, 0, 0)
BuildABoatForTreasureautofarm.TextSize = 17.000
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





MADCityautofarmcash.Name = "MAD City auto farm cash"
MADCityautofarmcash.Parent = Frame
MADCityautofarmcash.BackgroundColor3 = Color3.fromRGB(13, 94, 23)
MADCityautofarmcash.Position = UDim2.new(0, 0, 0.208577007, 0)
MADCityautofarmcash.Size = UDim2.new(0, 246, 0, 50)
MADCityautofarmcash.Font = Enum.Font.SciFi
MADCityautofarmcash.Text = "MAD City auto farm cash"
MADCityautofarmcash.TextColor3 = Color3.fromRGB(0, 0, 0)
MADCityautofarmcash.TextSize = 24.000
MADCityautofarmcash.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Eazvy/Mad-City-Advanced-Autofarm/main/Autofarm.lua"))()
end)

Madcityautofarmxp.Name = "Mad city auto farm xp"
Madcityautofarmxp.Parent = Frame
Madcityautofarmxp.BackgroundColor3 = Color3.fromRGB(13, 94, 23)
Madcityautofarmxp.Position = UDim2.new(0.492000014, 0, 0.208577007, 0)
Madcityautofarmxp.Size = UDim2.new(0, 254, 0, 50)
Madcityautofarmxp.Font = Enum.Font.SciFi
Madcityautofarmxp.Text = "Mad city auto farm xp"
Madcityautofarmxp.TextColor3 = Color3.fromRGB(0, 0, 0)
Madcityautofarmxp.TextSize = 26.000
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

skywarsautofarmcoins.Name = "sky wars auto farm coins"
skywarsautofarmcoins.Parent = Frame
skywarsautofarmcoins.BackgroundColor3 = Color3.fromRGB(13, 94, 23)
skywarsautofarmcoins.Position = UDim2.new(0, 0, 0.30604291, 0)
skywarsautofarmcoins.Size = UDim2.new(0, 246, 0, 50)
skywarsautofarmcoins.Font = Enum.Font.SciFi
skywarsautofarmcoins.Text = "sky wars auto farm coins"
skywarsautofarmcoins.TextColor3 = Color3.fromRGB(0, 0, 0)
skywarsautofarmcoins.TextSize = 24.000
skywarsautofarmcoins.MouseButton1Down:connect(function()
	local cpos = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame

	local stuff = workspace:getDescendants()
	for i=1,#stuff do
		if stuff[i].Name == "Block" and stuff[i].Parent.Name == "Ores" then
			repeat
				wait()
				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = stuff[i].CFrame
				game.Players.LocalPlayer.Character.Axe.RemoteEvent:FireServer(stuff[i])
			until stuff[i].Name ~= "Block" or not game.Players.LocalPlayer.Character:findFirstChild("Axe")
		end
	end

	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = cpos
end)


ImpossibleGlassBridgeSquidGameautowinfarm.Name = "Impossible Glass Bridge Squid Game auto win farm"
ImpossibleGlassBridgeSquidGameautowinfarm.Parent = Frame
ImpossibleGlassBridgeSquidGameautowinfarm.BackgroundColor3 = Color3.fromRGB(13, 94, 23)
ImpossibleGlassBridgeSquidGameautowinfarm.Position = UDim2.new(0.492000014, 0, 0.30604288, 0)
ImpossibleGlassBridgeSquidGameautowinfarm.Size = UDim2.new(0, 254, 0, 50)
ImpossibleGlassBridgeSquidGameautowinfarm.Font = Enum.Font.SciFi
ImpossibleGlassBridgeSquidGameautowinfarm.Text = "Impossible Glass Bridge Squid Game auto win farm"
ImpossibleGlassBridgeSquidGameautowinfarm.TextColor3 = Color3.fromRGB(0, 0, 0)
ImpossibleGlassBridgeSquidGameautowinfarm.TextSize = 11.000
ImpossibleGlassBridgeSquidGameautowinfarm.MouseButton1Down:connect(function()
	getgenv().AutoMoneyTeleport = true -- Set true Teleport to end
	getgenv().AutoMoneyTween = true -- set true to use tween to end 

	loadstring(game:HttpGet('https://raw.githubusercontent.com/BaconLords/Random-Shit/main/Impossible%20Glass%20Bridge%20AutoFarm.lua'))()
end)

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(61, 60, 58)
Frame_2.Position = UDim2.new(-0.202004015, 0, 0.111111112, 0)
Frame_2.Size = UDim2.new(0, 100, 0, 399)

AUTOFARMGUI1.Name = "AUTO FARM GUI #1"
AUTOFARMGUI1.Parent = Frame_2
AUTOFARMGUI1.BackgroundColor3 = Color3.fromRGB(13, 94, 23)
AUTOFARMGUI1.Position = UDim2.new(0, 0, -0.00167084485, 0)
AUTOFARMGUI1.Size = UDim2.new(0, 100, 0, 50)
AUTOFARMGUI1.Font = Enum.Font.SciFi
AUTOFARMGUI1.Text = "AUTO FARM GUI #1"
AUTOFARMGUI1.TextColor3 = Color3.fromRGB(0, 0, 0)
AUTOFARMGUI1.TextSize = 14.000

DestructionSimulatorgui.Name = "Destruction Simulator gui"
DestructionSimulatorgui.Parent = Frame
DestructionSimulatorgui.BackgroundColor3 = Color3.fromRGB(13, 94, 23)
DestructionSimulatorgui.Position = UDim2.new(0, 0, 0.403508782, 0)
DestructionSimulatorgui.Size = UDim2.new(0, 246, 0, 50)
DestructionSimulatorgui.Font = Enum.Font.SciFi
DestructionSimulatorgui.Text = "Destruction Simulator gui"
DestructionSimulatorgui.TextColor3 = Color3.fromRGB(0, 0, 0)
DestructionSimulatorgui.TextSize = 18.000
DestructionSimulatorgui.MouseButton1Down:connect(function()
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
end)

kickoffautogoal.Name = "kick off auto goal"
kickoffautogoal.Parent = Frame
kickoffautogoal.BackgroundColor3 = Color3.fromRGB(13, 94, 23)
kickoffautogoal.Position = UDim2.new(0.492000014, 0, 0.403508782, 0)
kickoffautogoal.Size = UDim2.new(0, 254, 0, 50)
kickoffautogoal.Font = Enum.Font.SciFi
kickoffautogoal.Text = "kick off auto goal "
kickoffautogoal.TextColor3 = Color3.fromRGB(0, 0, 0)
kickoffautogoal.TextSize = 30.000
kickoffautogoal.MouseButton1Down:connect(function()
	getgenv().AutoFarmGoals = true
	loadstring(game:HttpGet("https://raw.githubusercontent.com/BaconLords/Random-Shit/main/Kick%20Off%20AutoGoal%20bitch.lua"))()
end)

MillionaireEmpireTycoonINFINITEMONEYANDREBIRTH.Name = "Millionaire Empire Tycoon INFINITE MONEY AND REBIRTH"
MillionaireEmpireTycoonINFINITEMONEYANDREBIRTH.Parent = Frame
MillionaireEmpireTycoonINFINITEMONEYANDREBIRTH.BackgroundColor3 = Color3.fromRGB(13, 94, 23)
MillionaireEmpireTycoonINFINITEMONEYANDREBIRTH.Position = UDim2.new(-0.000985980732, 0, 0.500974655, 0)
MillionaireEmpireTycoonINFINITEMONEYANDREBIRTH.Size = UDim2.new(0, 246, 0, 50)
MillionaireEmpireTycoonINFINITEMONEYANDREBIRTH.Font = Enum.Font.SciFi
MillionaireEmpireTycoonINFINITEMONEYANDREBIRTH.Text = "Millionaire Empire Tycoon INFINITE MONEY AND REBIRTH"
MillionaireEmpireTycoonINFINITEMONEYANDREBIRTH.TextColor3 = Color3.fromRGB(0, 0, 0)
MillionaireEmpireTycoonINFINITEMONEYANDREBIRTH.TextSize = 10.000
MillionaireEmpireTycoonINFINITEMONEYANDREBIRTH.MouseButton1Down:connect(function()
	loadstring(game:HttpGetAsync"https://gist.githubusercontent.com/HaxxV1/6fc1784543e165299d9b5d29e4e64f08/raw/836cdbddae5db40224741bcc7c674b37a7e97058")()
end)

ZombieRushautofarm.Name = "Zombie Rush auto farm"
ZombieRushautofarm.Parent = Frame
ZombieRushautofarm.BackgroundColor3 = Color3.fromRGB(13, 94, 23)
ZombieRushautofarm.Position = UDim2.new(0.492000014, 0, 0.500974655, 0)
ZombieRushautofarm.Size = UDim2.new(0, 254, 0, 50)
ZombieRushautofarm.Font = Enum.Font.SciFi
ZombieRushautofarm.Text = "Zombie Rush auto farm"
ZombieRushautofarm.TextColor3 = Color3.fromRGB(0, 0, 0)
ZombieRushautofarm.TextSize = 25.000
ZombieRushautofarm.MouseButton1Down:connect(function()
	game:GetService("RunService").Stepped:connect(function()
		game.Players.LocalPlayer.Character:WaitForChild("Humanoid"):ChangeState(11)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-153.47319, 52.5, -4828.72021, -0.998862445, 4.47831461e-08, 0.0476949513, 4.73453277e-08, 1, 5.25903197e-08, -0.0476949513, 5.47886252e-08, -0.998862445)
	end)

	spawn(function()
		while wait () do
			for i, v in pairs(workspace["Zombie Storage"]:GetChildren()) do wait()
				if v:FindFirstChild("Head") then
					local args = {
						[1] = {
							["LaserProperties"] = {
								[1] = {
									[1] = "Neon",
									[2] = BrickColor.new(1003),
									[3] = Vector3.new(0, 0, 0),
									[4] = CFrame.new(Vector3.new(121, 200, 4869), Vector3.new(-0, -0, -1)),
									[5] = Vector3.new(150.73249816895, 24.428089141846, 114.7022857666),
									[6] = 9000000000,
									[7] = true,
									[8] = Vector3.new(0, 0, 0)
								}
							},
							["RealTool"] = game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Tool"),
							["Tool"] = game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Tool"),
							["HumanoidTables"] = {
								[1] = {
									["HeadHits"] = 10,
									["THumanoid"] = v.Humanoid,
									["BodyHits"] = 0
								}
							}
						}
					}

					game:GetService("ReplicatedStorage").Remotes.WeaponEvent:FireServer(unpack(args))
					for i, v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
						if v.ClassName == "Tool" and v:FindFirstChild("GunController") then
							v.Parent = game.Players.LocalPlayer.Character
						end end end end end end)

	local vu = game:GetService("VirtualUser")
	game:GetService("Players").LocalPlayer.Idled:connect(function()
		vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
		wait(1)
		vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
	end)
end)

ExpeditionAntarcticaautofarmcoin.Name = "Expedition Antarctica  auto farm coin"
ExpeditionAntarcticaautofarmcoin.Parent = Frame
ExpeditionAntarcticaautofarmcoin.BackgroundColor3 = Color3.fromRGB(13, 94, 23)
ExpeditionAntarcticaautofarmcoin.Position = UDim2.new(-0.000985980732, 0, 0.598440528, 0)
ExpeditionAntarcticaautofarmcoin.Size = UDim2.new(0, 246, 0, 50)
ExpeditionAntarcticaautofarmcoin.Font = Enum.Font.SciFi
ExpeditionAntarcticaautofarmcoin.Text = "Expedition Antarctica auto farm coin"
ExpeditionAntarcticaautofarmcoin.TextColor3 = Color3.fromRGB(0, 0, 0)
ExpeditionAntarcticaautofarmcoin.TextSize = 16.000
ExpeditionAntarcticaautofarmcoin.MouseButton1Down:connect(function()
--[[
    Script [1]: its just farming 3 places (Camp1,Camp2,Camp3)
    Script [2]: farming 4 places (Camp1,Camp2,Camp3,SouthPole)
]]--

getgenv().FarmCoin = true
DEBUG_MODE = true -- logging farming process, print out on dev console F9

local SelectScript = 1
local _FERXIIC = ({[1] = game:HttpGet('https://pastebin.com/raw/GK6a9sVQ'), [2] = game:HttpGet('https://pastebin.com/raw/iPK1r1NN')})[SelectScript]
	loadstring(_FERXIIC)()
	end)


CreaturesofSonariaautofarmbell.Name = "Creatures of Sonaria auto farm bell"
CreaturesofSonariaautofarmbell.Parent = Frame
CreaturesofSonariaautofarmbell.BackgroundColor3 = Color3.fromRGB(13, 94, 23)
CreaturesofSonariaautofarmbell.Position = UDim2.new(0.492000014, 0, 0.598440528, 0)
CreaturesofSonariaautofarmbell.Size = UDim2.new(0, 254, 0, 50)
CreaturesofSonariaautofarmbell.Font = Enum.Font.SciFi
CreaturesofSonariaautofarmbell.Text = "Creatures of Sonaria auto farm bell"
CreaturesofSonariaautofarmbell.TextColor3 = Color3.fromRGB(0, 0, 0)
CreaturesofSonariaautofarmbell.TextSize = 18.000
CreaturesofSonariaautofarmbell.MouseButton1Down:connect(function()
	-- Set everything to false to stop the farm

	getgenv().BellFarm = true
	getgenv().Bells = true
	getgenv().Trivia_scrambler = true

	local TriviaAnswer = "SubmitTriviaAnswer"
	local Answer = {
		["answer"] = "None"
	}
	local Scrambler = "ScramblerAnswer"
	local Answer1 = "Ani"

	-- Touching all the Presents

	task.spawn(function()
		while getgenv().BellFarm == true do
			task.wait(0.5)
			for i, v in pairs(game:GetService("Workspace"):GetDescendants()) do
				if v.Name == "TouchInterest" and v.Parent.Name == "Present" then
					firetouchinterest(game.Players.LocalPlayer.Character.HumanoidRootPart, v.Parent, 0)
				end
			end
		end
	end)

	-- gives wrong answer to Trivia and Scrambler (you still get bells for wrong answers)

	task.spawn(function()
		while getgenv().Trivia_scrambler == true do
			task.wait(0.5)
			for i, v in pairs(game:GetService("Players").LocalPlayer.PlayerGui:GetChildren()) do
				if v.Name == "Trivia" then
					game:GetService("Players").LocalPlayer.RemoteFunction:InvokeServer(TriviaAnswer, Answer)
					wait(1)
					v:Destroy()
				elseif v.Name == "Scramble" then
					game:GetService("Players").LocalPlayer.RemoteEvent:FireServer(Scrambler, Answer1)
					wait(1)
					v:Destroy()
				end
			end
		end
	end)

	-- Touch all the bells, can also be used to steal people's bells on the ground

	task.spawn(function()
		while getgenv().Bells == true do
			task.wait(0.5)
			for i,v in pairs(workspace.DroppedWisps:GetDescendants()) do
				if v:IsA("TouchTransmitter") then
					firetouchinterest(game.Players.LocalPlayer.Character.HumanoidRootPart, v.Parent, 0)
					firetouchinterest(game.Players.LocalPlayer.Character.HumanoidRootPart, v.Parent, 1)
				end
			end
		end
	end)
end)
