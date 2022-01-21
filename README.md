-- Made by XYZZAYANY


local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local UIGradient = Instance.new("UIGradient")
local X = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local XY = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local Hud = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local ToolName = Instance.new("TextBox")
local UICorner_5 = Instance.new("UICorner")
local Farm = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local AntiAfk = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local Drop = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local FPS = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local Reviz = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local Equip = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local UnequipWeights = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local Open = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(217, 217, 217)
Frame.Position = UDim2.new(0.507403731, 0, 0.305502832, 0)
Frame.Size = UDim2.new(0, 429, 0, 219)
Frame.Visible = false
Frame.Active = true
Frame.Draggable = true

UICorner.Parent = Frame

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(170, 85, 255)), ColorSequenceKeypoint.new(0.34, Color3.fromRGB(146, 119, 255)), ColorSequenceKeypoint.new(0.46, Color3.fromRGB(85, 170, 255)), ColorSequenceKeypoint.new(0.78, Color3.fromRGB(170, 85, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(97, 195, 255))}
UIGradient.Parent = Frame

X.Name = "X"
X.Parent = Frame
X.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
X.Position = UDim2.new(0.874057293, 0, 0.0585365854, 0)
X.Size = UDim2.new(0, 41, 0, 41)
X.Font = Enum.Font.GothamBlack
X.Text = "X"
X.TextColor3 = Color3.fromRGB(0, 0, 0)
X.TextSize = 30.000

UICorner_2.Parent = X

XY.Name = "XY"
XY.Parent = Frame
XY.BackgroundColor3 = Color3.fromRGB(255, 125, 245)
XY.Position = UDim2.new(0.251816839, 0, 0.0621761419, 0)
XY.Size = UDim2.new(0, 213, 0, 45)
XY.Font = Enum.Font.Cartoon
XY.Text = "Niggas's Farming GUI"
XY.TextColor3 = Color3.fromRGB(0, 0, 0)
XY.TextSize = 18.000

UICorner_3.Parent = XY

Hud.Name = "Hud"
Hud.Parent = Frame
Hud.BackgroundColor3 = Color3.fromRGB(85, 255, 127)
Hud.Position = UDim2.new(0.0187165774, 0, 0.554629564, 0)
Hud.Size = UDim2.new(0, 100, 0, 36)
Hud.Font = Enum.Font.GothamBlack
Hud.Text = "Delete - Hud"
Hud.TextColor3 = Color3.fromRGB(0, 0, 0)
Hud.TextSize = 14.000
Hud.MouseButton1Down:connect(function()
	game:GetService("Players").LocalPlayer.PlayerGui.HUD:Destroy()
end)

UICorner_4.Parent = Hud

ToolName.Name = "Tool Name"
ToolName.Parent = Frame
ToolName.BackgroundColor3 = Color3.fromRGB(128, 255, 251)
ToolName.Position = UDim2.new(0.338817954, 0, 0.331606239, 0)
ToolName.Size = UDim2.new(0, 137, 0, 37)
ToolName.Font = Enum.Font.GothamBlack
ToolName.Text = "Double Weight"
ToolName.TextColor3 = Color3.fromRGB(0, 0, 0)
ToolName.TextSize = 14.000

UICorner_5.Parent = ToolName

Farm.Name = "Farm"
Farm.Parent = Frame
Farm.BackgroundColor3 = Color3.fromRGB(85, 255, 127)
Farm.Position = UDim2.new(0.309406281, 0, 0.543334424, 0)
Farm.Size = UDim2.new(0, 160, 0, 41)
Farm.Font = Enum.Font.GothamBlack
Farm.Text = "Farm"
Farm.TextColor3 = Color3.fromRGB(0, 0, 0)
Farm.TextSize = 20.000
Farm.MouseButton1Down:connect(function()
	Farm.Visible = true
	_G.Farm = true
	while _G.Farm do
		wait(0.6)
		for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
			if v.Name == ToolName.Text then v:Activate() end
		end
	end
end)

UICorner_6.Parent = Farm

AntiAfk.Name = "Anti-Afk"
AntiAfk.Parent = Frame
AntiAfk.BackgroundColor3 = Color3.fromRGB(85, 255, 127)
AntiAfk.Position = UDim2.new(0.0187165942, 0, 0.77736944, 0)
AntiAfk.Size = UDim2.new(0, 100, 0, 36)
AntiAfk.Font = Enum.Font.GothamBlack
AntiAfk.Text = "Anti-Afk"
AntiAfk.TextColor3 = Color3.fromRGB(0, 0, 0)
AntiAfk.TextSize = 14.000
AntiAfk.MouseButton1Down:connect(function()
	wait(0.5)local ba=Instance.new("ScreenGui")
	local ca=Instance.new("TextLabel")local da=Instance.new("Frame")
	local _b=Instance.new("TextLabel")local ab=Instance.new("TextLabel")ba.Parent=game.CoreGui
	ba.ZIndexBehavior=Enum.ZIndexBehavior.Sibling;ca.Parent=ba;ca.Active=true
	ca.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ca.Draggable=true
	ca.Position=UDim2.new(0.698610067,0,0.098096624,0)ca.Size=UDim2.new(0,370,0,52)
	ca.Font=Enum.Font.SourceSansSemibold;ca.Text="Anti Afk"ca.TextColor3=Color3.new(0,1,1)
	ca.TextSize=22;da.Parent=ca
	da.BackgroundColor3=Color3.new(0.196078,0.196078,0.196078)da.Position=UDim2.new(0,0,1.0192306,0)
	da.Size=UDim2.new(0,370,0,107)_b.Parent=da
	_b.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)_b.Position=UDim2.new(0,0,0.800455689,0)
	_b.Size=UDim2.new(0,370,0,21)_b.Font=Enum.Font.Arial;_b.Text="Made by nigas"
	_b.TextColor3=Color3.new(0,1,1)_b.TextSize=20;ab.Parent=da
	ab.BackgroundColor3=Color3.new(0.176471,0.176471,0.176471)ab.Position=UDim2.new(0,0,0.158377,0)
	ab.Size=UDim2.new(0,370,0,44)ab.Font=Enum.Font.ArialBold;ab.Text="Status: Active"
	ab.TextColor3=Color3.new(0,1,1)ab.TextSize=20;local bb=game:service'VirtualUser'
	game:service'Players'.LocalPlayer.Idled:connect(function()
		bb:CaptureController()bb:ClickButton2(Vector2.new())
		ab.Text="Roblox kicked you but we didnt let them!"wait(2)ab.Text="Status : Active"end)
