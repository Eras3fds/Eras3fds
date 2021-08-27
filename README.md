-- Made By MatterDev#4894
-- Discord https://discord.gg/5AmJ6GAJxt 
local LoginScreen = Instance.new("ScreenGui")
local login = Instance.new("ImageLabel")
local Enter = Instance.new("TextButton")
local label = Instance.new("TextLabel")
local box = Instance.new("ImageLabel")
local password = Instance.new("TextBox")
local main = Instance.new("ImageLabel")
local Arsenal = Instance.new("TextButton")
local MurderMystery2 = Instance.new("TextButton")
local DaHood = Instance.new("TextButton")
local BeeSwarmSimulator = Instance.new("TextButton")
local BulidABoatForTreasure = Instance.new("TextButton")
local Destruction = Instance.new("TextButton")
local AnimeFigtersSimulator = Instance.new("TextButton")
local Adoptme = Instance.new("TextButton")
local label_2 = Instance.new("TextLabel")
local label_3 = Instance.new("TextLabel")
local label_4 = Instance.new("TextLabel")
local label_5 = Instance.new("TextLabel")
local label_6 = Instance.new("TextLabel")
--[[ Properties ]]--
LoginScreen.Name = "LoginScreen"
LoginScreen.Parent = game.Workspace

login.Name = "login"
login.Parent = LoginScreen
login.BackgroundColor3 = Color3.new(1, 1, 1)
login.BackgroundTransparency = 1
login.Position = UDim2.new(0.274337471, 0, 0.259393007, 0)
login.Size = UDim2.new(0, 469, 0, 253)
login.Image = "rbxassetid://3570695787"
login.ImageColor3 = Color3.new(0.305882, 0.305882, 0.305882)
login.ScaleType = Enum.ScaleType.Slice
login.SliceCenter = Rect.new(100, 100, 100, 100)

Enter.Name = "Enter"
Enter.Parent = login
Enter.BackgroundColor3 = Color3.new(0.203922, 0.184314, 0.184314)
Enter.BorderSizePixel = 0
Enter.Position = UDim2.new(0.267320842, 0, 0.612393618, 0)
Enter.Size = UDim2.new(0, 217, 0, 66)
Enter.Font = Enum.Font.GothamBold
Enter.Text = "Submit"
Enter.TextColor3 = Color3.new(1, 1, 1)
Enter.TextScaled = true
Enter.TextSize = 14
Enter.TextWrapped = true

label.Name = "label"
label.Parent = Enter
label.BackgroundColor3 = Color3.new(1, 1, 1)
label.BackgroundTransparency = 1
label.Position = UDim2.new(-0.577757955, 0, -0.893939376, 0)
label.Size = UDim2.new(0, 469, 0, 66)
label.Font = Enum.Font.GothamBold
label.Text = "Key Is TheXersnNewX765"
label.TextColor3 = Color3.new(1, 1, 1)
label.TextScaled = true
label.TextSize = 14
label.TextWrapped = true

box.Name = "box"
box.Parent = login
box.BackgroundColor3 = Color3.new(1, 1, 1)
box.BackgroundTransparency = 1
box.Position = UDim2.new(0.0810234547, 0, 0.105591789, 0)
box.Size = UDim2.new(0, 405, 0, 70)
box.Image = "rbxassetid://3570695787"
box.ImageColor3 = Color3.new(0.211765, 0.211765, 0.211765)
box.ScaleType = Enum.ScaleType.Slice
box.SliceCenter = Rect.new(100, 100, 100, 100)

password.Name = "password"
password.Parent = box
password.BackgroundColor3 = Color3.new(0.305882, 0.286275, 0.301961)
password.BackgroundTransparency = 1
password.BorderSizePixel = 0
password.Position = UDim2.new(0.00164704502, 0, 0.03038821, 0)
password.Size = UDim2.new(0, 405, 0, 66)
password.Font = Enum.Font.SourceSansLight
password.PlaceholderText = "Key Here"
password.Text = ""
password.TextColor3 = Color3.new(1, 1, 1)
password.TextSize = 60
password.TextXAlignment = Enum.TextXAlignment.Left

main.Name = "main"
main.Parent = LoginScreen
main.BackgroundColor3 = Color3.new(1, 1, 1)
main.BackgroundTransparency = 1
main.BorderColor3 = Color3.new(0.105882, 0.164706, 0.207843)
main.Position = UDim2.new(0.549423993, 0, 0.65871942, 0)
main.Size = UDim2.new(0, 469, 0, 253)
main.Visible = false
main.Image = "rbxassetid://3570695787"
main.ImageColor3 = Color3.new(0.305882, 0.305882, 0.305882)
main.ScaleType = Enum.ScaleType.Slice
main.SliceCenter = Rect.new(100, 100, 100, 100)

Arsenal.Name = "Arsenal"
Arsenal.Parent = main
Arsenal.BackgroundColor3 = Color3.new(0.431373, 0.431373, 0.431373)
Arsenal.Position = UDim2.new(0.0149253746, 0, 0.059288539, 0)
Arsenal.Size = UDim2.new(0, 200, 0, 50)
Arsenal.Font = Enum.Font.SourceSans
Arsenal.Text = "Arsenal"
Arsenal.TextColor3 = Color3.new(0, 0, 0)
Arsenal.TextSize = 14
Arsenal.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/T3fzg7tm", true))()
end)

