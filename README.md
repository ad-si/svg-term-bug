# svg-term-bug

Bug in svg-term

![Bug](bug.svg)

Bug fixed (replacing css with svg attributes)

![Bug fixed](bug-fixed.svg)


https://asciinema.org/a/WjieFWejN9qfjzFsyj1jzoYq0


```
svg-term \
  --no-cursor \
  --at 99999 \
  --window \
  --term iterm2 \
  --profile ../../dotfiles/terminal/adius.itermcolors \
  < bug.json \
  > bug.svg
```
