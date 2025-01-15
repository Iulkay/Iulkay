-- Create a ScreenGui
local screenGui = Instance.new("ScreenGui")
screenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

-- Create a Frame
local frame = Instance.new("Frame")
frame.Size = UDim2.new(0.5, 0, 0.3, 0)
frame.Position = UDim2.new(0.25, 0, 0.35, 0)
frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
frame.Parent = screenGui

-- Create a TextLabel
local textLabel = Instance.new("TextLabel")
textLabel.Size = UDim2.new(1, 0, 1, 0)
textLabel.Text = "Once you pay me **1.7k**, you can have it!"
textLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
textLabel.TextScaled = true
textLabel.BackgroundTransparency = 1
textLabel.Parent = frame

-- Optional: Create a Close Button
local closeButton = Instance.new("TextButton")
closeButton.Size = UDim2.new(0.2, 0, 0.1, 0)
closeButton.Position = UDim2.new(0.4, 0, 0.85, 0)
closeButton.Text = "Close"
closeButton.Parent = frame

-- Close the UI when the button is clicked
closeButton.MouseButton1Click:Connect(function()
    screenGui:Destroy()
end)
