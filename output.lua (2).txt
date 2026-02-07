-- [CRYPTA] this script was environment logged @ discord.gg/rY4TYaEPNY
local RunService1 = game:GetService("RunService")
local UserInputService1 = game:GetService("UserInputService")
local TweenService1 = game:GetService("TweenService")
local Players1 = game:GetService("Players")
local Animation1 = Instance.new('Animation')
local Animation2 = Instance.new('Animation')
local Animation3 = Instance.new('Animation')
local Animation4 = Instance.new('Animation')
Animation1.AnimationId = "rbxassetid://718076987"
Animation2.AnimationId = "rbxassetid://92365791487740"
Animation3.AnimationId = "rbxassetid://85064366773524"
Animation4.AnimationId = "rbxassetid://11394033602"
RunService1.Heartbeat:Connect(function()
-- error: ./input.lua:911: attempt to perform arithmetic (mul) on number and nil
end)
RunService1.Heartbeat:Connect(function()
tick.tick()
-- error: ./input.lua:911: attempt to perform arithmetic (sub) on table and number
end)
isfolder("InvincibleFly")
makefolder("InvincibleFly")
isfile("InvincibleFly/settings.json")
local ScreenGui1 = Instance.new('ScreenGui')
ScreenGui1.Name = "FlightAnimationUI"
ScreenGui1.ResetOnSpawn = false
Players1.LocalPlayer:WaitForChild({
    WaitForChild = { }
}, "PlayerGui")
ScreenGui1.Parent = { }
local ImageButton1 = Instance.new('ImageButton')
ImageButton1.Name = "AnimToggleButton"
ImageButton1.Size = UDim2.new(0, 60, 0, 60)
ImageButton1.Position = UDim2.new(1, -70, 0, 20)
ImageButton1.AnchorPoint = Vector2.new(1, 0)
ImageButton1.BackgroundColor3 = Color3.fromRGB(90, 50, 140)
ImageButton1.BackgroundTransparency = 0.1
ImageButton1.Image = "rbxassetid://135684785837881"
ImageButton1.ScaleType = { }
ImageButton1.ImageColor3 = Color3.fromRGB(240, 200, 255)
ImageButton1.AutoButtonColor = false
ImageButton1.Parent = ScreenGui1
local UIGradient1 = Instance.new('UIGradient')
UIGradient1.Color = ColorSequence({'soon'})
UIGradient1.Rotation = 45
UIGradient1.Parent = ImageButton1
TweenInfo:new(4, { }, { }, -1, true)
TweenService1:Create(TweenService1, UIGradient1, { }, {
    Rotation = 405
})
TweenService1.Create:Play({
    Play = { }
})
local ImageLabel1 = Instance.new('ImageLabel')
ImageLabel1.Name = "Glow"
ImageLabel1.Size = UDim2.new(1, 20, 1, 20)
ImageLabel1.Position = UDim2.new(0, -10, 0, -10)
ImageLabel1.BackgroundTransparency = 1
ImageLabel1.Image = "rbxassetid://5028857084"
ImageLabel1.ImageColor3 = Color3.fromRGB(160, 100, 220)
ImageLabel1.ImageTransparency = 0.6
ImageLabel1.ScaleType = { }
Rect:new(24, 24, 276, 276)
ImageLabel1.SliceCenter = { }
ImageLabel1.ZIndex = -1
ImageLabel1.Parent = UIGradient1.Parent
TweenInfo:new(2, { }, { }, -1, true)
TweenService1:Create(TweenService1, ImageLabel1, { }, {
    ImageTransparency = 0.4
})
TweenService1.Create:Play({
    Play = { }
})
local UICorner1 = Instance.new('UICorner')
UICorner1.CornerRadius = UDim.new(0.5, 0)
UICorner1.Parent = ImageLabel1.Parent
TweenInfo:new(2, { }, { }, -1, true)
TweenService1:Create(TweenService1, UICorner1.Parent, { }, {
    Size = UDim2.new(0, 62, 0, 62)
})
TweenService1.Create:Play({
    Play = { }
})
local Frame1 = Instance.new('Frame')
Frame1.Name = "MainFrame"
Frame1.Size = UDim2.new(0.8, 0, 0.7, 0)
Frame1.Position = UDim2.new(0.5, 0, 0.5, 0)
Frame1.AnchorPoint = Vector2.new(0.5, 0.5)
Frame1.BackgroundColor3 = Color3.fromRGB(10, 5, 20)
Frame1.BackgroundTransparency = 0.1
Frame1.BorderSizePixel = 0
Frame1.ClipsDescendants = true
Frame1.Visible = false
Frame1.Parent = ImageButton1.Parent
local UIGradient2 = Instance.new('UIGradient')
UIGradient2.Color = ColorSequence({'soon'})
UIGradient2.Rotation = 90
UIGradient2.Parent = Frame1
TweenInfo:new(8, { }, { }, -1, true)
TweenService1:Create(TweenService1, UIGradient2, { }, {
    Rotation = 450
})
TweenService1.Create:Play({
    Play = { }
})
local UICorner2 = Instance.new('UICorner')
UICorner2.CornerRadius = UDim.new(0, 15)
UICorner2.Parent = UIGradient2.Parent
local Frame2 = Instance.new('Frame')
Frame2.Name = "Border"
Frame2.Size = UDim2.new(1, 6, 1, 6)
Frame2.Position = UDim2.new(0, -3, 0, -3)
Frame2.BackgroundTransparency = 1
Frame2.ZIndex = -1
Frame2.Parent = UICorner2.Parent
local UIGradient3 = Instance.new('UIGradient')
UIGradient3.Color = ColorSequence({'soon'})
UIGradient3.Rotation = 0
UIGradient3.Parent = Frame2
TweenInfo:new(4, { }, { }, -1, true)
TweenService1:Create(TweenService1, UIGradient3, { }, {
    Rotation = 360
})
TweenService1.Create:Play({
    Play = { }
})
local Frame3 = Instance.new('Frame')
Frame3.Name = "TitleBar"
Frame3.Size = UDim2.new(1, 0, 0.1, 0)
Frame3.Position = UDim2.new(0, 0, 0, 0)
Frame3.BackgroundColor3 = Color3.fromRGB(25, 15, 40)
Frame3.BackgroundTransparency = 0.2
Frame3.BorderSizePixel = 0
Frame3.Parent = Frame2.Parent
local UICorner3 = Instance.new('UICorner')
UICorner3.CornerRadius = UDim.new(0, 15)
UICorner3.Parent = Frame3
local TextLabel1 = Instance.new('TextLabel')
TextLabel1.Name = "Title"
TextLabel1.Size = UDim2.new(0.7, 0, 0.8, 0)
TextLabel1.Position = UDim2.new(0.05, 0, 0.1, 0)
TextLabel1.BackgroundTransparency = 1
TextLabel1.Text = "ANIMATIONS & SETTINGS"
TextLabel1.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel1.TextScaled = true
TextLabel1.Font = { }
TextLabel1.TextXAlignment = { }
TextLabel1.Parent = UICorner3.Parent
local ImageButton2 = Instance.new('ImageButton')
ImageButton2.Name = "LockButton"
ImageButton2.Size = UDim2.new(0.1, 0, 0.7, 0)
ImageButton2.Position = UDim2.new(0.88, 0, 0.15, 0)
ImageButton2.BackgroundColor3 = Color3.fromRGB(80, 40, 120)
ImageButton2.BackgroundTransparency = 0.1
ImageButton2.Image = "rbxassetid://4772171909"
ImageButton2.ScaleType = ImageButton1.ScaleType
ImageButton2.ImageColor3 = Color3.fromRGB(200, 150, 255)
ImageButton2.Parent = TextLabel1.Parent
local Frame4 = Instance.new('Frame')
Frame4.Name = "RedOverlay"
Frame4.Size = UDim2.new(1, 0, 1, 0)
Frame4.BackgroundColor3 = Color3.fromRGB(255, 100, 100)
Frame4.BackgroundTransparency = 1
Frame4.BorderSizePixel = 0
Frame4.Parent = ImageButton2
local UICorner4 = Instance.new('UICorner')
UICorner4.CornerRadius = UDim.new(0.3, 0)
UICorner4.Parent = Frame4.Parent
local TextButton1 = Instance.new('TextButton')
TextButton1.Name = "CloseButton"
TextButton1.Size = UDim2.new(0.1, 0, 0.7, 0)
TextButton1.Position = UDim2.new(0.77, 0, 0.15, 0)
TextButton1.BackgroundColor3 = Color3.fromRGB(130, 80, 180)
TextButton1.BackgroundTransparency = 0.1
TextButton1.Text = "X"
TextButton1.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton1.TextSize = 16
TextButton1.Font = { }
TextButton1.Parent = ImageButton2.Parent
local UICorner5 = Instance.new('UICorner')
UICorner5.CornerRadius = UDim.new(0.5, 0)
UICorner5.Parent = TextButton1
local UICorner6 = Instance.new('UICorner')
UICorner6.CornerRadius = UDim.new(0, 8)
UICorner6.Parent = nil
local TextButton2 = Instance.new('TextButton')
TextButton2.Name = "ButtonThemesTab"
TextButton2.Size = UDim2.new(0.3, 0, 1, 0)
TextButton2.Position = UDim2.new(0.35, 0, 0, 0)
TextButton2.BackgroundColor3 = Color3.fromRGB(60, 30, 90)
TextButton2.BackgroundTransparency = 0.3
TextButton2.Text = "BUTTON THEMES"
TextButton2.TextColor3 = Color3.fromRGB(200, 200, 200)
TextButton2.TextSize = 12
TextButton2.Font = TextButton1.Font
TextButton2.Parent = nil
local UICorner7 = Instance.new('UICorner')
UICorner7.CornerRadius = UDim.new(0, 8)
UICorner7.Parent = TextButton2
local TextButton3 = Instance.new('TextButton')
TextButton3.Name = "GUIThemesTab"
TextButton3.Size = UDim2.new(0.3, 0, 1, 0)
TextButton3.Position = UDim2.new(0.7, 0, 0, 0)
TextButton3.BackgroundColor3 = Color3.fromRGB(60, 30, 90)
TextButton3.BackgroundTransparency = 0.3
TextButton3.Text = "GUI THEMES"
TextButton3.TextColor3 = Color3.fromRGB(200, 200, 200)
TextButton3.TextSize = 12
TextButton3.Font = TextButton2.Font
TextButton3.Parent = nil
local UICorner8 = Instance.new('UICorner')
UICorner8.CornerRadius = UDim.new(0, 8)
UICorner8.Parent = TextButton3
local Frame5 = Instance.new('Frame')
Frame5.Name = "TabContainer"
Frame5.Size = UDim2.new(1, -20, 0.08, 0)
Frame5.Position = UDim2.new(0, 10, 0.9, 0)
Frame5.BackgroundTransparency = 1
Frame5.Parent = Frame3.Parent
local TextButton4 = Instance.new('TextButton')
TextButton4.Name = "AnimationsTab"
TextButton4.Size = UDim2.new(0.235, 0, 1, 0)
TextButton4.Position = UDim2.new(0, 0, 0, 0)
TextButton4.BackgroundColor3 = Color3.fromRGB(80, 40, 120)
TextButton4.BackgroundTransparency = 0.1
TextButton4.Text = "ANIMATIONS"
TextButton4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton4.TextSize = 12
TextButton4.Font = TextButton3.Font
TextButton4.Parent = Frame5
local UICorner9 = Instance.new('UICorner')
UICorner9.CornerRadius = UDim.new(0, 8)
local TextButton5 = Instance.new('TextButton')
TextButton5.Name = "ButtonThemesTab"
TextButton5.Size = UDim2.new(0.235, 0, 1, 0)
TextButton5.Position = UDim2.new(0.255, 0, 0, 0)
TextButton5.BackgroundColor3 = Color3.fromRGB(60, 30, 90)
TextButton5.BackgroundTransparency = 0.3
TextButton5.Text = "BUTTON THEMES"
TextButton5.TextColor3 = Color3.fromRGB(200, 200, 200)
TextButton5.TextSize = 12
TextButton5.Font = TextButton4.Font
TextButton5.Parent = TextButton4.Parent
local UICorner10 = Instance.new('UICorner')
UICorner10.CornerRadius = UDim.new(0, 8)
local TextButton6 = Instance.new('TextButton')
TextButton6.Name = "GUIThemesTab"
TextButton6.Size = UDim2.new(0.235, 0, 1, 0)
TextButton6.Position = UDim2.new(0.51, 0, 0, 0)
TextButton6.BackgroundColor3 = Color3.fromRGB(60, 30, 90)
TextButton6.BackgroundTransparency = 0.3
TextButton6.Text = "GUI THEMES"
TextButton6.TextColor3 = Color3.fromRGB(200, 200, 200)
TextButton6.TextSize = 12
TextButton6.Font = TextButton5.Font
TextButton6.Parent = TextButton5.Parent
local UICorner11 = Instance.new('UICorner')
UICorner11.CornerRadius = UDim.new(0, 8)
local TextButton7 = Instance.new('TextButton')
TextButton7.Name = "SettingsTab"
TextButton7.Size = UDim2.new(0.235, 0, 1, 0)
TextButton7.Position = UDim2.new(0.765, 0, 0, 0)
TextButton7.BackgroundColor3 = Color3.fromRGB(60, 30, 90)
TextButton7.BackgroundTransparency = 0.3
TextButton7.Text = "SETTINGS"
TextButton7.TextColor3 = Color3.fromRGB(200, 200, 200)
TextButton7.TextSize = 12
TextButton7.Font = TextButton6.Font
TextButton7.Parent = TextButton6.Parent
local UICorner12 = Instance.new('UICorner')
UICorner12.CornerRadius = UDim.new(0, 8)
local ScrollingFrame1 = Instance.new('ScrollingFrame')
ScrollingFrame1.Name = "AnimationScroller"
ScrollingFrame1.Size = UDim2.new(0.45, -10, 0.75, -50)
ScrollingFrame1.Position = UDim2.new(0.02, 0, 0.12, 0)
ScrollingFrame1.BackgroundTransparency = 1
ScrollingFrame1.ScrollBarThickness = 8
ScrollingFrame1.ScrollBarImageColor3 = Color3.fromRGB(150, 100, 200)
ScrollingFrame1.ScrollBarImageTransparency = 0.3
ScrollingFrame1.Visible = true
ScrollingFrame1.Parent = Frame5.Parent
local UIListLayout1 = Instance.new('UIListLayout')
UIListLayout1.Name = "ListLayout"
UIListLayout1.Padding = UDim.new(0, 8)
UIListLayout1.SortOrder = { }
UIListLayout1.Parent = ScrollingFrame1
local ScrollingFrame2 = Instance.new('ScrollingFrame')
ScrollingFrame2.Name = "ButtonThemesFrame"
ScrollingFrame2.Size = UDim2.new(0.9, 0, 0.75, -50)
ScrollingFrame2.Position = UDim2.new(0.05, 0, 0.12, 0)
ScrollingFrame2.BackgroundTransparency = 1
ScrollingFrame2.ScrollBarThickness = 8
ScrollingFrame2.ScrollBarImageColor3 = Color3.fromRGB(150, 100, 200)
ScrollingFrame2.ScrollBarImageTransparency = 0.3
ScrollingFrame2.Visible = false
ScrollingFrame2.Parent = ScrollingFrame1.Parent
local UIListLayout2 = Instance.new('UIListLayout')
UIListLayout2.Name = "ButtonThemesListLayout"
UIListLayout2.Padding = UDim.new(0, 8)
UIListLayout2.SortOrder = UIListLayout1.SortOrder
UIListLayout2.Parent = ScrollingFrame2
local ScrollingFrame3 = Instance.new('ScrollingFrame')
ScrollingFrame3.Name = "GUIThemesFrame"
ScrollingFrame3.Size = UDim2.new(0.9, 0, 0.75, -50)
ScrollingFrame3.Position = UDim2.new(0.05, 0, 0.12, 0)
ScrollingFrame3.BackgroundTransparency = 1
ScrollingFrame3.ScrollBarThickness = 8
ScrollingFrame3.ScrollBarImageColor3 = Color3.fromRGB(150, 100, 200)
ScrollingFrame3.ScrollBarImageTransparency = 0.3
ScrollingFrame3.Visible = false
ScrollingFrame3.Parent = ScrollingFrame2.Parent
local UIListLayout3 = Instance.new('UIListLayout')
UIListLayout3.Name = "GUIThemesListLayout"
UIListLayout3.Padding = UDim.new(0, 8)
UIListLayout3.SortOrder = UIListLayout2.SortOrder
UIListLayout3.Parent = ScrollingFrame3
local ScrollingFrame4 = Instance.new('ScrollingFrame')
ScrollingFrame4.Name = "SettingsPageFrame"
ScrollingFrame4.Size = UDim2.new(0.9, 0, 0.75, -50)
ScrollingFrame4.Position = UDim2.new(0.05, 0, 0.12, 0)
ScrollingFrame4.BackgroundTransparency = 1
ScrollingFrame4.ScrollBarThickness = 8
ScrollingFrame4.ScrollBarImageColor3 = Color3.fromRGB(150, 100, 200)
ScrollingFrame4.ScrollBarImageTransparency = 0.3
ScrollingFrame4.Visible = false
ScrollingFrame4.Parent = ScrollingFrame3.Parent
local UIListLayout4 = Instance.new('UIListLayout')
UIListLayout4.Name = "SettingsListLayout"
UIListLayout4.Padding = UDim.new(0, 10)
UIListLayout4.SortOrder = UIListLayout3.SortOrder
UIListLayout4.Parent = ScrollingFrame4
UIListLayout4:GetPropertyChangedSignal(UIListLayout4, "AbsoluteContentSize")
UIListLayout4.GetPropertyChangedSignal:Connect(function()
-- error: ./input.lua:911: attempt to perform arithmetic (add) on table and number
end)
local Frame6 = Instance.new('Frame')
Frame6.Name = "SettingsFrame"
Frame6.Size = UDim2.new(0.5, -15, 0.75, -50)
Frame6.Position = UDim2.new(0.5, 5, 0.12, 0)
Frame6.BackgroundColor3 = Color3.fromRGB(25, 15, 40)
Frame6.BackgroundTransparency = 0.2
Frame6.Visible = true
Frame6.Parent = ScrollingFrame4.Parent
local UICorner13 = Instance.new('UICorner')
UICorner13.CornerRadius = UDim.new(0, 10)
UICorner13.Parent = Frame6
local Frame7 = Instance.new('Frame')
Frame7.Name = "StatsContainer"
Frame7.Size = UDim2.new(1, -20, 0.45, 0)
Frame7.Position = UDim2.new(0, 10, 0.02, 0)
Frame7.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
Frame7.BackgroundTransparency = 0.2
Frame7.Parent = UICorner13.Parent
local UICorner14 = Instance.new('UICorner')
UICorner14.CornerRadius = UDim.new(0, 8)
UICorner14.Parent = Frame7
local TextLabel2 = Instance.new('TextLabel')
TextLabel2.Name = "StatsTitle"
TextLabel2.Size = UDim2.new(1, -10, 0.2, 0)
TextLabel2.Position = UDim2.new(0, 5, 0, 5)
TextLabel2.BackgroundTransparency = 1
TextLabel2.Text = "FLIGHT STATUS"
TextLabel2.TextColor3 = Color3.fromRGB(230, 200, 255)
TextLabel2.TextSize = 16
TextLabel2.TextXAlignment = { }
TextLabel2.Font = TextButton7.Font
TextLabel2.Parent = UICorner14.Parent
local Frame8 = Instance.new('Frame')
Frame8.Name = "StatusContainer"
Frame8.Size = UDim2.new(1, -20, 0.15, 0)
Frame8.Position = UDim2.new(0, 10, 0.25, 0)
Frame8.BackgroundTransparency = 1
Frame8.Parent = TextLabel2.Parent
local TextLabel3 = Instance.new('TextLabel')
TextLabel3.Name = "StatusStat"
TextLabel3.Size = UDim2.new(0.8, 0, 1, 0)
TextLabel3.Position = UDim2.new(0.2, 0, 0, 0)
TextLabel3.BackgroundTransparency = 1
TextLabel3.Text = "GROUNDED"
TextLabel3.TextColor3 = Color3.fromRGB(255, 120, 120)
TextLabel3.TextSize = 14
TextLabel3.TextXAlignment = TextLabel1.TextXAlignment
TextLabel3.Font = { }
TextLabel3.Parent = Frame8
local Frame9 = Instance.new('Frame')
Frame9.Name = "SpeedContainer"
Frame9.Size = UDim2.new(1, -20, 0.15, 0)
Frame9.Position = UDim2.new(0, 10, 0.45, 0)
Frame9.BackgroundTransparency = 1
Frame9.Parent = Frame8.Parent
local TextLabel4 = Instance.new('TextLabel')
TextLabel4.Name = "SpeedStat"
TextLabel4.Size = UDim2.new(0.8, 0, 1, 0)
TextLabel4.Position = UDim2.new(0.2, 0, 0, 0)
TextLabel4.BackgroundTransparency = 1
TextLabel4.Text = "SPEED: 50"
TextLabel4.TextColor3 = Color3.fromRGB(210, 180, 240)
TextLabel4.TextSize = 14
TextLabel4.TextXAlignment = TextLabel3.TextXAlignment
TextLabel4.Font = TextLabel3.Font
TextLabel4.Parent = Frame9
local Frame10 = Instance.new('Frame')
Frame10.Name = "BoostContainer"
Frame10.Size = UDim2.new(1, -20, 0.15, 0)
Frame10.Position = UDim2.new(0, 10, 0.65, 0)
Frame10.BackgroundTransparency = 1
Frame10.Parent = Frame9.Parent
local TextLabel5 = Instance.new('TextLabel')
TextLabel5.Name = "BoostStat"
TextLabel5.Size = UDim2.new(0.8, 0, 1, 0)
TextLabel5.Position = UDim2.new(0.2, 0, 0, 0)
TextLabel5.BackgroundTransparency = 1
TextLabel5.Text = "BOOST: OFF"
TextLabel5.TextColor3 = Color3.fromRGB(210, 180, 240)
TextLabel5.TextSize = 14
TextLabel5.TextXAlignment = TextLabel4.TextXAlignment
TextLabel5.Font = TextLabel4.Font
TextLabel5.Parent = Frame10
local Frame11 = Instance.new('Frame')
Frame11.Name = "AnimContainer"
Frame11.Size = UDim2.new(1, -20, 0.15, 0)
Frame11.Position = UDim2.new(0, 10, 0.85, 0)
Frame11.BackgroundTransparency = 1
Frame11.Parent = Frame10.Parent
local TextLabel6 = Instance.new('TextLabel')
TextLabel6.Name = "AnimationStat"
TextLabel6.Size = UDim2.new(0.8, 0, 1, 0)
TextLabel6.Position = UDim2.new(0.2, 0, 0, 0)
TextLabel6.BackgroundTransparency = 1
TextLabel6.Text = "DefaultIdle"
TextLabel6.TextColor3 = Color3.fromRGB(210, 180, 240)
TextLabel6.TextSize = 12
TextLabel6.TextXAlignment = TextLabel5.TextXAlignment
TextLabel6.Font = TextLabel5.Font
TextLabel6.Parent = Frame11
local TextButton8 = Instance.new('TextButton')
TextButton8.Name = "DefaultIdle"
TextButton8.Size = UDim2.new(1, -8, 0, 40)
TextButton8.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton8.BackgroundTransparency = 0.1
TextButton8.Text = "DefaultIdle"
TextButton8.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton8.TextSize = 14
TextButton8.Font = TextLabel6.Font
TextButton8.LayoutOrder = 1
TextButton8.Parent = UIListLayout1.Parent
local UICorner15 = Instance.new('UICorner')
UICorner15.CornerRadius = UDim.new(0, 8)
UICorner15.Parent = TextButton8
local Frame12 = Instance.new('Frame')
Frame12.Name = "SelectionIndicator"
Frame12.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame12.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame12.BackgroundColor3 = Color3.fromRGB(180, 130, 230)
Frame12.Parent = UICorner15.Parent
local UICorner16 = Instance.new('UICorner')
UICorner16.CornerRadius = UDim.new(0.5, 0)
UICorner16.Parent = Frame12
Frame12.Parent.MouseEnter:Connect(function()
end)
Frame12.Parent.MouseLeave:Connect(function()
end)
Frame12.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton8.Parent)
task.delay(2, function()
end)
end)
local TextButton9 = Instance.new('TextButton')
TextButton9.Name = "MustacheMark"
TextButton9.Size = UDim2.new(1, -8, 0, 40)
TextButton9.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton9.BackgroundTransparency = 0.1
TextButton9.Text = "MustacheMark"
TextButton9.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton9.TextSize = 14
TextButton9.Font = TextButton8.Font
TextButton9.LayoutOrder = 2
TextButton9.Parent = TextButton8.Parent
local UICorner17 = Instance.new('UICorner')
UICorner17.CornerRadius = UDim.new(0, 8)
UICorner17.Parent = TextButton9
local Frame13 = Instance.new('Frame')
Frame13.Name = "SelectionIndicator"
Frame13.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame13.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame13.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame13.Parent = UICorner17.Parent
local UICorner18 = Instance.new('UICorner')
UICorner18.CornerRadius = UDim.new(0.5, 0)
UICorner18.Parent = Frame13
Frame13.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame13.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame13.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame13.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame13.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton9.Parent)
task.delay(2, function()
end)
end)
local TextButton10 = Instance.new('TextButton')
TextButton10.Name = "RelaxedFly"
TextButton10.Size = UDim2.new(1, -8, 0, 40)
TextButton10.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton10.BackgroundTransparency = 0.1
TextButton10.Text = "RelaxedFly"
TextButton10.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton10.TextSize = 14
TextButton10.Font = TextButton9.Font
TextButton10.LayoutOrder = 3
TextButton10.Parent = TextButton9.Parent
local UICorner19 = Instance.new('UICorner')
UICorner19.CornerRadius = UDim.new(0, 8)
UICorner19.Parent = TextButton10
local Frame14 = Instance.new('Frame')
Frame14.Name = "SelectionIndicator"
Frame14.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame14.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame14.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame14.Parent = UICorner19.Parent
local UICorner20 = Instance.new('UICorner')
UICorner20.CornerRadius = UDim.new(0.5, 0)
UICorner20.Parent = Frame14
Frame14.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame14.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame14.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame14.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame14.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton10.Parent)
task.delay(2, function()
end)
end)
local TextButton11 = Instance.new('TextButton')
TextButton11.Name = "ZombieMark"
TextButton11.Size = UDim2.new(1, -8, 0, 40)
TextButton11.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton11.BackgroundTransparency = 0.1
TextButton11.Text = "ZombieMark"
TextButton11.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton11.TextSize = 14
TextButton11.Font = TextButton10.Font
TextButton11.LayoutOrder = 4
TextButton11.Parent = TextButton10.Parent
local UICorner21 = Instance.new('UICorner')
UICorner21.CornerRadius = UDim.new(0, 8)
UICorner21.Parent = TextButton11
local Frame15 = Instance.new('Frame')
Frame15.Name = "SelectionIndicator"
Frame15.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame15.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame15.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame15.Parent = UICorner21.Parent
local UICorner22 = Instance.new('UICorner')
UICorner22.CornerRadius = UDim.new(0.5, 0)
UICorner22.Parent = Frame15
Frame15.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame15.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame15.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame15.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame15.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton11.Parent)
task.delay(2, function()
end)
end)
local TextButton12 = Instance.new('TextButton')
TextButton12.Name = "ChillLevitate"
TextButton12.Size = UDim2.new(1, -8, 0, 40)
TextButton12.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton12.BackgroundTransparency = 0.1
TextButton12.Text = "ChillLevitate"
TextButton12.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton12.TextSize = 14
TextButton12.Font = TextButton11.Font
TextButton12.LayoutOrder = 5
TextButton12.Parent = TextButton11.Parent
local UICorner23 = Instance.new('UICorner')
UICorner23.CornerRadius = UDim.new(0, 8)
UICorner23.Parent = TextButton12
local Frame16 = Instance.new('Frame')
Frame16.Name = "SelectionIndicator"
Frame16.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame16.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame16.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame16.Parent = UICorner23.Parent
local UICorner24 = Instance.new('UICorner')
UICorner24.CornerRadius = UDim.new(0.5, 0)
UICorner24.Parent = Frame16
Frame16.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame16.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame16.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame16.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame16.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton12.Parent)
task.delay(2, function()
end)
end)
local TextButton13 = Instance.new('TextButton')
TextButton13.Name = "StillIdle"
TextButton13.Size = UDim2.new(1, -8, 0, 40)
TextButton13.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton13.BackgroundTransparency = 0.1
TextButton13.Text = "StillIdle"
TextButton13.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton13.TextSize = 14
TextButton13.Font = TextButton12.Font
TextButton13.LayoutOrder = 6
TextButton13.Parent = TextButton12.Parent
local UICorner25 = Instance.new('UICorner')
UICorner25.CornerRadius = UDim.new(0, 8)
UICorner25.Parent = TextButton13
local Frame17 = Instance.new('Frame')
Frame17.Name = "SelectionIndicator"
Frame17.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame17.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame17.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame17.Parent = UICorner25.Parent
local UICorner26 = Instance.new('UICorner')
UICorner26.CornerRadius = UDim.new(0.5, 0)
UICorner26.Parent = Frame17
Frame17.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame17.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame17.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame17.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame17.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton13.Parent)
task.delay(2, function()
end)
end)
local TextButton14 = Instance.new('TextButton')
TextButton14.Name = "MetroMan"
TextButton14.Size = UDim2.new(1, -8, 0, 40)
TextButton14.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton14.BackgroundTransparency = 0.1
TextButton14.Text = "MetroMan"
TextButton14.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton14.TextSize = 14
TextButton14.Font = TextButton13.Font
TextButton14.LayoutOrder = 7
TextButton14.Parent = TextButton13.Parent
local UICorner27 = Instance.new('UICorner')
UICorner27.CornerRadius = UDim.new(0, 8)
UICorner27.Parent = TextButton14
local Frame18 = Instance.new('Frame')
Frame18.Name = "SelectionIndicator"
Frame18.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame18.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame18.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame18.Parent = UICorner27.Parent
local UICorner28 = Instance.new('UICorner')
UICorner28.CornerRadius = UDim.new(0.5, 0)
UICorner28.Parent = Frame18
Frame18.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame18.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame18.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame18.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame18.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton14.Parent)
task.delay(2, function()
end)
end)
local TextButton15 = Instance.new('TextButton')
TextButton15.Name = "ViltrimiteMark"
TextButton15.Size = UDim2.new(1, -8, 0, 40)
TextButton15.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton15.BackgroundTransparency = 0.1
TextButton15.Text = "ViltrimiteMark"
TextButton15.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton15.TextSize = 14
TextButton15.Font = TextButton14.Font
TextButton15.LayoutOrder = 8
TextButton15.Parent = TextButton14.Parent
local UICorner29 = Instance.new('UICorner')
UICorner29.CornerRadius = UDim.new(0, 8)
UICorner29.Parent = TextButton15
local Frame19 = Instance.new('Frame')
Frame19.Name = "SelectionIndicator"
Frame19.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame19.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame19.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame19.Parent = UICorner29.Parent
local UICorner30 = Instance.new('UICorner')
UICorner30.CornerRadius = UDim.new(0.5, 0)
UICorner30.Parent = Frame19
Frame19.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame19.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame19.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame19.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame19.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton15.Parent)
task.delay(2, function()
end)
end)
local TextButton16 = Instance.new('TextButton')
TextButton16.Name = "FlashyFly"
TextButton16.Size = UDim2.new(1, -8, 0, 40)
TextButton16.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton16.BackgroundTransparency = 0.1
TextButton16.Text = "FlashyFly"
TextButton16.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton16.TextSize = 14
TextButton16.Font = TextButton15.Font
TextButton16.LayoutOrder = 9
TextButton16.Parent = TextButton15.Parent
local UICorner31 = Instance.new('UICorner')
UICorner31.CornerRadius = UDim.new(0, 8)
UICorner31.Parent = TextButton16
local Frame20 = Instance.new('Frame')
Frame20.Name = "SelectionIndicator"
Frame20.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame20.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame20.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame20.Parent = UICorner31.Parent
local UICorner32 = Instance.new('UICorner')
UICorner32.CornerRadius = UDim.new(0.5, 0)
UICorner32.Parent = Frame20
Frame20.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame20.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame20.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame20.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame20.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton16.Parent)
task.delay(2, function()
end)
end)
local TextButton17 = Instance.new('TextButton')
TextButton17.Name = "NoGoggles"
TextButton17.Size = UDim2.new(1, -8, 0, 40)
TextButton17.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton17.BackgroundTransparency = 0.1
TextButton17.Text = "NoGoggles"
TextButton17.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton17.TextSize = 14
TextButton17.Font = TextButton16.Font
TextButton17.LayoutOrder = 10
TextButton17.Parent = TextButton16.Parent
local UICorner33 = Instance.new('UICorner')
UICorner33.CornerRadius = UDim.new(0, 8)
UICorner33.Parent = TextButton17
local Frame21 = Instance.new('Frame')
Frame21.Name = "SelectionIndicator"
Frame21.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame21.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame21.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame21.Parent = UICorner33.Parent
local UICorner34 = Instance.new('UICorner')
UICorner34.CornerRadius = UDim.new(0.5, 0)
UICorner34.Parent = Frame21
Frame21.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame21.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame21.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame21.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame21.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton17.Parent)
task.delay(2, function()
end)
end)
local TextButton18 = Instance.new('TextButton')
TextButton18.Name = "TargetMark"
TextButton18.Size = UDim2.new(1, -8, 0, 40)
TextButton18.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton18.BackgroundTransparency = 0.1
TextButton18.Text = "TargetMark"
TextButton18.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton18.TextSize = 14
TextButton18.Font = TextButton17.Font
TextButton18.LayoutOrder = 11
TextButton18.Parent = TextButton17.Parent
local UICorner35 = Instance.new('UICorner')
UICorner35.CornerRadius = UDim.new(0, 8)
UICorner35.Parent = TextButton18
local Frame22 = Instance.new('Frame')
Frame22.Name = "SelectionIndicator"
Frame22.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame22.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame22.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame22.Parent = UICorner35.Parent
local UICorner36 = Instance.new('UICorner')
UICorner36.CornerRadius = UDim.new(0.5, 0)
UICorner36.Parent = Frame22
Frame22.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame22.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame22.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame22.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame22.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton18.Parent)
task.delay(2, function()
end)
end)
local TextButton19 = Instance.new('TextButton')
TextButton19.Name = "Sinisterv3"
TextButton19.Size = UDim2.new(1, -8, 0, 40)
TextButton19.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton19.BackgroundTransparency = 0.1
TextButton19.Text = "Sinisterv3"
TextButton19.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton19.TextSize = 14
TextButton19.Font = TextButton18.Font
TextButton19.LayoutOrder = 12
TextButton19.Parent = TextButton18.Parent
local UICorner37 = Instance.new('UICorner')
UICorner37.CornerRadius = UDim.new(0, 8)
UICorner37.Parent = TextButton19
local Frame23 = Instance.new('Frame')
Frame23.Name = "SelectionIndicator"
Frame23.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame23.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame23.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame23.Parent = UICorner37.Parent
local UICorner38 = Instance.new('UICorner')
UICorner38.CornerRadius = UDim.new(0.5, 0)
UICorner38.Parent = Frame23
Frame23.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame23.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame23.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame23.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame23.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton19.Parent)
task.delay(2, function()
end)
end)
local TextButton20 = Instance.new('TextButton')
TextButton20.Name = "TrackSuitMark"
TextButton20.Size = UDim2.new(1, -8, 0, 40)
TextButton20.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton20.BackgroundTransparency = 0.1
TextButton20.Text = "TrackSuitMark"
TextButton20.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton20.TextSize = 14
TextButton20.Font = TextButton19.Font
TextButton20.LayoutOrder = 13
TextButton20.Parent = TextButton19.Parent
local UICorner39 = Instance.new('UICorner')
UICorner39.CornerRadius = UDim.new(0, 8)
UICorner39.Parent = TextButton20
local Frame24 = Instance.new('Frame')
Frame24.Name = "SelectionIndicator"
Frame24.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame24.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame24.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame24.Parent = UICorner39.Parent
local UICorner40 = Instance.new('UICorner')
UICorner40.CornerRadius = UDim.new(0.5, 0)
UICorner40.Parent = Frame24
Frame24.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame24.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame24.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame24.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame24.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton20.Parent)
task.delay(2, function()
end)
end)
local TextButton21 = Instance.new('TextButton')
TextButton21.Name = "BaldMark"
TextButton21.Size = UDim2.new(1, -8, 0, 40)
TextButton21.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton21.BackgroundTransparency = 0.1
TextButton21.Text = "BaldMark"
TextButton21.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton21.TextSize = 14
TextButton21.Font = TextButton20.Font
TextButton21.LayoutOrder = 14
TextButton21.Parent = TextButton20.Parent
local UICorner41 = Instance.new('UICorner')
UICorner41.CornerRadius = UDim.new(0, 8)
UICorner41.Parent = TextButton21
local Frame25 = Instance.new('Frame')
Frame25.Name = "SelectionIndicator"
Frame25.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame25.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame25.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame25.Parent = UICorner41.Parent
local UICorner42 = Instance.new('UICorner')
UICorner42.CornerRadius = UDim.new(0.5, 0)
UICorner42.Parent = Frame25
Frame25.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame25.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame25.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame25.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame25.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton21.Parent)
task.delay(2, function()
end)
end)
local TextButton22 = Instance.new('TextButton')
TextButton22.Name = "LongHairMark"
TextButton22.Size = UDim2.new(1, -8, 0, 40)
TextButton22.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton22.BackgroundTransparency = 0.1
TextButton22.Text = "LongHairMark"
TextButton22.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton22.TextSize = 14
TextButton22.Font = TextButton21.Font
TextButton22.LayoutOrder = 15
TextButton22.Parent = TextButton21.Parent
local UICorner43 = Instance.new('UICorner')
UICorner43.CornerRadius = UDim.new(0, 8)
UICorner43.Parent = TextButton22
local Frame26 = Instance.new('Frame')
Frame26.Name = "SelectionIndicator"
Frame26.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame26.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame26.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame26.Parent = UICorner43.Parent
local UICorner44 = Instance.new('UICorner')
UICorner44.CornerRadius = UDim.new(0.5, 0)
UICorner44.Parent = Frame26
Frame26.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame26.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame26.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame26.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame26.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton22.Parent)
task.delay(2, function()
end)
end)
local TextButton23 = Instance.new('TextButton')
TextButton23.Name = "FlaxanMark"
TextButton23.Size = UDim2.new(1, -8, 0, 40)
TextButton23.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton23.BackgroundTransparency = 0.1
TextButton23.Text = "FlaxanMark"
TextButton23.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton23.TextSize = 14
TextButton23.Font = TextButton22.Font
TextButton23.LayoutOrder = 16
TextButton23.Parent = TextButton22.Parent
local UICorner45 = Instance.new('UICorner')
UICorner45.CornerRadius = UDim.new(0, 8)
UICorner45.Parent = TextButton23
local Frame27 = Instance.new('Frame')
Frame27.Name = "SelectionIndicator"
Frame27.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame27.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame27.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame27.Parent = UICorner45.Parent
local UICorner46 = Instance.new('UICorner')
UICorner46.CornerRadius = UDim.new(0.5, 0)
UICorner46.Parent = Frame27
Frame27.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame27.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame27.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame27.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame27.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton23.Parent)
task.delay(2, function()
end)
end)
local TextButton24 = Instance.new('TextButton')
TextButton24.Name = "MasklessMark"
TextButton24.Size = UDim2.new(1, -8, 0, 40)
TextButton24.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton24.BackgroundTransparency = 0.1
TextButton24.Text = "MasklessMark"
TextButton24.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton24.TextSize = 14
TextButton24.Font = TextButton23.Font
TextButton24.LayoutOrder = 17
TextButton24.Parent = TextButton23.Parent
local UICorner47 = Instance.new('UICorner')
UICorner47.CornerRadius = UDim.new(0, 8)
UICorner47.Parent = TextButton24
local Frame28 = Instance.new('Frame')
Frame28.Name = "SelectionIndicator"
Frame28.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame28.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame28.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame28.Parent = UICorner47.Parent
local UICorner48 = Instance.new('UICorner')
UICorner48.CornerRadius = UDim.new(0.5, 0)
UICorner48.Parent = Frame28
Frame28.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame28.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame28.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame28.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame28.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton24.Parent)
task.delay(2, function()
end)
end)
local TextButton25 = Instance.new('TextButton')
TextButton25.Name = "BulletProofMark"
TextButton25.Size = UDim2.new(1, -8, 0, 40)
TextButton25.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton25.BackgroundTransparency = 0.1
TextButton25.Text = "BulletProofMark"
TextButton25.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton25.TextSize = 14
TextButton25.Font = TextButton24.Font
TextButton25.LayoutOrder = 18
TextButton25.Parent = TextButton24.Parent
local UICorner49 = Instance.new('UICorner')
UICorner49.CornerRadius = UDim.new(0, 8)
UICorner49.Parent = TextButton25
local Frame29 = Instance.new('Frame')
Frame29.Name = "SelectionIndicator"
Frame29.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame29.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame29.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame29.Parent = UICorner49.Parent
local UICorner50 = Instance.new('UICorner')
UICorner50.CornerRadius = UDim.new(0.5, 0)
UICorner50.Parent = Frame29
Frame29.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame29.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame29.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame29.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame29.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton25.Parent)
task.delay(2, function()
end)
end)
local TextButton26 = Instance.new('TextButton')
TextButton26.Name = "PrisonerMark"
TextButton26.Size = UDim2.new(1, -8, 0, 40)
TextButton26.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton26.BackgroundTransparency = 0.1
TextButton26.Text = "PrisonerMark"
TextButton26.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton26.TextSize = 14
TextButton26.Font = TextButton25.Font
TextButton26.LayoutOrder = 19
TextButton26.Parent = TextButton25.Parent
local UICorner51 = Instance.new('UICorner')
UICorner51.CornerRadius = UDim.new(0, 8)
UICorner51.Parent = TextButton26
local Frame30 = Instance.new('Frame')
Frame30.Name = "SelectionIndicator"
Frame30.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame30.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame30.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame30.Parent = UICorner51.Parent
local UICorner52 = Instance.new('UICorner')
UICorner52.CornerRadius = UDim.new(0.5, 0)
UICorner52.Parent = Frame30
Frame30.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame30.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame30.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame30.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame30.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton26.Parent)
task.delay(2, function()
end)
end)
local TextButton27 = Instance.new('TextButton')
TextButton27.Name = "UpsideDown"
TextButton27.Size = UDim2.new(1, -8, 0, 40)
TextButton27.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton27.BackgroundTransparency = 0.1
TextButton27.Text = "UpsideDown"
TextButton27.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton27.TextSize = 14
TextButton27.Font = TextButton26.Font
TextButton27.LayoutOrder = 20
TextButton27.Parent = TextButton26.Parent
local UICorner53 = Instance.new('UICorner')
UICorner53.CornerRadius = UDim.new(0, 8)
UICorner53.Parent = TextButton27
local Frame31 = Instance.new('Frame')
Frame31.Name = "SelectionIndicator"
Frame31.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame31.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame31.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame31.Parent = UICorner53.Parent
local UICorner54 = Instance.new('UICorner')
UICorner54.CornerRadius = UDim.new(0.5, 0)
UICorner54.Parent = Frame31
Frame31.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame31.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame31.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame31.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame31.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton27.Parent)
task.delay(2, function()
end)
end)
local TextButton28 = Instance.new('TextButton')
TextButton28.Name = "CasualFloat"
TextButton28.Size = UDim2.new(1, -8, 0, 40)
TextButton28.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton28.BackgroundTransparency = 0.1
TextButton28.Text = "CasualFloat"
TextButton28.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton28.TextSize = 14
TextButton28.Font = TextButton27.Font
TextButton28.LayoutOrder = 21
TextButton28.Parent = TextButton27.Parent
local UICorner55 = Instance.new('UICorner')
UICorner55.CornerRadius = UDim.new(0, 8)
UICorner55.Parent = TextButton28
local Frame32 = Instance.new('Frame')
Frame32.Name = "SelectionIndicator"
Frame32.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame32.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame32.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame32.Parent = UICorner55.Parent
local UICorner56 = Instance.new('UICorner')
UICorner56.CornerRadius = UDim.new(0.5, 0)
UICorner56.Parent = Frame32
Frame32.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame32.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame32.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame32.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame32.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton28.Parent)
task.delay(2, function()
end)
end)
local TextButton29 = Instance.new('TextButton')
TextButton29.Name = "SheistyMark"
TextButton29.Size = UDim2.new(1, -8, 0, 40)
TextButton29.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton29.BackgroundTransparency = 0.1
TextButton29.Text = "SheistyMark"
TextButton29.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton29.TextSize = 14
TextButton29.Font = TextButton28.Font
TextButton29.LayoutOrder = 22
TextButton29.Parent = TextButton28.Parent
local UICorner57 = Instance.new('UICorner')
UICorner57.CornerRadius = UDim.new(0, 8)
UICorner57.Parent = TextButton29
local Frame33 = Instance.new('Frame')
Frame33.Name = "SelectionIndicator"
Frame33.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame33.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame33.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame33.Parent = UICorner57.Parent
local UICorner58 = Instance.new('UICorner')
UICorner58.CornerRadius = UDim.new(0.5, 0)
UICorner58.Parent = Frame33
Frame33.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame33.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame33.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame33.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame33.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton29.Parent)
task.delay(2, function()
end)
end)
local TextButton30 = Instance.new('TextButton')
TextButton30.Name = "PreparedIdle"
TextButton30.Size = UDim2.new(1, -8, 0, 40)
TextButton30.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton30.BackgroundTransparency = 0.1
TextButton30.Text = "PreparedIdle"
TextButton30.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton30.TextSize = 14
TextButton30.Font = TextButton29.Font
TextButton30.LayoutOrder = 23
TextButton30.Parent = TextButton29.Parent
local UICorner59 = Instance.new('UICorner')
UICorner59.CornerRadius = UDim.new(0, 8)
UICorner59.Parent = TextButton30
local Frame34 = Instance.new('Frame')
Frame34.Name = "SelectionIndicator"
Frame34.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame34.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame34.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame34.Parent = UICorner59.Parent
local UICorner60 = Instance.new('UICorner')
UICorner60.CornerRadius = UDim.new(0.5, 0)
UICorner60.Parent = Frame34
Frame34.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame34.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame34.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame34.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame34.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton30.Parent)
task.delay(2, function()
end)
end)
local TextButton31 = Instance.new('TextButton')
TextButton31.Name = "AnnoyedIdle"
TextButton31.Size = UDim2.new(1, -8, 0, 40)
TextButton31.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton31.BackgroundTransparency = 0.1
TextButton31.Text = "AnnoyedIdle"
TextButton31.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton31.TextSize = 14
TextButton31.Font = TextButton30.Font
TextButton31.LayoutOrder = 24
TextButton31.Parent = TextButton30.Parent
local UICorner61 = Instance.new('UICorner')
UICorner61.CornerRadius = UDim.new(0, 8)
UICorner61.Parent = TextButton31
local Frame35 = Instance.new('Frame')
Frame35.Name = "SelectionIndicator"
Frame35.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame35.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame35.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame35.Parent = UICorner61.Parent
local UICorner62 = Instance.new('UICorner')
UICorner62.CornerRadius = UDim.new(0.5, 0)
UICorner62.Parent = Frame35
Frame35.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame35.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame35.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame35.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame35.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton31.Parent)
task.delay(2, function()
end)
end)
local TextButton32 = Instance.new('TextButton')
TextButton32.Name = "ViltrimiteIdle"
TextButton32.Size = UDim2.new(1, -8, 0, 40)
TextButton32.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton32.BackgroundTransparency = 0.1
TextButton32.Text = "ViltrimiteIdle"
TextButton32.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton32.TextSize = 14
TextButton32.Font = TextButton31.Font
TextButton32.LayoutOrder = 25
TextButton32.Parent = TextButton31.Parent
local UICorner63 = Instance.new('UICorner')
UICorner63.CornerRadius = UDim.new(0, 8)
UICorner63.Parent = TextButton32
local Frame36 = Instance.new('Frame')
Frame36.Name = "SelectionIndicator"
Frame36.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame36.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame36.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame36.Parent = UICorner63.Parent
local UICorner64 = Instance.new('UICorner')
UICorner64.CornerRadius = UDim.new(0.5, 0)
UICorner64.Parent = Frame36
Frame36.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame36.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame36.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame36.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame36.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton32.Parent)
task.delay(2, function()
end)
end)
local TextButton33 = Instance.new('TextButton')
TextButton33.Name = "Sinister2"
TextButton33.Size = UDim2.new(1, -8, 0, 40)
TextButton33.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton33.BackgroundTransparency = 0.1
TextButton33.Text = "Sinister2"
TextButton33.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton33.TextSize = 14
TextButton33.Font = TextButton32.Font
TextButton33.LayoutOrder = 26
TextButton33.Parent = TextButton32.Parent
local UICorner65 = Instance.new('UICorner')
UICorner65.CornerRadius = UDim.new(0, 8)
UICorner65.Parent = TextButton33
local Frame37 = Instance.new('Frame')
Frame37.Name = "SelectionIndicator"
Frame37.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame37.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame37.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame37.Parent = UICorner65.Parent
local UICorner66 = Instance.new('UICorner')
UICorner66.CornerRadius = UDim.new(0.5, 0)
UICorner66.Parent = Frame37
Frame37.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame37.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame37.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame37.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame37.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton33.Parent)
task.delay(2, function()
end)
end)
local TextButton34 = Instance.new('TextButton')
TextButton34.Name = "Conquest"
TextButton34.Size = UDim2.new(1, -8, 0, 40)
TextButton34.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton34.BackgroundTransparency = 0.1
TextButton34.Text = "Conquest"
TextButton34.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton34.TextSize = 14
TextButton34.Font = TextButton33.Font
TextButton34.LayoutOrder = 27
TextButton34.Parent = TextButton33.Parent
local UICorner67 = Instance.new('UICorner')
UICorner67.CornerRadius = UDim.new(0, 8)
UICorner67.Parent = TextButton34
local Frame38 = Instance.new('Frame')
Frame38.Name = "SelectionIndicator"
Frame38.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame38.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame38.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame38.Parent = UICorner67.Parent
local UICorner68 = Instance.new('UICorner')
UICorner68.CornerRadius = UDim.new(0.5, 0)
UICorner68.Parent = Frame38
Frame38.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame38.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame38.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame38.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame38.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton34.Parent)
task.delay(2, function()
end)
end)
local TextButton35 = Instance.new('TextButton')
TextButton35.Name = "MohawkMark"
TextButton35.Size = UDim2.new(1, -8, 0, 40)
TextButton35.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton35.BackgroundTransparency = 0.1
TextButton35.Text = "MohawkMark"
TextButton35.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton35.TextSize = 14
TextButton35.Font = TextButton34.Font
TextButton35.LayoutOrder = 28
TextButton35.Parent = TextButton34.Parent
local UICorner69 = Instance.new('UICorner')
UICorner69.CornerRadius = UDim.new(0, 8)
UICorner69.Parent = TextButton35
local Frame39 = Instance.new('Frame')
Frame39.Name = "SelectionIndicator"
Frame39.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame39.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame39.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame39.Parent = UICorner69.Parent
local UICorner70 = Instance.new('UICorner')
UICorner70.CornerRadius = UDim.new(0.5, 0)
UICorner70.Parent = Frame39
Frame39.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame39.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame39.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame39.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame39.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton35.Parent)
task.delay(2, function()
end)
end)
local TextButton36 = Instance.new('TextButton')
TextButton36.Name = "MainInvincible"
TextButton36.Size = UDim2.new(1, -8, 0, 40)
TextButton36.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton36.BackgroundTransparency = 0.1
TextButton36.Text = "MainInvincible"
TextButton36.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton36.TextSize = 14
TextButton36.Font = TextButton35.Font
TextButton36.LayoutOrder = 29
TextButton36.Parent = TextButton35.Parent
local UICorner71 = Instance.new('UICorner')
UICorner71.CornerRadius = UDim.new(0, 8)
UICorner71.Parent = TextButton36
local Frame40 = Instance.new('Frame')
Frame40.Name = "SelectionIndicator"
Frame40.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame40.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame40.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame40.Parent = UICorner71.Parent
local UICorner72 = Instance.new('UICorner')
UICorner72.CornerRadius = UDim.new(0.5, 0)
UICorner72.Parent = Frame40
Frame40.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame40.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame40.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame40.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame40.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton36.Parent)
task.delay(2, function()
end)
end)
local TextButton37 = Instance.new('TextButton')
TextButton37.Name = "BasicIdle"
TextButton37.Size = UDim2.new(1, -8, 0, 40)
TextButton37.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton37.BackgroundTransparency = 0.1
TextButton37.Text = "BasicIdle"
TextButton37.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton37.TextSize = 14
TextButton37.Font = TextButton36.Font
TextButton37.LayoutOrder = 30
TextButton37.Parent = TextButton36.Parent
local UICorner73 = Instance.new('UICorner')
UICorner73.CornerRadius = UDim.new(0, 8)
UICorner73.Parent = TextButton37
local Frame41 = Instance.new('Frame')
Frame41.Name = "SelectionIndicator"
Frame41.Size = UDim2.new(0.02, 0, 0.6, 0)
Frame41.Position = UDim2.new(0.02, 0, 0.2, 0)
Frame41.BackgroundColor3 = Color3.fromRGB(80, 50, 100)
Frame41.Parent = UICorner73.Parent
local UICorner74 = Instance.new('UICorner')
UICorner74.CornerRadius = UDim.new(0.5, 0)
UICorner74.Parent = Frame41
Frame41.Parent.MouseEnter:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame41.Parent, { }, {
    BackgroundTransparency = 0.05,
    Size = UDim2.new(1, -4, 0, 42)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame41.Parent.MouseLeave:Connect(function()
TweenInfo:new(0.2)
TweenService1:Create(TweenService1, Frame41.Parent, { }, {
    BackgroundTransparency = 0.1,
    Size = UDim2.new(1, -8, 0, 40)
})
TweenService1.Create:Play({
    Play = { }
})
end)
Frame41.Parent.MouseButton1Click:Connect(function()
TextButton8.Parent:GetChildren(TextButton37.Parent)
task.delay(2, function()
end)
end)
local TextButton38 = Instance.new('TextButton')
TextButton38.Name = "ModernTheme"
TextButton38.Size = UDim2.new(1, -8, 0, 50)
TextButton38.BackgroundColor3 = Color3.fromRGB(80, 50, 120)
TextButton38.BackgroundTransparency = 0.1
TextButton38.Text = "MODERN THEME\
(Centered, Draggable)"
TextButton38.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton38.TextSize = 12
TextButton38.Font = TextButton37.Font
TextButton38.TextWrapped = true
TextButton38.LayoutOrder = 1
TextButton38.Parent = UIListLayout2.Parent
local UICorner75 = Instance.new('UICorner')
UICorner75.CornerRadius = UDim.new(0, 8)
UICorner75.Parent = TextButton38
local TextButton39 = Instance.new('TextButton')
TextButton39.Name = "ClassicTheme"
TextButton39.Size = UDim2.new(1, -8, 0, 50)
TextButton39.BackgroundColor3 = Color3.fromRGB(35, 20, 50)
TextButton39.BackgroundTransparency = 0.1
TextButton39.Text = "CLASSIC THEME\
(Right Side, Static)"
TextButton39.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton39.TextSize = 12
TextButton39.Font = TextButton38.Font
TextButton39.TextWrapped = true
TextButton39.LayoutOrder = 2
TextButton39.Parent = TextButton38.Parent
local UICorner76 = Instance.new('UICorner')
UICorner76.CornerRadius = UDim.new(0, 8)
UICorner76.Parent = TextButton39
local TextLabel7 = Instance.new('TextLabel')
TextLabel7.Name = "ComingSoon"
TextLabel7.Size = UDim2.new(1, -8, 0, 100)
TextLabel7.BackgroundTransparency = 1
TextLabel7.Text = "COMING SOON\
\
More GUI themes will be available in future updates!"
TextLabel7.TextColor3 = Color3.fromRGB(200, 200, 200)
TextLabel7.TextSize = 14
TextLabel7.Font = TextButton39.Font
TextLabel7.TextWrapped = true
TextLabel7.TextTransparency = 0.5
TextLabel7.LayoutOrder = 1
TextLabel7.Parent = UIListLayout3.Parent
UIListLayout1:GetPropertyChangedSignal(UIListLayout1, "AbsoluteContentSize")
UIListLayout1.GetPropertyChangedSignal:Connect(function()
-- error: ./input.lua:911: attempt to perform arithmetic (add) on table and number
end)
UIListLayout2:GetPropertyChangedSignal(UIListLayout2, "AbsoluteContentSize")
UIListLayout2.GetPropertyChangedSignal:Connect(function()
-- error: ./input.lua:911: attempt to perform arithmetic (add) on table and number
end)
UIListLayout3:GetPropertyChangedSignal(UIListLayout3, "AbsoluteContentSize")
UIListLayout3.GetPropertyChangedSignal:Connect(function()
-- error: ./input.lua:911: attempt to perform arithmetic (add) on table and number
end)
UICorner75.Parent.MouseButton1Click:Connect(function()
end)
UICorner76.Parent.MouseButton1Click:Connect(function()
ScreenGui1.Parent:WaitForChild({
    WaitForChild = ScreenGui1.Parent
}, "PlayerGui")
ScreenGui1.Parent:FindFirstChild(ScreenGui1.Parent, "MobileFlyControls")
local Frame42 = Instance.new('Frame')
Frame42.Name = "MobileControls"
Frame42.Size = UDim2.new(1, 0, 1, 0)
Frame42.BackgroundTransparency = 1
Frame42.Parent = { }
local TextButton40 = Instance.new('TextButton')
TextButton40.Name = "FlyButton"
TextButton40.Size = UDim2.new(0.15, 0, 0.15, 0)
TextButton40.Position = UDim2.new(0.929, 0, 0.5, 0)
TextButton40.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton40.BackgroundTransparency = 0.2
TextButton40.BackgroundColor3 = Color3.fromRGB(255, 60, 60)
TextButton40.Text = "FLY"
TextButton40.TextColor3 = Color3.new(1, 1, 1)
TextButton40.TextScaled = true
TextButton40.Font = TextLabel2.Font
TextButton40.TextStrokeTransparency = 0.5
local UICorner77 = Instance.new('UICorner')
UICorner77.CornerRadius = UDim.new(1, 0)
UICorner77.Parent = TextButton40
local ImageLabel2 = Instance.new('ImageLabel')
ImageLabel2.Name = "Shadow"
ImageLabel2.Size = UDim2.new(1, 10, 1, 10)
ImageLabel2.Position = UDim2.new(0, -5, 0, -5)
ImageLabel2.BackgroundTransparency = 1
ImageLabel2.Image = "rbxassetid://1316045217"
ImageLabel2.ImageColor3 = Color3.new(0, 0, 0)
ImageLabel2.ImageTransparency = 0.8
ImageLabel2.ScaleType = ImageLabel1.ScaleType
ImageLabel1.SliceCenter:new(10, 10, 118, 118)
ImageLabel2.SliceCenter = ImageLabel1.SliceCenter
ImageLabel2.Parent = UICorner77.Parent
ImageLabel2.Parent.InputBegan:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
ImageLabel2.Parent.InputEnded:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
local TextButton41 = Instance.new('TextButton')
TextButton41.Name = "BoostButton"
TextButton41.Size = UDim2.new(0.15, 0, 0.15, 0)
TextButton41.Position = UDim2.new(0.929, 0, 0.35, 0)
TextButton41.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton41.BackgroundTransparency = 0.2
TextButton41.BackgroundColor3 = Color3.fromRGB(0, 150, 255)
TextButton41.Text = "BOOST"
TextButton41.TextColor3 = Color3.new(1, 1, 1)
TextButton41.TextScaled = true
TextButton41.Font = TextButton40.Font
TextButton41.TextStrokeTransparency = 0.5
local UICorner78 = Instance.new('UICorner')
UICorner78.CornerRadius = UDim.new(1, 0)
UICorner78.Parent = TextButton41
local ImageLabel3 = Instance.new('ImageLabel')
ImageLabel3.Name = "Shadow"
ImageLabel3.Size = UDim2.new(1, 10, 1, 10)
ImageLabel3.Position = UDim2.new(0, -5, 0, -5)
ImageLabel3.BackgroundTransparency = 1
ImageLabel3.Image = "rbxassetid://1316045217"
ImageLabel3.ImageColor3 = Color3.new(0, 0, 0)
ImageLabel3.ImageTransparency = 0.8
ImageLabel3.ScaleType = ImageLabel2.ScaleType
ImageLabel2.SliceCenter:new(10, 10, 118, 118)
ImageLabel3.SliceCenter = ImageLabel2.SliceCenter
ImageLabel3.Parent = UICorner78.Parent
ImageLabel3.Parent.InputBegan:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
ImageLabel3.Parent.InputEnded:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
ImageLabel2.Parent.Parent = Frame42
ImageLabel3.Parent.Parent = ImageLabel2.Parent.Parent
ImageLabel2.Parent.MouseButton1Click:Connect(function()
Players1.LocalPlayer.Character:FindFirstChild({
    FindFirstChild = { }
}, "Humanoid")
Players1.LocalPlayer.Character:FindFirstChild({
    FindFirstChild = { }
}, "HumanoidRootPart")
Players1.LocalPlayer.Character.FindFirstChild.PlatformStand = true
local BodyVelocity1 = Instance.new('BodyVelocity')
BodyVelocity1.Name = "FlightVelocity"
BodyVelocity1.Parent = {
    PlatformStand = true
}
BodyVelocity1.MaxForce = Vector3.new(9000000000, 9000000000, 9000000000)
BodyVelocity1.Velocity = Vector3.new(0, 0, 0)
local BodyGyro1 = Instance.new('BodyGyro')
BodyGyro1.Name = "FlightGyro"
BodyGyro1.Parent = BodyVelocity1.Parent
BodyGyro1.MaxTorque = Vector3.new(9000000000, 9000000000, 9000000000)
BodyGyro1.P = 10000
BodyGyro1.D = 500
BodyGyro1.Parent.Died:Connect(function()
BodyGyro1.Parent:FindFirstChild({
    FindFirstChild = BodyGyro1.Parent
}, "HumanoidRootPart")
Players1.LocalPlayer.Character.HumanoidRootPart:FindFirstChild({
    FindFirstChild = { }
}, "FlightVelocity")
Players1.LocalPlayer.Character.HumanoidRootPart.FlightVelocity:Destroy({
    Destroy = { }
})
Players1.LocalPlayer.Character.HumanoidRootPart:FindFirstChild({
    FlightVelocity = {
        Destroy = { }
    },
    FindFirstChild = { }
}, "FlightGyro")
Players1.LocalPlayer.Character.HumanoidRootPart.FlightGyro:Destroy({
    Destroy = { }
})
BodyGyro1.Parent:FindFirstChild({
    HumanoidRootPart = {
        FlightVelocity = {
            Destroy = { }
        },
        FlightGyro = {
            Destroy = { }
        },
        FindFirstChild = { }
    },
    FindFirstChild = BodyGyro1.Parent
}, "Humanoid")
Players1.LocalPlayer.Character.Humanoid.PlatformStand = false
Players1.LocalPlayer.Character:GetChildren({
    GetChildren = { },
    Humanoid = {
        PlatformStand = false
    },
    HumanoidRootPart = {
        FlightVelocity = {
            Destroy = { }
        },
        FlightGyro = {
            Destroy = { }
        },
        FindFirstChild = { }
    },
    FindFirstChild = BodyGyro1.Parent
})
end)
RunService1.Heartbeat:Connect(function()
end)
BodyGyro1.Parent:IsA(BodyGyro1.Parent, "Humanoid")
Players1.LocalPlayer.Character:GetChildren({
    GetChildren = { },
    Humanoid = {
        PlatformStand = false
    },
    HumanoidRootPart = {
        FlightVelocity = {
            Destroy = { }
        },
        FlightGyro = {
            Destroy = { }
        },
        FindFirstChild = { }
    },
    FindFirstChild = BodyGyro1.Parent
})
BodyGyro1.Parent:LoadAnimation(BodyGyro1.Parent, Animation4)
BodyGyro1.Parent.LoadAnimation.Looped = false
BodyGyro1.Parent.LoadAnimation:Play({
    Play = { },
    Looped = false
})
BodyGyro1.Parent.LoadAnimation.TimePosition = 0.1
BodyGyro1.Parent.LoadAnimation:AdjustSpeed({
    TimePosition = 0.1,
    Looped = false,
    Play = { },
    AdjustSpeed = { }
}, 0.3)
RunService1.Heartbeat:Connect(function()
BodyGyro1.Parent.LoadAnimation:Stop({
    Stop = { },
    TimePosition = 0.1,
    IsPlaying = { },
    Looped = false,
    Play = { },
    AdjustSpeed = { }
}, 0.1)
BodyGyro1.Parent.LoadAnimation:Destroy({
    Destroy = { },
    Stop = { },
    TimePosition = 0.1,
    IsPlaying = { },
    Looped = false,
    Play = { },
    AdjustSpeed = { }
})
Players1.LocalPlayer.Character:GetChildren({
    GetChildren = { },
    Humanoid = {
        PlatformStand = false
    },
    HumanoidRootPart = {
        FlightVelocity = {
            Destroy = { }
        },
        FlightGyro = {
            Destroy = { }
        },
        FindFirstChild = { }
    },
    FindFirstChild = BodyGyro1.Parent
})
end)
RunService1.RenderStepped:Connect(function()
end)
end)
ImageLabel3.Parent.MouseButton1Click:Connect(function()
end)
isfolder("InvincibleFly")
makefolder("InvincibleFly")
local HttpService1 = game:GetService("HttpService")
warn("Failed to encode settings")
local TextLabel8 = Instance.new('TextLabel')
TextLabel8.Size = UDim2.new(0.8, 0, 0.1, 0)
TextLabel8.Position = UDim2.new(0.1, 0, 0.45, 0)
TextLabel8.BackgroundColor3 = Color3.fromRGB(80, 120, 80)
TextLabel8.BackgroundTransparency = 0.2
TextLabel8.Text = "Classic theme applied!"
TextLabel8.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel8.TextSize = 14
TextLabel8.Font = TextButton41.Font
TextLabel8.Parent = Frame6.Parent
TweenInfo:new(0.5)
TweenService1:Create(TweenService1, TextLabel8, { }, {
    BackgroundTransparency = 0.8
})
TweenService1.Create:Play({
    Play = { }
})
task.wait(2)
TextLabel8:Destroy(TextLabel8)
end)
UICorner4.Parent.MouseButton1Click:Connect(function()
local TextLabel9 = Instance.new('TextLabel')
TextLabel9.Size = UDim2.new(0.8, 0, 0.1, 0)
TextLabel9.Position = UDim2.new(0.1, 0, 0.45, 0)
TextLabel9.BackgroundColor3 = Color3.fromRGB(200, 60, 80)
TextLabel9.BackgroundTransparency = 0.2
TextLabel9.Text = "Lock feature not available in Classic theme!"
TextLabel9.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel9.TextSize = 14
TextLabel9.Font = TextLabel8.Font
TextLabel9.Parent = TextLabel8.Parent
TweenInfo:new(0.5)
TweenService1:Create(TweenService1, TextLabel9, { }, {
    BackgroundTransparency = 0.8
})
TweenService1.Create:Play({
    Play = { }
})
task.wait(2)
TextLabel9:Destroy(TextLabel9)
end)
TextButton4.MouseButton1Click:Connect(function()
end)
TextButton5.MouseButton1Click:Connect(function()
end)
TextButton6.MouseButton1Click:Connect(function()
end)
TextButton7.MouseButton1Click:Connect(function()
end)
RunService1.Heartbeat:Connect(function()
end)
local TextLabel10 = Instance.new('TextLabel')
TextLabel10.Size = UDim2.new(1, -8, 0, 28)
TextLabel10.BackgroundTransparency = 1
TextLabel10.Text = "HOVER SETTINGS"
TextLabel10.TextColor3 = Color3.fromRGB(230, 200, 255)
TextLabel10.TextSize = 16
TextLabel10.Font = TextLabel9.Font
TextLabel10.TextXAlignment = TextLabel6.TextXAlignment
TextLabel10.LayoutOrder = 1
TextLabel10.Parent = UIListLayout4.Parent
local Frame43 = Instance.new('Frame')
Frame43.Size = UDim2.new(1, -8, 0, 62)
Frame43.BackgroundTransparency = 1
local TextLabel11 = Instance.new('TextLabel')
TextLabel11.Size = UDim2.new(0.7, 0, 0, 18)
TextLabel11.Position = UDim2.new(0, 0, 0, 0)
TextLabel11.BackgroundTransparency = 1
TextLabel11.Text = "HOVER HEIGHT"
TextLabel11.TextColor3 = Color3.fromRGB(210, 180, 240)
TextLabel11.TextSize = 13
TextLabel11.Font = TextLabel7.Font
TextLabel11.TextXAlignment = TextLabel10.TextXAlignment
TextLabel11.Parent = Frame43
local TextLabel12 = Instance.new('TextLabel')
TextLabel12.Size = UDim2.new(0.3, 0, 0, 18)
TextLabel12.Position = UDim2.new(0.7, 0, 0, 0)
TextLabel12.BackgroundTransparency = 1
TextLabel12.Text = "0.8"
TextLabel12.TextColor3 = Color3.fromRGB(250, 230, 255)
TextLabel12.TextSize = 13
TextLabel12.Font = TextLabel10.Font
TextLabel12.TextXAlignment = { }
TextLabel12.Parent = TextLabel11.Parent
local Frame44 = Instance.new('Frame')
Frame44.Size = UDim2.new(1, 0, 0, 14)
Frame44.Position = UDim2.new(0, 0, 0, 34)
Frame44.BackgroundColor3 = Color3.fromRGB(50, 30, 70)
Frame44.Parent = TextLabel12.Parent
local UICorner79 = Instance.new('UICorner')
UICorner79.CornerRadius = UDim.new(0.5, 0)
local Frame45 = Instance.new('Frame')
Frame45.Size = UDim2.new(0, 1, 1, 0)
Frame45.BackgroundColor3 = Color3.fromRGB(180, 130, 230)
Frame45.Parent = Frame44
local UICorner80 = Instance.new('UICorner')
UICorner80.CornerRadius = UDim.new(0.5, 0)
Frame44.Parent.LayoutOrder = 2
Frame44.Parent.Parent = TextLabel10.Parent
local Frame46 = Instance.new('Frame')
Frame46.Size = UDim2.new(1, -8, 0, 62)
Frame46.BackgroundTransparency = 1
local TextLabel13 = Instance.new('TextLabel')
TextLabel13.Size = UDim2.new(0.7, 0, 0, 18)
TextLabel13.Position = UDim2.new(0, 0, 0, 0)
TextLabel13.BackgroundTransparency = 1
TextLabel13.Text = "HOVER SPEED"
TextLabel13.TextColor3 = Color3.fromRGB(210, 180, 240)
TextLabel13.TextSize = 13
TextLabel13.Font = TextLabel11.Font
TextLabel13.TextXAlignment = TextLabel11.TextXAlignment
TextLabel13.Parent = Frame46
local TextLabel14 = Instance.new('TextLabel')
TextLabel14.Size = UDim2.new(0.3, 0, 0, 18)
TextLabel14.Position = UDim2.new(0.7, 0, 0, 0)
TextLabel14.BackgroundTransparency = 1
TextLabel14.Text = "2.9"
TextLabel14.TextColor3 = Color3.fromRGB(250, 230, 255)
TextLabel14.TextSize = 13
TextLabel14.Font = TextLabel12.Font
TextLabel14.TextXAlignment = TextLabel12.TextXAlignment
TextLabel14.Parent = TextLabel13.Parent
local Frame47 = Instance.new('Frame')
Frame47.Size = UDim2.new(1, 0, 0, 14)
Frame47.Position = UDim2.new(0, 0, 0, 34)
Frame47.BackgroundColor3 = Color3.fromRGB(50, 30, 70)
Frame47.Parent = TextLabel14.Parent
local UICorner81 = Instance.new('UICorner')
UICorner81.CornerRadius = UDim.new(0.5, 0)
local Frame48 = Instance.new('Frame')
Frame48.Size = UDim2.new(0, 1, 1, 0)
Frame48.BackgroundColor3 = Color3.fromRGB(180, 130, 230)
Frame48.Parent = Frame47
local UICorner82 = Instance.new('UICorner')
UICorner82.CornerRadius = UDim.new(0.5, 0)
Frame47.Parent.LayoutOrder = 3
Frame47.Parent.Parent = Frame44.Parent.Parent
local TextButton42 = Instance.new('TextButton')
TextButton42.Name = "ResetHoverButton"
TextButton42.Size = UDim2.new(1, -8, 0, 36)
TextButton42.BackgroundColor3 = Color3.fromRGB(70, 30, 100)
TextButton42.BackgroundTransparency = 0.1
TextButton42.Text = "RESET HOVER SETTINGS"
TextButton42.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton42.TextSize = 12
TextButton42.Font = TextLabel14.Font
TextButton42.LayoutOrder = 4
TextButton42.Parent = Frame47.Parent.Parent
local UICorner83 = Instance.new('UICorner')
UICorner83.CornerRadius = UDim.new(0, 6)
local TextLabel15 = Instance.new('TextLabel')
TextLabel15.Size = UDim2.new(1, -8, 0, 28)
TextLabel15.BackgroundTransparency = 1
TextLabel15.Text = "SPEED SETTINGS"
TextLabel15.TextColor3 = Color3.fromRGB(230, 200, 255)
TextLabel15.TextSize = 16
TextLabel15.Font = TextButton42.Font
TextLabel15.TextXAlignment = TextLabel13.TextXAlignment
TextLabel15.LayoutOrder = 1
TextLabel15.Parent = TextButton42.Parent
local Frame49 = Instance.new('Frame')
Frame49.Size = UDim2.new(1, -8, 0, 62)
Frame49.BackgroundTransparency = 1
local TextLabel16 = Instance.new('TextLabel')
TextLabel16.Size = UDim2.new(0.7, 0, 0, 18)
TextLabel16.Position = UDim2.new(0, 0, 0, 0)
TextLabel16.BackgroundTransparency = 1
TextLabel16.Text = "BASE SPEED"
TextLabel16.TextColor3 = Color3.fromRGB(210, 180, 240)
TextLabel16.TextSize = 13
TextLabel16.Font = TextLabel13.Font
TextLabel16.TextXAlignment = TextLabel15.TextXAlignment
TextLabel16.Parent = Frame49
local TextLabel17 = Instance.new('TextLabel')
TextLabel17.Size = UDim2.new(0.3, 0, 0, 18)
TextLabel17.Position = UDim2.new(0.7, 0, 0, 0)
TextLabel17.BackgroundTransparency = 1
TextLabel17.Text = "50"
TextLabel17.TextColor3 = Color3.fromRGB(250, 230, 255)
TextLabel17.TextSize = 13
TextLabel17.Font = TextLabel15.Font
TextLabel17.TextXAlignment = TextLabel14.TextXAlignment
TextLabel17.Parent = TextLabel16.Parent
local Frame50 = Instance.new('Frame')
Frame50.Size = UDim2.new(1, 0, 0, 14)
Frame50.Position = UDim2.new(0, 0, 0, 34)
Frame50.BackgroundColor3 = Color3.fromRGB(50, 30, 70)
Frame50.Parent = TextLabel17.Parent
local UICorner84 = Instance.new('UICorner')
UICorner84.CornerRadius = UDim.new(0.5, 0)
local Frame51 = Instance.new('Frame')
Frame51.Size = UDim2.new(0, 1, 1, 0)
Frame51.BackgroundColor3 = Color3.fromRGB(180, 130, 230)
Frame51.Parent = Frame50
local UICorner85 = Instance.new('UICorner')
UICorner85.CornerRadius = UDim.new(0.5, 0)
Frame50.Parent.LayoutOrder = 6
Frame50.Parent.Parent = TextLabel15.Parent
local Frame52 = Instance.new('Frame')
Frame52.Size = UDim2.new(1, -8, 0, 62)
Frame52.BackgroundTransparency = 1
local TextLabel18 = Instance.new('TextLabel')
TextLabel18.Size = UDim2.new(0.7, 0, 0, 18)
TextLabel18.Position = UDim2.new(0, 0, 0, 0)
TextLabel18.BackgroundTransparency = 1
TextLabel18.Text = "BOOST SPEED"
TextLabel18.TextColor3 = Color3.fromRGB(210, 180, 240)
TextLabel18.TextSize = 13
TextLabel18.Font = TextLabel16.Font
TextLabel18.TextXAlignment = TextLabel16.TextXAlignment
TextLabel18.Parent = Frame52
local TextLabel19 = Instance.new('TextLabel')
TextLabel19.Size = UDim2.new(0.3, 0, 0, 18)
TextLabel19.Position = UDim2.new(0.7, 0, 0, 0)
TextLabel19.BackgroundTransparency = 1
TextLabel19.Text = "100"
TextLabel19.TextColor3 = Color3.fromRGB(250, 230, 255)
TextLabel19.TextSize = 13
TextLabel19.Font = TextLabel17.Font
TextLabel19.TextXAlignment = TextLabel17.TextXAlignment
TextLabel19.Parent = TextLabel18.Parent
local Frame53 = Instance.new('Frame')
Frame53.Size = UDim2.new(1, 0, 0, 14)
Frame53.Position = UDim2.new(0, 0, 0, 34)
Frame53.BackgroundColor3 = Color3.fromRGB(50, 30, 70)
Frame53.Parent = TextLabel19.Parent
local UICorner86 = Instance.new('UICorner')
UICorner86.CornerRadius = UDim.new(0.5, 0)
local Frame54 = Instance.new('Frame')
Frame54.Size = UDim2.new(0, 1, 1, 0)
Frame54.BackgroundColor3 = Color3.fromRGB(180, 130, 230)
Frame54.Parent = Frame53
local UICorner87 = Instance.new('UICorner')
UICorner87.CornerRadius = UDim.new(0.5, 0)
Frame53.Parent.LayoutOrder = 7
Frame53.Parent.Parent = Frame50.Parent.Parent
local TextButton43 = Instance.new('TextButton')
TextButton43.Name = "ResetSpeedButton"
TextButton43.Size = UDim2.new(1, -8, 0, 36)
TextButton43.BackgroundColor3 = Color3.fromRGB(70, 30, 100)
TextButton43.BackgroundTransparency = 0.1
TextButton43.Text = "RESET SPEED SETTINGS"
TextButton43.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton43.TextSize = 12
TextButton43.Font = TextLabel19.Font
TextButton43.LayoutOrder = 8
TextButton43.Parent = Frame53.Parent.Parent
local UICorner88 = Instance.new('UICorner')
UICorner88.CornerRadius = UDim.new(0, 6)
Frame45.Parent.InputBegan:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
Frame45.Parent.InputChanged:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
Frame45.Parent.InputEnded:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
Frame48.Parent.InputBegan:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
Frame48.Parent.InputChanged:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
Frame48.Parent.InputEnded:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
Frame51.Parent.InputBegan:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
Frame51.Parent.InputChanged:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
Frame51.Parent.InputEnded:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
Frame54.Parent.InputBegan:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
Frame54.Parent.InputChanged:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
Frame54.Parent.InputEnded:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
TextButton42.MouseButton1Click:Connect(function()
TweenInfo:new(0.3)
TweenService1:Create(TweenService1, Frame45, { }, {
    Size = UDim2.new(0.20000000000000004, 0, 1, 0)
})
TweenService1.Create:Play({
    Play = { }
})
TweenInfo:new(0.3)
TweenService1:Create(TweenService1, Frame48, { }, {
    Size = UDim2.new(0.475, 0, 1, 0)
})
TweenService1.Create:Play({
    Play = { }
})
isfolder("InvincibleFly")
makefolder("InvincibleFly")
local HttpService2 = game:GetService("HttpService")
warn("Failed to encode settings")
local TextLabel20 = Instance.new('TextLabel')
TextLabel20.Size = UDim2.new(0.8, 0, 0.1, 0)
TextLabel20.Position = UDim2.new(0.1, 0, 0.45, 0)
TextLabel20.BackgroundColor3 = Color3.fromRGB(80, 120, 80)
TextLabel20.BackgroundTransparency = 0.2
TextLabel20.Text = "Hover settings reset!"
TextLabel20.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel20.TextSize = 14
TextLabel20.Font = TextButton43.Font
TextLabel20.Parent = TextLabel9.Parent
TweenInfo:new(0.5)
TweenService1:Create(TweenService1, TextLabel20, { }, {
    BackgroundTransparency = 0.8
})
TweenService1.Create:Play({
    Play = { }
})
task.wait(2)
TextLabel20:Destroy(TextLabel20)
end)
TextButton43.MouseButton1Click:Connect(function()
TweenInfo:new(0.3)
TweenService1:Create(TweenService1, Frame51, { }, {
    Size = UDim2.new(0.13793103448275862, 0, 1, 0)
})
TweenService1.Create:Play({
    Play = { }
})
TweenInfo:new(0.3)
TweenService1:Create(TweenService1, Frame54, { }, {
    Size = UDim2.new(0.15254237288135594, 0, 1, 0)
})
TweenService1.Create:Play({
    Play = { }
})
isfolder("InvincibleFly")
makefolder("InvincibleFly")
local HttpService3 = game:GetService("HttpService")
warn("Failed to encode settings")
local TextLabel21 = Instance.new('TextLabel')
TextLabel21.Size = UDim2.new(0.8, 0, 0.1, 0)
TextLabel21.Position = UDim2.new(0.1, 0, 0.45, 0)
TextLabel21.BackgroundColor3 = Color3.fromRGB(80, 120, 80)
TextLabel21.BackgroundTransparency = 0.2
TextLabel21.Text = "Speed settings reset!"
TextLabel21.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel21.TextSize = 14
TextLabel21.Font = TextLabel20.Font
TextLabel21.Parent = TextLabel20.Parent
TweenInfo:new(0.5)
TweenService1:Create(TweenService1, TextLabel21, { }, {
    BackgroundTransparency = 0.8
})
TweenService1.Create:Play({
    Play = { }
})
task.wait(2)
TextLabel21:Destroy(TextLabel21)
end)
TextButton1.Parent.InputBegan:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
TextButton1.Parent.InputChanged:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
TextButton1.Parent.InputEnded:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
UICorner1.Parent.InputBegan:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
UICorner1.Parent.InputChanged:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
UICorner1.Parent.InputEnded:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
UICorner1.Parent.MouseButton1Click:Connect(function()
TweenInfo:new(0.4, { }, { })
TweenService1:Create(TweenService1, TextLabel21.Parent, { }, {
    Size = UDim2.new(0.8, 0, 0.7, 0)
})
TweenService1.Create:Play({
    Play = { }
})
TweenInfo:new(0.3)
TweenService1:Create(TweenService1, UICorner1.Parent, { }, {
    ImageColor3 = Color3.fromRGB(200, 150, 255)
})
TweenService1.Create:Play({
    Play = { }
})
end)
UICorner5.Parent.MouseButton1Click:Connect(function()
TweenInfo:new(0.4, { }, { })
TweenService1:Create(TweenService1, TextLabel21.Parent, { }, {
    Size = UDim2.new(0, 0, 0, 0)
})
TweenService1.Create:Play({
    Play = { }
})
TweenInfo:new(0.3)
TweenService1:Create(TweenService1, UICorner1.Parent, { }, {
    ImageColor3 = Color3.fromRGB(240, 200, 255)
})
TweenService1.Create:Play({
    Play = { }
})
task.wait(0.4)
end)
ImageLabel3.Parent.Parent:Destroy(ImageLabel3.Parent.Parent)
ScreenGui1.Parent:WaitForChild({
    Character = {
        GetChildren = { },
        Humanoid = {
            PlatformStand = false
        },
        HumanoidRootPart = {
            FlightVelocity = {
                Destroy = { }
            },
            FlightGyro = {
                Destroy = { }
            },
            FindFirstChild = { }
        },
        FindFirstChild = BodyGyro1.Parent
    },
    WaitForChild = ScreenGui1.Parent
}, "PlayerGui")
Frame42.Parent:FindFirstChild(ScreenGui1.Parent, "MobileFlyControls")
local Frame55 = Instance.new('Frame')
Frame55.Name = "MobileControls"
Frame55.Size = UDim2.new(1, 0, 1, 0)
Frame55.BackgroundTransparency = 1
Frame55.Parent = Frame42.Parent
local TextButton44 = Instance.new('TextButton')
TextButton44.Name = "FlyButton"
TextButton44.Size = UDim2.new(0.15, 0, 0.15, 0)
TextButton44.Position = UDim2.new(0.929, 0, 0.5, 0)
TextButton44.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton44.BackgroundTransparency = 0.2
TextButton44.BackgroundColor3 = Color3.fromRGB(255, 60, 60)
TextButton44.Text = "FLY"
TextButton44.TextColor3 = Color3.new(1, 1, 1)
TextButton44.TextScaled = true
TextButton44.Font = TextLabel21.Font
TextButton44.TextStrokeTransparency = 0.5
local UICorner89 = Instance.new('UICorner')
UICorner89.CornerRadius = UDim.new(1, 0)
UICorner89.Parent = TextButton44
local ImageLabel4 = Instance.new('ImageLabel')
ImageLabel4.Name = "Shadow"
ImageLabel4.Size = UDim2.new(1, 10, 1, 10)
ImageLabel4.Position = UDim2.new(0, -5, 0, -5)
ImageLabel4.BackgroundTransparency = 1
ImageLabel4.Image = "rbxassetid://1316045217"
ImageLabel4.ImageColor3 = Color3.new(0, 0, 0)
ImageLabel4.ImageTransparency = 0.8
ImageLabel4.ScaleType = ImageLabel3.ScaleType
ImageLabel3.SliceCenter:new(10, 10, 118, 118)
ImageLabel4.SliceCenter = ImageLabel3.SliceCenter
ImageLabel4.Parent = UICorner89.Parent
ImageLabel4.Parent.InputBegan:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
ImageLabel4.Parent.InputEnded:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
local TextButton45 = Instance.new('TextButton')
TextButton45.Name = "BoostButton"
TextButton45.Size = UDim2.new(0.15, 0, 0.15, 0)
TextButton45.Position = UDim2.new(0.929, 0, 0.35, 0)
TextButton45.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton45.BackgroundTransparency = 0.2
TextButton45.BackgroundColor3 = Color3.fromRGB(0, 150, 255)
TextButton45.Text = "BOOST"
TextButton45.TextColor3 = Color3.new(1, 1, 1)
TextButton45.TextScaled = true
TextButton45.Font = TextButton44.Font
TextButton45.TextStrokeTransparency = 0.5
local UICorner90 = Instance.new('UICorner')
UICorner90.CornerRadius = UDim.new(1, 0)
UICorner90.Parent = TextButton45
local ImageLabel5 = Instance.new('ImageLabel')
ImageLabel5.Name = "Shadow"
ImageLabel5.Size = UDim2.new(1, 10, 1, 10)
ImageLabel5.Position = UDim2.new(0, -5, 0, -5)
ImageLabel5.BackgroundTransparency = 1
ImageLabel5.Image = "rbxassetid://1316045217"
ImageLabel5.ImageColor3 = Color3.new(0, 0, 0)
ImageLabel5.ImageTransparency = 0.8
ImageLabel5.ScaleType = ImageLabel4.ScaleType
ImageLabel4.SliceCenter:new(10, 10, 118, 118)
ImageLabel5.SliceCenter = ImageLabel4.SliceCenter
ImageLabel5.Parent = UICorner90.Parent
ImageLabel5.Parent.InputBegan:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
ImageLabel5.Parent.InputEnded:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'UserInputType'
end)
ImageLabel4.Parent.Parent = Frame55
ImageLabel5.Parent.Parent = ImageLabel4.Parent.Parent
ImageLabel4.Parent.MouseButton1Click:Connect(function()
BodyGyro1.Parent:FindFirstChild({
    GetChildren = { },
    Humanoid = {
        PlatformStand = false
    },
    HumanoidRootPart = {
        FlightVelocity = {
            Destroy = { }
        },
        FlightGyro = {
            Destroy = { }
        },
        FindFirstChild = { }
    },
    FindFirstChild = BodyGyro1.Parent
}, "Humanoid")
BodyGyro1.Parent:FindFirstChild({
    GetChildren = { },
    Humanoid = {
        PlatformStand = false
    },
    HumanoidRootPart = {
        FlightVelocity = {
            Destroy = { }
        },
        FlightGyro = {
            Destroy = { }
        },
        FindFirstChild = { }
    },
    FindFirstChild = BodyGyro1.Parent
}, "HumanoidRootPart")
local BodyVelocity2 = Instance.new('BodyVelocity')
BodyVelocity2.Name = "FlightVelocity"
BodyVelocity2.Parent = BodyGyro1.Parent
BodyVelocity2.MaxForce = Vector3.new(9000000000, 9000000000, 9000000000)
BodyVelocity2.Velocity = Vector3.new(0, 0, 0)
local BodyGyro2 = Instance.new('BodyGyro')
BodyGyro2.Name = "FlightGyro"
BodyGyro2.Parent = BodyVelocity2.Parent
BodyGyro2.MaxTorque = Vector3.new(9000000000, 9000000000, 9000000000)
BodyGyro2.P = 10000
BodyGyro2.D = 500
BodyGyro1.Parent.Died:Connect(function()
BodyGyro2.Parent:FindFirstChild({
    GetChildren = { },
    Humanoid = {
        PlatformStand = false
    },
    HumanoidRootPart = {
        FlightVelocity = {
            Destroy = { }
        },
        FlightGyro = {
            Destroy = { }
        },
        FindFirstChild = { }
    },
    FindFirstChild = BodyGyro2.Parent
}, "HumanoidRootPart")
Players1.LocalPlayer.Character.HumanoidRootPart:FindFirstChild({
    FlightVelocity = {
        Destroy = { }
    },
    FlightGyro = {
        Destroy = { }
    },
    FindFirstChild = { }
}, "FlightVelocity")
Players1.LocalPlayer.Character.HumanoidRootPart.FlightVelocity:Destroy({
    Destroy = { }
})
Players1.LocalPlayer.Character.HumanoidRootPart:FindFirstChild({
    FlightVelocity = {
        Destroy = { }
    },
    FlightGyro = {
        Destroy = { }
    },
    FindFirstChild = { }
}, "FlightGyro")
Players1.LocalPlayer.Character.HumanoidRootPart.FlightGyro:Destroy({
    Destroy = { }
})
BodyGyro2.Parent:FindFirstChild({
    GetChildren = { },
    Humanoid = {
        PlatformStand = false
    },
    HumanoidRootPart = {
        FlightVelocity = {
            Destroy = { }
        },
        FlightGyro = {
            Destroy = { }
        },
        FindFirstChild = { }
    },
    FindFirstChild = BodyGyro2.Parent
}, "Humanoid")
Players1.LocalPlayer.Character:GetChildren({
    GetChildren = { },
    Humanoid = {
        PlatformStand = false
    },
    HumanoidRootPart = {
        FlightVelocity = {
            Destroy = { }
        },
        FlightGyro = {
            Destroy = { }
        },
        FindFirstChild = { }
    },
    FindFirstChild = BodyGyro2.Parent
})
end)
RunService1.Heartbeat:Connect(function()
end)
BodyGyro1.Parent:IsA(BodyGyro2.Parent, "Humanoid")
Players1.LocalPlayer.Character:GetChildren({
    GetChildren = { },
    Humanoid = {
        PlatformStand = false
    },
    HumanoidRootPart = {
        FlightVelocity = {
            Destroy = { }
        },
        FlightGyro = {
            Destroy = { }
        },
        FindFirstChild = { }
    },
    FindFirstChild = BodyGyro2.Parent
})
BodyGyro1.Parent:LoadAnimation(BodyGyro2.Parent, Animation4)
BodyGyro1.Parent.LoadAnimation:Play({
    Destroy = { },
    Stop = { },
    TimePosition = 0.1,
    IsPlaying = { },
    Looped = false,
    Play = { },
    AdjustSpeed = { }
})
BodyGyro1.Parent.LoadAnimation:AdjustSpeed({
    Destroy = { },
    Stop = { },
    TimePosition = 0.1,
    IsPlaying = { },
    Looped = false,
    Play = { },
    AdjustSpeed = { }
}, 0.3)
RunService1.Heartbeat:Connect(function()
BodyGyro1.Parent.LoadAnimation:Stop({
    Destroy = { },
    Stop = { },
    TimePosition = 0.1,
    IsPlaying = { },
    Looped = false,
    Play = { },
    AdjustSpeed = { }
}, 0.1)
BodyGyro1.Parent.LoadAnimation:Destroy({
    Destroy = { },
    Stop = { },
    TimePosition = 0.1,
    IsPlaying = { },
    Looped = false,
    Play = { },
    AdjustSpeed = { }
})
Players1.LocalPlayer.Character:GetChildren({
    GetChildren = { },
    Humanoid = {
        PlatformStand = false
    },
    HumanoidRootPart = {
        FlightVelocity = {
            Destroy = { }
        },
        FlightGyro = {
            Destroy = { }
        },
        FindFirstChild = { }
    },
    FindFirstChild = BodyGyro2.Parent
})
end)
RunService1.RenderStepped:Connect(function()
end)
end)
ImageLabel5.Parent.MouseButton1Click:Connect(function()
end)
BodyGyro2.Parent:FindFirstChild({
    GetChildren = { },
    Humanoid = {
        PlatformStand = false
    },
    HumanoidRootPart = {
        FlightVelocity = {
            Destroy = { }
        },
        FlightGyro = {
            Destroy = { }
        },
        FindFirstChild = { }
    },
    FindFirstChild = BodyGyro2.Parent
}, "Humanoid")
BodyGyro1.Parent.Died:Connect(function()
end)
Players1.LocalPlayer.CharacterAdded:Connect(function()
-- error: ./input.lua:911: attempt to index nil with 'WaitForChild'
end)
