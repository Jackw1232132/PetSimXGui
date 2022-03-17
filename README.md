-- Gui to Lua
-- Version: 3.2

-- Instances:

local GameGui = Instance.new("ScreenGui")
local GameFrame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Main = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local Title = Instance.new("TextLabel")
local MainFrame = Instance.new("Frame")
local Bank = Instance.new("TextButton")
local Collection = Instance.new("TextButton")
local DarkMatter = Instance.new("TextButton")
local EnchantPets = Instance.new("TextButton")
local FusePets = Instance.new("TextButton")
local Golden = Instance.new("TextButton")
local Merchant = Instance.new("TextButton")
local Rainbow = Instance.new("TextButton")
local MainGrid = Instance.new("UIGridLayout")
local Upgrades = Instance.new("TextButton")
local Mastery = Instance.new("TextButton")
local Open = Instance.new("TextButton")
local Close = Instance.new("TextButton")
local PlayerList = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local Main_2 = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local Title_2 = Instance.new("TextLabel")
local List = Instance.new("ScrollingFrame")
local ListTemplate = Instance.new("Frame")
local Avatar = Instance.new("ImageLabel")
local PlayerName = Instance.new("TextLabel")
local PlayerDisplayName = Instance.new("TextLabel")
local UIGridLayout = Instance.new("UIGridLayout")
local Player = game.Players.LocalPlayer
local Ready = false
local Can = false

--Properties:

GameGui.Name = "GameGui"
GameGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
GameGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

GameFrame.Name = "GameFrame"
GameFrame.Parent = GameGui
GameFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
GameFrame.BackgroundTransparency = 0.300
GameFrame.Position = UDim2.new(0.0185933709, 0, 0.695187151, 0)
GameFrame.Size = UDim2.new(0, 257, 0, 257)

UICorner.Parent = GameFrame

Main.Name = "Main"
Main.Parent = GameFrame
Main.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Main.BackgroundTransparency = 0.200
Main.Size = UDim2.new(0, 257, 0, 39)

UICorner_2.Parent = Main

Title.Name = "Title"
Title.Parent = Main
Title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title.BackgroundTransparency = 1.000
Title.Size = UDim2.new(0, 257, 0, 39)
Title.Font = Enum.Font.FredokaOne
Title.Text = "Gui"
Title.TextColor3 = Color3.fromRGB(85, 255, 127)
Title.TextScaled = true
Title.TextSize = 14.000
Title.TextWrapped = true

MainFrame.Name = "MainFrame"
MainFrame.Parent = GameFrame
MainFrame.BackgroundColor3 = Color3.fromRGB(118, 118, 118)
MainFrame.BackgroundTransparency = 0.100
MainFrame.BorderSizePixel = 0
MainFrame.Position = UDim2.new(0, 0, 0.151750967, 0)
MainFrame.Size = UDim2.new(0, 256, 0, 180)

Bank.Name = "Bank"
Bank.Parent = MainFrame
Bank.BackgroundColor3 = Color3.fromRGB(2, 2, 2)
Bank.BackgroundTransparency = 0.300
Bank.BorderSizePixel = 2
Bank.Position = UDim2.new(0.5, 0, 0.200000003, 0)
Bank.Size = UDim2.new(0, 128, 0, 36)
Bank.Font = Enum.Font.FredokaOne
Bank.Text = "Bank (Z)"
Bank.TextColor3 = Color3.fromRGB(255, 255, 255)
Bank.TextScaled = true
Bank.TextSize = 14.000
Bank.TextWrapped = true

Collection.Name = "Collection"
Collection.Parent = MainFrame
Collection.BackgroundColor3 = Color3.fromRGB(2, 2, 2)
Collection.BackgroundTransparency = 0.300
Collection.BorderSizePixel = 2
Collection.Position = UDim2.new(0.5, 0, 0.400000006, 0)
Collection.Size = UDim2.new(0, 128, 0, 36)
Collection.Font = Enum.Font.FredokaOne
Collection.Text = "Collection (C)"
Collection.TextColor3 = Color3.fromRGB(255, 255, 255)
Collection.TextScaled = true
Collection.TextSize = 14.000
Collection.TextWrapped = true

