# Arsenal 2 WinSock+DirectPlay Fix

DirectPlay is deprecated in Windows 10.

To install, you must go into Windows features and install it, but, is incomplete because WinSocks is also deprecated. In order to WinSock+DirectPlay multiplayer games to work you must install the missing DLLs.

We have created a very simple installer that automatically puts everything in its place and reboots the computer (if you want to).

This will enable TCP/IP, IPX and Serial/Modem DirectPlay.

Check the releases page to download.

# Ultraeasy Install

1. Go to releases, download the release.
2. Install (UAC: YES, Next..., Finish).
3. Have fun.

# Manual Install? Sure.

1. Download the source.
2. Extract the file.
3. Copy the two dll files to %WINDIR%\System32 and %WINDIR%\SysWoW64 (this last one only in 64-bit Windows).
4. Restart (may be this is not required, but recommended).
5. Have fun.

# License

Released with the MIT license, you can do whatever you want with the source, we don't mind.
