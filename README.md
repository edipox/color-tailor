# Color Tailor [![Build Status](https://travis-ci.org/dguo/color-tailor.svg?branch=master)](https://travis-ci.org/dguo/color-tailor)
A [dynamic Firefox
theme](https://developer.mozilla.org/en-US/Add-ons/Themes/Theme_concepts#Dynamic_themes)
that changes the theme to the current website's "primary" color. Available in [Firefox
Add-ons](https://addons.mozilla.org/en-US/firefox/addon/color-tailor/).

Order of precedence for determining the color:
1. The meta [theme-color](https://html.spec.whatwg.org/multipage/semantics.html#meta-theme-color) element
2. The dominant color in the [favicon](https://en.wikipedia.org/wiki/Favicon), as determined by [node-vibrant](https://github.com/akfish/node-vibrant)
3. White as a fallback

![screenshot](https://i.imgur.com/uqJqd3A.png)

## Installation
Install Color Tailor from the
[Add-ons](https://addons.mozilla.org/en-US/firefox/addon/color-tailor/) page.
Firefox 60 and above is required.

## Prior Art
Color Tailor was inspired by an [iTunes feature](https://stackoverflow.com/q/13637892/1481479) that would change UI colors on the fly to match album covers.

Chrome on Android does a [similar thing](https://developers.google.com/web/updates/2014/11/Support-for-theme-color-in-Chrome-39-for-Android) with the toolbar color, and there is an [open issue](https://bugzilla.mozilla.org/show_bug.cgi?id=1098544) to do the same for Firefox.

## Other Themes
* [Chromatastic](https://addons.mozilla.org/en-US/firefox/addon/chromatastic/): continuously cycles through colors
* [Containers Theme](https://addons.mozilla.org/en-US/firefox/addon/containers-theme/): changes the theme color to match the active [container tab](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/)
* [Picture Paint](https://addons.mozilla.org/en-US/firefox/addon/picture-paint/): changes the theme to match the color palette of the current National Geographic Photo of the Day
* [Quantum Lights](https://addons.mozilla.org/en-US/firefox/addon/quantum-lights-dynamic/): Firefox Quantum palette-inspired theme that changes based on the time of day
* [Gradientus](https://addons.mozilla.org/en-US/firefox/addon/gradientus/): also changes colors based on the time of day

## License
[MIT](https://github.com/dguo/color-tailor/blob/master/LICENSE)
