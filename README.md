# Breeze+
Breeze+ is an icon theme which adds more icons to KDE's Breeze icon theme.
We hope lots of those icons will find themselves in the main Breeze icon theme.

# Requriments
For this icon theme to work you need to have Breeze icon theme installed.
You can install it like this:
- Debian & Ubuntu:
  `sudo apt install breeze-icon-theme`
- Fedora:
  `sudo dnf install breeze-icon-theme`
- Arch:
  `sudo pacman -Syu breeze-icons`
All of following commands will work on forks of those distros if 1) they use the main distro repos 2) they have the package on their repo under the same name.

# Installing
- System-wide:
  1. `git clone` Breeze+ or download it by 1) downloading the source or 2) downloading it from releases.
  2. Extract files from the source package or release package if you didn't `git clone` it.
  3. Make sure files are in a directory called Breeze+ and that on root of Breeze+ directory there is theme.index and folders with icons (example: apps and under apps 48)
  4. Copy Breeze+ directory to `/usr/share/icons`. You can use `sudo cp /path/to/Breeze+ /usr/share/icons`
- Local Install (for each user)
-   1. `git clone` Breeze+ or download it by 1) downloading the source or 2) downloading it from releases.
  2. Extract files from the source package or release package if you didn't `git clone` it.
  3. Make sure files are in a directory called Breeze+ and that on root of Breeze+ directory there is theme.index and folders with icons (example: apps and under apps 48)
  4. Copy Breeze+ directory to `/home/username/.local/icons`. You can use `sudo cp /path/to/Breeze+ /home/username/.local/icons` or you can use your file manager.

# Applying
If you use KDE Plasma, open System Settings, then go to Colors & Themes, then Icons. Now, select Breeze+ and hit Apply.
