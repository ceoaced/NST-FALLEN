-- [ Settings ] --
getgenv().AutoRejoin = true
getgenv().AutoRestart = true
getgenv().AutoSkip = true
getgenv().AutoSkipCutscenes = true
getgenv().AutoChain = true
getgenv().AutoMedic = true
getgenv().AutoDJ = true
getgenv().AutoNecro = true
getgenv().AutoMercenary = true
-- [ End Settings ] --

local TDS = loadstring(game:HttpGet("https://getaether.cc/loader.lua"))()

TDS:Loadout("Assassin", "Crook Boss", "Gatling Gun", "DJ Booth", "Minigunner")
TDS:Mode("Fallen")
TDS:GameInfo("Simplicity", {})

TDS:Place("Assassin", -17.71588134765625, 1.0000003576278687, -2.0627222061157227)
TDS:Place("Assassin", -18.611862182617188, 1.0000007152557373, -3.927096366882324)
TDS:SetTarget(1, "Last")
TDS:SetTarget(1, "Strongest")
TDS:SetTarget(2, "Last")
TDS:SetTarget(2, "Strongest")
TDS:SetTarget(2, "Strongest")
TDS:Ready()

-- [ Wave 1 ] --
TDS:Place("Assassin", -17.831188201904297, 0.9999834895133972, -5.811810493469238)

-- [ Wave 2 ] --
TDS:Upgrade(1)

-- [ Wave 3 ] --
TDS:Upgrade(2)

-- [ Wave 4 ] --
TDS:Upgrade(3)
TDS:Upgrade(1)

-- [ Wave 5 ] --
TDS:Upgrade(2)
TDS:Upgrade(3)

-- [ Wave 7 ] --
TDS:Place("Crook Boss", -7.312689781188965, 0.9999865293502808, -3.386719226837158)
TDS:Upgrade(4)

-- [ Wave 9 ] --
TDS:Upgrade(4)

-- [ Wave 12 ] --
TDS:Place("Gatling Gun", -10.921796798706055, 0.9999831914901733, -3.7962255477905273)
TDS:Upgrade(5)

-- [ Wave 14 ] --
TDS:Upgrade(5)

-- [ Wave 15 ] --
TDS:Place("DJ Booth", -12.6591796875, 1, 0.39818763732910156)
TDS:Upgrade(6)
TDS:Upgrade(6)
TDS:SetOption(6, "Track", "Green")
TDS:Upgrade(6)

-- [ Wave 16 ] --
TDS:Place("Crook Boss", -8.777910232543945, 1.000000238418579, -0.7231259346008301)
TDS:Upgrade(7)
TDS:Upgrade(7)

-- [ Wave 18 ] --
TDS:Upgrade(5)
TDS:Upgrade(6)

-- [ Wave 20 ] --
TDS:Upgrade(5)

-- [ Wave 22 ] --
TDS:Upgrade(6)

-- [ Wave 25 ] --
TDS:Place("Crook Boss", -4.274919509887695, 0.9999902844429016, -3.5031397342681885)
TDS:Upgrade(8)
TDS:Upgrade(8)
TDS:Place("Crook Boss", -2.6455016136169434, 0.9999831914901733, 2.227681875228882)
TDS:Upgrade(9)
TDS:Upgrade(9)

-- [ Wave 26 ] --
TDS:Place("Crook Boss", -7.711280822753906, 0.9999997019767761, 2.0990028381347656)
TDS:Upgrade(10)
TDS:Upgrade(10)
TDS:Upgrade(5)
TDS:Upgrade(1)

-- [ Wave 27 ] --
TDS:Upgrade(2)
TDS:Upgrade(3)
TDS:Place("Assassin", -18.611862182617188, 0.9999834895133972, -7.696524620056152)
TDS:Upgrade(11)
TDS:Upgrade(11)
TDS:Upgrade(11)
TDS:Upgrade(11)
TDS:Upgrade(1)
TDS:Upgrade(2)
TDS:Upgrade(3)

