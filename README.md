# **aysOS Handbook**

#### aysOS is an OS aimed at being closed-source. My coding type is unusual, and I have figured out a lot of tricks while making this project. I'll show you some! (Read the ENTIRE handbook) Ask me anything: nova\_26876 on Discord

## **TRICKS**

##### aysOS is a custom OS made in one year. It contains a lot of features. But first, here are some tricks!

1. Ever want to make a broadcast with info but you don't want separate broadcasts? Use another variable! First, you set the variable with the data you want, and then, broadcast it! You can use as much variables as you need.
2. Do you want to store multiple values? Use lists! If you look inside aysOS, you can see that I use a lot of lists.
3. **Use TurboWarp.** This is a big one. If you won't you'll regret it!
4. **Configure the addons you want in TurboWarp.** Another big one. TurboWarp doesn't immediately have all the features you want. You have to activate each one by one. You can look at the top and download the "scratch-addons-settings.json" file for a quick start!
5. **Don't want to edit the code?** You don't need to! Just edit the costumes until they look right!
6. **DO NOT USE TEXT ENGINES!!!** From my own experience, text engines are massively terrible! It's either you have the 300 clone limit or low quality fonts.

## MANUAL (if you want to modify the code)

#### aysOS12 is a system that is deeply integrated with itself. With great power comes great responsibility! I'll list all of the sprites and what they do for a quick start!

1. **Real Smooth**
This is a sprite to speed up performance by not making Scratch load the blocks in the background.
2. **Smooth**
Used to be the old real smooth...

**TIER 1 (Boot, impact: HIGH)**

1. **Logo**
The logo.
2. **metroDots**
This is a super cool sprite because it lets you have an animation for broadcasting.
Only use it to "mimic" loading. You can use it by setting the "metroDots type" to either circle or line,
setting "metroDots" to the broadcast you want it to broadcast. Type it in exactly. If you mispell the broadcast,
it won't work :(. Then, you can broadcast "metroDots".

**TIER 2 (Kernel, impact: MEDIUM)**

1. **aysHome**
This is the lock screen. You should keep it in sync with your wallpaper,
because it has a feature to take from the cache to show the wallpaper.
It also tells you to move to TurboWarp, if you don't use it.
2. **Time UI**
This is a helper sprite for aysHome to show the current time.
3. **ProfileMain**
Don't even touch the code of this sprite
otherwise it **WILL** explode. You can modify the costumes
safely, though :).
4. **Delete**
Helper sprite of ProfileMain
5. **Add**
Helper sprite of ProfileMain
6. **AutoSave**
Just like the name says, when you're logged in,
this is the sprite responsible for saving your account\*\*.\*\*
It can save automatically, when you stop the project,
or on command using the "save" broadcast. You can
also turn it off by broadcasting "disable auto-save".
That broadcast was a **LIFESAVER**
7. **SaveCode**
It is responsible for loading and creating save codes.
You should use a list of all the possible options of your setting,
and if you can't, just PLEASE place the raw values!
**Saving:**
Add a value to "aysAccount save"
If in a list, find the "item # of that" value.
You can probably guess the rest.
**Loading:**
use the "next i" value, and then set the variable to the "val" value.
For values in a list, find the item of that number in your list,
and set the variable to the "val" variable.
For values in a variable, you can guess.
8. **BootManage**
The boot manager. Uses the "boot" variable to pick which boot option.
As of now, there's 3: setup, laptop mode, and phone mode.
9. **Setup**
It's the setup. It's responsible for letting the user
customize their aysOS.
10. **Smart Setup**
Setup and Smart Setup are different.
Smart Setup is kind of a short tutorial
to use aysOS.

**TIER 3 (Desktop, impact: LOW. ugh it took me forever)**

1. **Icon UI**
The icons. It lets you pin apps, unpin apps,
and change the taskbar position
2. **UAP**
This is what Icon UI launches: UAP is like the
desktop app infrastructure in aysOS.
3. **Push UI**
The notifications service in aysOS.
Send a notification by setting
"open app" to "push",
"push" to 1-9,
and broadcasting "push"
4. **Magic UI**
Used to be nyan cleaner, but rebranded into
a magic wand. It "swipes" away all the apps
you have open.
5. **Milena**
The AI assistant in aysOS. You really thought
it didn't have one? It's brains are located in these lists:
metroApps, USER QUESTION, AI RESPONSE, actions, your chats.
6. **Actions**
The main code of all aysOS apps.
Ask me more about it in the Discord.
7. **Talk UX**
Speak to any other person active on aysOS!
Has encoding/decoding logic, lobbies, and more.
8. **edit**
the edit button to edit icons and tiles
9. **delete**
deletes icons and tiles
10. **add**
adds icons and tiles
11. **Charm UI**
The Charms Bar: lets
you open settings, boot manager, magic UI, milena, save state, launcher, and log out.
12. **metroTiles**
The service for tiles
13. **aysLaunch**
A metro app launcher to open apps
14. **metroLaunch**
Lets you launch metro apps.
Set "metroLaunch" to any app you'd like plus "M" at the end
The M is a way for aysOS to recognize its a metro app.
15. **metroUI**
Think of this as the UAP but for metro apps.
16. **simpleFS**
A simple filesystem pretending to be a filesystem
It's really just one list.
17. **sleep**
Takes care of aysResume.
Also puts your project to sleep.
"disable sleep" broadcast.
18. **warning**
When I make thumbnails,
I activate this.
19. **aysPhone setup**
More like phone mode
description.
20. **Logo Applie**r
Apply a custom Scratch logo!
Tutorial: https://scratch.mit.edu/projects/1311303013/
Rule for this: don't do anything related to "style applier"

## CONCLUSION

aysOS is a complicated OS.
I recommend you to collaborate with me,
as this is the first release of this handbook.
Remember, the more collaboration = the more info!
And, just like I said, with great power comes great
responsibility!
---
