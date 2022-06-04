# SaferRiskAcceptance
This repository is a fork of AstralRiskAcceptance where I compile it for my friends. It's not really "safer" if you don't know me in game and trust me. These are my changes:
- The URL of allowed.txt points to one I control in case it's possible to do some weird exploit.
- Deletion of the world name is removed as this version is designed for users of ReMod and not ReModCE.

Credits for 99% of the work goes to the upstream repository and its readme is pasted below.
# AstralRiskAcceptance
Forces RiskyFunctions to be allowed

(we know the risks, why limit us?)

# Features
- Hooks `System.Net` `WebRequest.CreateHttp(Uri)`
- Hooks `System.Net` `WebRequest.DownloadString(string)`
- Hooks `UnityEngine.Networking` `UnityWebRequest.Get(string)`

Create an [issue](https://github.com/Astrum-Project/AstralRiskAcceptance/issues/new) if you find any mods that use an alternative method.

# Mods I have tested this with:
- [StandaloneThirdPerson](https://github.com/gompoc/VRChatMods/tree/master/StandaloneThirdPerson) (gompoc)
- [VRChatUtilityKit](https://github.com/loukylor/VRC-Mods/tree/main/VRChatUtilityKit) (loukylor)
- [TeleporterVR](https://github.com/MintLily/VRChat-TeleporterVR) (KortyBoi/MintLily)
- [ReModCE](https://github.com/RequiDev/ReModCE) (RequiDev)