-- [ Wave 30 ] --
TDS:Upgrade(5)
TDS:Upgrade(7)

-- [ Wave 31 ] --
TDS:Upgrade(4)
TDS:Upgrade(10)
TDS:Upgrade(9)
TDS:Upgrade(8)
TDS:Upgrade(10)

-- [ Wave 32 ] --
TDS:Upgrade(7)

-- [ Wave 33 ] --
TDS:Upgrade(4)
TDS:Upgrade(8)

-- [ Wave 34 ] --
TDS:Upgrade(9)
TDS:Place("Minigunner", -16.355241775512695, 0.9999891519546509, -8.834760665893555)
TDS:Upgrade(12)
TDS:Upgrade(12)
TDS:Upgrade(12)
TDS:Upgrade(12)
TDS:Place("Minigunner", -13.315241813659668, 0.9999898672103882, -8.834760665893555)
TDS:Upgrade(13)
TDS:Upgrade(13)

-- [ Wave 35 ] --
TDS:Upgrade(13)
TDS:Upgrade(13)

-- [ Wave 36 ] --
TDS:Place("Minigunner", -15.515891075134277, 0.9999995231628418, 3.254899024963379)
TDS:Upgrade(14)
TDS:Upgrade(14)
TDS:Upgrade(14)
TDS:Upgrade(14)
TDS:Place("Minigunner", -18.555891036987305, 0.9999995231628418, 3.254899024963379)
TDS:Upgrade(15)
TDS:Upgrade(15)
TDS:Upgrade(15)
TDS:Upgrade(15)
TDS:Place("Minigunner", -21.595890045166016, 0.9999995231628418, 3.254899024963379)

-- [ Wave 37 ] --
TDS:Upgrade(16)
TDS:Upgrade(16)
TDS:Upgrade(16)
TDS:Upgrade(16)
TDS:Place("Minigunner", -10.306376457214355, 0.999999463558197, 3.6823792457580566)
TDS:Upgrade(17)
TDS:Upgrade(17)
TDS:Upgrade(17)
TDS:Upgrade(17)
TDS:Place("Minigunner", -7.759317398071289, 0.9999831914901733, 5.354970932006836)
TDS:Upgrade(18)
TDS:Upgrade(18)
TDS:Upgrade(18)
TDS:Upgrade(18)
TDS:Place("Minigunner", -11.461553573608398, 0.9999989867210388, 6.494347095489502)
TDS:Upgrade(19)
TDS:Upgrade(19)
TDS:Upgrade(19)
TDS:Upgrade(19)

-- [ Wave 38 ] --
TDS:Place("Minigunner", -14.4774169921875, 0.9999990463256836, 6.112025260925293)
TDS:Upgrade(20)
TDS:Upgrade(20)
TDS:Upgrade(20)
TDS:Upgrade(20)
TDS:Place("Minigunner", -1.2730079889297485, 0.9999831914901733, -3.299297571182251)
TDS:Upgrade(21)
TDS:Upgrade(21)
TDS:Upgrade(21)
TDS:Upgrade(21)
TDS:Place("Minigunner", -17.51741600036621, 0.9999991059303284, 6.112025260925293)
TDS:Upgrade(22)
TDS:Upgrade(22)
TDS:Upgrade(22)
TDS:Upgrade(22)
TDS:Place("Minigunner", 1.7669919729232788, 0.9999831914901733, -3.299297571182251)
TDS:Upgrade(23)
TDS:Upgrade(23)
TDS:Upgrade(23)
TDS:Upgrade(23)
TDS:Place("Minigunner", -0.07581651210784912, 0.9999831914901733, 3.7771406173706055)
TDS:Upgrade(24)
TDS:Upgrade(24)
TDS:Upgrade(24)
TDS:Upgrade(24)
TDS:Place("Minigunner", 2.6282620429992676, 0.9999831914901733, 2.203768730163574)
TDS:Upgrade(25)
TDS:Upgrade(25)
TDS:Upgrade(25)
TDS:Upgrade(25)
TDS:Place("Minigunner", 4.806992053985596, 0.9999831914901733, -3.299297571182251)
TDS:Upgrade(26)
TDS:Upgrade(26)
TDS:Upgrade(26)
TDS:Upgrade(26)
TDS:Place("Minigunner", 5.030594825744629, 0.9999831914901733, 4.065975666046143)
TDS:Upgrade(27)
TDS:Upgrade(27)
TDS:Upgrade(27)
TDS:Upgrade(27)
TDS:Ability(5, "FPS", {enabled = true})
TDS:Ability(5, "FPS", {enabled = false})

