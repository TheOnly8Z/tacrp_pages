---
layout: post
title: Update 2
author: 8Z
category: TacRP
tags: [Update]
---

WIP Second update.

If you encounter any issues, you can always report them in the [GitHub issues page](https://github.com/HaodongMo/tacrp/issues) or the [Diamond Doves Discord](https://discord.gg/gaHXusZ).

## Highlights

### Toggle Aiming
Give your index finger a rest - you can now toggle aiming instead of having to hold it down.

![toggleaim]({{ '/assets/images/toggleaim.png' | relative_url }})

### Out of Ammo, But Not Out Of Options
Getting caught with your pants down is not very tactical. Now, you can break out of a reload instantly by melee bashing or quickthrowing.

<video muted src="{{ '/assets/videos/reloadcancel.mp4' | relative_url }}" controls="controls" style="max-width: 100%;"></video>

Shotguns are also more responsive to reload cancelling now. You can interrupt the reload at any point, and if you interrupted it before a round was loaded, the finish animation doesn't play and you can start firing faster.

<video muted src="{{ '/assets/videos/reloadcancel2.mp4' | relative_url }}" controls="controls" style="max-width: 100%;"></video>

### Most Tactical
A few touches to the tactical attachments. The Radar's beeping is made quieter when nothing is around. You can disable it for yourself if you still find it too grating - but this doesn't affect other players hearing your radar (and you hearing theirs)!

Also, you can now tell if the target is above or below you, as they will show up as a pointed triangle.

![radar_triangle]({{ '/assets/images/radar_triangle.png' | relative_url }})

The Rangefinder and Spread Gauge use the point of aim after sway. Rangefinder also has a cross indicating range now (it fades out at minimum damage), which is usable even with Physical Bullets off.

![rangefinder]({{ '/assets/images/rangefinder.jpg' | relative_url }})

## Update Notes

- **Added:** Clientside Toggle Aim ConVar, disabled by default.
- **Added:** Clientside ConVar to disable radar sounds on the user.
- **Added:** Radar triangle icons for targets above/below the user (threshold of 128HU).
- **Added:** Rangefinder cross to indicate damage falloff and center of aim.
- **Changed:** Rangefinder and Spread Gauge draws helpers from point of aim after sway.
- **Changed:** Shotgun reloading can be interrupted immediately. If no round was loaded, the gun readies quicker.
- **Changed:** Radar beeps (for yourself) is quieter, but gets louder with more targets.
- **Changed:** Melee and Quickthrow can interrupt reloads.
- **Changed:** Melee will cancel aiming briefly and exit blindfire.
- **Fixed:** Holding USE during a runaway burst causing non-stop melee instead of shooting.
- **Fixed:** Shotguns reloading cannot load with 0 ammo, even if infinite ammo is on.
- **Rebalance:** Melee Damage increased from 20 to 25; delay between swings increased from 0.6s to 0.7s.
- **Rebalance:** Melee Damage w/ Smackdown increased to 40 from 35.
- **Rebalance:** Non-Arcade melee slowdown reduced from 50% to 15%, duration from 1.5s to 1s.