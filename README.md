EmuChe (Emulator cheat-Engine Table converter)

- An Application that converts .ct files of Cheat-Engine used for emulators, it can convert of one emulator to another of the same type, for example playstation emulators from ePSXe 2.0.5 to Duckstation, NDS emulators Desmume to melonDS.

- Some emulators use same addresses for emulating, you can use static mode converting, but in case the converted address is not accurate, use relative mode.

- Relative mode (actual address in console memeory) is useful when working with debuggers.

- It written by:
C++ programming languague
TGUI Graphics Library https://tgui.eu/
tinyxml2 xml parser  https://github.com/leethomason/tinyxml2

- I will be glad to email me for bug report feature request.
- Upcoming features
	- Raw code conversion
	- Fix some GUI issues
	- Support any Emulator under request (I'll be glad to add your favourite Emulator)
	- Address / offset adjustment

Change log:
- v1.0
* converting Cheat-Engine table file for following psx emulators & viceversa:
	- ePSXe 2.0.5, 2.0.2, 2.0.0, 1.9.23, 1.9.0, 1.8.0, 1.7.0
	- Mednafen-1.21.3
	- DuckStation 0.1-4743-g8864b48c
	- NO$PSX debug and tiny versions
	- psxfin 1.13
	- pcsxr-pgxp (reloaded)
	- Pcsx 1.5 with debugger Ver2 and Ver1
* converting Cheat-Engine table file for following NDS emulators & viceversa:
	- DeSmuME_0.9.11_x64
	- melonDS 0.9.3
* Recursive addresses conversion
* Support Address conversion with "Module_name"+12345
