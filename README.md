# How To Build A Travel Pad For Under $190

Hello gamers, this is probably the most in-depth travel pad guide you will find. This pad is basically Bandit's travel pad, but slightly modified. It’s a very easy build, and only takes 1-2 hours. It dosen’t require any soldering. Just have some slight background knowledge on breadboards (which I did not have when building this, lol) Finished product image is at the bottom (once I can take it.) READ EACH ENTIRE STEP BEFORE DOING THE STEP. 

## Parts List


| Item                                                                                       | Prices (USD)             |
|--------------------------------------------------------------------------------------------|--------------------------|
| [2x2 Board](https://www.homedepot.com/p/Sanded-Plywood-Common-15-32-in-x-2-ft-x-2-ft-Actual-0-451-in-x-23-75-in-x-23-75-in-300888/202093832?g_store=4180&source=shoppingads&locale=en-US)                                                                              | $12                      |
| [Breadboard](https://www.amazon.com/Pcs-MCIGICM-Points-Solderless-Breadboard/dp/B07PCJP9DY/ref=sr_1_7?dchild=1&keywords=breadboards&qid=1623441551&sr=8-7)                                                                             | $6                       |
| [Wires For Breadboard](https://www.amazon.com/AUSTOR-Lengths-Assorted-Preformed-Breadboard/dp/B07CJYSL2T/ref=sr_1_3?dchild=1&keywords=breadboard+wires&qid=1623441581&sr=8-3)                                                                   | $10                      |
| [Resistors](https://www.amazon.com/Elegoo-Values-Resistor-Assortment-Compliant/dp/B072BL2VX1/ref=sr_1_3?dchild=1&keywords=resistor+kit&qid=1623441602&sr=8-3)                                                                              | $12                      |
| [Teensy LC Microcontroller](https://www.amazon.com/Teensy-LC-with-pins/dp/B016MZVBOA/ref=sr_1_1?dchild=1&keywords=teensy+lc&qid=1623441625&sr=8-1)                                                              | $17                      |
| [Micro USB Cable](https://www.amazon.com/s?k=micro+usb+cable&crid=2AK4RHF2IM0ZI&sprefix=micro+usb+cab%2Caps%2C472&ref=nb_sb_ss_ts-doa-p_1_13) _any length, whatever you need to go from machine to pad_              | depends on  what you get |
| [Wires for FSR’s](https://www.amazon.com/EDGELEC-Breadboard-Optional-Assorted-Multicolored/dp/B07GD2BWPY/ref=sr_1_4?dchild=1&keywords=breadboard+jumper+wires&qid=1623441650&sr=8-4) _wires that go around the pad_                                         | $5                       |
| [FSR's](https://buyinterlinkelectronics.com/products/fsr-model-408-300mm-length?_pos=4&_sid=0b9c66a78&_ss=r) _order 4_                                                                        | $25                      |
| [Velcro ](https://www.amazon.com/VELCRO-Brand-Mounting-Adhesive-Concrete/dp/B09BNPHCZX/ref=sr_1_4?crid=25L34I0GGKYVJ&keywords=velcro+tape&qid=1643228556&sprefix=velcro+tape%2Caps%2C84&sr=8-4)                                                                                 | $12                      |
| [Scotch Tape](https://www.amazon.com/Learning-Resources-MMM3105-Scotch-Inches/dp/B016XTHB0I/ref=sr_1_3?dchild=1&keywords=scotch+tape&qid=1623441773&sr=8-3) _for wires and cable management_                                           | $6                       |
| [Panels](https://www.tapplastics.com/product/plastics/cut_to_size_plastic/polycarbonate_sheets/516) _order these to the sizing on the image,  the three corner panels are optional_ | $70                      |

![alt text](https://lh6.googleusercontent.com/sgTGmuUYJRUlOQxntgMo7a1ClsjP7E7tSf5ghex1MjURzje0U8Q5nkkzAGFcL8WvvsTZRY2bljqY1I9Pm6tbZQObU2p2M3k8tlyc0mf3eITMdioXAjiMTvNNMi8qWVjCw-9vWIXD)

Total: $175 (not including micro usb, again, depends on what you get)

# Guide

## Attaching Panels
**USE THINNER VELCRO THAN PICTURED, USE 1" OR SO**


1. Place your panels on the board to where you want them, and outline them with a pencil. It should be in this order, as if you’ve never seen a pad before.
![alt text](https://lh6.googleusercontent.com/LfSvpIpiNeRMPY35QtFitAa-Rq6XzXbZxiHji6KSWBoUBoTlnM3SqHOq0oGH5dkS3Gs9LRX_jpIL9IMzovk7FtBEVs-FH0lOmeXi1yF-bL5XureB1JrrrftcqjBJKw44Xkdl5CX5)

2. Start with the center panel, and line up your velcro in the same way I did it. The pokey roll of velcro side goes on the board, and the other softer roll of velcro is what sticks to the panel.
3. Once you lay out your pokey velcro on the board, cut pieces of the softer roll of velcro to the same size as the pokey ones, so that they match up. For each panel, I recommend cutting the velcro thinner. As you can see, for the FSRs, I cut the velcro thinner. You should do this for the outer layer of velcro too. For the center panel, it should not matter unless you plan to remove it.
4. For your four arrow panels, on the inner layer of the velcro is where your FSR’s will go. Make sure to leave the paper on the back of the FSR’s, so in case you would need to remove the FSR from the velcro strip, it will easily come off. 

he red boxes are where the FSR’s go, and the green lines are where the connectors should face. Cut the FSR’s to be short enough for fit under the panel and not stick out, as I did

![alt text](https://lh4.googleusercontent.com/pQVOHZWkJp4AkNxsHN6x-B3AayUMqLBKSfOIJ8bRpzCJaMdBuc1rxHpz5vVNEsODbDKHBi066Wwgkn3obAounRks8G3ikfKsGUaZWY5H6pNzaRlFeI0r-OhJaKI0SzWRz-GwGsKy)

Here is a video guide that I made which explains everything I just did: https://www.youtube.com/watch?v=HUUXpGWz8Wc

## Wiring
Now we’re on to the wiring stage. This is probably the hardest part of building this pad, which is still pretty easy. 

1. Wire up your breadboard. First, push your Teensy LC into the breadboard, and wire from there. Use 330ohm resistors for the resistors. Here is an image as to where everything will go on the breadboard. 
![alt text](https://lh6.googleusercontent.com/9R0bf6alMcnYX5_5ooqffDPpWqmE8lXokOfNFBwsROGCq4GiIZoDhuZIPSpSNp_urYUhaO6y9WJyUGOZGZz9IkhMGEmcXygMiV-Pb506OH9XIOLNAKNXuL_tKoXlJ8sxKKHfdcTB)

2. Now it is time to connect your FSRs to the breadboard. Two wires come out of each FSR, and it does not matter as to which wire goes to the positive, and which one goes into the A slots. A0-A3 are the ports used for each panel. I have mine wired up as the following:

A0: Left
A1: Down
A2: Up
A3: Right

Here is a photo as to where the FSR’s connect to the breadboard. Thanks to teejusb for this image.

Blue = A0
Green = A1
White = A2
Yellow = A3

![alt text](https://lh3.googleusercontent.com/wI7e1QWydvNEFqShcWEfiSsirp8gG64zz7NwLTxrDX21ZDzSgy5icTmMbITVC4QRm4zkEGtX5lYlqtdxV15PnLrS7D9kzaxks8ZBGeR1k2wH0tjyjzW_5neScHZa75UjpOscjdLV)

Here is how I routed my FSR’s wires across the pad:

![alt text](https://lh4.googleusercontent.com/OB__IkSKys3D-z1x4K57DEV-3Ln63b8oMytikRfI2SDVCpOkMyAhTUtVOqE5yrKnR3-PAeFkvQhm3lx8CDdhytLpRpgcvTPqwjU1L3iL)

Each color obviously represents a different sensor. Using the other images above, it’s clear to see where each sensor connects. To get down and left arrows to connect, just string 3-4 female to male wires until they can reach the breadboard.

4. Once everything is connected, velcro your breadboard down to the top right corner of the board (to the right of the up arrow panel, above the right arrow panel). 

Here is a video that I made which explains wiring: 
https://www.youtube.com/watch?v=a4EGyhCXONA

## Software 

I don’t need to explain anything here. Just follow [teejusb's guide](https://github.com/teejusb/fsr)

## Finishing Touches

 If you’ve decided to order the corner panels, velcro those down in every corner except the corner with the breadboard (top right). 

Lastly, tape wires together and down to the board for cable management. This is your preference to how you want to do this if you want to do it all.

Thanks for following this guide!

If you have any questions, DM me on discord: Azirixx#6186

## Playtest

**VIDEO WILL BE OUT SOON**

This pad works amazingly. Works for everything. Stamina, ECFA, DDR Originals, and anything you throw at it. Since it uses FSRs for sensors, it's obvious that it's going to work pretty well. Also very easy to slide just as pro stamina players do. This pad can easily handle high BPM stamina and won't drop inputs. Also, the polycarbonate panels are pretty durable.
