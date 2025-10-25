# FineBe Loadstring
``local FineBe = loadstring(game:HttpGet("https://raw.githubusercontent.com/arkanzulfadliputra-oss/FineBe/refs/heads/main/FineBe.Source"))()``

## FineBe Window
``local Win = FineBe:CreateWindow("FineBe Executor")``

## FineBe Tab
``Win:CreateTab("Home")``

## FineBe Button
``:CreateButton("Mulai", function() print("Start") end)``

## FineBe Toggle
``:CreateToggle("AutoFarm", false, function(v) print("AutoFarm:", v) end)``
## FineBe DropDown
``:CreateDropdown("Mode", {"Easy","Hard"}, function(v) print("Mode:", v) end)``
## FineBe Slider
``:CreateSlider("Speed", 0, 100, 16, function(v) print("Speed:", v) end)``
## FineBe TextBox
``:CreateTextBox("Masukkan Nama", function(v) print("Nama:", v) end)``
