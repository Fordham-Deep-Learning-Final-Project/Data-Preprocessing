# Data-Preprocessing

## Image Source
Could access thorough the link: https://drive.google.com/open?id=1OYEOAOJrAGfZcnwZuDraGL2sY9-d4FVZ

## Download V2.py
Improved version of image crawler from the csv file.
This version use different packages and workflow, improving the speed and stability of the crawler.

## Download.py (Suggested to be replaced by V2)
~~This file is used for download the source image from the csv table. 
The order of the image folder is followed as the csv table.~~

## Process.py 
Given that we cannot find the original image without red or other color boxes, and not knowing the effect 
of CoCo framework. I make some simple work to remove the parts outside of the boxes. Just in case if we need it for training.
