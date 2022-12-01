# M7 UI Library 
A Documentation of **[`M7 UI Library`](https://github.com/M7/M7-UI-Library)**.

## Call the Library
```lua
local notilib={}function notilib:MakeNoti(b,c,d)local e=Instance.new("ScreenGui")local f=Instance.new("Frame")local g=Instance.new("UICorner")local h=Instance.new("TextLabel")local i=Instance.new("TextLabel")e.Name="Noti"e.Parent=game.Players.LocalPlayer:WaitForChild("PlayerGui")f.Parent=e;f.BackgroundColor3=Color3.fromRGB(45,45,45)f.Position=UDim2.new(0.296000004,0,0.814999998,0)f.Size=UDim2.new(0.407999992,0,0.145999998,0)g.Parent=f;h.Name="Name"h.Parent=f;h.BackgroundColor3=Color3.fromRGB(255,255,255)h.BackgroundTransparency=1.000;h.Size=UDim2.new(1,0,0.322,0)h.Font=Enum.Font.SourceSans;h.Text=b;h.TextColor3=Color3.fromRGB(255,255,255)h.TextScaled=true;h.TextSize=14.000;h.TextWrapped=true;i.Name="Text"i.Parent=f;i.BackgroundColor3=Color3.fromRGB(255,255,255)i.BackgroundTransparency=1.000;i.Position=UDim2.new(0,0,0.370490015,0)i.Size=UDim2.new(1,0,0.667,0)i.Font=Enum.Font.SourceSans;i.Text=c;i.TextColor3=Color3.fromRGB(255,255,255)i.TextSize=32.000;i.TextWrapped=true;i.TextScaled=true;wait(d)e:Destroy()return a end
```

## Make notification
```lua
local noti = notilib:MakeNoti(title,Text,Time)
```