DarkMatter.Name = "DarkMatter"
DarkMatter.Parent = MainFrame
DarkMatter.BackgroundColor3 = Color3.fromRGB(2, 2, 2)
DarkMatter.BackgroundTransparency = 0.300
DarkMatter.BorderSizePixel = 2
DarkMatter.Position = UDim2.new(0.5, 0, 0.600000024, 0)
DarkMatter.Size = UDim2.new(0, 128, 0, 36)
DarkMatter.Font = Enum.Font.FredokaOne
DarkMatter.Text = "DarkMatter (V)"
DarkMatter.TextColor3 = Color3.fromRGB(255, 255, 255)
DarkMatter.TextScaled = true
DarkMatter.TextSize = 14.000
DarkMatter.TextWrapped = true

EnchantPets.Name = "EnchantPets"
EnchantPets.Parent = MainFrame
EnchantPets.BackgroundColor3 = Color3.fromRGB(2, 2, 2)
EnchantPets.BackgroundTransparency = 0.300
EnchantPets.BorderSizePixel = 2
EnchantPets.Position = UDim2.new(0.5, 0, 0.800000012, 0)
EnchantPets.Size = UDim2.new(0, 128, 0, 36)
EnchantPets.Font = Enum.Font.FredokaOne
EnchantPets.Text = "Enchant (B)"
EnchantPets.TextColor3 = Color3.fromRGB(255, 255, 255)
EnchantPets.TextScaled = true
EnchantPets.TextSize = 14.000
EnchantPets.TextWrapped = true

FusePets.Name = "FusePets"
FusePets.Parent = MainFrame
FusePets.BackgroundColor3 = Color3.fromRGB(2, 2, 2)
FusePets.BackgroundTransparency = 0.300
FusePets.BorderSizePixel = 2
FusePets.Position = UDim2.new(0, 0, 0.199999988, 0)
FusePets.Size = UDim2.new(0, 128, 0, 36)
FusePets.Font = Enum.Font.FredokaOne
FusePets.Text = "Fuse (N)"
FusePets.TextColor3 = Color3.fromRGB(255, 255, 255)
FusePets.TextScaled = true
FusePets.TextSize = 14.000
FusePets.TextWrapped = true

Golden.Name = "Golden"
Golden.Parent = MainFrame
Golden.BackgroundColor3 = Color3.fromRGB(2, 2, 2)
Golden.BackgroundTransparency = 0.300
Golden.BorderSizePixel = 2
Golden.Position = UDim2.new(0, 0, 0.399999976, 0)
Golden.Size = UDim2.new(0, 128, 0, 36)
Golden.Font = Enum.Font.FredokaOne
Golden.Text = "Golden (M)"
Golden.TextColor3 = Color3.fromRGB(255, 255, 255)
Golden.TextScaled = true
Golden.TextSize = 14.000
Golden.TextWrapped = true

Merchant.Name = "Merchant"
Merchant.Parent = MainFrame
Merchant.BackgroundColor3 = Color3.fromRGB(2, 2, 2)
Merchant.BackgroundTransparency = 0.300
Merchant.BorderSizePixel = 2
Merchant.Position = UDim2.new(0, 0, 0.799999952, 0)
Merchant.Size = UDim2.new(0, 128, 0, 36)
Merchant.Font = Enum.Font.FredokaOne
Merchant.Text = "Merchant (L)"
Merchant.TextColor3 = Color3.fromRGB(255, 255, 255)
Merchant.TextScaled = true
Merchant.TextSize = 14.000
Merchant.TextWrapped = true

Rainbow.Name = "Rainbow"
Rainbow.Parent = MainFrame
Rainbow.BackgroundColor3 = Color3.fromRGB(2, 2, 2)
Rainbow.BackgroundTransparency = 0.300
Rainbow.BorderSizePixel = 2
Rainbow.Size = UDim2.new(0, 128, 0, 36)
Rainbow.Font = Enum.Font.FredokaOne
Rainbow.Text = "Rainbow (K)"
Rainbow.TextColor3 = Color3.fromRGB(255, 255, 255)
Rainbow.TextScaled = true
Rainbow.TextSize = 14.000
Rainbow.TextWrapped = true

MainGrid.Name = "MainGrid"
MainGrid.Parent = MainFrame
MainGrid.SortOrder = Enum.SortOrder.LayoutOrder
MainGrid.CellPadding = UDim2.new(0, 0, 0, 0)
MainGrid.CellSize = UDim2.new(0, 128, 0, 36)

