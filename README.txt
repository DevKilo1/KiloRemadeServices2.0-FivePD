Installation:
 Drag and drop the RemadeServicesByKilo folder into your fivepd/plugins folder. Make sure you have the following line added to your fivepd fxmanifest.lua files: "'./plugins/**/config.json'" without the double quotation marks

This only has QBCore compatibility for the purpose of healing players. Unfortunately, it will only heal the player who called it but it works with QBCore. If you don't have a roleplay framework that has custom revives, then you can enable QBCore but leave the treatPlayer false. If reviving the player is as simple as resurrecting their character, this will undoubtedly work. QBCore has its own system for revives, so that's why it's a separate thing. Long story short, if your framework plays an animation when your character dies then it won't work unless your server is QBCore and in that case you need HealPlayer set to true for it to work.

There is no backspacing feature at this time.