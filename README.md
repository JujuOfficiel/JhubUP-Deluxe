local  = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()
local Window = Rayfield:CreateWindow({
   Name = "🎩JHub🎩 | Undetected | v5.0.3 | DELUXE",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "JHub - Loading, please wait.",
   LoadingSubtitle = "by Juju",
   ShowText = "Show JHub Deluxe", -- for mobile users to unhide rayfield, change if you'd like
   Theme = "AmberGlow", -- Check https://docs.sirius.menu/rayfield/configuration/themes

   ToggleUIKeybind = "K", -- The keybind to toggle the UI visibility (string like "K" or Enum.KeyCode)

   DisableRayfieldPrompts = true,
   DisableBuildWarnings = false, -- Prevents Rayfield from warning when the script has a version mismatch with the interface

   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "JHub_K7893Deluxe416"
   },

   Discord = {
      Enabled = true, -- Prompt the user to join your Discord server if their executor supports it
      Invite = "Q5MZxNDtWa", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },

   KeySystem = true, -- Set this to true to use our key system
   KeySettings = {
      Title = "Juju Hub | KeySystem",
      Subtitle = "The key will change every week",
      Note = "Join Discord and complete steps to get the key (.gg/Q5MZxNDtWa)", -- Use this to tell the user how to get a key
      FileName = "JHub_Deluxe_5-0-3", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"KEY_GB78YUu6g57kTGbynfut8485btbTBFt4b6i6fh5K646giuUOd7"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

local Tab = Window:CreateTab("📜Welcome",104365492568677) -- Title, Image

local Paragraph = Tab:CreateParagraph({Title = "Welcome !", Content = "If you need any help join : https://discord.gg/Q5MZxNDtWa"})
local Paragraph = Tab:CreateParagraph({Title = "New Version !", Content = "Updated on 11/20/2025 v5.0.3"})
local Paragraph = Tab:CreateParagraph({Title = "For More Updates", Content = "Juju Hub is updated weekly if not, get the latest version on the the loadstring itself, scriptblox, if the script is broken or you can't find the latest version join the discord : https://discord.gg/Q5MZxNDtWa"})

local Button = Tab:CreateButton({
   Name = "Destroy JHub",
   Callback = function()
   Rayfield:Destroy()
   end,
})

local Paragraph = Tab:CreateParagraph({Title = "LocalConfig", Content = "Press K to hide/open gui, use Destroy UI to boot the AMPK (for people that coported EFIc)"})

local Tab = Window:CreateTab("🎲Misc", 104365492568677) -- Title, Image

local Button = Tab:CreateButton({
   Name = "Combat Script (Aimbot, ESP, Hitbox)",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/ItsIYce/Iyce/refs/heads/main/main.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "NEW - VAPE Systems (All combat aimbot and things you need)",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/AsuraXowner/SentinelVAPE/refs/heads/main/NewMainScript.lua", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Infinite Yield",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Infinite-Yield_500"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Dex",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/peyton2465/Dex/master/out.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Mobile Aimbot",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Aimbot-Mobile-34677"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Stream Snipe",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Guest3D/ZirconHub/refs/heads/main/StreamSniper.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "NEW - Bring Parts",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/JujuOfficiel/bring-parts/refs/heads/main/bring%20parts"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Aimbot",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/new-gugus/aimbot-neptune/refs/heads/main/aimbot.lua", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Shift Lock For Mobile",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Mobile-Console-20843"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Freecam",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Freecam'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Keyboard (buttons)",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Mobile-Keyboard-Script-20056"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "AFEM Animations Gui",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-AFEM-14048"))()
   end,
})

local Tab = Window:CreateTab("🎮Games",104365492568677) -- Title, Image

local Button = Tab:CreateButton({
   Name = "NEW - Brookhaven : Sander XY",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-Sander-XY-35845"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "NEW - Brookhaven : Auto Candy Hunt",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Brookhaven-RP-NT-EVENT-FARM-CANDY-60736"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "NEW - 99 nights in the forest",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/VapeVoidware/VWExtra/main/NightsInTheForest.lua", true))("t.me/i_s_m_max")
   end,
})


