k-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local Frame_2 = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")
local UICorner = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local Frame_3 = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local widgets = Instance.new("ImageButton")
local TextButton_2 = Instance.new("TextButton")
local dns = Instance.new("ImageButton")
local TextButton_3 = Instance.new("TextButton")
local toys = Instance.new("ImageButton")
local TextButton_4 = Instance.new("TextButton")
local accessibility = Instance.new("ImageButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(12, 0, 18)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.292293221, 0, 0.0809248537, 0)
Frame.Size = UDim2.new(0, 609, 0, 417)

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(28, 21, 46)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0.218390808, 0, 0, 0)
Frame_2.Size = UDim2.new(0, 476, 0, 417)

ImageLabel.Parent = Frame_2
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.Position = UDim2.new(0.371848732, 0, 0.105515584, 0)
ImageLabel.Size = UDim2.new(0, 100, 0, 100)
ImageLabel.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

UICorner.CornerRadius = UDim.new(0, 300)
UICorner.Parent = ImageLabel

TextLabel.Parent = Frame_2
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.266806722, 0, 0.405275792, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 50)
TextLabel.Font = Enum.Font.GothamSemibold
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 20.000

TextLabel_2.Parent = Frame_2
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.266806722, 0, 0.625899255, 0)
TextLabel_2.Size = UDim2.new(0, 200, 0, 50)
TextLabel_2.Font = Enum.Font.GothamSemibold
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 20.000

Frame_3.Parent = ScreenGui
Frame_3.BackgroundColor3 = Color3.fromRGB(28, 34, 71)
Frame_3.BorderSizePixel = 0
Frame_3.Position = UDim2.new(0.292293221, 0, 0.0809248537, 0)
Frame_3.Size = UDim2.new(0, 133, 0, 417)

TextButton.Parent = Frame_3
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.BackgroundTransparency = 1.000
TextButton.Position = UDim2.new(0.165413529, 0, 0.035971202, 0)
TextButton.Size = UDim2.new(0, 88, 0, 50)
TextButton.Font = Enum.Font.GothamSemibold
TextButton.Text = "Da Hood"
TextButton.TextColor3 = Color3.fromRGB(231, 231, 231)
TextButton.TextSize = 14.000

widgets.Name = "widgets"
widgets.Parent = TextButton
widgets.BackgroundTransparency = 1.000
widgets.Position = UDim2.new(-0.163265303, 0, 0.299999982, 0)
widgets.Size = UDim2.new(0, 22, 0, 20)
widgets.ZIndex = 2
widgets.Image = "rbxassetid://3926307971"
widgets.ImageRectOffset = Vector2.new(644, 404)
widgets.ImageRectSize = Vector2.new(36, 36)

TextButton_2.Parent = Frame_3
TextButton_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.BackgroundTransparency = 1.000
TextButton_2.Position = UDim2.new(0.165413529, 0, 0.262598991, 0)
TextButton_2.Size = UDim2.new(0, 76, 0, 29)
TextButton_2.Font = Enum.Font.GothamSemibold
TextButton_2.Text = "Server"
TextButton_2.TextColor3 = Color3.fromRGB(231, 231, 231)
TextButton_2.TextSize = 14.000

dns.Name = "dns"
dns.Parent = TextButton_2
dns.BackgroundTransparency = 1.000
dns.LayoutOrder = 6
dns.Position = UDim2.new(-0.184210539, 0, 0.120689675, 0)
dns.Size = UDim2.new(0, 23, 0, 22)
dns.ZIndex = 2
dns.Image = "rbxassetid://3926305904"
dns.ImageRectOffset = Vector2.new(444, 524)
dns.ImageRectSize = Vector2.new(36, 36)

TextButton_3.Parent = Frame_3
TextButton_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.BackgroundTransparency = 1.000
TextButton_3.Position = UDim2.new(0.165413529, 0, 0.193054631, 0)
TextButton_3.Size = UDim2.new(0, 76, 0, 29)
TextButton_3.Font = Enum.Font.GothamSemibold
TextButton_3.Text = "Aiming"
TextButton_3.TextColor3 = Color3.fromRGB(231, 231, 231)
TextButton_3.TextSize = 14.000

toys.Name = "toys"
toys.Parent = TextButton_3
toys.BackgroundTransparency = 1.000
toys.LayoutOrder = 4
toys.Position = UDim2.new(-0.184210524, 0, 0.120689645, 0)
toys.Size = UDim2.new(0, 21, 0, 21)
toys.ZIndex = 2
toys.Image = "rbxassetid://3926305904"
toys.ImageRectOffset = Vector2.new(764, 164)
toys.ImageRectSize = Vector2.new(36, 36)

TextButton_4.Parent = Frame_3
TextButton_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.BackgroundTransparency = 1.000
TextButton_4.Position = UDim2.new(0.00751879066, 0, 0.127098322, 0)
TextButton_4.Size = UDim2.new(0, 109, 0, 27)
TextButton_4.Font = Enum.Font.GothamSemibold
TextButton_4.Text = " Player"
TextButton_4.TextColor3 = Color3.fromRGB(231, 231, 231)
TextButton_4.TextSize = 14.000

accessibility.Name = "accessibility"
accessibility.Parent = TextButton_4
accessibility.BackgroundTransparency = 1.000
accessibility.LayoutOrder = 12
accessibility.Position = UDim2.new(0.0608501136, 0, 0.111111045, 0)
accessibility.Size = UDim2.new(0, 22, 0, 21)
accessibility.ZIndex = 2
accessibility.Image = "rbxassetid://3926307971"
accessibility.ImageRectOffset = Vector2.new(164, 124)
accessibility.ImageRectSize = Vector2.new(36, 36)

-- Scripts:

local function DRDB_fake_script() -- ImageLabel.LocalScript 
	local script = Instance.new('LocalScript', ImageLabel)

	local Players = game:GetService("Players")
	
	local player = Players.LocalPlayer
	
	-- Fetch the thumbnail
	local userId = player.UserId
	local thumbType = Enum.ThumbnailType.HeadShot
	local thumbSize = Enum.ThumbnailSize.Size420x420
	local content, isReady = Players:GetUserThumbnailAsync(userId, thumbType, thumbSize)
	
	-- Set the ImageLabel's content to the user thumbnail
	local imageLabel = script.Parent
	imageLabel.Image = content
end
coroutine.wrap(DRDB_fake_script)()
local function ODQY_fake_script() -- TextLabel.LocalScript 
	local script = Instance.new('LocalScript', TextLabel)

	local player = game.Players.LocalPlayer
	
	if player then 
		script.Parent.Text = ""..player.Name..""
	end
end
coroutine.wrap(ODQY_fake_script)()
