# PrimeMapper

##Overview
**PrimeMapper** is a simple Python script allowing you to generate .GIF files that contain every prime number in it's binary representation formed by a red pixel for 0's and a green pixel for 1's.

##Configuration
Inside PrimeMapper.py there is the following code:<br/>
`python
wid = 64        #Width of the final image
`
<br/>
`python
hei = 8192      #Height of the final image
`
<br/>
`python
fin = 84015     #Number to go to
`
<br/>
`python
fnm = "PrimeMap"  #File name to export
`
<br/>
The code is pretty much self explanatory with the comments. *wid* and *hei* are the final image's width and height respectively, *fin* is the last number it will go through before it stops finding primes. You can calculate this number easily. If the primes found are more than the image can fit, last primes won't appear anywhere. If the found primes are less than the image can fit, the remaining pixels of the image will be blank. *fnm* is the filename of the image. All images have the extension .GIF and this cannot be changed.

##Example
![Prime Generation](http://i.imgur.com/DVY6XSc.gif)