-- [ Wave 39 ] --
TDS:Place("Minigunner", -18.28351402282715, 0.9999908208847046, -11.184945106506348)
TDS:Upgrade(28)
TDS:Upgrade(28)
TDS:Upgrade(28)
TDS:Upgrade(28)
TDS:Place("Minigunner", -15.284058570861816, 0.9999936819076538, -11.67978572845459)
TDS:Upgrade(29)
TDS:Upgrade(29)
TDS:Upgrade(29)
TDS:Upgrade(29)
TDS:Place("Minigunner", -10.27524185180664, 0.9999874830245972, -8.834760665893555)
TDS:Upgrade(30)
TDS:Upgrade(30)
TDS:Upgrade(30)
TDS:Upgrade(30)
TDS:Place("Minigunner", -12.244071960449219, 0.9999834895133972, -11.688796997070312)
TDS:Upgrade(31)
TDS:Upgrade(31)
TDS:Upgrade(31)
TDS:Upgrade(31)
TDS:Place("Minigunner", -7.235241889953613, 0.9999884366989136, -8.834760665893555)
TDS:Upgrade(32)
TDS:Upgrade(32)
TDS:Upgrade(32)
TDS:Upgrade(32)
TDS:Place("Minigunner", -24.33184814453125, 0.9999998807907104, 1.128190279006958)
TDS:Upgrade(33)
TDS:Upgrade(33)
TDS:Upgrade(33)
TDS:Upgrade(33)
TDS:Place("Minigunner", -23.72879981994629, 1.0000003576278687, -1.8910765647888184)
TDS:Upgrade(34)
TDS:Upgrade(34)
TDS:Upgrade(34)
TDS:Upgrade(34)
TDS:Place("Minigunner", -24.2698974609375, 1.0000008344650269, -4.882533073425293)
TDS:Upgrade(35)
TDS:Upgrade(35)
TDS:Upgrade(35)
TDS:Upgrade(35)
TDS:Place("Minigunner", -25.927936553955078, 1.000001311302185, -7.411979675292969)
TDS:Upgrade(36)
TDS:Upgrade(36)
TDS:Upgrade(36)
TDS:Upgrade(36)
TDS:Place("Minigunner", 6.663058757781982, 0.9999831914901733, -5.706913948059082)

-- [ Wave 40 ] --
TDS:Upgrade(37)
TDS:Upgrade(37)
TDS:Upgrade(37)
TDS:Upgrade(37)
TDS:Place("Minigunner", -2.9745986461639404, 1.0000014305114746, -8.802138328552246)
TDS:Upgrade(38)
TDS:Upgrade(38)
TDS:Upgrade(38)
TDS:Upgrade(38)
TDS:Place("Minigunner", 0.06540131568908691, 0.9999831914901733, -8.802138328552246)
TDS:Upgrade(39)
TDS:Upgrade(39)
TDS:Upgrade(39)
TDS:Upgrade(39)
TDS:Place("Minigunner", -20.5466365814209, 0.9999990463256836, 6.3678131103515625)
TDS:Upgrade(40)
TDS:Upgrade(40)
TDS:Upgrade(40)
TDS:Upgrade(40)
TDS:SetOption(6, "Track", "Red")
