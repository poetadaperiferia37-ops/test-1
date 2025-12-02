--[=[
 d888b  db    db d888888b      .d888b.      db      db    db  .d8b.  
88' Y8b 88    88   `88'        VP  `8D      88      88    88 d8' `8b 
88      88    88    88            odD'      88      88    88 88ooo88 
88  ooo 88    88    88          .88'        88      88    88 88~~~88 
88. ~8~ 88b  d88   .88.        j88.         88booo. 88b  d88 88   88    @uniquadev
 Y888P  ~Y8888P' Y888888P      888888D      Y88888P ~Y8888P' YP   YP  CONVERTER 
]=]

-- Instances: 32 | Scripts: 4 | Modules: 0 | Tags: 0
local G2L = {};

-- Workspace.MainModule.ScreenGui
G2L["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
G2L["1"]["ZIndexBehavior"] = Enum.ZIndexBehavior.Sibling;


-- Workspace.MainModule.ScreenGui.Frame
G2L["2"] = Instance.new("Frame", G2L["1"]);
G2L["2"]["BorderSizePixel"] = 0;
G2L["2"]["BackgroundColor3"] = Color3.fromRGB(45, 45, 45);
G2L["2"]["Size"] = UDim2.new(0, 509, 0, 616);
G2L["2"]["Position"] = UDim2.new(0.48213, 0, 0.13017, 0);
G2L["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);


-- Workspace.MainModule.ScreenGui.Frame.ImageLabel
G2L["3"] = Instance.new("ImageLabel", G2L["2"]);
G2L["3"]["BorderSizePixel"] = 0;
G2L["3"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["3"]["Image"] = [[rbxassetid://82430723506268]];
G2L["3"]["Size"] = UDim2.new(0, 496, 0, 592);
G2L["3"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["3"]["Position"] = UDim2.new(0.01179, 0, 0.02346, 0);


-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame
G2L["4"] = Instance.new("ScrollingFrame", G2L["2"]);
G2L["4"]["Active"] = true;
G2L["4"]["BorderSizePixel"] = 0;
G2L["4"]["CanvasSize"] = UDim2.new(0, 0, 7, 0);
G2L["4"]["BackgroundColor3"] = Color3.fromRGB(25, 25, 25);
G2L["4"]["Size"] = UDim2.new(0, 493, 0, 616);
G2L["4"]["ScrollBarImageColor3"] = Color3.fromRGB(150, 0, 0);
G2L["4"]["Position"] = UDim2.new(0.03015, 0, 0.01372, 0);
G2L["4"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["4"]["BackgroundTransparency"] = 1;


-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["5"] = Instance.new("TextButton", G2L["4"]);
G2L["5"]["TextWrapped"] = true;
G2L["5"]["BorderSizePixel"] = 2;
G2L["5"]["TextSize"] = 14;
G2L["5"]["TextScaled"] = true;
G2L["5"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["5"]["BackgroundColor3"] = Color3.fromRGB(136, 136, 136);
G2L["5"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["5"]["Size"] = UDim2.new(0, 52, 0, 29);
G2L["5"]["BorderColor3"] = Color3.fromRGB(41, 41, 41);
G2L["5"]["Text"] = [[t0_adro-ast]];
G2L["5"]["Position"] = UDim2.new(0, 6, 0, 160);


-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.Script
G2L["6"] = Instance.new("Script", G2L["5"]);



-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.RemoteEvent
G2L["7"] = Instance.new("RemoteEvent", G2L["5"]);



-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["8"] = Instance.new("TextButton", G2L["4"]);
G2L["8"]["TextWrapped"] = true;
G2L["8"]["BorderSizePixel"] = 2;
G2L["8"]["TextSize"] = 14;
G2L["8"]["TextScaled"] = true;
G2L["8"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["8"]["BackgroundColor3"] = Color3.fromRGB(136, 136, 136);
G2L["8"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["8"]["Size"] = UDim2.new(0, 58, 0, 39);
G2L["8"]["BorderColor3"] = Color3.fromRGB(41, 41, 41);
G2L["8"]["Text"] = [[skybox]];
G2L["8"]["Position"] = UDim2.new(0, 72, 0, 108);


-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.Script
G2L["9"] = Instance.new("Script", G2L["8"]);



-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["a"] = Instance.new("TextButton", G2L["4"]);
G2L["a"]["TextWrapped"] = true;
G2L["a"]["BorderSizePixel"] = 2;
G2L["a"]["TextSize"] = 14;
G2L["a"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["a"]["BackgroundColor3"] = Color3.fromRGB(136, 136, 136);
G2L["a"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["a"]["Size"] = UDim2.new(0, 52, 0, 38);
G2L["a"]["BorderColor3"] = Color3.fromRGB(41, 41, 41);
G2L["a"]["Text"] = [[decalspam]];
G2L["a"]["Position"] = UDim2.new(0, 6, 0, 108);


-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.Script
G2L["b"] = Instance.new("Script", G2L["a"]);



-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["c"] = Instance.new("TextButton", G2L["4"]);
G2L["c"]["TextWrapped"] = true;
G2L["c"]["BorderSizePixel"] = 2;
G2L["c"]["TextSize"] = 14;
G2L["c"]["TextScaled"] = true;
G2L["c"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["c"]["BackgroundColor3"] = Color3.fromRGB(136, 136, 136);
G2L["c"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["c"]["Size"] = UDim2.new(0, 59, 0, 29);
G2L["c"]["BorderColor3"] = Color3.fromRGB(41, 41, 41);
G2L["c"]["Text"] = [[j_hn doe]];
G2L["c"]["Position"] = UDim2.new(0, 71, 0, 157);


-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.Script
G2L["d"] = Instance.new("Script", G2L["c"]);



-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["e"] = Instance.new("LocalScript", G2L["c"]);



-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.RemoteEvent
G2L["f"] = Instance.new("RemoteEvent", G2L["c"]);



-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["10"] = Instance.new("TextButton", G2L["4"]);
G2L["10"]["TextWrapped"] = true;
G2L["10"]["BorderSizePixel"] = 2;
G2L["10"]["TextSize"] = 14;
G2L["10"]["TextScaled"] = true;
G2L["10"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["10"]["BackgroundColor3"] = Color3.fromRGB(114, 114, 114);
G2L["10"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["10"]["Size"] = UDim2.new(0, 68, 0, 29);
G2L["10"]["BorderColor3"] = Color3.fromRGB(25, 25, 25);
G2L["10"]["Text"] = [[R6]];
G2L["10"]["Position"] = UDim2.new(0, 340, 0, 6);


-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.Script
G2L["11"] = Instance.new("Script", G2L["10"]);



-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["12"] = Instance.new("LocalScript", G2L["10"]);



-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["13"] = Instance.new("TextButton", G2L["4"]);
G2L["13"]["TextWrapped"] = true;
G2L["13"]["BorderSizePixel"] = 2;
G2L["13"]["TextSize"] = 14;
G2L["13"]["TextScaled"] = true;
G2L["13"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["13"]["BackgroundColor3"] = Color3.fromRGB(114, 114, 114);
G2L["13"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["13"]["Size"] = UDim2.new(0, 68, 0, 29);
G2L["13"]["BorderColor3"] = Color3.fromRGB(25, 25, 25);
G2L["13"]["Text"] = [[RESET]];
G2L["13"]["Position"] = UDim2.new(0, 407, 0, 6);


-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
G2L["14"] = Instance.new("LocalScript", G2L["13"]);



-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["15"] = Instance.new("TextButton", G2L["4"]);
G2L["15"]["TextWrapped"] = true;
G2L["15"]["BorderSizePixel"] = 2;
G2L["15"]["TextSize"] = 14;
G2L["15"]["TextScaled"] = true;
G2L["15"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["15"]["BackgroundColor3"] = Color3.fromRGB(95, 95, 95);
G2L["15"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["15"]["Size"] = UDim2.new(0, 53, 0, 28);
G2L["15"]["BorderColor3"] = Color3.fromRGB(40, 40, 40);
G2L["15"]["Text"] = [[logo particles]];
G2L["15"]["Position"] = UDim2.new(0, 72, 0, 199);


-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.Script
G2L["16"] = Instance.new("Script", G2L["15"]);



-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.TextButton
G2L["17"] = Instance.new("TextButton", G2L["15"]);
G2L["17"]["TextWrapped"] = true;
G2L["17"]["BorderSizePixel"] = 2;
G2L["17"]["TextSize"] = 14;
G2L["17"]["TextScaled"] = true;
G2L["17"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["17"]["BackgroundColor3"] = Color3.fromRGB(72, 72, 72);
G2L["17"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["17"]["Size"] = UDim2.new(0, 53, 0, 24);
G2L["17"]["BorderColor3"] = Color3.fromRGB(40, 40, 40);
G2L["17"]["Text"] = [[hint]];
G2L["17"]["Position"] = UDim2.new(0, 0, 0, 39);


-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.TextButton.Script
G2L["18"] = Instance.new("Script", G2L["17"]);



-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["19"] = Instance.new("TextButton", G2L["4"]);
G2L["19"]["TextWrapped"] = true;
G2L["19"]["BorderSizePixel"] = 2;
G2L["19"]["TextSize"] = 14;
G2L["19"]["TextScaled"] = true;
G2L["19"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["19"]["BackgroundColor3"] = Color3.fromRGB(77, 77, 77);
G2L["19"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["19"]["Size"] = UDim2.new(0, 52, 0, 30);
G2L["19"]["BorderColor3"] = Color3.fromRGB(40, 40, 40);
G2L["19"]["Text"] = [[c00lkidd world tour jump]];
G2L["19"]["Position"] = UDim2.new(0, 6, 0, 198);


-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.Script
G2L["1a"] = Instance.new("Script", G2L["19"]);



-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["1b"] = Instance.new("TextButton", G2L["4"]);
G2L["1b"]["TextWrapped"] = true;
G2L["1b"]["BorderSizePixel"] = 2;
G2L["1b"]["TextSize"] = 14;
G2L["1b"]["TextScaled"] = true;
G2L["1b"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1b"]["BackgroundColor3"] = Color3.fromRGB(73, 73, 73);
G2L["1b"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1b"]["Size"] = UDim2.new(0, 49, 0, 27);
G2L["1b"]["BorderColor3"] = Color3.fromRGB(39, 39, 39);
G2L["1b"]["Text"] = [[m1g p4_r*ticles]];
G2L["1b"]["Position"] = UDim2.new(0, 9, 0, 236);


-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.Script
G2L["1c"] = Instance.new("Script", G2L["1b"]);



-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton
G2L["1d"] = Instance.new("TextButton", G2L["4"]);
G2L["1d"]["TextWrapped"] = true;
G2L["1d"]["BorderSizePixel"] = 2;
G2L["1d"]["TextSize"] = 14;
G2L["1d"]["TextScaled"] = true;
G2L["1d"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1d"]["BackgroundColor3"] = Color3.fromRGB(108, 108, 108);
G2L["1d"]["FontFace"] = Font.new([[rbxasset://fonts/families/Arial.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1d"]["Size"] = UDim2.new(0, 48, 0, 27);
G2L["1d"]["BorderColor3"] = Color3.fromRGB(32, 32, 32);
G2L["1d"]["Text"] = [[tiktok musix]];
G2L["1d"]["Position"] = UDim2.new(0, 9, 0, 274);


-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.Script
G2L["1e"] = Instance.new("Script", G2L["1d"]);



-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextLabel
G2L["1f"] = Instance.new("TextLabel", G2L["4"]);
G2L["1f"]["BorderSizePixel"] = 0;
G2L["1f"]["TextSize"] = 40;
G2L["1f"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
G2L["1f"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
G2L["1f"]["TextColor3"] = Color3.fromRGB(171, 0, 0);
G2L["1f"]["BackgroundTransparency"] = 1;
G2L["1f"]["Size"] = UDim2.new(0, 179, 0, 50);
G2L["1f"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
G2L["1f"]["Text"] = [[bypass gui  v1 original edition]];
G2L["1f"]["Position"] = UDim2.new(0.26356, 0, 0.00974, 0);


-- Workspace.MainModule.ScreenGui.Frame.Drag Gui Script
G2L["20"] = Instance.new("LocalScript", G2L["2"]);
G2L["20"]["Name"] = [[Drag Gui Script]];


-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_e()
local script = G2L["e"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.RemoteEvent:FireServer()
	end)
end;
task.spawn(C_e);
-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_12()
local script = G2L["12"];
	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.RemoteEvent:FireServer()
	end)
end;
task.spawn(C_12);
-- Workspace.MainModule.ScreenGui.Frame.ScrollingFrame.TextButton.LocalScript
local function C_14()
local script = G2L["14"];
	
	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.Humanoid.Health = 0
	end)
end;
task.spawn(C_14);
-- Workspace.MainModule.ScreenGui.Frame.Drag Gui Script
local function C_20()
local script = G2L["20"];
	function dragify(Main)
	dragToggle = nil
	dragSpeed = 0.95 -- You can edit this.
	dragInput = nil
	dragStart = nil
	dragPos = nil
	
	function updateInput(input)
	Delta = input.Position - dragStart
	Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + Delta.X, startPos.Y.Scale, startPos.Y.Offset + Delta.Y)
	game:GetService("TweenService"):Create(Main, TweenInfo.new(.25), {Position = Position}):Play()
	end
	
	Main.InputBegan:Connect(function(input)
	if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then
	dragToggle = true
	dragStart = input.Position
	startPos = Main.Position
	input.Changed:Connect(function()
	if (input.UserInputState == Enum.UserInputState.End) then
	dragToggle = false
	end
	end)
	end
	end)
	
	Main.InputChanged:Connect(function(input)
	if (input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch) then
	dragInput = input
	end
	end)
	
	game:GetService("UserInputService").InputChanged:Connect(function(input)
	if (input == dragInput and dragToggle) then
	updateInput(input)
	end
	end)
	end
	
	dragify(script.Parent)
end;
task.spawn(C_20);

return G2L["1"], require;