MurderMystery2.Name = "Murder Mystery 2"
MurderMystery2.Parent = main
MurderMystery2.BackgroundColor3 = Color3.new(0.431373, 0.431373, 0.431373)
MurderMystery2.Position = UDim2.new(0.0149253746, 0, 0.284584969, 0)
MurderMystery2.Size = UDim2.new(0, 200, 0, 50)
MurderMystery2.Font = Enum.Font.SourceSans
MurderMystery2.Text = "Murder Mystery 2"
MurderMystery2.TextColor3 = Color3.new(0, 0, 0)
MurderMystery2.TextSize = 14
MurderMystery2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(("https://raw.githubusercontent.com/Ethanoj1/EclipseMM2/master/Script"),true))() 
end)

DaHood.Name = "Da Hood"
DaHood.Parent = main
DaHood.BackgroundColor3 = Color3.new(0.431373, 0.431373, 0.431373)
DaHood.Position = UDim2.new(0.0149253746, 0, 0.525691688, 0)
DaHood.Size = UDim2.new(0, 200, 0, 50)
DaHood.Font = Enum.Font.SourceSans
DaHood.Text = "Da Hood"
DaHood.TextColor3 = Color3.new(0, 0, 0)
DaHood.TextSize = 14
DaHood.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/urmomugly/lua-project/main/Script%26/RAYXV001'))()
end)

BeeSwarmSimulator.Name = "Bee Swarm Simulator"
BeeSwarmSimulator.Parent = main
BeeSwarmSimulator.BackgroundColor3 = Color3.new(0.431373, 0.431373, 0.431373)
BeeSwarmSimulator.Position = UDim2.new(0.0149253746, 0, 0.754940689, 0)
BeeSwarmSimulator.Size = UDim2.new(0, 200, 0, 50)
BeeSwarmSimulator.Font = Enum.Font.SourceSans
BeeSwarmSimulator.Text = "Bee Swarm Simulator"
BeeSwarmSimulator.TextColor3 = Color3.new(0, 0, 0)
BeeSwarmSimulator.TextSize = 14
BeeSwarmSimulator.MouseButton1Down:connect(function()
	loadstring(game:GetObjects("rbxassetid://4384103988")[0X1].Source)("Pepsi Swarm")
end)

BulidABoatForTreasure.Name = "Bulid A Boat For Treasure"
BulidABoatForTreasure.Parent = main
BulidABoatForTreasure.BackgroundColor3 = Color3.new(0.431373, 0.431373, 0.431373)
BulidABoatForTreasure.Position = UDim2.new(0.560767591, 0, 0.059288539, 0)
BulidABoatForTreasure.Size = UDim2.new(0, 200, 0, 50)
BulidABoatForTreasure.Font = Enum.Font.SourceSans
BulidABoatForTreasure.Text = "Build A Boat For Treasure"
BulidABoatForTreasure.TextColor3 = Color3.new(0, 0, 0)
BulidABoatForTreasure.TextSize = 14
BulidABoatForTreasure.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Vynixius/main/Build%20A%20Boat%20For%20Treasure/BABFT"))()
end)

Destruction.Name = "Destruction"
Destruction.Parent = main
Destruction.BackgroundColor3 = Color3.new(0.431373, 0.431373, 0.431373)
Destruction.Position = UDim2.new(0.560767591, 0, 0.284584969, 0)
Destruction.Size = UDim2.new(0, 200, 0, 50)
Destruction.Font = Enum.Font.SourceSans
Destruction.Text = "Destruction Simulator"
Destruction.TextColor3 = Color3.new(0, 0, 0)
Destruction.TextSize = 14
Destruction.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/AquaModz/DestructionSIMModded/main/DestructionSimAqua.lua'))()
end)

AnimeFigtersSimulator.Name = "Anime Figters Simulator"
AnimeFigtersSimulator.Parent = main
AnimeFigtersSimulator.BackgroundColor3 = Color3.new(0.431373, 0.431373, 0.431373)
AnimeFigtersSimulator.Position = UDim2.new(0.560767591, 0, 0.525691688, 0)
AnimeFigtersSimulator.Size = UDim2.new(0, 200, 0, 50)
AnimeFigtersSimulator.Font = Enum.Font.SourceSans
AnimeFigtersSimulator.Text = "Anime Fighters Simulator"
AnimeFigtersSimulator.TextColor3 = Color3.new(0, 0, 0)
AnimeFigtersSimulator.TextSize = 14
AnimeFigtersSimulator.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/rbxhubs/robloxscript/main/script.lua"))()
end)

