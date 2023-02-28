# GGC-Weapons
 Free Weapon Pack for FiveM

## Drop first code in ``qb-core/shared/items.lua``
```lua

    -- GGC Custom Weapons -- Melees
    ['weapon_katana'] 				 = {['name'] = 'weapon_katana', 	 		  	['label'] = 'Katana', 					['weight'] = 2000, 		['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'weapon_katana.png', 			['unique'] = true, 		['useable'] = false,	['description'] = 'A single-edged sword that is the longer of a pair worn by the Japanese samurai.'},
    ['weapon_shiv'] 				 = {['name'] = 'weapon_shiv', 	 		  		['label'] = 'Shiv', 					['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'weapon_shiv.png', 				['unique'] = true, 		['useable'] = false,	['description'] = 'An instrument composed of a blade fixed into a handle, used for cutting or as a weapon.'},
    ['weapon_sledgehammer'] 		 = {['name'] = 'weapon_sledgehammer', 	 		['label'] = 'Sledge Hammer', 			['weight'] = 9000, 		['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'weapon_sledgehammer.png', 		['unique'] = true, 		['useable'] = false,	['description'] = 'A Sledge Hammer to destroy peoples heads... jk... unless...'},
    ['weapon_karambit'] 			 = {['name'] = 'weapon_karambit', 			 	['label'] = 'Karambit', 				['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'weapon_karambit.png', 		    ['unique'] = true, 		['useable'] = false,	['description'] = 'A short knife with a pointed and edged blade, used as a weapon'},
    ['weapon_keyboard'] 			 = {['name'] = 'weapon_keyboard', 				['label'] = 'Keyboard', 				['weight'] = 3000, 		['type'] = 'weapon', 	['ammotype'] = nil,			    	['image'] = 'weapon_keyboard.png', 			['unique'] = true, 		['useable'] = false, 	['description'] = 'YOU CAN USE THIS TO HIT YOUR SON xD'},
    -- GGC Custom Weapons -- Lethals
	['weapon_beanbag'] 			     = {['name'] = 'weapon_beanbag', 	 	  		['label'] = 'Bean Bag', 				['weight'] = 10000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_SHOTGUN',			['image'] = 'weapon_beanbag.png', 			['unique'] = true, 		['useable'] = false, 	['description'] = 'A shotgun? no!'},
	-- GGC Custom Weapons -- Hand Guns
	['weapon_glock17'] 				 = {['name'] = 'weapon_glock17', 				['label'] = 'Glock-17', 				['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'weapon_glock17.png', 			['unique'] = true, 		['useable'] = false,	['description'] = 'The Glock 17 is the original 9×19mm Parabellum model, with a standard magazine capacity of 17 rounds.'},
	['weapon_glock18c'] 			 = {['name'] = 'weapon_glock18c', 				['label'] = 'Glock-18C', 				['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'weapon_glock18c.png', 			['unique'] = true, 		['useable'] = false,	['description'] = 'The Glock 18C is a selective-fire variant of the Glock 17.'},
	['weapon_glock22'] 			     = {['name'] = 'weapon_glock22', 				['label'] = 'Glock-22', 				['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'weapon_glock22.png', 			['unique'] = true, 		['useable'] = false,	['description'] = 'The Glock 22 is a .40 S&W version of the full-sized Glock 17.'},
	['weapon_deagle'] 					 = {['name'] = 'weapon_deagle', 			['label'] = 'Desert Eagle',			    ['weight'] = 8000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'weapon_deagle.png', 			['unique'] = true, 		['useable'] = false,	['description'] = 'The Desert Eagle is a gas-operated, semi-automatic pistol known for chambering the .50 Action Express, the largest centerfire cartridge of any magazine-fed, self-loading pistol.'},
	['weapon_fnx45'] 				 = {['name'] = 'weapon_fnx45', 	 				['label'] = 'FN FNX-45', 				['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'weapon_fnx45.png', 			['unique'] = true, 		['useable'] = false,	['description'] = 'The FN FNX pistol is a series of semi-automatic, the pistol is chambered for the 9×19mm Parabellum, .40 S&W, and .45 ACP cartridges.'},
	['weapon_m1911'] 				 = {['name'] = 'weapon_m1911', 	 			  	['label'] = 'M1911', 					['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'weapon_m1911.png',  			['unique'] = true, 		['useable'] = false,	['description'] = 'The M1911 (Colt 1911 or Colt Government) is a single-action, recoil-operated, semi-automatic pistol chambered for the .45 ACP cartridge.'},
    ['weapon_glock20'] 				 = {['name'] = 'weapon_glock20', 	 			['label'] = 'Glock-20', 				['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'weapon_glock20.png',  			['unique'] = true, 		['useable'] = false,	['description'] = 'An ambidextrous, reversible magazine latch makes the GLOCK 20 an ideal handgun for right- and left-handed shooters.'},
    ['weapon_glock19gen4'] 			 = {['name'] = 'weapon_glock19gen4', 	 		['label'] = 'Glock-19 Gen 4', 			['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'weapon_glock19gen4.png',  		['unique'] = true, 		['useable'] = false,	['description'] = 'The GLOCK 19 Gen4 pistol in 9 mm Luger offers great firepower while allowing to shoot quick and accurately.'},
    ['weapon_browning'] 		     = {['name'] = 'weapon_browning', 				['label'] = 'Browning', 				['weight'] = 5000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'weapon_browning.png', 			['unique'] = true, 		['useable'] = false, 	['description'] = 'The Browning 9-mm pistol is a personal protection weapon used mainly in close-quarter combat.'},
    -- GGC Custom Weapons -- SMGs
    ['weapon_pmxfm'] 				 = {['name'] = 'weapon_pmxfm', 	 			  	['label'] = 'Beretta PMX', 				['weight'] = 11000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_SMG',				['image'] = 'weapon_pmxfm.png',  			['unique'] = true, 		['useable'] = false,	['description'] = 'The Beretta PMX is a 9x19mm Parabellum caliber submachine gun, designed and manufactured by the Italian company Beretta.'},
    ['weapon_mac10'] 				 = {['name'] = 'weapon_mac10', 			 		['label'] = 'MAC-10', 					['weight'] = 10000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_SMG',				['image'] = 'weapon_mac10.png', 			['unique'] = true, 		['useable'] = false, 	['description'] = 'The Military Armament Corporation Model 10, commonly known as the MAC 10 and also known as the M10 or MAC-10.'},
    -- GGC Custom Weapons -- Rifles
    ['weapon_mk47fm'] 				 = {['name'] = 'weapon_mk47fm', 	 			['label'] = 'MK47 Mutant', 				['weight'] = 16000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'weapon_mk47fm.png',  			['unique'] = true, 		['useable'] = false,	['description'] = 'The Mk47 Mutant is an American-made semi-automatic rifle chambered in 7.62×39mm caliber.'},
    ['weapon_m6ic'] 				 = {['name'] = 'weapon_m6ic', 	 			  	['label'] = 'LWRC M6IC', 				['weight'] = 14000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'weapon_m6ic.png',  			['unique'] = true, 		['useable'] = false,	['description'] = 'The LWRC M6IC is an AR-15 direct impingement rifle made by LWRC and was created for the US Military.'},
    ['weapon_scarsc'] 				 = {['name'] = 'weapon_scarsc', 	 			['label'] = 'Scar SC', 					['weight'] = 14000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'weapon_scarsc.png',  			['unique'] = true, 		['useable'] = false,	['description'] = 'The FN SCAR-SC is offered in the U.S. as select-fire only with a non-reciprocating charging handle and telescoping buttstock.'},
    ['weapon_m4'] 					 = {['name'] = 'weapon_m4', 	 			  	['label'] = 'M4A1 Carbine', 			['weight'] = 13000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'weapon_m4.png',			 	['unique'] = true, 		['useable'] = false,	['description'] = 'The M4 carbine is a 5.56×45mm NATO, gas-operated, magazine-fed carbine developed in the United States during the 1980s.'},
    ['weapon_ak47'] 		 		 = {['name'] = 'weapon_ak47', 	 			  	['label'] = 'AK-47', 					['weight'] = 13000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'weapon_ak47.png', 				['unique'] = true, 		['useable'] = false,	['description'] = 'The AK-47, officially known as the Avtomat Kalashnikova, is a gas-operated assault rifle that is chambered for the 7.62×39mm cartridge.'},
    ['weapon_ak74'] 		 		 = {['name'] = 'weapon_ak74', 	 			  	['label'] = 'AK-74', 					['weight'] = 13000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'weapon_ak74.png', 				['unique'] = true, 		['useable'] = false,	['description'] = 'The AK-74 or Kalashnikov automatic rifle model 1974 is a 5.45mm assault rifle developed in the early 1970s in the Soviet Union.'},
    ['weapon_aks74'] 		 		 = {['name'] = 'weapon_aks74', 	 			  	['label'] = 'AKS-74', 					['weight'] = 13000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'weapon_aks74.png', 			['unique'] = true, 		['useable'] = false,	['description'] = 'The AKS-74U Short Assault Rifle is a shortened version of the AKS-74 Assault Rifle released in 1979.'},
    ['weapon_groza'] 				 = {['name'] = 'weapon_groza', 			 		['label'] = 'OTs-14 Groza', 			['weight'] = 15000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'weapon_groza.png', 			['unique'] = true, 		['useable'] = false, 	['description'] = 'The OTs-14 Groza is a Russian selective fire bullpup assault rifle chambered for the 7.62×39 round and the 9×39mm subsonic round.'},

```

