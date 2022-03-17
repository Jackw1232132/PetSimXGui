-- Gui to Lua
-- Version: 3.2

-- Instances:

local GameGui = Instance.new("ScreenGui")
local GuiFrame = Instance.new("Frame")
local Corner = Instance.new("UICorner")
local ExclusiveShop = Instance.new("TextButton")
local UIGridLayout = Instance.new("UIGridLayout")
local Golden = Instance.new("TextButton")
local Trading = Instance.new("TextButton")
local Upgrades = Instance.new("TextButton")
local Achievements = Instance.new("TextButton")
local Teleport = Instance.new("TextButton")
local FusePets = Instance.new("TextButton")
local Rainbow = Instance.new("TextButton")
local EnchantPets = Instance.new("TextButton")
local Collection = Instance.new("TextButton")
local Merchant = Instance.new("TextButton")
local DarkMatter = Instance.new("TextButton")
local Bank = Instance.new("TextButton")
local Mastery = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local GoldenKey = "C"
local TradingKey = "V"
local UpgradesKey = "B"
local AchievementsKey = "N"
local TeleportKey = "M"
local FuseKey = "L"
local RainbowKey = "K"
local ExclusiveShopKey = "J"
local EnchantKey = "H"
local CollectionKet = "G"
local MerchantKey = "P"
local DarkMatterKey = "O"
local BankKey = "I"
local MasteryKey = "U"
local Can = false
local Player = game.Players.LocalPlayer
local PlaceIdd = 6284583030


--Properties:

GameGui.Name = "GameGui"
GameGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
GameGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

GuiFrame.Name = "GuiFrame"
GuiFrame.Parent = GameGui
GuiFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
GuiFrame.BackgroundTransparency = 0.400
GuiFrame.Position = UDim2.new(0.014551322, 0, 0.60641712, 0)
GuiFrame.Size = UDim2.new(0, 327, 0, 344)

Corner.CornerRadius = UDim.new(0, 14)
Corner.Name = "Corner"
Corner.Parent = GuiFrame

ExclusiveShop.Name = "ExclusiveShop"
ExclusiveShop.Parent = GuiFrame
ExclusiveShop.BackgroundColor3 = Color3.fromRGB(173, 173, 173)
ExclusiveShop.BackgroundTransparency = 0.900
ExclusiveShop.BorderColor3 = Color3.fromRGB(0, 0, 0)
ExclusiveShop.BorderSizePixel = 3
ExclusiveShop.Size = UDim2.new(0, 163, 0, 59)
ExclusiveShop.Font = Enum.Font.FredokaOne
ExclusiveShop.Text = "Exclusive (C)"
ExclusiveShop.TextColor3 = Color3.fromRGB(208, 208, 208)
ExclusiveShop.TextScaled = true
ExclusiveShop.TextSize = 14.000
ExclusiveShop.TextWrapped = true

UIGridLayout.Parent = GuiFrame
UIGridLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIGridLayout.CellPadding = UDim2.new(0, 1, 0, 1)
UIGridLayout.CellSize = UDim2.new(0, 163, 0, 40)

Golden.Name = "Golden"
Golden.Parent = GuiFrame
Golden.BackgroundColor3 = Color3.fromRGB(173, 173, 173)
Golden.BackgroundTransparency = 0.900
Golden.BorderColor3 = Color3.fromRGB(0, 0, 0)
Golden.BorderSizePixel = 3
Golden.Size = UDim2.new(0, 163, 0, 59)
Golden.Font = Enum.Font.FredokaOne
Golden.Text = "Golden (V)"
Golden.TextColor3 = Color3.fromRGB(208, 208, 208)
Golden.TextScaled = true
Golden.TextSize = 14.000
Golden.TextWrapped = true

Trading.Name = "Trading"
Trading.Parent = GuiFrame
Trading.BackgroundColor3 = Color3.fromRGB(173, 173, 173)
Trading.BackgroundTransparency = 0.900
Trading.BorderColor3 = Color3.fromRGB(0, 0, 0)
Trading.BorderSizePixel = 3
Trading.Size = UDim2.new(0, 163, 0, 59)
Trading.Font = Enum.Font.FredokaOne
Trading.Text = "Trading (L)"
Trading.TextColor3 = Color3.fromRGB(208, 208, 208)
Trading.TextScaled = true
Trading.TextSize = 14.000
Trading.TextWrapped = true

