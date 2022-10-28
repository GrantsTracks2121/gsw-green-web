---
title: Lots of large images
category: 
favicon: 
---

## Here are a bunch of large images!
![[assets/images/axp-photography-wCtquP4WQ8U-unsplash.jpg]]
![[assets/images/jaromir-kalina-vT-HkcWMGm4-unsplash.jpg]]
![[assets/images/op23-sDxUwZjuBfo-unsplash.jpg]]
![[assets/images/pascal-bullan-r1Va0XGZVrc-unsplash.jpg]]

Here's the command I'm trying on Imagemagick. And yes, that flat-bed truck and trailer just driving away is what delivered this.
```
-filter Triangle -define filter:support=2 -unsharp 0.25x0.08+8.3+0.045 -dither None -posterize 136 -quality 82 -define jpeg:fancy-upsampling=off -define png:compression-filter=5 -define png:compression-level=9 -define png:compression-strategy=1 -define png:exclude-chunk=all -interlace none -colorspace sRGB
```