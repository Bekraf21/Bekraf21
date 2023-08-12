-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local TextButton_3 = Instance.new("TextButton")
local TextButton_4 = Instance.new("TextButton")
local TextButton_5 = Instance.new("TextButton")
local CloseGui = Instance.new("ImageButton")
local Discord = Instance.new("ImageButton")
local TextLabel = Instance.new("TextLabel")
local Extras = Instance.new("ImageButton")
local ImageLabel = Instance.new("ImageLabel")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.00597779686, 0, 0.0175953079, 0)
Frame.Size = UDim2.new(0, 198, 0, 344)

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.237373888, 0, 0.0813953504, 0)
TextButton.Size = UDim2.new(0, 150, 0, 50)
TextButton.Font = Enum.Font.Unknown
TextButton.Text = "COMBAT"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextSize = 28.000
TextButton.TextWrapped = true

TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.237373888, 0, 0.662790716, 0)
TextButton_2.Size = UDim2.new(0, 150, 0, 50)
TextButton_2.Font = Enum.Font.Unknown
TextButton_2.Text = "WORLD"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextSize = 28.000

TextButton_3.Parent = Frame
TextButton_3.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0.237373888, 0, 0.517441869, 0)
TextButton_3.Size = UDim2.new(0, 150, 0, 50)
TextButton_3.Font = Enum.Font.Unknown
TextButton_3.Text = "UTILITY"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextSize = 28.000

TextButton_4.Parent = Frame
TextButton_4.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
TextButton_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0.237373888, 0, 0.372093022, 0)
TextButton_4.Size = UDim2.new(0, 150, 0, 50)
TextButton_4.Font = Enum.Font.Unknown
TextButton_4.Text = "RENDER"
TextButton_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.TextSize = 28.000

TextButton_5.Parent = Frame
TextButton_5.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
TextButton_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(0.237373888, 0, 0.22674419, 0)
TextButton_5.Size = UDim2.new(0, 150, 0, 50)
TextButton_5.Font = Enum.Font.Unknown
TextButton_5.Text = "BLATANT"
TextButton_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_5.TextSize = 28.000

CloseGui.Name = "CloseGui"
CloseGui.Parent = Frame
CloseGui.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CloseGui.BorderColor3 = Color3.fromRGB(0, 0, 0)
CloseGui.BorderSizePixel = 0
CloseGui.Position = UDim2.new(0.848484874, 0, 0, 0)
CloseGui.Size = UDim2.new(0, 30, 0, 28)
CloseGui.Image = "rbxassetid://14297772632"

Discord.Name = "Discord"
Discord.Parent = Frame
Discord.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Discord.BorderColor3 = Color3.fromRGB(0, 0, 0)
Discord.BorderSizePixel = 0
Discord.Position = UDim2.new(0.696969688, 0, 0, 0)
Discord.Size = UDim2.new(0, 30, 0, 28)
Discord.Image = "rbxassetid://14297769031"

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(35, 35, 35)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Size = UDim2.new(0, 138, 0, 28)
TextLabel.Font = Enum.Font.Unknown
TextLabel.Text = "V6 HUB"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 26.000
TextLabel.TextWrapped = true

Extras.Name = "Extras"
Extras.Parent = Frame
Extras.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Extras.BorderColor3 = Color3.fromRGB(0, 0, 0)
Extras.BorderSizePixel = 0
Extras.Position = UDim2.new(0.767676771, 0, 0.889534891, 0)
Extras.Size = UDim2.new(0, 45, 0, 38)
Extras.Image = "rbxassetid://14298072167"

ImageLabel.Parent = Extras
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(-1.4666667, 0, 1.73684216, 0)
ImageLabel.Size = UDim2.new(0, 211, 0, 227)
ImageLabel.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

-- Scripts:

local function XJCID_fake_script() -- Extras.LocalScript 
	local script = Instance.new('LocalScript', Extras)

	script.Parent.MouseButton1Down:Connect(function()
		script.Parent.Parent.extra.Visible = true
	end)
end
coroutine.wrap(XJCID_fake_script)()
