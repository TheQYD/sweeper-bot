A remote controlled sweeper bot that uses, RaspberryPI, Raspbian, 
Playstation DualShock3 controller, a bluetooth dongle, and SDL. To setup
bluetooth, take a look at this blog entry:

  http://www.raspians.com/Knowledgebase/ps3-dualshock-controller-install-on-the-raspberry-pi
 
For SDL, install sdl1.2-dev by entering:

  sudo apt-get update && apt-get install libsdl1.2-dev

The rest is a matter of installing BrickPi and it's libraries. Information
concerning BrickPi using C can be found here:
  
  www.dexterindustries.com/BrickPi/program-it/c

To compile it, place DexterIndustries' BrickPi.h and tick.h in the folder, then
enter:

  gcc -o sweeper sweeper.c -lSDL -lrt -lm -L/usr/local/lib -lwiringPi

Images of the bot can be found here:

  https://plus.google.com/photos/112321570613330986901/albums/6109871844300485905

It's relatively simple. You can always modify it or the code to suit your needs. 

Have fun!





