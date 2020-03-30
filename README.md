# Material Theme for Facebook
A Material Dark Theme for Facebook

3 themes available : Oceanic, Darker, Palenight

Based on awesome **[VSCode Material Theme](https://github.com/equinusocio/vsc-material-theme)** by **Mattia Astorino**

![Material Theme Facebook](https://github.com/CharlieEtienne/material-facebook/blob/master/screenshot.png)

## How to use it

1. Install **Stylus Extension** [for Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne), [for Firefox](https://addons.mozilla.org/fr/firefox/addon/styl-us/) or [for Opera](https://addons.opera.com/en-gb/extensions/details/stylus/)

2. Install [https://userstyles.org/styles/181736/material-dark-facebook](https://userstyles.org/styles/181736/material-dark-facebook) 

## About

### IMPORTANT

- You must have "new" Facebook enabled. ([See how](https://www.pocket-lint.com/apps/news/facebook/150761-the-new-facebook-update-how-the-all-new-design-looks-and-works))
- You need to activate "Dark mode" (See link just above)
- Doesn't work on messenger currently

This theme is SUPER easy to customize ; you just need to change hue and/or saturation to get your own dark nuance.
Thanks to new facebook theme and css vars, this color theme needs only 30 lines of css to work

Custom accent doesn't work everywhere for now. You can uncomment to test it but it won't apply everywhere.

If your eyes like it, I did the same on some other well-known websites with the same theme:
https://userstyles.org/users/763420

## Colors
The only thing changing between the three available themes are `hue` and `saturation`.

|           | `hue` | `saturation` |
|-----------|-------|--------------|
| Oceanic   | 200   | 19           |
| Palenight | 229   | 20           |
| Darker    | 0     | 0            |

Thanks to hsl(a) colors, all necessary shades can be achieved in a very simple way.

```css
:root{
    --bg1: hsl(var(--hue), var(--saturation), 13%);
    --bg2: hsl(var(--hue), var(--saturation), 15%);
    --bg3: hsl(var(--hue), var(--saturation), 18%);
    --bg4: hsl(var(--hue), var(--saturation), 21%);
    --bg5: hsl(var(--hue), var(--saturation), 24%);
    --bg6: hsl(var(--hue), var(--saturation), 27%);
	
    --ov: hsla(var(--hue), var(--saturation), 70%, .18);
}
```

## Contributions

Contributions are very welcome! Feel free to suggest changes in a new issue or make a PR.
