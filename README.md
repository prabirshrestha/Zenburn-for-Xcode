![Zenburn](https://img.skitch.com/20110923-tudq2cm22x6bmmahqhtuh6f6qq.jpg)

1. Create folder ~/Library/Developer/Xcode/UserData/FontAndColorThemes/ if it is not there.
2. Copy Zenburn.dvtcolortheme to the folder.
3. Restart Xcode.

```bash
mkdir -p ~/Library/Developer/Xcode/UserData/FontAndColorThemes/
cd ~/Library/Developer/Xcode/UserData/FontAndColorThemes/
curl https://raw.github.com/prabirshrestha/Zenburn-for-Xcode/master/Zenburn.dvtcolortheme -o Zenburn.dvtcolortheme
```