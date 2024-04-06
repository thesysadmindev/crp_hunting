# crp_hunting
Fivem Hunting script made for ox_inventory

![image](https://user-images.githubusercontent.com/55892717/163342386-b07ff6ee-0316-4f18-a060-727fdc35afed.png)

## Features:
- Allow the player to hunt animals naturally spawning.
- Carcass are physically drag/carry.
- Carcass quality is defined by the type weapon used and if the animal has been headshot
- Anti-farm (force player to not stay on the same animal spawn point)
- Carcass degradation (sell price will decrease overtime)
### TODO:
- Clean Animation
- Optimisation
#### Maybe:
- Add poaching
- sell point owned by player
- hunting card

## Dependencies:
ox_inventory : https://www.github.com/overextended/ox_inventory/releases/latest

ox_lib : https://github.com/overextended/ox_lib/releases/latest

qtarget : https://github.com/overextended/qtarget/releases/latest

Item to add :
```lua
	['carcass_boar'] = {
		label = 'Boar Carcass',
		weight = 20000,
		stack = false,
		degrade = 5*60,
		client = {
            add = function()
                TriggerEvent('crp_hunting:CarryCarcass')
            end,
            remove = function()
				TriggerEvent('crp_hunting:CarryCarcass')
            end
        }
	},
	['carcass_hawk'] = {
		label = 'Hawk Carcass',
		weight = 3000,
		stack = false,
		degrade = 5*60,
		client = {
            add = function()
                TriggerEvent('crp_hunting:CarryCarcass')
            end,
            remove = function()
				TriggerEvent('crp_hunting:CarryCarcass')
            end
        }
	},
	['carcass_cormorant'] = {
		label = 'Cormorant Carcass',
		weight = 3000,
		stack = false,
		degrade = 5*60,
		client = {
            add = function()
                TriggerEvent('crp_hunting:CarryCarcass')
            end,
            remove = function()
				TriggerEvent('crp_hunting:CarryCarcass')
            end
        }
	},
	['carcass_coyote'] = {
		label = 'Coyote Carcass',
		weight = 3000,
		stack = false,
		degrade = 5*60,
		client = {
            add = function()
                TriggerEvent('crp_hunting:CarryCarcass')
            end,
            remove = function()
				TriggerEvent('crp_hunting:CarryCarcass')
            end
        }
	},
	['carcass_deer'] = {
		label = 'Deer Carcass',
		weight = 18000,
		stack = false,
		degrade = 5*60,
		client = {
            add = function()
                TriggerEvent('crp_hunting:CarryCarcass')
            end,
            remove = function()
				TriggerEvent('crp_hunting:CarryCarcass')
            end
        }
	},
	['carcass_mtlion'] = {
		label = 'Mountain Lion Carcass',
		weight = 16000,
		stack = false,
		degrade = 5*60,
		client = {
            add = function()
                TriggerEvent('crp_hunting:CarryCarcass')
            end,
            remove = function()
				TriggerEvent('crp_hunting:CarryCarcass')
            end
        }
	},
	['carcass_rabbit'] = {
		label = 'Rabbit Carcass',
		weight = 3000,
		stack = false,
		degrade = 5*60,
		client = {
            add = function()
                TriggerEvent('crp_hunting:CarryCarcass')
            end,
            remove = function()
				TriggerEvent('crp_hunting:CarryCarcass')
            end
        }
	},
```

<br><h2>License</h2>
<table><tr><td>
crp_hunting

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.


This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.


You should have received a copy of the GNU General Public License along with this program.  
If not, see <https://www.gnu.org/licenses/gpl-3.0.html>
</td></tr></table>
