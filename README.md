[![Vehicle Spawner](https://img.londonstudios.net/vehicle-spawner/VehicleSpawner1.png)](https://store.londonstudios.net/package/vehicle-spawner)

# This resource has been replaced

You are looking at the original Vehicle Spawner from 2020. It still works, but it is **no longer supported or updated by us**, and it has been replaced by a completely rebuilt version.

The new **Vehicle Spawner** does everything this one did and a great deal more:

- **Build your menu in-game** - Add, rename, reorder, move and delete categories and vehicles from inside the game. No text files to edit and no server restarts.
- **Decide who sees what** - Lock a whole category, a sub-category or a single vehicle to a job or group using Ace Permissions, ESX, QBCore, QBX or vRP. Police get their fleet, fire get theirs.
- **Nothing spawns that you have not approved** - Every spawn is checked on the server, so players cannot pull models that are not in your menu.
- **Search, favourites and recent spawns** - Find anything by name, model, tag or category, and let everyone keep their own shortlist.
- **Set each vehicle up properly** - Plates, liveries, extras, tags, descriptions and images per vehicle.
- **Vehicle keys** - Keys are handed over as soon as the vehicle appears, with support for 13 key and garage scripts.
- **Backups** - Every save keeps a snapshot you can load again if you change your mind.

### Get it here for £9.99 GBP: https://store.londonstudios.net/package/vehicle-spawner

It is also included in our Full Access subscription: https://store.londonstudios.net/category/subscriptions

# London Studios - Update

Since forming London Studios in April 2020 we've created a number of **high quality** and **premium** resources for the FiveM project, focusing on the emergency services and aiming to bring your server to the next level.

Although we made a number of free resources such as this one in the first year, we've now switched to creating paid content, keeping them constantly updated and working along with providing the best possible support to our customers.

Our **most popular** resources now include *Smart Fires, Police Grappler* and *Smart Hose*.

With **thousands** of **happy customers** we are confident you'll love our resources and our active support team are on hand to help if you have any questions!

# Our store: https://store.londonstudios.net/github
# Our discord: https://discord.gg/nC2krpN

The full source code of this old version is still available below should you wish to make any changes to it yourself.

---

# VehicleSpawner (2020) - London Studios
**VehicleSpawner** is a **FiveM** resource coded in **C#** allowing you to create a custom vehicle spawner menu with categories and the ability to mark a vehicle "out of service", locking it from being spawned.

This plugin is made by **LondonStudios**, we have created a variety of releases including TaserFramework, SearchHandler, ActivateAlarm, SmartTester, SmartSounds, CustodyAlarm, SmartObservations and more!

Join our **Discord** [HERE](https://discord.gg/nC2krpN).

<a href="https://www.buymeacoffee.com/londonstudios" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" style="height: 51px !important;width: 217px !important;" ></a>

![VehicleSpawner](https://i.imgur.com/H0szUIY.png)

## Usage
**/vs** - Open or close the vehicle spawner menu

This command is changeable in the **config.ini** file, please see below for more information.
## Installation
 1.  Create a new **resource folder** on your server.
 2.  Add the contents of **"resource"** inside it. This includes:
"Client.net.dll", "fxmanifest.lua", "config.ini", "SharpConfig.dll", "NativeUI.dll"
3. In **server.cfg**, "ensure" VehicleSpawner, to make it load with your server startup.
## Configuration
The "config.ini" file allows you to add categories and vehicles to the menu, you are also able to change the comamnd used to open/close it.

    [VehicleSpawner]
    DisabledVehicles = {policeb, police2} # These will appear out of service
    CommandName = vs
    
	[FP: Frontline Policing]
	irv = IRV Vauxhall Astra
	irv2 = IRV I3
	
	[Category Name]
	spawncode = Name on menu
	policet = Police Transport

On **line 2**, you can add **Disabled Vehicles**, these will appear out of service and locked on the menu.
On **line 3**, you can set the **CommandName** to open the menu. Do not add "/".

**Creating a category:**
All categories must start with [Category Name] on a new line.

**Adding vehicles to a category:**
  You must list vehicles under the relevant category you want them to appear in.
  spawncode = Name on menu
*eg, police = Police Cruiser*
  
## Source Code
Please find the source code in the **"src"** folder. Please ensure you follow the licence in **"LICENCE.md"**.

## Screenshots
Take a look at some screenshots of the old plugin in action!

![VehicleSpawner](https://i.imgur.com/REgtP6X.png)

![VehicleSpawner](https://i.imgur.com/uAgJf1O.png)
