This projects contains a set of high-res images of poker cards, for use in iOS applications, and now any Game Dev 3D File as well has been included. We also removed scripts from original source, if needed find them below:

Original Source Credit:
[https://github.com/Xadeck/xCards/master/]

Fork Credit:
[https://github.com/alchme]

Initial card design obtained from https://sourceforge.net/projects/vector-cards/?source=typ_redirect
They were split into single files, and exported as SVG using [Sketch](https://www.sketchapp.com/).
They were then converted to fix the maximum sized indicated by https://www.paintcodeapp.com/news/ultimate-guide-to-iphone-resolutions, that is:

```
320x480
750x1334
1242x2208
```

Poker cards have dimensions of 63.5cmx88.9cm according to [wikipedia](https://en.wikipedia.org/wiki/Standard_52-card_deck), which means an aspect ratio of 0.714. Applying that to above dimensions with fixed width yields the following sizes:
  
```
320x448
750x1050
1242x1739
```

Revised by Wolf on Github as Alchme
