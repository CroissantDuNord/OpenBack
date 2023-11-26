# TeamByte Backrooms Texture Pack Explained

The server use a custom texture pack, With [Custom Model Data](), To use multiple texture on the same item

Each item with custom texture have overrides with their "Texture Location" and "ID", in multiple JSON file located in "pack\assets\minecraft\models\item\*" This files contains those ID and texture location use a give command to see them in-game (/give @p iron_hoe{CustomModelData:3} 1) This will give you an iron rod with the texture (override) of the crowbar ID 3, Change the item & ID to use another texture

*Item in-game*

![image](https://github.com/CroissantDuNord/OpenBack/assets/79372025/8b65c660-5f63-42b9-973e-2b8a0ceccd21)


**ITEM FILE EXPLAINED:** (pack\assets\minecraft\models\item\iron_hoe.json)
```
	"overrides": [
		{"predicate": {"custom_model_data":3}, "model": "item/weapons/crowbar"}
		                                  = ITEM ID         = TEXTURE FILE / LOCATION
	]
```


## Item Texture Custom Model Data Usage
Those are the item used with their overrides, check the file to see the IDs

* tripwire_hook: Keys
* string: copperCoil copperWire 
* stick: ironRod IronStaff
* spiderEye: smilerEye
* scute (UNKNOWN)
* rotten_flesh skinPiece, redFlesh
* red_stained_glass: guiDeclineButton, GuiExitButton
* lime_stained_glass: guiConfirmButton
* light_blue_stained_glass: guiLastButton, guiNextButton
* red_dye: advancedCircutBoard
* potion: antibiotics
* poisonous_potato: wormling
* paper: TitaniumPlate
* netherite_sword: living_sword
* netherite_shovel: blaster, disruptor, taser, jitterzapper, thunderstorm
* netherbrick: LivingFragment
* light_gray_dye: Plastic
* lapis_lazuli: complexCircutBoard
* iron_sword: ironKnife, IronSword
* iron_pickaxe: ironPickaxe
* iron_nugget: antibiotics, fungicideSpray
* iron_ingot: TitaniumIngot, TitaniumScrap
* iron_hoe: CrowBar
* gray_stained_glass: guiTile
* gray_dye: toughFabric
* golden_sword: memorySword
