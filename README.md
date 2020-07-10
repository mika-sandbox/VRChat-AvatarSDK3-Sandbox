# VRChat Avatar SDK Version 3 Sandbox Repository

Experimental Unity Project that testing VRChat Avatar 3.0.

> NOTICE: THIS PROJECT IS EXPERIMENTAL. PLEASE USE IT AT YOUR OWN RISK.

## Requirements

- Unity 2018.4
- VRChat that supports Avatar 3.0 (currently in beta on Steam)
  - SDK Version : `VRCSDK-AVATAR-2020.07.09.15.19_Public`

## Implementations

### Fukidashi System (Avatar Message Board)

> LIMITATION: Only some animations are set.

See this video : https://twitter.com/6jz/status/1281639944444801024

#### How to use

1. Attach below assets to `VRC Avatar Descriptor`
   - `Mochizuki/VRChat/FukidashiSystem/AnimationControllers/FXLayer` to `Animation Layers -> FX`
   - `Mochizuki/VRChat/FukidashiSystem/Expressions/FrontMenu` to `Expressions -> Expressions Menu`
2. Set `Mochizuki/VRChat/FukidashiSystem/Prefabs/Constraints` to child of avatar root
3. Build and Test Avatar
