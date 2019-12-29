# Seti UI Icons for Sublime Text

These icons have been lifted from the [Seti_ST3](https://github.com/ctf0/Seti_ST3) Sublime Text port of [jesseweed's](https://github.com/jesseweed/seti-ui) Github Atom theme. You can use it with any other Sublime theme you like, but only if they're dark - [Soda Dark](https://github.com/buymeasoda/soda-theme/) works especially well.

The screenshots below show

![Seti screenshot](screenshot-1.jpg)
![Soda Dark 3 screenshot](screenshot-3.png)


## Install

### Via Package Control

Not Yet. Probably not ever :(

### Manual

1. [Download the .zip](https://github.com/mrmartineau/SetiUI-Icons-Sublime/archive/master.zip).

2. Unzip and Copy the folder into `Packages/User` directory
   - you can find the fullpatht o `Packages/User` directory by using the menu item `Preferences -> Browse Packages...` in Sublime Text.
   
3. Rename the unzipped folder to the exact name of your current theme's parent folder
    - If your theme is "Adaptive.sublime-theme", then new name of the unzipped folder is `Adaptive`
    - You can find the name of your current theme by using the menu item `Perferences -> Settings`. 
      - the above will open 2 panels; 
        - one for `Perferences.sublime-settings - Default`
        - the other for `Perferences.sublime-settings - User`
      - If you are using a custom theme, then your current theme is set in `Perferences.sublime-settings - User`. Look for the line: "theme": "theme_name" 
      - if you are not using a custom theme, then you current theme is is set in `Perferences.sublime-settings - Default`. Look for the line: "theme": "theme_name" 
      
4. Create a new file inside the renamed directory. The name of the new file should match the name of your theme. 
    - for example,if your theme is "Adaptive.sublime-theme", then the new file is named "Adaptive.sublime-theme".
    
    
5. Restart Sublime :)

### Credits
- Seti UI port by [ctf0](https://github.com/ctf0/Seti_ST3)
- Theme is originally by [jesseweed](https://github.com/jesseweed/seti-ui) for Github's Atom editor.

# Notes
- There is a folder included with some files types from `jesseweed` and `DanBrooker` to test the icons.
- Anything less than 'ST3 Build 3062' wont get the sidebar icons to work.

### Differences from the original

- No file icon in the opened tabs, ST lacks this.
- Not as icon rich as the original because ST can't see anything other than Extensions ,and even though its still hard to use the icon you want.

