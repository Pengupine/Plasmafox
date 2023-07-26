# Plasmafox
A fast blazing browser, who is minimal and designed for use on pretty much old computers.

:older_man: + :computer: + Browser = Plasmafox!

It is coded in Python to keep a slight cross-platform, binaries supported yet are only M1 Mac, you can effectively compile from source using Nuitka or Pyinstaller.

Requirement for compilation: Nuitka, Python, PyQt5

|  Browsers  | Memory Usage | CPU Usage |
| ---------- | ------------ | --------- |
|  Firefox   | 1,12 Go      | 0,3%      |
|  Plasmafox | 170,7 Mo     | 6,6%      | 
|  Chrome    | 100,8 Mo     | 8,1%      |
# Installation
If under Mac M1: simply put the binary in Applications.

If under Mac (Requirement: Nuitka):
Please use these commands in Terminal to compile and get the browser binary:
nuitka3 --standalone --include-data-dir=Icons=Icons Plasmafox.py
sudo mv Plasmafox.bin /Library/Applications/Plasmafox

If under Linux (Requirement: Nuitka):
Please use these commands in Terminal to compile and get the browser binary:
nuitka3 --standalone --include-data-dir=Icons=Icons Plasmafox.py
sudo mv Plasmafox.bin /Library/Applications/Plasmafox
