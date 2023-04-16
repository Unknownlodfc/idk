local controls = require(game:GetService("Players").LocalPlayer.PlayerScripts.PlayerModule):GetControls() controls:Enable()
local cmdlp = game:GetService("Players").LocalPlayer
cmdlp.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Jumping,true) 
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")


ScreenGui.Parent = game.CoreGui

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.new(2,5,0)
Frame.BorderColor3 = Color3.new(6,4,9)
Frame.Position = UDim2.new(0.8,0.5,0.7)
Frame.Size = UDim2.new(0.2,0,0.3)
Frame.Active = true
Frame.Draggable = true

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.new(2,5,2)
TextButton.BackgroundTransparency = 0
TextButton.Position = UDim2.new(0.103524067, 0, 0.200333327, 0)
TextButton.Size = UDim2.new(0.8,0.9,0.6)
TextButton.Font = Enum.Font.SourceSansLight
TextButton.FontSize = Enum.FontSize.Size14
TextButton.Text = "Infi Jump"
TextButton.TextScaled = true
TextButton.TextSize = 8
TextButton.TextWrapped = true

run = false
TextButton.MouseButton1Click:connect(function()
run = not run
game:GetService"Players".LocalPlayer.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")
end)