Upgrades.Name = "Upgrades"
Upgrades.Parent = MainFrame
Upgrades.BackgroundColor3 = Color3.fromRGB(2, 2, 2)
Upgrades.BackgroundTransparency = 0.300
Upgrades.BorderSizePixel = 2
Upgrades.Position = UDim2.new(0, 0, 0.199999988, 0)
Upgrades.Size = UDim2.new(0, 128, 0, 36)
Upgrades.Font = Enum.Font.FredokaOne
Upgrades.Text = "Upgrades (J)"
Upgrades.TextColor3 = Color3.fromRGB(255, 255, 255)
Upgrades.TextScaled = true
Upgrades.TextSize = 14.000
Upgrades.TextWrapped = true

Mastery.Name = "Mastery"
Mastery.Parent = MainFrame
Mastery.BackgroundColor3 = Color3.fromRGB(2, 2, 2)
Mastery.BackgroundTransparency = 0.300
Mastery.BorderSizePixel = 2
Mastery.Position = UDim2.new(0, 0, 0.199999988, 0)
Mastery.Size = UDim2.new(0, 128, 0, 36)
Mastery.Font = Enum.Font.FredokaOne
Mastery.Text = "Mastery (P)"
Mastery.TextColor3 = Color3.fromRGB(255, 255, 255)
Mastery.TextScaled = true
Mastery.TextSize = 14.000
Mastery.TextWrapped = true

Open.Name = "Open"
Open.Parent = GameFrame
Open.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Open.BackgroundTransparency = 1.000
Open.Position = UDim2.new(0, 0, 0.852140069, 0)
Open.Size = UDim2.new(0, 128, 0, 38)
Open.Font = Enum.Font.FredokaOne
Open.Text = "Open"
Open.TextColor3 = Color3.fromRGB(85, 255, 127)
Open.TextScaled = true
Open.TextSize = 14.000
Open.TextTransparency = 0.200
Open.TextWrapped = true

Close.Name = "Close"
Close.Parent = GameFrame
Close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Close.BackgroundTransparency = 1.000
Close.Position = UDim2.new(0.501945496, 0, 0.852140069, 0)
Close.Size = UDim2.new(0, 128, 0, 38)
Close.Font = Enum.Font.FredokaOne
Close.Text = "Close"
Close.TextColor3 = Color3.fromRGB(255, 0, 0)
Close.TextScaled = true
Close.TextSize = 14.000
Close.TextTransparency = 0.200
Close.TextWrapped = true

PlayerList.Name = "PlayerList"
PlayerList.Parent = GameGui
PlayerList.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
PlayerList.BackgroundTransparency = 0.300
PlayerList.Position = UDim2.new(0.0172736347, 0, 0.40427807, 0)
PlayerList.Size = UDim2.new(0, 257, 0, 257)
PlayerList.Active = true
PlayerList.Draggable = true

UICorner_3.Parent = PlayerList

Main_2.Name = "Main"
Main_2.Parent = PlayerList
Main_2.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Main_2.BackgroundTransparency = 0.200
Main_2.Size = UDim2.new(0, 257, 0, 39)

UICorner_4.Parent = Main_2

Title_2.Name = "Title"
Title_2.Parent = Main_2
Title_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_2.BackgroundTransparency = 1.000
Title_2.Size = UDim2.new(0, 257, 0, 39)
Title_2.Font = Enum.Font.FredokaOne
Title_2.Text = "PlayerList"
Title_2.TextColor3 = Color3.fromRGB(85, 255, 127)
Title_2.TextScaled = true
Title_2.TextSize = 14.000
Title_2.TextWrapped = true

List.Name = "List"
List.Parent = PlayerList
List.Active = true
List.BackgroundColor3 = Color3.fromRGB(190, 190, 190)
List.BackgroundTransparency = 0.300
List.BorderSizePixel = 0
List.Position = UDim2.new(0, 0, 0.151750967, 0)
List.Size = UDim2.new(0, 256, 0, 203)
List.ScrollBarThickness = 9

ListTemplate.Name = "ListTemplate"
ListTemplate.Parent = List
ListTemplate.BackgroundColor3 = Color3.fromRGB(58, 58, 58)
ListTemplate.BackgroundTransparency = 0.300
ListTemplate.Size = UDim2.new(0, 247, 0, 38)
ListTemplate.Visible = false

Avatar.Name = "Avatar"
Avatar.Parent = ListTemplate
Avatar.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Avatar.BackgroundTransparency = 1.000
Avatar.Size = UDim2.new(0, 56, 0, 38)
Avatar.Image = "rbxasset://textures/ui/GuiImagePlaceholder.png"

