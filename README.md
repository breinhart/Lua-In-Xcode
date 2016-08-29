# Lua Support for Xcode 4+ #
1. download the two files (Add-Lua.sh, Lua.xclangspec)
2. Open Add-Lua.sh and change the DVTFOUNDATION_PATH if necessary.  You probably do not need to change this if you are on Xcode 4.3+.
3. Make sure Xcode is closed
4. Run Add-Lua.sh from the terminal with sudo (I.E. `sudo Add-Lua.sh`)
5. Enter your admin password and hit enter
6. Open Xcode and notice the 'Lua' entry under "Editor->Syntax Coloring"

# Lua Support for Xcode Betas #
If you are running a beta version of Xcode, you need to pass the `--beta` flag.
For example:
```
sudo ./Add-Lua.sh --beta
```

Special thanks to [araxara](https://github.com/araxara) for the Objective-J version of this code.
