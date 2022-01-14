# userChrome.css
A clean, minimal, and professional Firefox userChrome.css for macOS

Traditionally, Firefox has allowed users to customize the user interface of
the browser itself by using CSS.  By placing a `userChrome.css` file inside
the `chrome` directory of your Firefox profile, you could change how the
browser looks and behaves.  Newer versions of Firefox (since 2019) disable
the use of userChrome.css by default.  Ironically, these newer versions have
poor user interfaces, and are most in need of customization to override bad
design.

To install:

1.  Go to `about:config` in a Firefox window.
2.  Search for the setting 
`toolkit.legacyUserProfileCustomizations.stylesheets` and set it to `true`.
3.  Go to `about:profiles`.
4.  Find the Root Directory for your profile and open it (e.g., on macOS, 
click `Show in Finder`).
5.  Open your profile directory and create a folder called `chrome` if one 
does not already exist.
6.  Place your `userChrome.css` file inside that folder.
7.  Restart Firefox. 

Features
- Disables the cartoonish animated location bar
- Makes menus more compact and navigable, with fewer icons
- Adjusts the placement and size of the mute icon for tabs with sound
- Restores traditional tab design and makes it easier to distinguish between
your active tab and inactive tabs, as well as easier to distinguish _between_
inactive tabs

