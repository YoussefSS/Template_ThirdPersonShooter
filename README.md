# Template: Third Person Shooter
3rd person shooter (TPP) template with animations (public assets)


#### Downloading animations from mixamo:

- Check In Place
- Format: .fbx
- Skin: Without Skin
- Keyframe Reduction: none

---

### (V1) Initial Commit - No weapons 
[Link to V1 commit](https://github.com/UE4-YSF/Template_ThirdPersonNoWeapon/commit/145684cb70a4750880e870c442c81c01bc855403)

It is the fifth (5th) commit in Eliminated \
[Link to commit in Eliminated](https://github.com/YoussefSS/Eliminated/commit/85be58c18f1790213b8d7cc00e4e68634f6bf0b3) 

Initial commit includes full third person animation for a character with no weapons.

###### Features
- **Diagonal speed is almost the exact same speed as vertical and horizontal by adding movement input on tick instead of its designated function**
- **Character rotation rate is reduced while in air**
- Blend space for movement speed with 0.5 interpolation
- Animation state machine for movement + jumping
- The character does not look directly at where the camera is looking 
- Sprinting

---

### (V2) Pistol and Aiming down sights update
[Link to V2 commit](https://github.com/UE4-YSF/Template_ThirdPersonShooter/commit/df2746c6c2365f7259500bb83bda4f5543a06742)

18th commit in Eliminated
[Link to commit in Eliminated](https://github.com/YoussefSS/Eliminated/commit/1b28fc0863ac5e9e3eb7c074842767533dfc1719)

Crouching, full movement control over aiming down sights, as well as a weapon base class
###### Features

 - Crouching
 - Aiming down sights
 - Complete pistol locomotion animations even while crouched
 - Pistol fire and reload additive animations (montage)
 - Weapon base class with lots of customizable variables that should work with all hitscan weapons
 - Weapon effects (muzzle + impact + trail + sound + bullet decal, etc..) 
 - Crosshair and ammo HUD
