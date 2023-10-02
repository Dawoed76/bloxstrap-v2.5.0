It's only been about a week since v2.4.0 was released, and I'm already out with a new version? Well, this is mostly just an amendment to that version. Some of you may know that this was originally versioned as v2.4.1 and not v2.5.0. But then I ended up adding new features and functionality, so instead of being a patch version bump, it's now a minor version bump. Oops. Sure, it may not be as big as v2.4.0, but it still is one nonetheless.

Additions
The FastFlag editor now has a search bar, and the ability to import from JSON. (#446)
Added options for configuring antialiasing quality. (#448)
Added the option to force reinstall Roblox on next launch, located in the menu's behaviour tab.
Outdated channel check on startup has been re-added.
Bloxstrap now detects if its installation is missing, on another drive, or is not correctly registered. (#474)
Improvements
An internet connectivity check is now performed when Bloxstrap starts.
The old avatar editor background has been adjusted to suit R15 characters. (#450)
The option for DPI scaling fixing is now optional instead of forced.
Fixed the emoji mod preset not working due to ISPs blocking raw.githubusercontent.com.
Improved Roblox version checking, now with a second fallback check from a different source.
Default framerate limit is now set depending on your main monitor's refresh rate.
Installing/updating Roblox should be more reliable, with automated retries, and improved error handling.
BloxstrapRPC, formerly known as Bloxstrap Game Messaging, has undergone a complete revamp. (thanks @EpixScripts!)
Notification area context menu now has icons.
Fluent dialog style now has Mica again. The children yearn for the Mica.
Logs are now written in UTF-8 instead of Unicode.
Exceptions are now logged in English.
Read-only files should now be less of a problem.
When uninstalling, the Roblox folder in AppData is now cleaned up, if there is no existing Roblox installation.
Fixes
Fixed the custom font mod not applying properly when installing for the first time.
Fixed the install location warning showing twice when installing for the first time.
Fixed check for N editions of Windows being hardcoded to the C: drive.
Fixed Bloxstrap crashing if ipinfo.io could not be contacted when fetching a game server's location. (#445)
Fixed Vulkan/OpenGL fullscreening not working properly.
Fixed duplicate launches erroring (again).
I'd like to mention that it has nearly been a year since I released the first version of Bloxstrap, on August 4th. This project is now one year old. Since then, it's gone through some very drastic changes, and I'm glad to see something I primarily made for myself become the versatile modding and enhancement tool that it is today. I guess here's to hoping that I keep this alive forever?
