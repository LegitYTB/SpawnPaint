local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

local Window = Library.CreateLib("Maxwell Maniacks Doors Hub", "BloodTheme")

local Tab = Window:NewTab("Items")
local Section = Tab:NewSection("Items Section")

Section:NewButton("NVCS-3000", "ButtonInfo", function()
    _G.scanner_fps = 30
_G.disable_static = false
loadstring(game:HttpGet("https://raw.githubusercontent.com/notpoiu/Scripts/main/Scanner.lua"))()
end)

Section:NewButton("Seek Plushie", "ButtonInfo", function()
    local plr = game.Players.LocalPlayer
local hum = plr.Character:WaitForChild("Humanoid")

local plush = game:GetObjects("rbxassetid://13613269677")[1]
plush.Parent = plr.Backpack
local anim = hum:LoadAnimation(plush.A.Hold)

plush.Equipped:Connect(function()
  anim:Play()
end)
plush.Unequipped:Connect(function()
  anim:Stop()
end)

plush.Activated:Connect(function()
  plush.Toy:Play()
end)
end)

Section:NewButton("Magnet", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/MrNeRD0/Doors-Hack/main/MagnetByNerd.lua"))
end)

Section:NewButton("Buffed Shears", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/MrNeRD0/Doors-Hack/main/shears_done.lua"))();
end)

Section:NewButton("1,000,000 Knobs Modifier", "ButtonInfo", function()
    local CustomModifiers = loadstring(game:HttpGet('https://raw.githubusercontent.com/iimateiYT/Custom-Modifiers/main/Source.lua'))() -- Load the Custom Modifiers module

CustomModifiers:ToggleConnotations(true) -- Helpful debug messages

CustomModifiers:CreateFloor({
	Title = "1,000,000 Knobs", -- Floor name
	Destination = "Hotel", -- Destination of where the elevator should lead to (Hotel, Mines, Backdoor)
	Image = "rbxassetid://13613269677", -- Background image for the floor
	Font = Enum.Font.Oswald, -- Font text for the floor text
	FontColor = Color3.fromRGB(255, 222, 189), -- Font color for the floor text
	Theme = Color3.fromRGB(252, 219, 187), -- The stroke and arrow color at the floor picker
	Sort = 1, -- Sorting order for the floor
	Requires = {
		NeedAll = false, -- If it needs all the achievements below
		Achievements = { -- Achievements, found in the documentations
			"Join", 
			"SpecialQATester"
		}
	},
	Moddable = true -- Makes modifiers visible for the floor
})

CustomModifiers:CreateCategory({
	Title = "Example Category", -- Category name
	Sort = 0, -- Category sort
	Floor = "Example Floor", -- Category floor
	Color = Color3.fromRGB(255, 222, 189) -- Category color
})

CustomModifiers:CreateModifier({
	Title = "1,000,000 Knobs", -- Modifier name
	Desc = "This is an example custom modifier!", -- Modifier description
	Color = Color3.fromRGB(255, 222, 189), -- Modifier color
	Category = "Example Category", -- Modifier category (handles which floor the modifier should be under)
	Sort = 1, -- Modifier sort
	Merge = "Combine", -- Combines two or more modifiers together so you can only select one in the list
	Bonus = 1000000, -- Modifier knob bonus
	Solo = false, -- Make it the only selectable modifier
	Penalties = {
		NoRift = true, -- No rift display
		NoProgress = true -- No progress display
	},
	Unlock = "Join", -- Achievement needed to activate the modifier
	Activation = [[ -- Custom code to execute right after the loading screen goes away
		print("Custom Code Logic In Here!")
	]]
})

end)
Section:NewButton("Spawn trollface", "ButtonInfo", function()

loadstring(game:HttpGet("https://api.hugebonus.xyz/scripts/TrollFaceSpawner.lua"))()
end)
Section:NewButton("mspaint", "ButtonInfo", function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/notpoiu/mspaint/main/main.lua"))()
end)
Section:NewButton("Trolling script", "ButtonInfo", function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/Ginxys/Doors-Troll/main/Script.Lua"))()
end)
Section:NewButton("Neuron x", "ButtonInfo", function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/Yumiara/Python/main/Main.lua"))()
end)
Section:NewButton("Rocket launcher", "ButtonInfo", function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/notpoiu/Scripts/main/rocketLauncher.lua"))()
end)
Section:NewButton("Morph script (need keyboard to deactivate)", "ButtonInfo", function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/ChronoAccelerator/Public-Scripts/main/Morphing/MorphScript.lua"))();
end)
