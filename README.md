# R-Emote

This is my latest piece of work.
 
I use Machine Learning in a somewhat practical setting. This project involves the full development of a convolutional neural network to detect hand gestures that can control smart appliances around me. This can read hand gestures, convert them to a computer-readable CSV file and then train a neural network to work accordingly. It even returns an emoji for the gesture it detects, as a visual cue.

I capture my hand gestures via my webcam, capture 1500 images per gesture for a total of 8 gestures. I train the model with 12000 images, and the results come out to be very accurate.

Note that if you want to use it, you will need a Sonos speaker and a Philips Hue bulb connected to the same internet connection. You will also have to change the IP address in the program to your own devices. Additional functionality can be added too, import other smart home APIs and automate your tasks. You can also generate a full new set of gestures and add/remove gestures from the code as you wish.

The use cases are endless. It can help technologically-challenged seniors, people who don't have the ability to speak or to do so properly for the machine to understand, people with accents that are not well-supported by the virtual assistants, people facing some sort of disability, people with lesser dexterity and people who don't have the ability to maneuver smart appliances otherwise.

The order of use is 1) createHandImpressions.ipynb, 2) bringTocsv.ipynb, and then 3) trainAndDetect.ipynb.

I have a very large dataset for the file which GitHub does not allow me to put up, however one can easily be generated with the code I have up here.
