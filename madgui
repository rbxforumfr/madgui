--[[
Madcity gui by Ilhan#0001
]]


if game.PlaceId ==  1224212277 then

    print('Executed For ARB')
    local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
    local Window = Library.CreateLib("Madcity gui", "Ocean")
    local Main = Window:NewTab("Menu")
    local Credits = Window:NewTab("Credits")
    local kill = Window:NewTab("Téléport")

    --Main
    local MainSection = Main:NewSection("Main")

    
    --Player
    local PlayerSection = Main:NewSection("Player")

    PlayerSection:NewSlider("Walkspeed", "Changes the player walkspeed", 250, 16, function(s)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
    end)

    PlayerSection:NewSlider("JumpPower", "Changes the player walkspeed", 500, 50, function(s)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
    end)

    PlayerSection:NewToggle("Godmode", "Grants The Player God Mode", function(v)
        getgenv().godmode = v
        while true do
            if not getgenv().godmode then return end
            print("Debug")
            game.Players.LocalPlayer.Character.Humanoid.Health = math.huge
            wait()
        end
    end)

    --Credits
    local CreditsSection = Credits:NewSection(".")
    local Extras = Credits:NewSection(".")

    CreditsSection:NewButton("Crée par Ilhan#0001", "héhé", function()
    end)

    CreditsSection:NewButton("Rejoint le discord", "https://discord.gg/w74gkGy6", function()
    end)
    --Credits
    local killSection = kill:NewSection("Main")
 
    -- Teleports
    killSection:NewDropdown("Teleports", "Teleports the player", {"Pyramid", "Bank", "Casino", "Criminal Base", "Police Base 1", "Police Base 2", "disco", "hero base", "airport"}, function(v)
        print(v)
        
        if v == "Pyramid" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1052.604, 20.954, -504.085)
        end

        if v == "Bank" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(681.571, 81.725, 580.626)
        end

        if v == "Casino" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1691.108, 38.367, 516.814)
        end

        if v == "Criminal Base" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2141.82, 23.465, 448.973)
        end

        if v == "Police Base 1" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-995.999, 50.582, -2948.06)
        end

        if v == "Police Base 2" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-60, 62, -278)
        end

        if v == "disco" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1361.828, 140.819, -54.59)
        end

        if v == "hero base" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-831.899, 343.878, 818.151)
        end

        if v == "airport" then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2477.313, 22.796, -1194.55)
        end

    end)


end   
