# fzf-launcher

A launcher program working with fzf<br>
![Alt Text](https://user-images.githubusercontent.com/20209694/193479265-f1c309c5-ad24-4b1c-982d-151eddabc8bf.png)

## my personal configuration
bspwmrc
```
bspc rule -a *:float:* state=floating
bspc rule -a *:float:* sticky=on
```
<br>

sxhkdrc
```
super + d
	urxvtc -name "float" -e "/home/pedro/scripts/launcher" -name "float"
```
