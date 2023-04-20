# qb-beehive
NoPixel 3.5 Inspired Beehive Script QBCore

# Thank you for choosing us <3 <3

# Step 1:
Go to qb-core/shared/items.lua folder and add them
	["beehive"]                             = {["name"] = "beehive",                   ["label"] = "Beehive",                 ["weight"] = 5000,         ["type"] = "item",         ["image"] = "beehive.png",                     ["unique"] = false,     ["useable"] = true,     ["shouldClose"] = true,       ["combinable"] = nil,   ["description"] = ""},
    ["beequeen"]                             = {["name"] = "beequeen",                   ["label"] = "Bee Queen",                 ["weight"] = 100,         ["type"] = "item",         ["image"] = "beequeen.png",                 ["unique"] = false,     ["useable"] = true,     ["shouldClose"] = true,       ["combinable"] = nil,   ["description"] = ""},
    ["beeswax"]                             = {["name"] = "beeswax",                   ["label"] = "Beeswax",                 ["weight"] = 500,         ["type"] = "item",         ["image"] = "beeswax.png",                     ["unique"] = false,     ["useable"] = true,     ["shouldClose"] = true,       ["combinable"] = nil,   ["description"] = ""},
    ["honey"]                                 = {["name"] = "honey",                   ["label"] = "Honey",                         ["weight"] = 500,         ["type"] = "item",         ["image"] = "honey.png",                     ["unique"] = false,     ["useable"] = true,     ["shouldClose"] = true,       ["combinable"] = nil,   ["description"] = ""},

# Step 2:
Enter the row-beekeeping script and read the sql file.

# Step 3:
Throw the images in the Depencies section to the inventory/html/images section of your inventory.

# Step 4:
qb-target/init.lua Config.TargetModels
	["BEE"] = {
		models = { `gate_beehive`, `gate_beehive02`, `gate_beehive03`,},
		options = {
			{
				event = "row-beekeeping:checkBeehive",
				icon = "fas fa-archive",
				label = "Check",
			},
		},
		distance = 1.5
	},

# Step 5:
After that, you can enter the game and start using it. Thank you again.

# Row Development

Support
Discord: https://discord.gg/c9dS9ruDyV
