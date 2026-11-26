# This .md file is where I will store my notes so I can put the information cleanly into my Journal

## November 25, 2026: Notes For "Specifics and Compatibility":

### Parts so far:
Clamshell Case (7 3/8" long, 4 7/32" wide, and 1 5/16" deep) (each half)<br>
5"-5.5" display<br>
Rectangular Keyboard<br>
Trackball

### Where Things Will Fit:

The keyboard will go in the bottom half on the left side.<br>
The trackball will go on the right side ~1" from the middle of the width to make space for the mechanical key switches.<br>
The mechanical key switches will go right above the trackball side by side like a mouse's buttons.<br>
Because the rotary encoder acts as the scroll wheel it will go either between the key switches or right above them.<br>
The display will go in the top half of the case just like a laptop and I will check the bezel sizes to make sure a 5"-5.5" display can fit<br>
Oh and I cant forget one of the most important parts, the power source! For the power source I will use a usb power bank because that provides 5v and I chose a 10,000 MaH one because that should keep it powered for about 7 hours [Power bank](https://a.co/d/0j1Qg3x0)<br>

I will check for the depth of some displays to see if the Orange Pi 2 W can fit into the top half with the display and if it cannot then it will have to go <br>

### Finding a Display:

Lets start with the display:<br>
I will look up some 5" displays and see if they are compatible with an Orange Pi 2 W.<br>
I found this display on Amazon: [5", 1024 x 600 ips display](https://www.amazon.ca/iPistBit-Capacitive-Touchscreen-Raspberry-Driver-Free/dp/B0FCR5WPV5/ref=asc_df_B0CP3DH3LN?mcid=95bbd2beb6903e91a7f3f4c4bd43c97b&tag=googleshopc0c-20&linkCode=df0&hvadid=706724917431&hvpos=&hvnetw=g&hvrand=17153053587808454353&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9195703&hvtargid=pla-2280483271340&hvcampaign=21500527601&hvocijid=17153053587808454353-B0CP3DH3LN-&hvexpln=0&gad_source=1&th=1)<br>
It is meant for a Raspberry Pi, so I think it will be compatible.<br>
It does appear to be compatible, but when I looked at the product dimensions even though the actual screen would fit there is quite a large bezel causing it to go about an inch above my max width.

##### My case is quite thick so should I look for a different aspect ratio?

Lets start off by looking at what different aspect ratios exist and are common for displays.<br>
21:9 and 4:1 appeared when I searched wide aspect ratios, but are they common enough to have an Orange Pi compatible display? <br>
Wait my Iphone XR fits perfectly in the case with enough clearance lets see what aspect ratio it uses<br>
While I am at it lets see what the ratio of the width and height of my case is<br>
How do I find the ratio?<br>
Ok so I need to divide both the width and height by their greatest common diviser lets first simplify my measurements<br>
7 3/8" long, 4 7/32" wide, and 1 5/16" deep I can make it 7.5 x 4.25 and what is their greatest common denominator?<br>
Wait I can make them whole numbers by multiplying both by 4 which equals.... 30 x 17 and that cant be simplified<br>
Ok that cant be simplified, but 16 is a much easier number to divide with so lets change that 17 to a 16 which only takes 0.25" off of the actual measurement<br>
the greatest common denominator of 30 and 16 is 2 so the ratio is ~15:8 and thats close enough to 16:9 which is a very common screen aspect ratio so lets just stick with that.

##### Finding a 16:9 Display Compatible With My SBC:

Lets start simple by just looking one up I am going to search "16:9 display with a max product width of 4" tall."<br>
Ok so it looks like the width of the screen is 7.11" if its 4" tall and at a 16:9 aspect ratio.<br>
that is good because it fits my case perfectly, but like I discovered yesterday Displays are usually measured with one measurement going from one corner to the opposite corner so lets use the pythagorean theorem to figure out that diagonal measurement<br>
7.11^2 + 4^2 = ~66.5 and the square root of 66.5 is ~8<br>
Ok so that narrows it down a lot, we are looking for an 8" 16:9 display (the resolution does not matter too much to me)<br>
with my knowledge of bezels taking up a bit of space I will lower that down to a 6.5" display and if that is not a common enough size then I will go to a 6"<br>
I think I found a good display, but first lets check the refresh rate to make sure its not incredibly slow <br>
Ok good it is 60HZ which will be great for my project.[6.5" display](https://a.co/d/0g706wP9)<br>
For the power it is 5 volts which is perfect because it can be powered by a usb power bank
