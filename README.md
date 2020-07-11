# VehicleSpawner - London Studios
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

## Feedback
We appreciate feedback, bugs and suggestions related to VehicleSpawner and future plugins. We hope you enjoy using the resource and look forward to hearing from people!

## Screenshots
Take a look at some screenshots of the plugin in action!

![VehicleSpawner](https://i.imgur.com/REgtP6X.png)

![VehicleSpawner](https://i.imgur.com/uAgJf1O.png)