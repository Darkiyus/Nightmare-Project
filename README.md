# Nightmare-Project
Nightmare was supposed to be an all-in-one client for VRChat, which was discontinued because it was no longer useful.
(Financially too low and I stopped playing VRC myself).

# Special Features

**ShadowGuard**
- Anti Password Theft
- ShadowGuard Account data encryption
- Programming code obfuscation, thanks to the leader in code obfuscation.

**Nightguard**
- VrChat's first anti-crash AI

**Avatar Favorites saved in a Database**
If you reinstall the client, your favorites list would remain :)

**The first client with launcher!
features:**
- Change your VRChat account if you were banned!
- Bot control in launcher
- ShadowGuard
- News and server status
- One Click to play without Mods
and much more

# All Features
- NightGuard - Anti Crash AI
- Single Target Crash / Avatar Crash ( Predefined Avatar Button Settings included, but also custom adjustable)
- Lobbycrash 
- Language Changer (EN & Ger)
- ESP
- Speed, Fly, Teleportation, NoClip
- See Block
- Force Clone
- VRCA and VRCW download
- Portal Freeze
- Avatar Hider Distance
- Cache Cleaner
- Headlight
- Avatar Search (ID, Author and Name)
- Avatar Favorites stored in a database
- microphone sensitivity better adjust
- fast login button
- Music & Crasherbots
- Playerlist
- Nightmare-Launcher
- Nightmare-App for Android
and much more...

Extra!
- A Nightmare email address with Web Portal
- Password manager powered by passbolt
- 20% discount code for one of your friends
- Preferred support

# Database
based on MariaDB
Database ERM - A serial key system has been added subsequently
<img src="/Nightmare/DatabaseERM.png" alt="ERM">


    CREATE TABLE Nightmare_User_Login (
        ID int,
        Username varchar(32),
        Password varchar(100)

    );

    CREATE TABLE Nightmare_User_Data (
      Nightmare_User_Login_ID int,
      E_Mail varchar(64),
      Created date,
      Rank int,
      Buyed boolean,
      LastPayment date,
      LastPaymentOptions int

    );

    CREATE TABLE Nightmare_User_Avatar_Favorits (
      Nightmare_User_Login_ID int,
      Avatar_ID varchar(41)
    );

    CREATE TABLE VRChat_Accounts (
      Nightmare_User_Login_ID int,
      VRC_ID varchar(40)
    );


# Avatar Cloud PAP
<img src="/Nightmare/Avatar_Cloud.png" alt="PAP">
Yeah its  German  xD

# Installer
<img src="/Nightmare/InstallerCode.png" alt="Installer Code">
<img src="/Nightmare/InstallerShow.png" alt="Installer Show">

# Launcher
**This is how the launcher should look like originally**
<img src="/Nightmare/LauncherPrototyp.png" alt="Launcher Proto">

**This is what he looked like in the end ;)**
<img src="/Nightmare/Screenshot 2022-06-11 015130.png" alt="Launcher Finally">
<img src="/Nightmare/Screenshot 2022-06-11 015147.png" alt="Launcher Finally">
<img src="/Nightmare/Screenshot 2022-06-11 015200.png" alt="Launcher Finally">
<img src="/Nightmare/Screenshot 2022-06-11 015221.png" alt="Launcher Finally">
<img src="/Nightmare/Screenshot 2022-06-11 015110.png" alt="Launcher Finally">


A slightly older version than the one before, but with Vr or Desktop Choice.
<img src="/Nightmare/LauncherPlay.gif" alt="Launcher Finally">

Video: https://streamable.com/6s6xsj

# Ingame Menu October
<img src="/Nightmare/FirstMenuOctober.png" alt="IG Menu">
<img src="/Nightmare/NightmareIGMenuOctober.png" alt="IG Menu">





