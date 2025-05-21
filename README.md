# Cyan Hexagon Plymouth Theme
  
Improved version of 'Hexagon Dots Alt' from [adi1090x/plymouth-themes](https://github.com/adi1090x/plymouth-themes)
  
Changes:
- Looping animation
- Improved positioning

You'll need to install `plymouth-plugin-script` for the theme to work:
```
dnf install plymouth-plugin-script
plymouth-set-default-theme -R cyan
```
Disable [simpledrm](https://fedoraproject.org/wiki/Changes/PlymouthUseSimpledrm#Release_Notes) if you encounter performance issues by passing the following kernel parameter:
```
plymouth.use-simpledrm=0
```