Upgrades.Name = "Upgrades"
Upgrades.Parent = GuiFrame
Upgrades.BackgroundColor3 = Color3.fromRGB(173, 173, 173)
Upgrades.BackgroundTransparency = 0.900
Upgrades.BorderColor3 = Color3.fromRGB(0, 0, 0)
Upgrades.BorderSizePixel = 3
Upgrades.Size = UDim2.new(0, 163, 0, 59)
Upgrades.Font = Enum.Font.FredokaOne
Upgrades.Text = "Upgrades (N)"
Upgrades.TextColor3 = Color3.fromRGB(208, 208, 208)
Upgrades.TextScaled = true
Upgrades.TextSize = 14.000
Upgrades.TextWrapped = true

Achievements.Name = "Achievements"
Achievements.Parent = GuiFrame
Achievements.BackgroundColor3 = Color3.fromRGB(173, 173, 173)
Achievements.BackgroundTransparency = 0.900
Achievements.BorderColor3 = Color3.fromRGB(0, 0, 0)
Achievements.BorderSizePixel = 3
Achievements.Size = UDim2.new(0, 163, 0, 59)
Achievements.Font = Enum.Font.FredokaOne
Achievements.Text = "Achievements (U)"
Achievements.TextColor3 = Color3.fromRGB(208, 208, 208)
Achievements.TextScaled = true
Achievements.TextSize = 14.000
Achievements.TextWrapped = true

Teleport.Name = "Teleport"
Teleport.Parent = GuiFrame
Teleport.BackgroundColor3 = Color3.fromRGB(173, 173, 173)
Teleport.BackgroundTransparency = 0.900
Teleport.BorderColor3 = Color3.fromRGB(0, 0, 0)
Teleport.BorderSizePixel = 3
Teleport.Size = UDim2.new(0, 163, 0, 59)
Teleport.Font = Enum.Font.FredokaOne
Teleport.Text = "Teleport (B)"
Teleport.TextColor3 = Color3.fromRGB(208, 208, 208)
Teleport.TextScaled = true
Teleport.TextSize = 14.000
Teleport.TextWrapped = true

FusePets.Name = "FusePets"
FusePets.Parent = GuiFrame
FusePets.BackgroundColor3 = Color3.fromRGB(173, 173, 173)
FusePets.BackgroundTransparency = 0.900
FusePets.BorderColor3 = Color3.fromRGB(0, 0, 0)
FusePets.BorderSizePixel = 3
FusePets.Size = UDim2.new(0, 163, 0, 59)
FusePets.Font = Enum.Font.FredokaOne
FusePets.Text = "Fuse (K)"
FusePets.TextColor3 = Color3.fromRGB(208, 208, 208)
FusePets.TextScaled = true
FusePets.TextSize = 14.000
FusePets.TextWrapped = true

Rainbow.Name = "Rainbow (M)"
Rainbow.Parent = GuiFrame
Rainbow.BackgroundColor3 = Color3.fromRGB(173, 173, 173)
Rainbow.BackgroundTransparency = 0.900
Rainbow.BorderColor3 = Color3.fromRGB(0, 0, 0)
Rainbow.BorderSizePixel = 3
Rainbow.Size = UDim2.new(0, 163, 0, 59)
Rainbow.Font = Enum.Font.FredokaOne
Rainbow.Text = "Rainbow (P)"
Rainbow.TextColor3 = Color3.fromRGB(208, 208, 208)
Rainbow.TextScaled = true
Rainbow.TextSize = 14.000
Rainbow.TextWrapped = true

EnchantPets.Name = "EnchantPets"
EnchantPets.Parent = GuiFrame
EnchantPets.BackgroundColor3 = Color3.fromRGB(173, 173, 173)
EnchantPets.BackgroundTransparency = 0.900
EnchantPets.BorderColor3 = Color3.fromRGB(0, 0, 0)
EnchantPets.BorderSizePixel = 3
EnchantPets.Size = UDim2.new(0, 163, 0, 59)
EnchantPets.Font = Enum.Font.FredokaOne
EnchantPets.Text = "Enchant (P)"
EnchantPets.TextColor3 = Color3.fromRGB(208, 208, 208)
EnchantPets.TextScaled = true
EnchantPets.TextSize = 14.000
EnchantPets.TextWrapped = true

Collection.Name = "Collection"
Collection.Parent = GuiFrame
Collection.BackgroundColor3 = Color3.fromRGB(173, 173, 173)
Collection.BackgroundTransparency = 0.900
Collection.BorderColor3 = Color3.fromRGB(0, 0, 0)
Collection.BorderSizePixel = 3
Collection.Size = UDim2.new(0, 163, 0, 59)
Collection.Font = Enum.Font.FredokaOne
Collection.Text = "Collection (J)"
Collection.TextColor3 = Color3.fromRGB(208, 208, 208)
Collection.TextScaled = true
Collection.TextSize = 14.000
Collection.TextWrapped = true

