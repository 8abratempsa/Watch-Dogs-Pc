# Watch Dogs Pc
  
I love a spot of virtual tourism, me. During the pandemic, I would scratch my travelling itches with some nice big sessions on Google Earth VR, where I would retrace my steps from holidays of old or explore new places I've always wanted to go.
 
**Download ———>>> [https://0cahau-conge.blogspot.com/?gbvx=2A0TeH](https://0cahau-conge.blogspot.com/?gbvx=2A0TeH)**


 
But those little imaginary expeditions pale in comparison to being able to actually wander around fully realised virtual worlds as a tourist, which is basically exactly what I did in this week's VR Corner thanks to a brand new update for Luke Ross' REAL VR mod. By the way, REAL stands for 'Reality Enhancement Augmentation Layer' if you've ever wondered!
 
I've featured plenty of Luke's mods on VR Corner before, but my favourite ones of his are always the ones with open-worlds that feel almost like real places. Thanks to the level of detail in the Chicago map that Ubisoft built for it's open-world hack-em-up, Watch Dogs, it's easy to imagine that you're really there. There's so much variety to the environments and buildings and so many lovely little details for you to lean towards and inspect. These range from the first person interiors of the game's cars, through to some of the most delicious looking muffins I've ever seen and even Aidan Pearce's teeth!
 
Luke's R.E.A.L. VR mod for Watch Dogs can be found on his Patreon page and as always it's incredibly simple to install and get running (it has to be if I'm able to do it!). There are a few wonky cutscenes here and there and, as you'll see in my video, sometimes the light sources can be a bit bright, but in general driving around Chicago in a lovely sports car and then getting out to explore the scenery up close any personal is just so much fun!

Once you're in there, bar a few UI issues, it really does feel like the game was made for VR and honestly, it kind of makes me sad that it wasn't. Ubisoft has created so many amazing recreations of cities from the past, present and even the future over the years like, say, Assassin's Creed Syndicate's London. Many of these are now just locked away on discs, gathering dust on people's shelves after new console generations have come in to pull players away from them. What Luke Ross is doing here then is freeing those worlds and giving VR owners the opportunity to explore and enjoy them all over again (or for the first time) in brand new ways. And you can watch me doing just that in the video above!
 
I'm having recurring crash to desktop after a few seconds of gameplay on Watch Dogs 2
Audio stalls and then game crashes

I have tried with minimum graphics settings, different refresh rates, scaling, disabling overlay and fiddled with all the settings the game offers.Nothing helps.
 
I tried the suggested fix on the Ubisoft forums of DeferredFxQuality="pc". This allowed me to play 1 entire mission. The next day, boom crash to desktop within 5 minutes. Checking the file, DeferredFxQuality="pc" is still changed and the file is still read only.
 
I very literally played Watchdogs 2 on my system (GTX 1060) the night before I installed my new AMD GPU (rx6700xt), Watchdogs 2 ran just fine on the GTX card. The only change I made, and when the problems with Watchdogs 2 started is when I installed an AMD GPU. Only WD2 won't work. I tried other games and other Ubisoft titles. Every other game works just fine.
 
Before installing the AMD card, I downloaded DDU and the newest AMD driver. Booted the PC into safe mode without networking. Ran DDU to remove Nvidia drivers. Shut the computer down. Unplugged it from the internet. Switched the part, rebooted the machine and installed the drivers I downloaded. Then plugged the internet back in.
 
I have found a solution that might help others. I tried everything that others have suggested, but nothing worked. My solution was to disable Resizable Bar/Smart Access Memory in the Radeon settings. After disabling it, the game runs perfectly! The HUD no longer flickers and there is no crashing whatsoever. I am now running the game in 4k with ultra setting, fullscreen mode, and I did not have to change any settings in the game data file.
 
I'm not exactly sure why the game works when you disable it, but once I turned it off in Radeon settings the game works perfectly. My guess is WD2 was produced before Rebar/SAM was available. As a result, it's possible there is a bug on some systems the use it. As for what is does technically, basically.. If you disable it, it disables a special communication between the CPU and GPU, and theoretically gives you a slightly less of a performance boost in some games. I would prefer to have it enabled in general.
 
So far the game hasn't crashed but i am just a few minutes into it. I am gonna let it run to see if it will continue to play while i eat lunch. By default i think the game crashes often on ultra settings.
 
Press Alt+R or just open the Adrenaline Software. Go to the game settings for WatchDogs 2 and disable all the driver interference, no anti lag, image sharpening.... just disable everything. I ran into crashes on other older games when messing with these settings. The issue persisted so I dug deeper.
 
As someone already said go to (C:\Users[username]\Documents\My Games\Watch\_Dogs 2\WD2\_GamerProfile.xml) open the file in Notepad and hit ctrl+F or click the ''File tab'' and hit ''Find''. Search for DeferredFxQuality= and set it to look like this DeferredFxQuality="pc" . In my case it said ''console''. After changing this the game was more stable but still crashed, so I kept going. I also set it to borderless fullscreen at this point but I don't think that matters.
 
Go back into Adrenaline and disable Smart Memory Access, this will make the screen go dark for a moment but it should come back. Sadly you cannot set this per application but at least you don't have to restart. Older games may not support resizable bar since that didn't exist back then. If the game still crashes try the following.
 
Go into Steam, click the settings gear on the right of the game library tab for WatchDogs2>hit properties>local files>browse, this will open the folder where the game is saved. Open the bin folder and find a file called WarchDogs2.exe rightclick that one and run as administrator. This solved the problem for me. You can force this file to always run as admin by rightclicking>properties>compatibility>change settings for all users and check the box for ''Run this program as an administrator'' hit ok then ok again and now every time you start the game a system prompt will appear because you are running it as admin. This completely solved the problem for me.
 
Thanks for putting all findings into a clear list! Unfortunately, the game still crashes on me. At random, just back to desktop. Sometimes the Ubisoft launcher picks it up and wants to send a report (which does not go through anyway), sometimes nothing. Takes all the fun out of it really
 
comparing stability with some nvidia user makes no sense , as lot of other rx6000 owner don't have any stability issue, so it's not because it's working with some nvidia user , that it won't work with all rx6000
 
that being said ... i would install latest driver if i where you .. don't know why so much people trying old drivers, this seems misleading to me and can only correct some specific application problems , but i don't think it can help with games in general , as is most case problem coming from elsewhere ... do you have a message with crash to desktop or nothing at all , just back on desktop ?
 
in another thread about this specific game, i checked on ubisoft forum where a support guy from ubisoft advised to play in "borderless mode" seem to be bettering the thing... but apparently not for everyone , then :
 
The game is too old to get more patches from ubi. I actually did get a "notification" once saying that easy-anti-cheat found a .dll that was intrusive. But the message went so quickly I barely got to read it.
 
Oof! Just got a new PC with a Radeon 6800 XT and experienced this issue. Gut-wrenching, as WD2 is the main game I was so excited to play with new hardware. I followed the steps here, disabling SAM and playing in Fullscreen Borderless. The game plays much better but I did just experience a crash during a mission with these fixes in place, so, crashing not 100% preventable.
 
But i found some crashing going on with latest drivers. Playing in Fullscreen Borderless helped with stability. I played a long time without a crash. BUT again I am unsure if it will crash again. I finished a couple missions.
 
I have a 6600 non xt and has played this game before on my 480 and had a lot of fun even though I had like 40 fps on lowest settings. But now I am trying to play this game again on my new system which is:
 
I have tried all the fixes I've seen through this whole post and as of typing this I am able to play the game for up to 45 mins straight at times and other times it crashes quicker but it is better than it used to be with it crashing every two mins. I might just replay the first watch dogs and hope amd or ubisoft fix these issue soon.
 
Yeah I have SAM, ant-lag and all driver overrides off and I've followed all instructions I have seen on here for increased stability and after opening the game three times over and over it still only lasts 10 seconds before closing itself.
 
Hey there.... I have done ALL of these recommendations, even uninstalled and reinstalled the game twice. still having issues. I have the RX 7900 XT GPU and game wont startup anymore, even a new game. Crashes right at the last second of the loading screen, and then im unable to send a bug report to Ubisoft. VERY frustrating.
 
One day you will purchase a multi-pack bag of assorted crisps. Maybe because you're going to a party, maybe because you're living on a budget. You won't be overly fond of any of the contained flavours, every bite will feel a little on the soft side of fresh, and the individual packets will be 90% air, but you'll at least feel comforted by having choice and abundance.
 a2f82b0cb4
 
