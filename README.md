<img width="2559" height="1440" alt="image" src="https://github.com/user-attachments/assets/8ca048dd-1309-4c29-805e-ef63bec37d26" />

# transparency-fox
Transparent firefox userchrome for people who want transparency and blur.

Designed under linux running hyprland using waterfox, mileage may vary for other setups.

Works best under dark theme.

# config
In `about:config` the following need to be changed


`userChrome.tab.bottom_rounded_corner` => false


`toolkit.legacyUserProfileCustomizations.stylesheets` => true

`browser.tabs.allow_transparent_browser` => true

## optionally
`userChrome.tab.dynamic_separator` => false

# Install
Copy paste the contents of the repository into your firefox profile/chrome folder

Menu > Help > More Troubleshooting Information, then under Profile Directory click open directory.

Make a new folder called `chrome`, and copy the contents in.

Restart your browser after installing and changing `about:config` items.

# Recommendations
Use this theme with hyprland or another compositor that has blurring support. Be sure to turn blur on.
