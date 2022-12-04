# awesome-libsm64
A collection of things made with libsm64.

## *Super Mario 64* Decompilation Project

https://github.com/n64decomp/sm64/

> A Super Mario 64 decompilation, brought to you by a bunch of clever folks.
> This repo contains a full decompilation of Super Mario 64 (J), (U), (E), and (SH).

## libsm64

https://github.com/libsm64/libsm64

> The purpose of this project is to provide a clean interface to the movement and rendering
> code which was reversed from SM64 by the SM64 decompilation project,
> so that Mario can be dropped in to existing game engines or other systems with minimal effort.
> This project produces a shared library file containing mostly code from the decompilation project,
> and loads an official SM64 ROM at runtime to get Mario's texture and animation data, so any project
> which makes use of this library must ask the user to provide a ROM for asset extraction.

* [Created by jaburns](https://jaburns.net/)
* [Fork which adds audio support](https://github.com/ckosmic/libsm64/tree/audio)
* [Fork for libsm64-sharp which exposes raycasting/collision logic](https://github.com/MeltyPlayer/libsm64-ext)
* [Fork for Retro64](https://github.com/Retro64Mod/libsm64-retro64)
* [Fork for G64](https://github.com/ckosmic/libsm64/tree/gmod)
* [Fork which fixes a crash in ckosmic's libsm64 audio fork under Linux](https://github.com/headshot2017/libsm64-linux-audio-fix)

## Bindings and Integrations

### Rust

https://github.com/nickmass/libsm64-rust

> This is a thin layer of rust bindings over the very excellent libsm64 project.

* [Documentation](https://nickmass.com/doc/libsm64/index.html)

### C#

https://github.com/MeltyPlayer/libsm64-sharp

> C# bindings for libsm64.
> 
> This library provides both:
> - A high-level C# object-oriented layer for safely calling the libsm64 methods.
> - A low-level interop layer for calling libsm64-ext's methods directly.

* [libsm64 fork](https://github.com/MeltyPlayer/libsm64-ext)
* Various tweets documenting development of the library
	* https://twitter.com/MeltyPlayer/status/1580808333963165698
	* https://twitter.com/MeltyPlayer/status/1582194769047916544
	* https://twitter.com/MeltyPlayer/status/1582539124053282816
	* https://twitter.com/MeltyPlayer/status/1582606006080917505
	* https://twitter.com/MeltyPlayer/status/1585529635038715905
	* https://twitter.com/MeltyPlayer/status/1585905294999453696
	* https://twitter.com/MeltyPlayer/status/1588362552668323840
	* https://twitter.com/MeltyPlayer/status/1590606020937920514

### Blender

https://github.com/libsm64/libsm64-blender

> This add-on integrates libsm64 into Blender and provides various additional integrations with [Fast64](https://bitbucket.org/kurethedead/fast64/).
> Practically, this means if you're making levels with Fast64 in Blender, you can use this add-on to drop a controller-playable Mario into your scene to run around and test your terrain layout.

![Mario jumping around in an example map](https://github.com/libsm64/libsm64-blender/raw/master/docs/example.gif)

* Various tweets demonstrating usage of the plugin
	* https://twitter.com/SM9O8O/status/1598092263313543174
	* https://twitter.com/KabajSAH/status/1585559221168480257
	* https://twitter.com/MJacobBarker/status/1512917058677211136
	* https://twitter.com/TerraDev64/status/1512404156174249986
	* https://twitter.com/WeLike_ToScrew/status/1511035274826076161
	* https://twitter.com/Theanine3D/status/1505650212152381441
	* https://twitter.com/raggysag/status/1504514985438826496
* [Bryan Lunduke talking about it](https://lunduke.substack.com/p/blender-libsm64-play-mario64-inside)

### Unity Engine

https://github.com/libsm64/libsm64-unity

> Unity engine demo client of libsm64. This repo provides a Unity package which can be imported
> from the package manager.

* [Empty Unity project for developing/testing the libsm64-unity package](https://github.com/libsm64/libsm64-unity-dev)
* [Tweet demonstrating using the package with multiplayer networking](https://twitter.com/roystanhonks/status/1569147883156566016)
* [April Fool's joke created with the package](https://twitter.com/i/status/1509881149530808329)

### Godot Engine

https://github.com/Brawmario/libsm64-godot

> Addon that binds the libsm64 to Godot via GDExtention, allowing to integrate Mario into any Godot 4 project.

![Mario standing in a a Godot project](https://camo.githubusercontent.com/14c3e1a60b43baa038aff0a347408aeb3824ba3b1f18a7bb7ddfcd6dc8e61d20/68747470733a2f2f692e696d6775722e636f6d2f6c38714f6e61642e706e67)

* Various tweets documenting development of the add-on
	* https://twitter.com/Brawmario/status/1514794557266747393
	* https://twitter.com/Brawmario/status/1574592349438902272
	* https://twitter.com/Brawmario/status/1575294891143446533
	* https://twitter.com/Brawmario/status/1576691591846449155
	* https://twitter.com/Brawmario/status/1577479359308374017
	* https://twitter.com/Brawmario/status/1578462496381276160
	* https://twitter.com/Brawmario/status/1579607964834738176
	* https://twitter.com/Brawmario/status/1588575473713311745
	* https://twitter.com/Brawmario/status/1512420782630133761
* [libsm64-godot-3D-Kinematic-Character-Demo](https://github.com/Brawmario/libsm64-godot-3D-Kinematic-Character-Demo)
	* [Tweet demonstration](https://twitter.com/Brawmario/status/1521272859338944519)

# Unreal Engine 5

https://github.com/LunaRyuko/SMUE5

>  A port of libsm64 to UE5

## Mods

### *Sonic Generations* (SM64 Generations) by [Skyth](https://twitter.com/bsthlc)

https://gamebanana.com/mods/368411

> This is a mod that allows you to play as the mustache man with the red cap from the 1996 video game
> with the exact same controls and moveset.

* [Gameplay video of Green Hill](https://www.youtube.com/watch?v=NXpOCfg8O64)
* Various tweets documenting development of the mod
	* https://twitter.com/bsthlc/status/1510019517455421443
	* https://twitter.com/bsthlc/status/1513232941849235457

### *Minecraft* (Retro64) by [Dylan](https://twitter.com/pdxdylan)

https://retro64mod.github.io/

> This mod lets you play your favorite 1996 platformer game in a modern Minecraft world.

* [Demonstration and explanation video](https://www.youtube.com/watch?v=2yWKqc2rmHI)
* [Mod source code](https://github.com/Retro64Mod/Retro64Mod)
* [libsm64 fork](https://github.com/Retro64Mod/libsm64-retro64)
* Various tweets documenting development of the mod
	* https://twitter.com/pdxdylan/status/1437538144728064002
	* https://twitter.com/pdxdylan/status/1518305408938610688
	* https://twitter.com/pdxdylan/status/1516545019657732108
	* https://twitter.com/pdxdylan/status/1512557691415277568
	* https://twitter.com/pdxdylan/status/1507759898637090827
	* https://twitter.com/pdxdylan/status/1532006436703715331

### *Rocket League* (Supersonic Mario) by [Serialbocks](https://twitter.com/Serialbocks)

> Supersonic Mario puts Mario from Super Mario 64 into Rocket League.

* [Source code](https://github.com/Serialbocks/SupersonicMarioPlugin)
* [Mod gameplay](https://www.youtube.com/watch?v=dhWxVM86iF8)
* Various tweets documenting development of the mod
	* https://twitter.com/SerialBocks/status/1521890993162924040
	* https://twitter.com/SerialBocks/status/1559620715694985216

### *Garry's Mod* (G64) by [ckosmic](https://twitter.com/_ckosmic)

https://github.com/ckosmic/g64

> A Garry's Mod addon that uses libsm64 to put a playable Mario in the game. 

* [Demonstration video](https://www.youtube.com/watch?v=JMLDKfCohl0)
* [libsm64 fork](https://github.com/ckosmic/libsm64/tree/gmod)
* [Binary module](https://github.com/ckosmic/libsm64-gmod)
* [Installer](https://github.com/ckosmic/G64Installer)
* [Auto-updater](https://github.com/ckosmic/g64_autoupdater)

### *ClassiCube* (Classic64) by [Headshotnoby](https://www.youtube.com/@Headshotnoby/featured)

https://github.com/headshot2017/Classic64

> A plugin for ClassiCube which uses libsm64 to insert a playable Mario from Super Mario 64 into the game.

* [Release trailer](https://www.youtube.com/watch?v=rw1hbkJeqJQ)

### *OpenLara SM64* by [Headshotnoby](https://www.youtube.com/@Headshotnoby/featured)

https://github.com/headshot2017/OpenLara

![Mario standing next to Lara Croft in a cave](https://github.com/headshot2017/OpenLara/raw/master/screenshot.png)

* [Release trailer](https://www.youtube.com/watch?v=LWZam_kt46w)
* Gameplay videos
	* [*Tomb Raider 1*](https://www.youtube.com/watch?v=TUKH5vfng_k)
	* [Backwards long-jumpinng in *Tomb Raider 1*](https://www.youtube.com/watch?v=BIyfljf-qP0)
	* [*Tomb Raider 2*](https://www.youtube.com/watch?v=-fM1_9LwO-Y)

### *Mario in DDNet* by [Headshotnoby](https://www.youtube.com/@Headshotnoby/featured)

https://github.com/headshot2017/ddnet-sm64

* [Demonstration video](https://www.reddit.com/r/SM64inOtherGames/comments/xz7w5a/mario_in_teeworlds_ddnet_sort_of/)

### *Mario in GZDoom* by [Headshotnoby](https://www.youtube.com/@Headshotnoby/featured)

https://github.com/headshot2017/gzdoom-sm64

> A fork of gzdoom 3.2.0 which replaces the player with Mario from Super Mario 64 by using libsm64 Mario in GZDoom

![Mario standing at the beginning of E1M1](https://github.com/headshot2017/gzdoom-sm64/raw/master/screenshot.png)

* [Gameplay video](https://www.youtube.com/watch?v=bEhT1GleNZo)

## Applications

### Augmented Super Mario 64

https://github.com/warrenm/AugmentedMario

> This project demonstrates how to use the libsm64 project to render Mario in augmented reality using ARKit and Metal.

* [Tweet demonstrating the app](https://twitter.com/warrenm/status/1511085739966025731)

### Venus

https://github.com/Llennpie/Venus

> Venus is a "machinima" editor for Super Mario 64, built on the Unity Engine and libsm64.

![Mario standing in a scene](https://camo.githubusercontent.com/fc5039a243cc7553c2172ef861ad942abacf9f190f35eb6700148b81ccd59131/68747470733a2f2f6d656469612e646973636f72646170702e6e65742f6174746163686d656e74732f3831343633303632343932303037363239382f3936353031343739323433373931393738342f756e6b6e6f776e2e706e67)

* [Release tweet](https://twitter.com/sm64rise/status/1515460750122397706)

## Discussion

### r/SM64inOtherGames

> This subreddit is about Mario from SM64 being ported to other games through the use of mods
> thanks to libsm64 created by jaburns

https://www.reddit.com/r/SM64inOtherGames/

## Postscript

Feel free to make a PR or issue if you have something to add
here. Shoutout to [Saltydkdan](https://www.youtube.com/watch?v=5YwjSUdx0wg) for introducing me to libsm64; I still have no idea
how this illuded me for over a year and got on the front page
of Hacker News without me noticing.
