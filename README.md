# NPCDoktroeByTCC
NPCDoktroeByTCC

Creating a Doctor NPC in the Hospital
First, you need to create a Doctor NPC in the hospital that will respond to player interaction and perform medical procedures. You can do this using the ESX framework for creating NPCs, such as using the ESX.Game.SpawnLocalNPC function in client.lua.

Creating a Function to Treat the Player
When interacting with the Doctor NPC, you need a function that will perform the actual player treatment. In this function, you can use the ESX framework for working with finance and inventory, such as using the ESX.PlayerData.money and ESX.PlayerData.addInventoryItem functions. You will also need resources for medicinal items, which you can obtain using the ESX framework for interacting with objects and weapons, such as using ESX.GetWeaponLabel and ESX.GetWeaponHash.

Configuring Compatibility with ox_inventory
To ensure compatibility with ox_inventory, you need to ensure that your script is able to interact with the player's inventory in ox_inventory. You can use the ox_inventory.addItem and ox_inventory.removeItem functions to add and remove items from the inventory.

Integration with ESX_extended
To provide additional functionality offered by ESX_extended, you can use functions such as ESX.RegisterUsableItem, which allows players to use items from their inventory as medicine.


you need 
es_extended https://github.com/mitlight/es_extended

ox_inventory https://github.com/overextended/ox_inventory
