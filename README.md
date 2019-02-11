# US International for Developer in X11

Aka layout close to MacOS US International

## Why

I just drop my Macbook to work on Manjaro Linux. So far I'm super happy with my setup. Except for the keyboard.

English intl layout is not good:
- The dead key version make the coding impossible, as you need to double key over `'`, `\``, `"` characters.
- The non-dead key version allow you with altgr to create character like é. But what about Ê?
- In my opinion, having `altgr` on the right is not very ergonomic. I like to keep my modifier over the left size of my
  keyboard, while using the right side modifier for options.

## Instructions

Put the `.Xmodmap` file into your home directory. It should be taken in consideration at the next startup of your Xserver.

If not starting automatically, or if you want to get the layout working now, just type:

```bash
xmodmap .Xmodmap
```