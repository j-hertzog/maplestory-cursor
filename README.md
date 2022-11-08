# maplestory-cursor
a custom maplestory theme for linux cursors. (x11 cursor format)
![clicking](https://user-images.githubusercontent.com/9396028/200469153-c92b3ffb-137b-4fe6-bc61-dfeb4ccb81b2.gif)
![progress](https://user-images.githubusercontent.com/9396028/200469155-08d04367-d4b3-4c73-b8be-0e5d8972b10a.gif)
![wait](https://user-images.githubusercontent.com/9396028/200469158-be1ad033-4a7c-4a96-9484-43a4e3702a54.gif)

I made this by downloading whatever maple cursor packs for windows I could find and then I converted them with [wind2xcur](https://pypi.org/project/win2xcur/) and finally manually copied them to their corresponding x11 file name. If I've missed any please open a PR!

Enjoy!


# install
gnome users: drag and drop the Maplestory/ directory to /usr/share/icons/ and it should appear as a selectable cursor theme in gnome tweaks

> note: Firefox always uses the default system cursor themes. To fix this append the line`gtk-cursor-theme-name=Maplestory` to the `~/.config/gtk-3.0/settings.ini` file.