## Drop the next code in ``qb-core/shared/weapons.lua``
```lua

    -- GGC Custom Weapons -- Melees
	[`weapon_katana`] 			 	= {['name'] = 'weapon_katana', 				['label'] = 'Katana', 					['weapontype'] = 'Melee',			['ammotype'] = nil,						['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
    [`weapon_shiv`] 			 	= {['name'] = 'weapon_shiv', 				['label'] = 'Shiv', 					['weapontype'] = 'Melee',			['ammotype'] = nil,						['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
    [`weapon_sledgehammer`] 		= {['name'] = 'weapon_sledgehammer', 		['label'] = 'Sledge Hammer', 			['weapontype'] = 'Melee',			['ammotype'] = nil,						['damagereason'] = 'Melee killed / Whacked / Executed / Beat down / Murdered / Battered'},
    [`weapon_karambit`] 			= {['name'] = 'weapon_karambit', 			['label'] = 'Karambit', 				['weapontype'] = 'Melee',			['ammotype'] = nil,						['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
    [`weapon_keyboard`] 			= {['name'] = 'weapon_keyboard', 			['label'] = 'Keyboard', 				['weapontype'] = 'Melee',			['ammotype'] = nil,						['damagereason'] = 'Melee killed / Whacked / Executed / Beat down / Murdered / Battered'},
    -- GGC Custom Weapons -- Lethals
	[`weapon_beanbag`] 				= {['name'] = 'weapon_beanbag', 			['label'] = 'Bean Bag', 				['weapontype'] = 'Shotgun',			['ammotype'] = 'AMMO_SHOTGUN',			['damagereason'] = 'Died'},
	-- GGC Custom Weapons -- Hand Guns
	[`weapon_glock17`] 		 		= {['name'] = 'weapon_glock17', 			['label'] = 'Glock-17',		    		['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',			['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_glock18c`] 		 	= {['name'] = 'weapon_glock18c', 			['label'] = 'Glock-18 Custom',		    ['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',			['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_glock22`] 		 		= {['name'] = 'weapon_glock22', 			['label'] = 'Glock-22',		    		['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',			['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_deagle`] 		 		= {['name'] = 'weapon_deagle', 				['label'] = 'Desert Eagle',		    	['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',			['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_fnx45`] 		 		= {['name'] = 'weapon_fnx45', 				['label'] = 'FN FNX-45',		    	['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',			['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_m1911`] 		 		= {['name'] = 'weapon_m1911', 				['label'] = 'M1911',		    		['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',			['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
    [`weapon_glock20`] 		 		= {['name'] = 'weapon_glock20', 			['label'] = 'Glock-20',		    		['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',			['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
    [`weapon_glock19gen4`] 		 	= {['name'] = 'weapon_glock19gen4', 		['label'] = 'Glock-19 Gen 4',		    ['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',			['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
    [`weapon_browning`] 		 	= {['name'] = 'weapon_browning', 			['label'] = 'Browning',		    		['weapontype'] = 'Pistol',			['ammotype'] = 'AMMO_PISTOL',			['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
    -- GGC Custom Weapons -- SMGs
    [`weapon_pmxfm`] 			 	= {['name'] = 'weapon_pmxfm', 				['label'] = 'Beretta PMX', 				['weapontype'] = 'Submachine Gun',	['ammotype'] = 'AMMO_SMG',				['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},
    [`weapon_mac10`] 			 	= {['name'] = 'weapon_mac10', 				['label'] = 'MAC-10', 					['weapontype'] = 'Submachine Gun',	['ammotype'] = 'AMMO_SMG',				['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},
    -- GGC Custom Weapons -- Rifles
	[`weapon_mk47fm`] 		 		= {['name'] = 'weapon_mk47fm', 	 			['label'] = 'MK47 Mutant', 				['weapontype'] = 'Assault Rifle',	['ammotype'] = 'AMMO_RIFLE',			['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
    [`weapon_m6ic`] 		 		= {['name'] = 'weapon_m6ic', 	 			['label'] = 'LWRC M6IC', 				['weapontype'] = 'Assault Rifle',	['ammotype'] = 'AMMO_RIFLE',			['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
    [`weapon_scarsc`] 		 		= {['name'] = 'weapon_scarsc', 	 			['label'] = 'Scar SC', 					['weapontype'] = 'Assault Rifle',	['ammotype'] = 'AMMO_RIFLE',			['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
    [`weapon_m4`] 		 			= {['name'] = 'weapon_m4', 	 				['label'] = 'M4A1 Carbine', 			['weapontype'] = 'Assault Rifle',	['ammotype'] = 'AMMO_RIFLE',			['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
    [`weapon_ak47`] 		 		= {['name'] = 'weapon_ak47', 	 			['label'] = 'AK-47', 					['weapontype'] = 'Assault Rifle',	['ammotype'] = 'AMMO_RIFLE',			['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
    [`weapon_ak74`] 		 		= {['name'] = 'weapon_ak74', 	 			['label'] = 'AK-74', 					['weapontype'] = 'Assault Rifle',	['ammotype'] = 'AMMO_RIFLE',			['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
    [`weapon_aks74`] 		 		= {['name'] = 'weapon_aks74', 	 			['label'] = 'AKS-74', 					['weapontype'] = 'Assault Rifle',	['ammotype'] = 'AMMO_RIFLE',			['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
    [`weapon_groza`] 		 		= {['name'] = 'weapon_groza', 	 			['label'] = 'OTs-14 Groza', 			['weapontype'] = 'Assault Rifle',	['ammotype'] = 'AMMO_RIFLE',			['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
    
```

## Drop the next code in ``qb-weapons/config.lua``
```lua
    -- GGC Custom Weapons -- Melees
	['weapon_katana'] 		    = 0.15,
	['weapon_shiv'] 		    = 0.15,
	['weapon_sledgehammer']     = 0.15,
	['weapon_karambit']         = 0.15,
	['weapon_keyboard']         = 0.15,
	-- GGC Custom Weapons -- Lethals
    ["weapon_beanbag"]          = 0.15,
	-- GGC Custom Weapons -- Hand Guns
	['weapon_glock17'] 		    = 0.15,
	['weapon_glock18c'] 		= 0.15,
	['weapon_glock22'] 			= 0.15,
	['weapon_deagle'] 			= 0.15,
	['weapon_fnx45'] 			= 0.15,
	['weapon_m1911'] 			= 0.15,
    ['weapon_glock20'] 			= 0.15,
    ['weapon_glock19gen4'] 		= 0.15,
    ['weapon_browning'] 		= 0.15,
    -- GGC Custom Weapons -- SMGs
    ['weapon_pmxfm'] 			= 0.15,
    ['weapon_mac10'] 			= 0.15,
    -- GGC Custom Weapons -- Rifles
    ['weapon_mk47fm'] 			= 0.15,
    ['weapon_m6ic'] 			= 0.15,
    ['weapon_scarsc'] 			= 0.15,
    ['weapon_m4'] 			    = 0.15,
    ['weapon_ak47'] 			= 0.15,
    ['weapon_ak74'] 			= 0.15,
    ['weapon_aks74'] 			= 0.15,
    ['weapon_groza'] 			= 0.15,

```

## Drop the next code in ``qb-weapons/config.lua`` (about line 209)
```lua

	-- GGC Custom Weapons -- Hand Guns
	['WEAPON_GLOCK17'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_GLOCK17_CLIP_01',
            item = 'pistol_defaultclip',
            type = 'clip',
        },
        ['extendedclip'] = {
            component = 'COMPONENT_GLOCK17_CLIP_02',
            item = 'pistol_extendedclip',
            type = 'clip',
        },
        ['flashlight'] = {
            component = 'COMPONENT_AT_PI_FLSH',
            item = 'pistol_flashlight',
        },
        ['suppressor'] = {
            component = 'COMPONENT_AT_PI_SUPP',
            item = 'pistol_suppressor',
        },
    },
    ['WEAPON_GLOCK18C'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_APPISTOL_CLIP_01',
            item = 'pistol_defaultclip',
            type = 'clip',
        },
    },
    ['WEAPON_GLOCK22'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_PISTOL_CLIP_01',
            item = 'pistol_defaultclip',
            type = 'clip',
        },
    },
    ['WEAPON_DEAGLE'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_DEAGlE_CLIP_01',
            item = 'pistol_defaultclip',
            type = 'clip',
        },
    },
    ['WEAPON_FNX45'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_FNX45_CLIP_01',
            item = 'pistol_defaultclip',
            type = 'clip',
        },
    },
    ['WEAPON_M1911'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_M1911_CLIP_01',
            item = 'pistol_defaultclip',
            type = 'clip',
        },
    },
    ['WEAPON_GLOCK20'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_PISTOL_CLIP_01',
            item = 'pistol_defaultclip',
            type = 'clip',
        },
    },
    ['WEAPON_GLOCK19GEN4'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_PISTOL_CLIP_01',
            item = 'pistol_defaultclip',
            type = 'clip',
        },
    },
    ['WEAPON_BROWNING'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_PISTOL_CLIP_01',
            item = 'pistol_defaultclip',
            type = 'clip',
        },
    },
    -- GGC Custom Weapons -- SMGs
    ['WEAPON_PMXFM'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_SMG_CLIP_01',
            item = 'smg_defaultclip',
            type = 'clip',
        },
    },
    ['WEAPON_MAC10'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_SMG_CLIP_01',
            item = 'smg_defaultclip',
            type = 'clip',
        },
    },
	-- GGC Custom Weapons -- Rifles
    ['WEAPON_MK47FM'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_MK47_CLIP_01',
            item = 'assaultrifle_defaultclip',
            type = 'clip',
        },
    },
    ['WEAPON_M6IC'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_ASSAULTRIFLE_CLIP_01',
            item = 'assaultrifle_defaultclip',
            type = 'clip',
        },
    },
    ['WEAPON_SCARSC'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_ASSAULTRIFLE_CLIP_01',
            item = 'assaultrifle_defaultclip',
            type = 'clip',
        },
    },
    ['WEAPON_M4'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_M4_CLIP_01',
            item = 'assaultrifle_defaultclip',
            type = 'clip',
        },
        ['extendedclip'] = {
            component = 'COMPONENT_M4_CLIP_02',
            item = 'assaultrifle_extendedclip',
            type = 'clip',
        },
    },
    ['WEAPON_AK47'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_AK47_CLIP_01',
            item = 'assaultrifle_defaultclip',
            type = 'clip',
        },
        ['extendedclip'] = {
            component = 'COMPONENT_AK47_CLIP_02',
            item = 'assaultrifle_extendedclip',
            type = 'clip',
        },
    },
    ['WEAPON_AK74'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_ASSAULTRIFLE_CLIP_01',
            item = 'assaultrifle_defaultclip',
            type = 'clip',
        },
    },
    ['WEAPON_AKS74'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_ASSAULTRIFLE_CLIP_01',
            item = 'assaultrifle_defaultclip',
            type = 'clip',
        },
    },
    ['WEAPON_GROZA'] = {
        ['defaultclip'] = {
            component = 'COMPONENT_ASSAULTRIFLE_CLIP_01',
            item = 'assaultrifle_defaultclip',
            type = 'clip',
        },
    },
```

## Add this in qb-smallresources/client/weapdraw.lua
```lua

    -- GGC Custom Weapons -- Melees
    'WEAPON_KATANA',
    'WEAPON_SHIV',
    'WEAPON_SLEDGEHAMMER',
    'WEAPON_KARAMBIT',
    'WEAPON_KEYBOARD',
    -- GGC Custom Weapons -- Lethals
    'WEAPON_BEANBAG',
    -- GGC Custom Weapons -- Hand Guns
    'WEAPON_GLOCK17',
    'WEAPON_GLOCK18C',
    'WEAPON_GLOCK22',
    'WEAPON_DEAGLE',
    'WEAPON_FNX45',
    'WEAPON_M1911',
    'WEAPON_GLOCK20',
    'WEAPON_GLOCK19GEN4',
    'WEAPON_BROWNING',
    -- GGC Custom Weapons -- SMGs
    'WEAPON_PMXFM',
    'WEAPON_MAC10',
    -- GGC Custom Weapons -- Rifles
    'WEAPON_MK47FM',
    'WEAPON_M6IC',
    'WEAPON_SCARSC',
    'WEAPON_M4',
    'WEAPON_AK47',
    'WEAPON_AK74',
    'WEAPON_AKS74',
    'WEAPON_GROZA',

```

## Replace the next code in ``qb-smallresources/vonfig.lua``
```lua
local holsterableWeapons = {
	-- GGC Custom Weapons -- Hand Guns
	'WEAPON_GLOCK17',
	'WEAPON_GLOCK18C',
	'WEAPON_GLOCK22',
	'WEAPON_DEAGLE',
	'WEAPON_FNX45',
	'WEAPON_M1911',
    'WEAPON_GLOCK20',
    'WEAPON_GLOCK19GEN4',
    'WEAPON_BROWNING',
}
```

## Drop the next code in ``qb-smallresources/client/recoil.lua`` ( LINE 107 )
```lua
    -- GGC Custom Weapons -- Lethals
    [GetHashKey("weapon_beanbag")] = 0.1,
	-- GGC Custom Weapons -- Hand Guns
	[GetHashKey("weapon_glock17")] = 0.40,
	[GetHashKey("weapon_glock18c")] = 0.45,
	[GetHashKey("weapon_glock22")] = 0.50,
	[GetHashKey("weapon_deagle")] = 0.60,
	[GetHashKey("weapon_fnx45")] = 0.55,
	[GetHashKey("weapon_m1911")] = 0.30,
    [GetHashKey("weapon_glock20")] = 0.40,
    [GetHashKey("weapon_glock19gen4")] = 0.40,
    [GetHashKey("weapon_browning")] = 0.40,
	-- GGC Custom Weapons -- SMGs
    [GetHashKey("weapon_pmxfm")] = 0.50,
    [GetHashKey("weapon_mac10")] = 0.50,
	-- GGC Custom Weapons -- Rifles
	[GetHashKey("weapon_mk47fm")] = 0.70,
    [GetHashKey("weapon_m6ic")] = 0.75,
    [GetHashKey("weapon_scarsc")] = 0.65,
    [GetHashKey("weapon_m4")] = 0.65,
    [GetHashKey("weapon_ak47")] = 0.65,
    [GetHashKey("weapon_ak74")] = 0.65,
    [GetHashKey("weapon_aks74")] = 0.75,
    [GetHashKey("weapon_groza")] = 0.75,
```

## Replace the next code in ``qb-ambulancejob/config.lua``
```lua
    --[[ HIGH CALIBER ]]
    -- GGC Custom Weapons -- Rifles
    [`WEAPON_MK47FM`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_M6IC`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_SCARSC`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_M4`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_AK47`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_AK74`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_AKS74`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_GROZA`] = Config.WeaponClasses['HIGH_CALIBER'],
    --[[ MEDIUM CALIBER ]]
    -- GGC Custom Weapons -- SMGs
    [`WEAPON_PMXFM`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_MAC10`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    --[[ SMALL CALIBER ]]
    -- GGC Custom Weapons -- Hand Guns
    [`WEAPON_GLOCK17`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_GLOCK18C`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_GLOCK22`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_DEAGLE`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_FNX45`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_M1911`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_GLOCK20`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_GLOCK19GEN4`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_BROWNING`] = Config.WeaponClasses['SMALL_CALIBER'],
    --[[ SHOTGUN ]]
    --[[ CUTTING ]]
    -- GGC Custom Weapons -- Melees
    [`WEAPON_KATANA`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_SHIV`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_KARAMBIT`] = Config.WeaponClasses['CUTTING'],
    --[[ HEAVY IMPACT ]]
    -- GGC Custom Weapons -- Melees
    [`WEAPON_SLEDGEHAMMER`] = Config.WeaponClasses['HEAVY_IMPACT'],
    [`WEAPON_KEYBOARD`] = Config.WeaponClasses['HEAVY_IMPACT'],
    --[[ Shotguns ]]--
    -- GGC Custom Weapons -- Lethals
    [`WEAPON_BEANBAG`] = Config.WeaponClasses['SHOTGUN'],
```

## Add this next line of code to your weaponsTable in `ps-dispatch/client/cl_events.lua`
```lua
    -- GGC Custom Weapons -- Lethals
    [GetHashKey("WEAPON_GLOCK17")] = "Bean Bag",
	-- GGC Custom Weapons -- Hand Guns
    [GetHashKey("WEAPON_GLOCK17")] = "CLASS 1: Glock-17",
    [GetHashKey("WEAPON_GLOCK18C")] = "CLASS 2: Glock-18 Custom",
    [GetHashKey("WEAPON_GLOCK22")] = "CLASS 1: Glock-22",
    [GetHashKey("WEAPON_DEAGLE")] = "CLASS 2: Desert Eagle",
    [GetHashKey("WEAPON_FNX45")] = "CLASS 1: FN FNX-45",
    [GetHashKey("WEAPON_M1911")] = "CLASS 1: M1911",
    [GetHashKey("WEAPON_GLOCK20")] = "CLASS 1: Glock-20",
    [GetHashKey("WEAPON_GLOCK19GEN4")] = "CLASS 1: Glock-19 Gen 4",
    [GetHashKey("WEAPON_BROWNING")] = "CLASS 1: Browning",
    -- GGC Custom Weapons -- SMGs
    [GetHashKey("WEAPON_PMXFM")] = "CLASS 2: Beretta PMX",
    [GetHashKey("WEAPON_MAC10")] = "CLASS 2: MAC-10",
    -- GGC Custom Weapons -- Rifles
    [GetHashKey("WEAPON_MK47FM")] = "CLASS 3: MK47 Mutant",
    [GetHashKey("WEAPON_M6IC")] = "CLASS 3: LWRC M6IC",
    [GetHashKey("WEAPON_SCARSC")] = "CLASS 3: Scar SC",
    [GetHashKey("WEAPON_M4")] = "CLASS 3: M4A1 Carbine",
    [GetHashKey("WEAPON_AK47")] = "CLASS 3: AK-47",
    [GetHashKey("WEAPON_AK74")] = "CLASS 3: AK-74",
    [GetHashKey("WEAPON_AKS74")] = "CLASS 3: AKS-74",
    [GetHashKey("WEAPON_GROZA")] = "CLASS 3: OTs-14 Groza",
```

## Add this to your backitems config/client
```lua
    -- GGC Weapons -- Melees
    ["weapon_sledgehammer"] = {
        model="w_me_sledgehammer",
        back_bone = 24818,
        x = -0.0,
        y = -0.17,
        z = 0.08,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_katana"] = {
        model="w_me_katana",
        back_bone = 24818,
        x = -0.0,
        y = -0.17,
        z = 0.08,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_keyboard"] = {
        model="w_me_keyboard",
        back_bone = 24818,
        x = -0.0,
        y = -0.17,
        z = 0.08,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    -- GGC Custom Weapons -- Lethals
    ["weapon_beanbag"] = {
        model="w_sg_beanbag",
        back_bone = 24818,
        x = 0.0,
        y = -0.17,
        z = -0.12,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    -- GGC Weapons -- SMGs
    ["weapon_pmxfm"] = {
        model="pmx_fluffymods",
        back_bone = 24818,
        x = 0.0,
        y = -0.17,
        z = -0.12,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_mac10"] = {
        model="w_sb_mac10",
        back_bone = 24818,
        x = 0.0,
        y = -0.17,
        z = -0.12,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    -- GGC Weapons -- Rifles
    ["weapon_ak47"] = {
        model="w_ar_ak47",
        back_bone = 24818,
        x = 0.0,
        y = -0.17,
        z = -0.12,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_ak74"] = {
        model="w_ar_ak74",
        back_bone = 24818,
        x =  0.12,
        y = -0.17,
        z = -0.0,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 0.0,
    },
    ["weapon_aks74"] = {
        model="w_ar_assaultrifle_aks74",
        back_bone = 24818,
        x =  0.12,
        y = -0.17,
        z = -0.0,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 0.0,
    },
    ["weapon_groza"] = {
        model="w_ar_groza",
        back_bone = 24818,
        x = 0.0,
        y = -0.17,
        z = -0.12,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_m4"] = {
        model="w_ar_m4",
        back_bone = 24818,
        x = -0.0,
        y = -0.17,
        z = 0.08,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_m6ic"] = {
        model="m6ic",
        back_bone = 24818,
        x =  0.12,
        y = -0.17,
        z = -0.0,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 0.0,
    },
    ["weapon_mk47fm"] = {
        model="MK47FluffysMods",
        back_bone = 24818,
        x = -0.0,
        y = -0.17,
        z = 0.08,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_scarsc"] = {
        model="w_ar_scarsc",
        back_bone = 24818,
        x =  0.12,
        y = -0.17,
        z = -0.0,
        x_rotation = 0.0,
        y_rotation = 180.0,
        z_rotation = 0.0,
    },
```