local kavoUi = loadstring(game:HttpGet("https://pastebin.com/raw/vff1bQ9F"))()
local window = kavoUi.CreateLib("The Maze V2","BloodTheme")

---Tabs

local Tab1 = window:NewTab("Main")
local Tab1Section = Tab1:NewSection("Main")
local Tab2 = window:NewTab("Player")
local Tab2Section = Tab2:NewSection("Player")
local Tab3 = window:NewTab("Teleport")
local Tab3Section = Tab3:NewSection("click hole firts to tp everywhere")

---Buttons

Tab1Section:NewButton("Inf Axe & Esp","Inf axe",function()
loadstring(game:HttpGet('https://pastebin.com/raw/tDZ4frsF'))()
end)

Tab1Section:NewButton("Fly Gui","For Pc And Mobile",function()
loadstring(game:HttpGet('https://pastebin.com/raw/5bXMQ6Ns'))()
end)

Tab1Section:NewButton("Infinite yield","Admin",function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

Tab2Section:NewSlider("Speed", "Sussy Speed", 120, 16, function(v)
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = v
end)

Tab2Section:NewSlider("Fov", "Sussy Fov", 120, 50, function(v)
game.Workspace.CurrentCamera.FieldOfView = v
end)

Tab2Section:NewButton("Noclip","Lets throgh the walls",function()
loadstring(game:HttpGet("https://pastebin.com/raw/pKV2Ys4E"))()
end)

Tab3Section:NewButton("Hole","Hole",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-231, -40, 37)
end)

Tab3Section:NewButton("Safe zone 1","safe zone",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(81, -89, -86)
end)

Tab3Section:NewButton("Safe zone 2","Safe zone 2",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(182, -87, -224)
end)

Tab3Section:NewButton("Safe Zone 3","safe zone 3",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(214, -89, 2)
end)

Tab3Section:NewButton("Camper","Holy Cow",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-179, 23, -142)
end)

Tab3Section:NewButton("Stone House","Stone House",function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(42, 19, -215)
end)
