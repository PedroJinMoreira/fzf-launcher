# fzf-launcher

A launcher program working with fzf<br>
![Alt Text](https://s4.gifyu.com/images/gif17569234b12e1724.gif)

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
