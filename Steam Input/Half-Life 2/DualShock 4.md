
# Table of Contents

1.  [Introduction](#introduction)
2.  [Resource summary](#resources)
3.  [Installation, summarized](#installation)
4.  [Installation, detailed](#installation_detailed)
5.  [Removal](#uninstall)
6.  [Controls](#controls)
    1.  [Basics](#basic_controls)
    2.  [Weapons](#weapons)
    3.  [Utility](#utility)
7.  [Feature List](#features)
8.  [Bugs/Problems](#bugs)
9.  [Possible Improvements](#improvements)



<a id="introduction"></a>

# Introduction

This page will help you set up and use a modern control scheme for
Half-Life 2 with a DualShock 4 controller, via Steam Input.

The Installation section will show you how to set everything up.
The Controls section will teach you how to use this control scheme.


<a id="resources"></a>

# Resource summary

-   Custom cfg file: [`gyro_revolution.cfg`](gyro_revolution.cfg)
-   Icon pack: [`HL2_TouchMenuIcons.zip`](HL2_TouchMenuIcons.zip)
-   Controller Configuration
    -   v1.0-beta URL: [`steam://controllerconfig/220/2073106958`](steam://controllerconfig/220/2073106958)
    -   VDF file for manual import: [`gyro_revolution_hl2_v1.0-beta.vdf`](gyro_revolution_hl2_v1.0-beta.vdf)
-   Changelog: **TODO**


<a id="installation"></a>

# Installation, summarized

1.  Extract icon pack into game's directory (`Half-Life 2`)
2.  Put `gyro_revolution.cfg` under the `hl2/cfg/` directory
3.  Add line with "`exec gyro_revolution`" to your `autoexec.cfg` file in the same directory (`hl2/cfg`). Create if necessary.
4.  Connect DS4 controller
5.  Enable PlayStation Configuration Support in Big Picture, if not already enabled
6.  Import my configuration


<a id="installation_detailed"></a>

# Installation, detailed

1.  Install icon pack and custom configuration file
    1.  Open the game's directory
        -   Right click game in Steam library > Manage > Browse local files  
            ![img](manage_browselocalfiles.png)
    2.  Extract the [Icon Pack zip](HL2_TouchMenuIcons.zip) there. You should now have a `TouchMenuIcons` directory.
    3.  Enter the hl2/cfg/ directory and place the [`gyro_revolution.cfg`](gyro_revolution.cfg) file there.
    4.  (optional) make a backup of your `config.cfg` file should you want to restore it later.
    5.  Add `exec gyro_revolution` to your `autoexec.cfg` file
        -   If you don't have an `autoexec.cfg` file, use this one: **TODO**
2.  Connect your DualShock 4 to your computer. Either:
    -   Wired using a micro USB cable
    -   Wireless using Bluetooth
        -   With the DualShock 4 turned off, hold SHARE and the PS
            button to enter Bluetooth pairing mode, then pair it with the
            computer.
3.  Enable DualShock 4 configuration support in Steam's Big Picture mode
    1.  Start Big Picture by clicking the button to the left of the "minimize" button in Steam  
        ![img](bpm_button.png)
    2.  Go to Setting > Controller Settings  
        ![img](bpm_settingicon.png) ![img](bpm_controllersettings.png)
    3.  Check "PlayStation Configuration Support" box  
        ![img](bpm_playstationsupport.png)
    4.  Select your controller under "Detected Controllers" and then click **Calibrate**  
        ![img](bpm_controllerselected.png)  
        ![img](bpm_calibratebutton.png)
    5.  Tune your joystick deadzones if necessary  
        ![img](bpm_joystickdeadzone.png)
    6.  Place the controller on a **stable, level surface** and click "Start Gyro-Only Calibration."  
        ![img](bpm_startgyrocalibration.png)
    7.  Make sure the controller stays completely still until the calibration is done (about 5 seconds).
4.  Import my configuration
    1.  [Click here](steam://controllerconfig/220/2073106958) to open the configuration in Steam. It should open this screen:  
        ![img](bpm_configpreview.png)
    2.  Press Square to apply, then Circle to exit
5.  Play the game!


<a id="uninstall"></a>

# Removal

1.  Remove the `exec gyro_revolution` line from your `autoexec.cfg` file
2.  Delete `config.cfg` and possibly restore a backup of it.


<a id="controls"></a>

# Controls


<a id="basic_controls"></a>

## Basics

Use the **right stick** and the **gyroscope** to **move the camera.**

It's recommended to rely on the gyro to aim precisely and to use
the right stick for broader motions only, such as turning,
recentering and coarse target acquisition.

The gyro is always-on by default, but you can temporarily toggle it
off by clicking the right stick (**R3**). This is recommended when driving.

Hold **L2** to aim more precisely. Gyro is always enabled when doing this.

If the camera moves on its own, you need to recalibrate the
gyroscope as explained in the detailed installation instructions.

Use the **left stick** to **move**.  
Click **L3** (left stick click) while moving to **sprint.** You will
stop sprinting when you return the stick to its neutral position.

**Tap X** to **jump.**  
**Press Circle** to **use.**  
**Tap Triangle** to **toggle crouch.**

**Hold X** to **crouch while jumping**, which may help extend your
reach, land tricky jumps or vault over obstacles.  
Note: the game itself automatically crouch jumps in some
situations, usually next to boxes/windows/vents/etc. This is only
useful for more advanced moves.

**Press OPTIONS** to **pause.**

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">
<caption class="t-above"><span class="table-number">Table 1:</span> Summary</caption>

<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Action</th>
<th scope="col" class="org-left">Control</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">Move</td>
<td class="org-left">LS - Left Stick</td>
</tr>


<tr>
<td class="org-left">Move Camera</td>
<td class="org-left">Gyro - Controller Motion</td>
</tr>


<tr>
<td class="org-left">Move Camera (coarse)</td>
<td class="org-left">RS - Right Stick</td>
</tr>


<tr>
<td class="org-left">Sprint</td>
<td class="org-left">L3 - Left Stick Click</td>
</tr>


<tr>
<td class="org-left">Jump</td>
<td class="org-left">X</td>
</tr>


<tr>
<td class="org-left">Crouch-jump</td>
<td class="org-left">X (hold)</td>
</tr>


<tr>
<td class="org-left">Toggle Crouch</td>
<td class="org-left">Triangle</td>
</tr>


<tr>
<td class="org-left">Pause</td>
<td class="org-left">OPTIONS</td>
</tr>
</tbody>
</table>


<a id="weapons"></a>

## Weapons

**Pull R2** for primary fire and **press R1** for secondary fire.
**Press Square** to **reload**

**Tap L1** to swap to your previously selected weapon.  
**Hold L1** to bring up the **Weapon Select Wheel** and select a weapon
**with the \*right stick**.

The **Weapon Select Wheel** is restricted to projectile weapons.

**Other Weapons** are placed differently:

-   **Crowbar** on **D-Pad UP**
-   **Grenades** on **Hold D-Pad UP**
-   **Gravity Gun** on **D-Pad DOWD**
-   **Pheropods** on **Hold D-Pad DOWN**
-   **RPG** on the **right edge of the touchpad**
-   **Squad Commands** on the **left edge of the touchpad**

You can also browse and select from available weapons the
traditional way with **D-Pad LEFT/RIGHT** and **R2** to confirm.

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">
<caption class="t-above"><span class="table-number">Table 2:</span> Summary</caption>

<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Action</th>
<th scope="col" class="org-left">Control</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">Fire</td>
<td class="org-left">R2</td>
</tr>


<tr>
<td class="org-left">Secondary fire</td>
<td class="org-left">R1</td>
</tr>


<tr>
<td class="org-left">Reload</td>
<td class="org-left">Square</td>
</tr>
</tbody>

<tbody>
<tr>
<td class="org-left">Weapon Wheel</td>
<td class="org-left">Hold L1 + RS</td>
</tr>


<tr>
<td class="org-left">Last Weapon</td>
<td class="org-left">Tap L1</td>
</tr>


<tr>
<td class="org-left">Previous/Next Slot</td>
<td class="org-left">D-Pad LEFT/RIGHT</td>
</tr>
</tbody>

<tbody>
<tr>
<td class="org-left">Crowbar</td>
<td class="org-left">D-Pad UP</td>
</tr>


<tr>
<td class="org-left">Gravity Gun (swap)</td>
<td class="org-left">D-Pad DOWN</td>
</tr>


<tr>
<td class="org-left">Grenade</td>
<td class="org-left">Hold D-Pad UP</td>
</tr>


<tr>
<td class="org-left">Pheropod</td>
<td class="org-left">Hold D-Pad DOWN</td>
</tr>


<tr>
<td class="org-left">RPG</td>
<td class="org-left">Touchpad, right edge</td>
</tr>


<tr>
<td class="org-left">Squad</td>
<td class="org-left">Touchpad, left edge</td>
</tr>
</tbody>
</table>


<a id="utility"></a>

## Utility

Hold down **L2** (left trigger) to zoom in and reduce aiming
sensitivity. Use it to aim with additional precision.

**Hold Y** to **toggle the flashlight**.

**Click and hold** the corresponding touchpad icons to **Quicksave** or
**Quickload**.   
The requirement to hold is so that you don't accidentally save or
\*load your game.

**Hold R3** to temporarily disable the gyroscope, allowing you to
reposition the controller without whipping the camera around.

**Press SHARE** to toggle always-on gyro aiming.  
Gyro aiming will still be available when holding the Aim button (L2).  
**Press R3** to quickly reenable always-on gyro aiming.

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">
<caption class="t-above"><span class="table-number">Table 3:</span> Summary</caption>

<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">Action</th>
<th scope="col" class="org-left">Control</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">Aim mode (ADS)</td>
<td class="org-left">L2</td>
</tr>


<tr>
<td class="org-left">Flashlight Toggle</td>
<td class="org-left">Hold Triangle</td>
</tr>


<tr>
<td class="org-left">Quickload/save</td>
<td class="org-left">Hold touchpad icons</td>
</tr>
</tbody>

<tbody>
<tr>
<td class="org-left">Gyro Stop</td>
<td class="org-left">Hold R3</td>
</tr>


<tr>
<td class="org-left">Gyro always-on toggle</td>
<td class="org-left">SHARE</td>
</tr>


<tr>
<td class="org-left">Enable Gyro always-on</td>
<td class="org-left">Tap R3</td>
</tr>
</tbody>
</table>


<a id="features"></a>

# Feature List

-   Weapon Selection Wheel (L1 + RS)
    -   Quickly select specific projectile weapons
    -   Optional game slowdown when selecting weapon (requires enabling cheats)
    -   Toggle to last weapon by tapping weapon wheel button
-   Quick access to special weapons with D-Pad UP/DOWN
-   (pseudo) Aim Down Sights button (L2)
    -   Zooms in and lowers sensitivity for finer aiming
    -   Higher magnification requires enabling cheats
    -   Doesn't really aim down sights. Get an actual mod for that
-   Modern sprint button (L3)
    -   Click once while moving to start sprinting, return stick to center
        position to stop sprinting.
-   Direct access to Crowbar and Gravity Gun (D-Pad UP/DOWN respectively)
-   Sequential weapon select (D-Pad LEFT/RIGHT)
-   Gyroscope aim
    -   Always on by default
    -   Can be temporarily stopped by holding R3
        -   e.g. hold R3 while readjusting your pose to avoid swinging the
            camera around
    -   Gyro can be turned on/off with OPTIONS button
        -   Still when holding ADS button (L2)
        -   Can be enabled again on a moment's notice by tapping R3
-   Quickload and Quicksave with safety (hold to trigger) on trackpad
-   Menu interaction mode
    -   Triggers automatically when the mouse pointer is displayed,
        returns to game mode when the mouse is hidden
    -   Trackpad and RS can be used to move the mouse, R3 and Touchpad
        click for Left Mouse Button
-   Squad Command and Pheropods on left edge of trackpad
-   Custom Steam Input Icons for Half-Life 2's Weapons
    -   Derived from game assets
-   Lowered rumble intensity (interferes with gyro aim and default is
    generally over the top)


<a id="bugs"></a>

# Bugs/Problems

-   Achievements are disabled due to enabling cheats
-   Potential weapon/mechanic spoilers from on-screen menus and documentation
    -   Maybe remove some labels but keep icons?
-   L3 doesn't uncrouch automatically.
    -   Need to find how directly go into uncrouched state after
        a `toggle_duck`. `-duck` doesn't cut it.


<a id="improvements"></a>

# Possible Improvements

-   Enhance icon visibility in weapon wheel
-   Blur the background or something when the weapon wheel slowdown is enabled.
    -   `mat_hsv 1` makes it black and white and could be used for a
        similar effect, but feels like a bad hack
-   Add animation to zoom and slow motion.
    -   Idea: make a dynamic re-aliasing-based binding that
        increments/decrements stuff progressively upon repeated presses
        and couple it with a turbo activator. Could be brittle, though.
-   Full gyro off mode (if anyone asks for it)
-   Fine tune sensitivities and timings
-   Find way to hide spoilers until needed
    -   No way to save state after changing to/from menu mode, though&#x2026;
    -   Proper Steam Input integration or gameside weapon wheel
        implementation would be best, but it'd require a mod or an
        update from Valve
        -   Maybe Half-Life 2: Update would accept to include such a
            feature?
-   Some features require cheats => find alternatives or make those
    easily optional. An alternate no-cheat cfg file could be easy.
-   Sounds aren't distorted when setting host<sub>timescale</sub> for the
    slowdown effect. See if there's any way to do this.

