# nx-universalprompts
Replaces ABXY button prompts on Nintendo Switch system menus with generic prompts based on button location.

It does not work in any games* and is not exhaustive in system menus (e.g. it does not update the 'A' prompt on the lock screen).  
<sub>(*unless the game is using the system font for its prompts which I don't know if any game does)</sub>

Under the hood, it's a RomFS patch for FontNintendoExtension. The font file already contains generic button icons and so was just modified to replace any ABXY icons with the respective generic one. It's a TrueType Font, encrypted as BFTTF — [BFTTFutil](https://github.com/hadashisora/BFTTFutil) or [NintyFont](https://github.com/hadashisora/NintyFont) can be used to decrypt it.

Requires a modded Switch running Atmosphère.
