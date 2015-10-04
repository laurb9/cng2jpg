# cng2jpg
Convert "Complete National Geographic" CNG files to JPG for use under Linux

## Basic usage

### copying from CD into local hard drive:

```sh
cng2jpg.py --src /run/media/_user_/CNG_DISC1/disc1/images --dst ~/CNG/discs/images
```

### convert a hard drive copy

```sh
cng2jpg.py --src ~/CNG/discs [--remove]
```
Use --remove to get rid of .cng files as they are converted, to avoid needing extra 40+Gb of space for both jpg and cng.

## References

"The cng files are all jpegs, XOR'd bitwise with 239"

http://www.subdude-site.com/WebPages_Local/RefInfo/Computer/Linux/LinuxGuidesByBlaze/appsImagePhotoTools/cng2jpgGuide/cng2jpg_guide.htm