PlayerName.Name = "PlayerName"
PlayerName.Parent = ListTemplate
PlayerName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlayerName.BackgroundTransparency = 1.000
PlayerName.Position = UDim2.new(0.226720646, 0, 0, 0)
PlayerName.Size = UDim2.new(0, 191, 0, 19)
PlayerName.Font = Enum.Font.FredokaOne
PlayerName.Text = "Roblox_Wmh"
PlayerName.TextColor3 = Color3.fromRGB(255, 170, 0)
PlayerName.TextScaled = true
PlayerName.TextSize = 14.000
PlayerName.TextWrapped = true

PlayerDisplayName.Name = "PlayerDisplayName"
PlayerDisplayName.Parent = ListTemplate
PlayerDisplayName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlayerDisplayName.BackgroundTransparency = 1.000
PlayerDisplayName.Position = UDim2.new(0.226720646, 0, 0.5, 0)
PlayerDisplayName.Size = UDim2.new(0, 191, 0, 19)
PlayerDisplayName.Font = Enum.Font.FredokaOne
PlayerDisplayName.Text = "@Roblox_Wmh"
PlayerDisplayName.TextColor3 = Color3.fromRGB(255, 170, 0)
PlayerDisplayName.TextScaled = true
PlayerDisplayName.TextSize = 14.000
PlayerDisplayName.TextWrapped = true

UIGridLayout.Parent = List
UIGridLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout.CellPadding = UDim2.new(0, 0, 0, 0)
UIGridLayout.CellSize = UDim2.new(0, 247, 0, 38)

Open.MouseButton1Click:Connect(function()
	Ready = false
end)

Close.MouseButton1Click:Connect(function()
	Ready = true
	for i,v in pairs(Player.PlayerGui:GetChildren()) do
		for i,a in pairs(MainFrame:GetChildren()) do
			if v.Name == a.Name and v.Enabled == true then
				v.Enabled = false
			end
		end
	end
end)

for i, Button in pairs(MainFrame:GetChildren()) do
	if Button:IsA("TextButton") then
		Button.MouseButton1Click:Connect(function()
			if Ready == false then
				Player.PlayerGui:FindFirstChild(Button.Name).Enabled = true
			end
		end)
	end
end

Player:GetMouse().KeyDown:Connect(function(Key)
	if Key == "z" and Ready == false then
		Player.PlayerGui.Bank.Enabled = true
	else
		if Key == "c" and Ready == false then
			Player.PlayerGui.Collection.Enabled = true
		else
			if Key == "v" and Ready == false then
				Player.PlayerGui.DarkMatter.Enabled = true
			else
				if Key == "b" and Ready == false then
					Player.PlayerGui.EnchantPets.Enabled = true
				else
					if Key == "n" and Ready == false then
						Player.PlayerGui.FusePets.Enabled = true
					else
						if Key == "m" and Ready == false then
							Player.PlayerGui.Golden.Enabled = true
						else
							if Key == "l" and Ready == false then
								Player.PlayerGui.Merchant.Enabled = true
							else
								if Key == "k" and Ready == false then
									Player.PlayerGui.Rainbow.Enabled = true
								else
									if Key == "j" and Ready == false then
										Player.PlayerGui.Upgrades.Enabled = true
									else
										if Key == "p" and Ready == false then
											Player.PlayerGui.Mastery.Enabled = true
										end
									end
								end
							end
						end
					end
				end
			end
		end
	end
end)

function  Clear ()
	for i,Frame in pairs(List:GetChildren()) do
		if Frame:IsA("Frame") then
			Frame:Destroy()
		end
	end
end

function  FillUp ()
	Clear()
	for i, Player1 in pairs(game.Players:GetChildren()) do
		ListTemplate:Destroy()
		local A = ListTemplate:Clone()
		local B = Avatar:Clone()
		local C = PlayerName:Clone()
		local D = PlayerDisplayName:Clone()
		A.Parent = List
		A.Visible = true
		B.Parent = A
		local userId = Player1.UserId
		local thumbtype = Enum.ThumbnailType.HeadShot
		local thumbsize = Enum.ThumbnailSize.Size420x420
		local content,isReady = game.Players:GetUserThumbnailAsync(userId,thumbtype,thumbsize)
		B.Image = content
		C.Parent = A
		C.Text =  Player1.DisplayName
		D.Parent = A
		D.Text = "@" .. Player1.Name
	end
end

FillUp()

while wait(0.1) do
	FillUp()
end
