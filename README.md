-- ShadowZen Hub Script Principal
-- GitHub Loader Ready
-- v1.0

-- Proteção e início
if not game:IsLoaded() then game.Loaded:Wait() end

local Players = game:GetService("Players")
local RunService = game:GetService("RunService")
local LocalPlayer = Players.LocalPlayer
local Mouse = LocalPlayer:GetMouse()

-- GUI Simples
local ScreenGui = Instance.new("ScreenGui", game.CoreGui)
ScreenGui.Name = "ShadowZenGUI"

local MainButton = Instance.new("TextButton", ScreenGui)
MainButton.Size = UDim2.new(0, 140, 0, 40)
MainButton.Position = UDim2.new(0, 10, 0, 10)
MainButton.Text = "ShadowZen Menu"
MainButton.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
MainButton.TextColor3 = Color3.new(1, 1, 1)
MainButton.Font = Enum.Font.GothamBold
MainButton.TextSize = 14

-- Painel flutuante
local MenuFrame = Instance.new("Frame", ScreenGui)
MenuFrame.Size = UDim2.new(0, 200, 0, 160)
MenuFrame.Position = UDim2.new(0, 10, 0, 60)
MenuFrame.Visible = false
MenuFrame.BackgroundColor3 = Color3.fromRGB(45, 45, 4
