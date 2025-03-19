## Comparison Table

Notice:

1. You could learn more differences between CC2 and CC1 from the [CC2 Product Page](https://www.charachorder.com/products/cc2).
2. It seems to me that other unmentioned specs of CC devices would be similar to those of CC1, and they would be marked with an * in the comparison table. 
3. You could further confirm the specs on their Discord server if you have any questions.
4. `???` are the specs which I am not sure about or cannot find information about. If you know of any helpful resources, please message me on Discord (Tangent Chang, @andy23512).
5. This comparison note has [a web application version](https://andy23512.github.io/device-comparator/).

||[Master Forge (M4G)](https://forgekeyboard.com/products/master-forge)|[CharaChorder Two (CC2)](https://www.charachorder.com/products/cc2)|CharaChorder One (CC1)|[CharaChorder Lite (CCL)](https://www.charachorder.com/products/charachorder-lite)|[CharaChorder X (CCX)](https://www.charachorder.com/products/charachorder-x)|[Svalboard (Sval)](https://svalboard.com/)|Market Leading Keyboard|
|-|-|-|-|-|-|-|-|
|==**Computational**==|==**------M4G------**==|==**------CC2------**==|==**------CC1------**==|==**------CCL------**==|==**------CCX------**==|==**------Sval------**==|==**--------------**==|
|**Modalities**|Programmable Keys & Key Combinations|Programmable Keys & Key Combinations|Programmable Keys & Key Combinations|Programmable Keys & Key Combinations|Programmable Keys & Key Combinations|Programmable Keys & Key Combinations|Individually Programmable Keys Only|
|**Possible Inputs**|> 13,000,000,000|> 13,000,000,000|> 13,000,000,000|> 17,000,000,000|> 17,000,000,000[^ccx_possible_input]|???|< 200|
|**Memory**|1,000,000 Actions|60,000 Actions|16,000 Actions|65,000 Actions[^ccl_memory]|65,000 Actions[^ccx_memory]|???|Uses Host CPU Resources|
|**Memory Type**|Embedded|Embedded|Embedded|Embedded|Embedded|Embedded|Uses Host CPU Resources|
|**Driver**|Driverless OS|Driverless OS|Driverless OS|Driverless OS|Driverless OS|???|Requires Custom Driver from Host CPU|
|**Configuration**|Web Based FOSS/Libre offline|Web Based FOSS/Libre offline|Web Based FOSS/Libre offline|Web Based FOSS/Libre offline|Web Based FOSS/Libre offline|Web Based FOSS/Libre offline|Requires Proprietary Software|
|**Microprocessor**|240 MHz Dual Core|240 MHz Dual Core|48 MHz|???|???|133 MHz Dual Core|150 MHz Single Core|
|**Input Style**|Fluid Chorded / Character Entry|Fluid Chorded / Character Entry|Fluid Chorded / Character Entry|Fluid Chorded / Character Entry|Fluid Chorded / Character Entry|Character Entry and Combos[^sval_input_style]|Character Entry Only|
|**API**|Open Serial API Specification|Open Serial API Specification|Open Serial API Specification|Open Serial API Specification|Open Serial API Specification|???|None|
|==**Electrical**==|==**------M4G------**==|==**------CC2------**==|==**------CC1------**==|==**------CCL------**==|==**------CCX------**==|==**------Sval------**==|==**--------------**==|
|**Routing Style**|AntiMatrix with Dedicated Channels|AntiMatrix with Dedicated Channels*|AntiMatrix with Dedicated Channels|AntiMatrix with Dedicated Channels*|N/A[^ccx_dependence]|???|Traditional Key Matrix|
|**Anti-Ghosting**|NKRO+|NKRO+*|NKRO+|NKRO+*|N/A[^ccx_dependence]|NKRO|NKRO|
|**HID Keyboard Schema**|Extended 12 Key Schema|Extended 12 Key Schema*|Extended 12 Key Schema|Extended 12 Key Schema*|Extended 12 Key Schema*|???|6 Key Schema|
|**USB-Hub Ports**|3|X|X|X|X|???|0-1|
|==**Mechanical**==|==**------M4G------**==|==**------CC2------**==|==**------CC1------**==|==**------CCL------**==|==**------CCX------**==|==**------Sval------**==|==**--------------**==|
|**Size (L\*W\*H)**|228\*115\*38 (mm)|295\*111\*29 (mm)[^cc2_size]|296\*110\*38 (mm)|295\*105\*33 (mm)[^cclite_size]|59\*23.25\*16.15 (mm)[^ccx_size]|190\*130\*90 (mm)[^sval_size]|450\*158\*38 (mm)|
|**Weight (Full Device, both hands)**|346-500 g|303 g[^cc2_weight]|308 g|468 g[^cclite_weight]|???|550 g[^sval_weight]|989 g|
|**Switch Style**|3-D Snap Action|3-D Tactile|3-D Tactile|1-D Mechanical[^ccl_switch]|N/A[^ccx_dependence]|3-D Magneto-optical|1-D Mechanical / Optical / Halls|
|**Actuation Force (4-direction / press-down for 3-D switch)**| 55-57 gf / N/A [^m4g_actuation_force]|42 gf / 240 gf|70 gf / 240 gf|35 gf[^ccl_switch]|N/A[^ccx_dependence]|20 gf / 20 gf|40-80 gf|
|**Hardware Interface**|Picatinny Railing|Female ¼”-20 Thread|N/A|N/A|N/A|Female M5 and ¼”-20 Thread|N/A|
|**Switch Durability (cycles each direction)**|20,000,000[^m4g_switch_durability]|1,000,000[^cc2_switch_durability]|200,000[^cc1_switch_durability]|???|N/A[^ccx_dependence]|???|???|
|**Number of 3D Switches**|16|18|18|N/A|N/A|10 (Key Clusters)|N/A|
|**Number of Keys on each 3D Switch**|4|5|5|N/A|N/A|5|N/A|
|**Switch**|[Omron Electronics D2LS-21(20M)](https://eu.mouser.com/ProductDetail/Omron-Electronics/D2LS-2120M?qs=OcgtsXO%2B3gskSBgTf6V7tw%3D%3D)|[Alps Alpine SKRHADE010](https://tech.alpsalpine.com/e/products/detail/SKRHADE010/)|[Alps Alpine SKRHABE010](https://tech.alpsalpine.com/e/products/detail/SKRHABE010/)|Gateron Clear/White|N/A|???|???|
|==**Material**==|==**------M4G------**==|==**------CC2------**==|==**------CC1------**==|==**------CCL------**==|==**------CCX------**==|==**------Sval------**==|==**--------------**==|
|**Shell**|5052 Aluminium Alloy[^m4g_shell_material]|Injection Molded ABS Plastic[^cc2_half_material]|Injection Molded ABS Plastic[^cc1_half_material]|ABS Plastic[^ccl_shell_material]|Injection Molded Plastic[^ccx_shell_material]|ABS Plastic|???|
|**Baseplate**|3D-printed Plastic[^m4g_base_material]|3D-printed Plastic[^cc2_half_material]|Injection Molded ABS Plastic[^cc1_half_material]|ABS Plastic[^ccl_base_material]|N/A|N/A|???|
|==**Other**==|==**------M4G------**==|==**------CC2------**==|==**------CC1------**==|==**------CCL------**==|==**------CCX------**==|==**------Sval------**==|==**--------------**==|==**------M4G------**==|==**------CC2------**==|==**------CC1------**==|==**------CCL------**==|==**------CCX------**==|==**------Sval------**==|==**--------------**==|==**------M4G------**==|==**------CC2------**==|==**------CC1------**==|==**------CCL------**==|==**------CCX------**==|==**------Sval------**==|==**--------------**==|
|**Pointing Device**[^pointing_device]|Trackball / None[^m4g_pointing_device]|Cursor Movement Key|Cursor Movement Key|None|None|Trackball / Touchpad / Trackpoint / None|???|

- **Quietness**: CC2 > CC1 > M4G

## References

### CharaChorder and Forge

- ["Master Forge: Specs Reveal" Video](https://youtu.be/x2swE9URxeA?feature=shared)
- [CC2 Product Page](https://www.charachorder.com/products/cc2)
- [CCL Product Page](https://www.charachorder.com/products/charachorder-lite)
- [CCX Kickstarter Page](https://www.kickstarter.com/projects/charachorder/charachorder-x-type-at-the-speed-of-thought/) 
- [CharaChorder Official Documentation](https://docs.charachorder.com)
- [CharaChorder Discord Server](https://discord.gg/charachorder)

### Svalboard

- [Svalboard Product Page](https://svalboard.com/products/lightly)
- [Svalboard Manual](https://docs.google.com/document/d/1Um4EAIK-GLQGw-9xHUFe-aCtHJDENYUSzhcqQi9ppwU/edit?tab=t.0)
- [QMK Combos Documentation](https://docs.qmk.fm/features/combo)
- [Svalboard Discord Server](https://discord.gg/DnGcHM4Rg8) 

[^m4g_switch_durability]: 20M ops according to [the switch detail page]( https://eu.mouser.com/ProductDetail/Omron-Electronics/D2LS-2120M?qs=OcgtsXO%2B3gskSBgTf6V7tw%3D%3D).

[^cc2_switch_durability]: According to [the CC2 product page](https://www.charachorder.com/products/cc2#:~:text=CC2%20switches%20are%20built%20tougher%2C%20and%20are%20engineered%20to%20last%205X%20longer%20than%20switches%20from%20the%201st%20generation), CC2 switches are built tougher, and are engineered to last 5X longer than switches from the 1st generation.

[^cc1_switch_durability]: 200,000 cycles for each direction according to [this Discord message](https://discord.com/channels/861730583092658206/938239528454475787/1068002221855363082).

[^ccx_memory]: 65,000 chords according to [the CCX Kickstarter page](https://www.kickstarter.com/projects/charachorder/charachorder-x-type-at-the-speed-of-thought/description#:~:text=CharaChorder%20X%20can%20store%20%2B65%2C000%20custom%20chords!)

[^ccx_dependence]: It depends on the spec of the connected keyboard so it doesn't seem to be the spec of CCX itself.

[^ccx_size]: Shell size of CCX from [the CharaChorder official documentation](https://docs.charachorder.com/CharaChorder%20X.html#id1:~:text=CharaChorder%20X%20Dimensions) is used.

[^ccx_possible_input]: CharaChorder Lite has over 17 billion possible input according to [the product page of it](https://www.charachorder.com/products/charachorder-lite#:~:text=Limitless%20Customization-,Over%2017%20Billion), so I think that CCX probably has a similar amount when using with a normal 60% keyboard.

[^m4g_actuation_force]: 55 gF is from [the comparison table in the specs reveal video](https://youtu.be/x2swE9URxeA?feature=shared&t=613). 57 gF is from [the measurement result in that video](https://youtu.be/x2swE9URxeA?feature=shared&t=562). Therefore I listed it as a range (55-57 gF) in table. Besides, regarding the press-down actuation force, since M4G doesn't have 3D press keys, I would define it as N/A here.

[^ccl_memory]: According to [this outdated wiki](https://charachorder.notion.site/FAQs-List-Lite-4a08faf376204974adaa57e8d098ad6d), 65k chords up to 247 actions (eg characters) in length can be stored in the memory

[^ccl_switch]: According to [the Switches section in the official CCL documentation](https://docs.charachorder.com/CharaChorder_Lite.html#switches)

[^cc2_size]: According to [CC2 Dimension and Weight in official CharaChorder document](https://docs.charachorder.com/FAQs.html#dimensions-and-weight), 11 ⅝” x 4 ⅜” x 1 ⅛”.

[^cc2_weight]: According to [CC2 Dimension and Weight in official CharaChorder document](https://docs.charachorder.com/FAQs.html#dimensions-and-weight), 10.7 oz without USB-C.

[^cclite_weight]: According to [CC Lite Dimensions and Weight in official CharaChorder document](https://docs.charachorder.com/FAQs.html#id1:~:text=or%200.52%20lbs-,CharaChorder%20Lite%20FAQs,Dimensions%20and%20Weight,-%EF%83%81), 1 lb 0.5 oz.

[^cclite_size]: According to [CC Lite Dimensions and Weight](https://docs.charachorder.com/FAQs.html#id1:~:text=or%200.52%20lbs-,CharaChorder%20Lite%20FAQs,Dimensions%20and%20Weight,-%EF%83%81), 11 ⅝” (length) x 4 ⅛” (width) x 1 5/16” (height).

[^cc2_half_material]: According to [the official CC2 documentation]( https://docs.charachorder.com/CharaChorder%20Two.html#the-halves).

[^cc1_half_material]: According to [the official CC1 documentation](https://docs.charachorder.com/CharaChorder%20One.html#the-halves)

[^ccl_base_material]: According to [the official CCL documentation](https://docs.charachorder.com/CharaChorder_Lite.html#base)

[^ccl_shell_material]: According to [the official CCL documentation](https://docs.charachorder.com/CharaChorder_Lite.html#key-plate)

[^ccx_shell_material]: According to [the official CCX documentation](https://docs.charachorder.com/CharaChorder%20X.html#the-body)

[^m4g_base_material]: The baseplate (called endoskeleton) is made by 3D printing according to [this video](https://youtu.be/7wb-JlZ2qP0?feature=shared&t=299).

[^m4g_shell_material]: The shell (called exoskeleton) is made of 5052 aluminium alloy according to [this video](https://youtu.be/7wb-JlZ2qP0?feature=shared&t=693). 

[^sval_weight]: According to [this message in Svalboard Discord server](https://discord.com/channels/1053081626898337902/1124364902811844739/1150412902457692221), 275 g per side.

[^sval_size]: According to [this message in Svalboard Discord server](https://discord.com/channels/1053081626898337902/1124364902811844739/1224420873663156224).

[^sval_input_style]: It is possible to use the combo feature of qmk to achieve the chording entry, but it seems that not many users do it.

[^pointing_device]: The default pointing devices on each device are listed. You can remap the cursor movement keys on CC devices, Master Forge, and Svalboard.

[^m4g_pointing_device]: Some tiers of Master Forge bundle don't include the Trackball Bolt-on.