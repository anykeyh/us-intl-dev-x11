# US International for Developer in X11

Aka layout inspired by OS/X US International layout, which is very confortable for French on QWERTY :-).

## Why

I just switch from MacOS to Manjaro Linux. So far I'm super happy with my setup. Except for the keyboard. The internationals layout sucks hard. It slow me down soooo much. 

- With dead key, I'm tired to type `letś go` instead of `let's go`.
- Without dead key, the layout doesn't allow so much combinaisons.

- Finally and in my opinion, having `altgr` on the right is not very ergonomic. I like to keep my modifier over the left size of my keyboard, while using the right side modifier for options so this mapping invert Alt and Alt+Gr by default (option removable).
  
## What
_"This keyboard layout changed my life and I çan enjoy Linux with āccènt wïthøut mispélling anymore" 
— The author._

- A keyboard layout heavily inspired from the US Intl on mac. Powerful and extensive, yet no dead key on non-modded key press.
- Most of the common european diacritics and accent should be present. if not, just make a PR.
- Some useful mathematics and monetary symbols.
- Most of the character with diacritics or accent are not mapped directly but the accent/diacritic is a dead-key under AltGr. So composition is needed. This is very useful because it allows virtually more characters and give room to other mapped keys.
- I tried to put the diacritics & accent intelligently. But I'm not so much knowledgeable for some of them. So feel free to discuss about it.

## Instructions

Put the `.Xmodmap` file into your home directory. It should be taken in consideration at the next startup of your Xserver.

=> If not starting automatically, or if you want to get the layout working now, just launch the command:

```bash
xmodmap .Xmodmap
```

- You may want to call the command on each X11 startup (e.g. in `.xinitrc`)

## AltGr vs Alt (aka. for Emacs users)

Alt and AltGr are reversed. You can comment the two first line of the map to avoid this behavior.

## Layout

note: `△` before character stand for deadkey

Each table represent a row of your QWERTY keyboard

```
1  !   ¡  ¹
2  @   ™  ²
3  #   £  ³
4  $   €  ¤
5  %   ¶  ¶
6  ^  △^  ¼
7  &  △˛  ½  
8  *   ·  °
9  (   ’  “
0  )   ’  ”
-  _  △¯  —
=  +   ≠  ±
```

```
q Q  œ Œ
w W △˙ ₩
e E △´ ´
r R ®  ₨
t T þ  Þ
y T ¥  ¥
u U △¨ ¨
i I í Í
o O ø Ø
p P ₧ ₧
[ { « «
] } » »
```

```
a A α  Α
s S ß  §
d D Ð  Ð
f F ƒ △ ̣
g G γ Γ
h H h H
j J j J
k K k K
l L l L
; : … …
' " æ Æ
```

```
z Z  ̛△  △ ̉
x X  △ ̣  △ ̣
c C  △¸ △¸
v V ▽ △
b B β Β
n N △~ ~
m M µ Μ
, < ≤ ×
. > ≥ ÷
/ ? ¿ ¿
```

## Help me

You're from northen europe? You are using diacritic I'm not even able to understand? There's room to improve this layout and make it the greatest International Layout ever :D

## Licence

Under MIT.
