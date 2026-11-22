# Frogun-VR
VR Mod for Frogun

unzip to game folder, only tested with virtual desktop XR


<img width="1254" height="1254" alt="Frogun VR Adventure" src="https://github.com/user-attachments/assets/374ba3da-9b72-4cd1-b561-f4ccda571826" />


FROGUN VR  v0.1.4 (test build) - Unity 2019.4.37f1, IL2CPP x64, built-in renderer
==================================================================================

Install
-------
unzip to game folder, only tested with virtual desktop XR
  make sure no controller is connected in VR session might a players 2

**[Nefarius ViGEmBus](https://github.com/nefarius/ViGEmBus/releases) support - with the driver installed (ViGEmBusSetup_x64.msi in the zip) the VR
        controllers are a real virtual Xbox 360 controller ([Controls] InputMethod = Auto / ViGEm / InputSystem).**

The views
---------
TAP R3 **(right stick click) ... first person <-> third person. Hold R3 (0.5 s) = the game's own R3.**

**HOLD X (0.8 s) ............... third person: the game's camera <-> following behind Renata.**
                               [View] StyleToggleHoldX (0 = off). Tapping X is still the game's X.
                               
THIRD PERSON (start) ......... the game's camera (the right stick moves it like on a pad, your view turns with
                               it), or following behind Renata ([View] Follow).
                               
FIRST PERSON ................. you are at Renata's head (head hidden); her arms follow your controllers.

Going through doors uses the game's camera ([View] GameCameraInScenes).

Frogun (6DoF)
-------------
FIRST PERSON only: the tongue is shot where the RIGHT controller points (third person aims as the normal game): Renata turns that way and the game's auto-aim picks targets
near that direction. With no target the tongue also goes up / down along the controller.
  [Frogun] AimWithController, AimUpDown       (VR menu -> "Frogun")
The red line from the frogun (the game's tongue line left drawn at rest) is hidden while the tongue is in
([Frogun] HideRedLine); the game's red crosshair stays. HOLD L3 = the mod's green aim laser on / off.
Right trigger <-> right grip: [Controls] SwapTriggerAndRightGrip = true (VR menu "Swap right trigger and right grip").

Arms
----
First person: Renata's hands follow your controllers (two-bone arm IK); the frogun is in her hand.
[Arms] HandsFollowControllers, InThirdPerson. Each hand can be moved / turned in the VR menu ("Hands").

Controls (the VR controllers are an Xbox pad)
--------
  A + B together ............... Start
  
  X + Y together ............... Back
  
  Tap both stick clicks ........ re-centre the view
  
  Hold both stick clicks 1.2 s . VR settings menu (right stick = choose / change, A = select, B = close)




Disable: to disable Mod rename winhttp.dll to winhttp.dll.bak

[VR Mod Manager](https://github.com/King-EJ/VR-Mod-Manager/releases/tag/VRModManager)

LICENSES
-
Uses Astien's OpenXR bridge. Free, non-commercial.