local Button = Tab:CreateButton({
   Name = "Basically FNF : Autoplayer Lite",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Basically-FNF:-Remix-AutoPlayer-Lite-9989"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Doors : Lolhax",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Robloxexploiterz/Release-Lolhax/refs/heads/main/LX%20Doors%20v3.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Murder VS Sheriff Duels : Lx39",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Murder-vs-sheriff-by-Lx39-17130"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "M.E.G Endless Reality : MegMenu",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/UPDATE-M.E.G.-Endless-Reality-MegMenu-32222"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "GRANNY : Haps",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Granny-Haps-cheat-29970"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Blade Ball : SGC",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/Avorrietz/Ghostobfuscate/refs/heads/main/SGC"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "War Tycoon : PastesWares",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Gripen-War-Tycoon-Pastee-29925"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "War Tycoon : Zendex",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/MANGUSTA-War-Tycoon-Zendex-32181"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Brookhaven : Darkbones",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Brookhaven-30409"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Granny Multiplayer : Zephyr Gab Edition",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Granny:-Gab-Edition-Retro-Zephyr-Gr4nny-G4b-Ed1tion-31372"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Dead Rails : Lunor",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet('https://raw.githubusercontent.com/Catto-YFCN/Lunor_Dependencies/refs/heads/main/Loader'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Fisch : Speed Hub X",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/AhmadV99/Speed-Hub-X/main/Speed%20Hub%20X.lua", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "War Tycoon : Facility Hub",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun ! Join the discord to bypass key",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/FacilityHUB/FacilityHub/refs/heads/main/WarTycoons"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Murder Mystery 2 : Overdrive H",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun ! Join the discord to bypass key",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://api.overdrivehub.xyz/v1/auth"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Fling Things and people : RuHub",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Fling-Things-and-People-RuHub-OP-FTAP-Script-35067"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Superbox Siege Defense : Autofarm V3",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun ! Join the discord to bypass key",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/QuorumHub1/QuorumHub/refs/heads/main/SbsdAutofarmV3.txt"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Piggy : StarHack",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/StarHackScripts/StarHack-Hub-Deepstar-Hub/refs/heads/main/StarHack%20Hub%20-%20Piggy%20Pro%20Hub.txt"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "RIVALS : Duckhub (Only For Mobile)",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/RIVALS-Best-Script-Duck-Hub-29813"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Ability Wars : ElysiumX",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/KylnDantas/ElysiumX/refs/heads/main/Loader.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "MM2 : Xhub",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/XMainHub/freemium/refs/heads/main/execute"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Dead Rails : OP Gui",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/ScriptBeLike/Tera-DeadRails/refs/heads/main/Meteor%20V1"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Prison Life : Triger Admin",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Prison-Life-Tiger-Admin-40262"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Natural Disaster Survival : NullFire",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Natural-Disaster-Survival-NullFire-NDS-24033"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Jailbreak : OP Script",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Jailbreak-Season-25-BEST-OP-UNDETECTED-SCRIPT-SILENT-AIM-ESP-AUTO-ARREST-CAR-MOD-31827"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Da Hood : Zins",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet('https://raw.githubusercontent.com/Zinzs/luascripting/main/canyoutellitsadahoodscriptornot.lua'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "NEW - Cave Diving Experience : Menu",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet('https://raw.githubusercontent.com/JujuOfficiel/cavediving/refs/heads/main/cavediving'))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Base Battles : Hitbox Extender",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   -- loop
game:GetService("RunService").Stepped:Connect(function()
    -- gets all players in the server
    for _, player in next, game:GetService("Players"):GetPlayers() do
        -- checks if the player found was not the local player, so the local player doesnt get his hitbox extended
        if player ~= game:GetService("Players").LocalPlayer then
            -- finds humanoid root part, then changes transparecy and can collide so you can walk through the hitbox and it wont be wonky
            local hrp = player.Character and player.Character:FindFirstChild("HumanoidRootPart")
            if hrp then
                hrp.CanCollide = false
                hrp.Transparency = 0.1  -- Biraz şəffaflıq əlavə et
                
                -- changes the humanoidrootpart size (basically the main code)
                if hrp.Size ~= Vector3.new(20, 20, 20) then
                    hrp.Size = Vector3.new(20, 20, 20)
                end
                
                
                hrp.Material = Enum.Material.Neon
                hrp.BrickColor = BrickColor.new("Bright red") 
                
                
                -- hrp.BrickColor = BrickColor.new("Bright blue") 
            end
        end
    end
end)
   end,
})

local Button = Tab:CreateButton({
   Name = "Grow A Garden : Autofarm",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   getgenv().VxezeHubConfig = {
    ["Auto Collect Plants"] = true,
    ["Loop Auto Sell"] = true,
    ["Auto Buy M+ Seeds"] = true,
    ["Auto Buy All Seeds"] = false,
    ["Auto Buy Eggs"] = false,
    ["Eggs"] = {
        ["Common"] = false,
        ["Uncommon"] = false,
        ["Rare"] = false,
        ["Legendary"] = true,
        ["Mythical"] = true,
        ["Bug"] = true,
    },
    ["Auto Plant All Seeds"] = false,
    ["Anti-AFK"] = true,
    ["Player NoClip"] = true,
    ["Camera NoClip"] = true,
    ["Continuous E Hold"] = true,
    ["Auto Max Zoom"] = true,
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/Dex-Bear/Vxezehub/refs/heads/main/VxezeHubGrowAGardenKaitun.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Prison Life : PrizzLife V2",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://rawscripts.net/raw/Prison-Life-Prizzlife-39787"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "NEW - Zombie Attack",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/rrixh/zombieattaxk/main/az_lulaslollipop",true))();
   end,
})

local Button = Tab:CreateButton({
   Name = "NEW - 99 Nights in the forest",
   Callback = function()
   Rayfield:Notify({
   Title = "Script Executed",
   Content = "Have Fun !",
   Duration = 6.5,
   Image = 104365492568677,
})
   loadstring(game:HttpGet("https://raw.githubusercontent.com/VapeVoidware/VWExtra/main/NightsInTheForest.lua", true))("t.me/i_s_m_max")
   end,
})


local Tab = Window:CreateTab("Credits", 104365492568677) -- Title, Image

local Paragraph = Tab:CreateParagraph({Title = "Creator", Content = "JujuOfficiel"})
local Paragraph = Tab:CreateParagraph({Title = "Helper", Content = "hb2obsk"})
local Paragraph = Tab:CreateParagraph({Title = "Supporter", Content = "secretmodedajyo"})

Rayfield:Notify({
   Title = "Deluxe",
   Content = "Thanks For Using Deluxe version !",
   Duration = 6.5,
   Image = 4483362458,
})