end)

UICorner_7.Parent = AntiAfk

Drop.Name = "Drop"
Drop.Parent = Frame
Drop.BackgroundColor3 = Color3.fromRGB(85, 255, 127)
Drop.Position = UDim2.new(0.748251736, 0, 0.541352093, 0)
Drop.Size = UDim2.new(0, 100, 0, 36)
Drop.Font = Enum.Font.GothamBlack
Drop.Text = "Drop Yourself"
Drop.TextColor3 = Color3.fromRGB(0, 0, 0)
Drop.TextSize = 14.000
Drop.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/CjVD4RZN", true))()
end)

UICorner_8.Parent = Drop

FPS.Name = "FPS"
FPS.Parent = Frame
FPS.BackgroundColor3 = Color3.fromRGB(85, 255, 127)
FPS.Position = UDim2.new(0.750582755, 0, 0.77736944, 0)
FPS.Size = UDim2.new(0, 100, 0, 36)
FPS.Font = Enum.Font.GothamBlack
FPS.Text = "FPS Script"
FPS.TextColor3 = Color3.fromRGB(0, 0, 0)
FPS.TextSize = 14.000
FPS.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/mmEr60d5", true))()
end)

UICorner_9.Parent = FPS

Reviz.Name = "Reviz"
Reviz.Parent = Frame
Reviz.BackgroundColor3 = Color3.fromRGB(255, 85, 255)
Reviz.Position = UDim2.new(0.303030312, 0, 0.786501825, 0)
Reviz.Size = UDim2.new(0, 169, 0, 34)
Reviz.Font = Enum.Font.GothamBlack
Reviz.Text = "Reviz Admin Script"
Reviz.TextColor3 = Color3.fromRGB(0, 0, 0)
Reviz.TextSize = 14.000
Reviz.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/pGhYnsxA", true))()
end)

UICorner_10.Parent = Reviz

Equip.Name = "Equip"
Equip.Parent = Frame
Equip.BackgroundColor3 = Color3.fromRGB(85, 255, 127)
Equip.BorderColor3 = Color3.fromRGB(0, 0, 0)
Equip.Position = UDim2.new(0.0187165942, 0, 0.331606239, 0)
Equip.Size = UDim2.new(0, 100, 0, 36)
Equip.Font = Enum.Font.GothamBlack
Equip.Text = "Equip Weights"
Equip.TextColor3 = Color3.fromRGB(0, 0, 0)
Equip.TextSize = 14.000
Equip.MouseButton1Down:connect(function()
	Equip.Visible = true
	_G.Equip = true
	while _G.Equip do
		wait()
		for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
			if v.Name == ToolName.Text then
				v.Parent = game.Players.LocalPlayer.Character
			end
		end
	end
end)

UICorner_11.Parent = Equip

UnequipWeights.Name = "Unequip Weights"
UnequipWeights.Parent = Frame
UnequipWeights.BackgroundColor3 = Color3.fromRGB(85, 255, 127)
UnequipWeights.Position = UDim2.new(0.748251736, 0, 0.331606239, 0)
UnequipWeights.Size = UDim2.new(0, 100, 0, 36)
UnequipWeights.Font = Enum.Font.GothamBlack
UnequipWeights.Text = "Unequip Weights"
UnequipWeights.TextColor3 = Color3.fromRGB(0, 0, 0)
UnequipWeights.TextSize = 12.000
UnequipWeights.MouseButton1Down:connect(function()
	Equip.Visible = true
	UnequipWeights.Visible = true
	_G.Equip = false
end)

UICorner_12.Parent = UnequipWeights

Open.Name = "Open"
Open.Parent = ScreenGui
Open.BackgroundColor3 = Color3.fromRGB(164, 255, 233)
Open.Position = UDim2.new(0.89930898, 0, 0.804554105, 0)
Open.Size = UDim2.new(0, 102, 0, 33)
Open.Font = Enum.Font.GothamBlack
Open.Text = "Open"
Open.TextColor3 = Color3.fromRGB(0, 0, 0)
Open.TextSize = 20.000

UICorner_13.Parent = Open

-- Scripts:

local function HOKJ_fake_script() -- X.LocalScript 
	local script = Instance.new('LocalScript', X)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(HOKJ_fake_script)()
local function TJASP_fake_script() -- Open.LocalScript 
	local script = Instance.new('LocalScript', Open)

	local frame = script.Parent.Parent.Frame
	
	script.parent.MouseButton1Click:Connect(function()
		frame.Visible = true
	
	end)
end
coroutine.wrap(TJASP_fake_script)()
