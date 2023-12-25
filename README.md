![Screenshot](/Screenshot.png?raw=true)

Unfinished - Provided as is

Place root folder containing README.md in firefox profile chrome folder,
then rename it from "firefox-theme" to "ChromiumFX"

add the following into userChrome.css in chrome folder:

@layer Dark, Light, PrivateBrowsing, GoogleChrome, Aero, final;

@import url("ChromiumFX/userChrome.css");

Set the following values to true in about:config:

- userChromes.ChromiumFX.Enabled
- userChromes.ChromiumFX.Aero
- toolkit.legacyUserProfileCustomizations.stylesheets
- svg.context-properties.content.enabled


KDE: force-blur script - add Navigator to config

zoom effect - set zoom factor to 1.00 and press meta+plus a few times to
workaround graphical glitch in firefox, slightly affects how the reflection effect looks

License: Mozilla Public License 2.0

Based on:
https://github.com/Godiesc/firefox-gx: MPL-2.0
https://github.com/QNetITQ/WaveFox:    MIT