Merchant.Name = "Merchant"
Merchant.Parent = GuiFrame
Merchant.BackgroundColor3 = Color3.fromRGB(173, 173, 173)
Merchant.BackgroundTransparency = 0.900
Merchant.BorderColor3 = Color3.fromRGB(0, 0, 0)
Merchant.BorderSizePixel = 3
Merchant.Size = UDim2.new(0, 163, 0, 59)
Merchant.Font = Enum.Font.FredokaOne
Merchant.Text = "Merchant (T)"
Merchant.TextColor3 = Color3.fromRGB(208, 208, 208)
Merchant.TextScaled = true
Merchant.TextSize = 14.000
Merchant.TextWrapped = true

DarkMatter.Name = "DarkMatter"
DarkMatter.Parent = GuiFrame
DarkMatter.BackgroundColor3 = Color3.fromRGB(173, 173, 173)
DarkMatter.BackgroundTransparency = 0.900
DarkMatter.BorderColor3 = Color3.fromRGB(0, 0, 0)
DarkMatter.BorderSizePixel = 3
DarkMatter.Size = UDim2.new(0, 163, 0, 59)
DarkMatter.Font = Enum.Font.FredokaOne
DarkMatter.Text = "Dark Matter (H)"
DarkMatter.TextColor3 = Color3.fromRGB(208, 208, 208)
DarkMatter.TextScaled = true
DarkMatter.TextSize = 14.000
DarkMatter.TextWrapped = true

Bank.Name = "Bank"
Bank.Parent = GuiFrame
Bank.BackgroundColor3 = Color3.fromRGB(173, 173, 173)
Bank.BackgroundTransparency = 0.900
Bank.BorderColor3 = Color3.fromRGB(0, 0, 0)
Bank.BorderSizePixel = 3
Bank.Size = UDim2.new(0, 163, 0, 59)
Bank.Font = Enum.Font.FredokaOne
Bank.Text = "Bank (Z)"
Bank.TextColor3 = Color3.fromRGB(208, 208, 208)
Bank.TextScaled = true
Bank.TextSize = 14.000
Bank.TextWrapped = true

Mastery.Name = "Mastery"
Mastery.Parent = GuiFrame
Mastery.BackgroundColor3 = Color3.fromRGB(173, 173, 173)
Mastery.BackgroundTransparency = 0.900
Mastery.BorderColor3 = Color3.fromRGB(0, 0, 0)
Mastery.BorderSizePixel = 3
Mastery.Size = UDim2.new(0, 163, 0, 59)
Mastery.Font = Enum.Font.FredokaOne
Mastery.Text = "Mastery (Y)"
Mastery.TextColor3 = Color3.fromRGB(208, 208, 208)
Mastery.TextScaled = true
Mastery.TextSize = 14.000
Mastery.TextWrapped = true

for i,Button in pairs(GuiFrame:GetChildren()) do
	if Button:IsA("TextButton") then
		Button.MouseButton1Click:Connect(function()
			if Can == false then
				Can = true
				Player.PlayerGui:FindFirstChild(Button.Name).Enabled = true
				wait(0.1)
				Can = false
			end
		end)
	end
end

Player:GetMouse().KeyDown:Connect(function(Key)
	if Key == "z" then
		Player.PlayerGui.Bank.Enabled = true
	else
		if Key == "c" then
			Player.PlayerGui.ExclusiveShop.Enabled = true
		else
			if Key == "v" then
				Player.PlayerGui.Golden.Enabled = true
			else
				if Key == "b" then
					Player.PlayerGui.Teleport.Enabled = true
				else
					if Key == "n" then
						Player.PlayerGui.Upgrades.Enabled = true
					else
						if Key == "m" then
							Player.PlayerGui.Rainbow.Enabled = true
						else
							if Key == "l" then
								Player.PlayerGui.Trading.Enabled = true
							else
								if Key == "k" then
									Player.PlayerGui.FusePets.Enabled = true
								else
									if Key == "j" then
										Player.PlayerGui.Collection.Enabled = true
									else
										if Key == "h" then
											Player.PlayerGui.DarkMatter.Enabled = true
										else
											if Key == "p" then
												Player.PlayerGui.EnchantPets.Enabled = true
											else
												if Key == "t" then
													Player.PlayerGui.Merchant.Enabled = true
												else
													if Key == "u" then
														Player.PlayerGui.Achievements.Enabled = true
													else
														if Key == "y" then
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
				end
			end
		end
	end
end)

Player.Chatted:Connect(function(Msg)
	for i, Gui in pairs(Player.PlayerGui:GetChildren()) do
		if Gui:IsA("ScreenGui") then
			if Gui.Name == Msg then
				Gui.Enabled = true
			end
		end
	end
end)