Adoptme.Name = "Adopt me"
Adoptme.Parent = main
Adoptme.BackgroundColor3 = Color3.new(0.431373, 0.431373, 0.431373)
Adoptme.Position = UDim2.new(0.560767591, 0, 0.754940689, 0)
Adoptme.Size = UDim2.new(0, 200, 0, 50)
Adoptme.Font = Enum.Font.SourceSans
Adoptme.Text = "Adopt Me"
Adoptme.TextColor3 = Color3.new(0, 0, 0)
Adoptme.TextSize = 14
Adoptme.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/1201for/V.G-Hub/main/V.Ghub'))()
end)

label_2.Name = "label"
label_2.Parent = main
label_2.BackgroundColor3 = Color3.new(1, 1, 1)
label_2.BackgroundTransparency = 1
label_2.Position = UDim2.new(0.428571433, 0, 0.0270092636, 0)
label_2.Size = UDim2.new(0, 66, 0, 66)
label_2.Font = Enum.Font.GothamBold
label_2.Text = "X"
label_2.TextColor3 = Color3.new(1, 1, 1)
label_2.TextSize = 34
label_2.TextWrapped = true

label_3.Name = "label"
label_3.Parent = main
label_3.BackgroundColor3 = Color3.new(1, 1, 1)
label_3.BackgroundTransparency = 1
label_3.Position = UDim2.new(0.428571433, 0, 0.256258279, 0)
label_3.Size = UDim2.new(0, 66, 0, 66)
label_3.Font = Enum.Font.GothamBold
label_3.Text = "E"
label_3.TextColor3 = Color3.new(1, 1, 1)
label_3.TextSize = 34
label_3.TextWrapped = true

label_4.Name = "label"
label_4.Parent = main
label_4.BackgroundColor3 = Color3.new(1, 1, 1)
label_4.BackgroundTransparency = 1
label_4.Position = UDim2.new(0.428571433, 0, 0.481554717, 0)
label_4.Size = UDim2.new(0, 66, 0, 66)
label_4.Font = Enum.Font.GothamBold
label_4.Text = "R"
label_4.TextColor3 = Color3.new(1, 1, 1)
label_4.TextSize = 34
label_4.TextWrapped = true

label_5.Name = "label"
label_5.Parent = main
label_5.BackgroundColor3 = Color3.new(1, 1, 1)
label_5.BackgroundTransparency = 1
label_5.Position = UDim2.new(0.428571433, 0, 0.722661436, 0)
label_5.Size = UDim2.new(0, 66, 0, 66)
label_5.Font = Enum.Font.GothamBold
label_5.Text = "S"
label_5.TextColor3 = Color3.new(1, 1, 1)
label_5.TextSize = 34
label_5.TextWrapped = true

label_6.Name = "label"
label_6.Parent = LoginScreen
label_6.BackgroundColor3 = Color3.new(1, 1, 1)
label_6.BackgroundTransparency = 1
label_6.Position = UDim2.new(0.357142866, 0, 0.415971398, 0)
label_6.Size = UDim2.new(0, 161, 0, 46)
label_6.Font = Enum.Font.GothamBold
label_6.Text = ""
label_6.TextColor3 = Color3.new(1, 1, 1)
label_6.TextScaled = true
label_6.TextSize = 14
label_6.TextWrapped = true
-- Scripts:
function SCRIPT_IGQS88_FAKESCRIPT() -- Enter.LocalScript 
	getfenv().script = Instance.new('LocalScript', Enter)

	
	local password = script.Parent.Parent.box.password
	
	local main = script.Parent.Parent.Parent.main
	
	local login = script.Parent.Parent
	
	local passwords = {"TheXersnNewX765"}
	
	script.Parent.MouseButton1Click:Connect(function() 
		
		for _, v in pairs(passwords) do
			
			if password.Text == v then
				
				password.Text = " "
				
				password.PlaceholderText = " "
				
				wait(0.1)
				
				password.Text = "Correct password."
				
				wait(1)
				
				password.Text = "Loading GUI."
				
				wait(1)
				
				password.Text = "Loading GUI.."
				
				wait(1)
				
				password.Text = "Loading GUI..."
				
				wait(1)
				
				password.Text = "Done."
				
				wait(0.5)
				
				script.Parent.Parent.Parent.main.Visible = true
				
				script.Parent.Parent.Parent.login.Visible = false
				
			else
				
				password.Text = " "
	
				password.PlaceholderText = " "
				
				wait(0.1)
				
				password.Text = "Invalid password."
				
				wait(1)
				
							password.Text = ""
				
				password.PlaceholderText = "Key Here"
				
			end
			
		end
		
	end)
	

end
coroutine.resume(coroutine.create(SCRIPT_IGQS88_FAKESCRIPT))
function SCRIPT_EDOQ81_FAKESCRIPT() -- login.Draggable 
	getfenv().script = Instance.new('LocalScript', login)

	script.Parent.Active = true
	script.Parent.Draggable = true

end
coroutine.resume(coroutine.create(SCRIPT_EDOQ81_FAKESCRIPT))
function SCRIPT_IVSJ67_FAKESCRIPT() -- main.Draggable 
	getfenv().script = Instance.new('LocalScript', main)

	script.Parent.Active = true
	script.Parent.Draggable = true

end
coroutine.resume(coroutine.create(SCRIPT_IVSJ67_FAKESCRIPT))
