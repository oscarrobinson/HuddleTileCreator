HuddleTileCreator
=================

A simple Python script to allow easy creation of image tiles formatted for HuddleCanvas

##Installation:
This script requires [Pillow](http://pillow.readthedocs.org/en/latest/index.html)<br>
Install Pillow:<br>
```$ pip install Pillow```

Then simply download huddle-tiler.py

##Using HuddleTileCreator:
Put huddle-tiler.py in the same directory as the image you want to tile

Then simply run
```$ python huddle-tiler.py [IMAGE NAME]```

e.g ```python huddle-tiler.py art.jpg```

You will see something like this:
```
created tile number 1 || saved as tile-500-0.png
created tile number 2 || saved as tile-1000-0.png
created tile number 3 || saved as tile-1500-0.png
created tile number 4 || saved as tile-2000-0.png
created tile number 5 || saved as tile-2500-0.png
created tile number 6 || saved as tile-3000-0.png
created tile number 7 || saved as tile-3500-0.png
created tile number 8 || saved as tile-4000-0.png
created tile number 9 || saved as tile-500-500.png
created tile number 10 || saved as tile-1000-500.png
created tile number 11 || saved as tile-1500-500.png
created tile number 12 || saved as tile-2000-500.png
created tile number 13 || saved as tile-2500-500.png
created tile number 14 || saved as tile-3000-500.png
...
...
created tile number 45 || saved as tile-2500-2500.png
created tile number 46 || saved as tile-3000-2500.png
created tile number 47 || saved as tile-3500-2500.png
created tile number 48 || saved as tile-4000-2500.png
```
Then just take all the images named tile-[number]-[number].png and put them in your [HuddleCanvas](https://github.com/scarrobin/HuddleCanvas) meteor project in the <b>public directory in a folder named tiles</b>
