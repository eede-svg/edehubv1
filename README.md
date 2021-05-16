local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wall%20v3')))()

local w = library:CreateWindow("EedeHubV1") -- Creates the window

local b = w:CreateFolder("JailBreak") -- Creates the folder(U will put here your buttons,etc)

b:Label("By : eede",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
}) 

b:Button("Vynixius ",function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Vynixius/main/Jailbreak/Jailbreak"))()
  
end)

b:Button("Autorob",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/wawsdasdacx/ohascriptnrrewading/main/jbsaxcriptidk1"))();
    
end)

b:Button("Nexagon",function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/opBandwidth/_Paragon_/main/main.lua"))()

end)

b:Button("Autoarrest ",function()
  loadstring(game:HttpGet("https://raw.githubusercontent.com/HazeWasTaken/Loaf-Group-Rise-Up/main/autoarrest.lua", true))()
  
end)

local b = w:CreateFolder("Arsenal") -- Creates the folder(U will put here your buttons,etc)

b:Button("Arsenal Menu",function()
    loadstring(game:HttpGet(('https://raw.githubusercontent.com/RandomAdamYT/DarkHub/master/Init'), true))()

end)

local b = w:CreateFolder("Murder Mystery 2") -- Creates the folder(U will put here your buttons,etc)

--[[
How to refresh a dropdown:
1)Create the dropdown and save it in a variable
local yourvariable = b:Dropdown("Hi",yourtable,function(a)
    print(a)
end)
2)Refresh it using the function
yourvariable:Refresh(yourtable)
How to refresh a label:
1)Create your label and save it in a variable
local yourvariable = b:Label("Pretty Useless NGL",{
    TextSize = 25; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255);
    BgColor = Color3.fromRGB(69,69,69);
})
2)Refresh it using the function
yourvariable:Refresh("Hello") It will only change the text ofc
]]
