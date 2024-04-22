<img align="left" width="88" height="88" src="https://cdn.discordapp.com/attachments/772832118161932308/1232030038841622579/Square44x44Logo.scale-200.png?ex=66391c63&is=6626a763&hm=43f3e0d0c2ef2103199be31f8e64eb2b13e990d6bf9bc4753a48e47bac604aa2&">

# Muse2014IntoVRChat

This project is based off BrainFlowsIntoVRChat, using some of the same math from it, with my own code alongside it. THANK YOU SO MUCH TO CHARLES (Creator of BrainFlowsIntoVRChat) for help with the math!

Some quick disclaimers before we get started:
I am not associated with Interaxon or the Muse corporation (whatever they go by these days).
Most of the software used alongside this project is abandonware, and it isn't guarenteed to work.

# What you'll need:

Muse MU-01 (2 charging ports)

MuseIO 3.4.1 (can be found at https://github.com/DrBrainlove/muse_tools)

Bluetooth Adapter

1. Install the Windows Muse SDK
2. Open CMD and navigate to C:/Program Files (x86)/Muse/
4. Put your muse in Pairing Mode (flashing light, hold down for 5 secs)
5. Connect it using bluetooth. (It will disconnect, just keep it paired)
6. Run this command:
   ```muse-io --device-name <DEVICE NAME> --osc osc.udp://localhost:1647```

And it should re-connect.

6. Download the zip of this repo and navigate into its folder on CMD
7. ```pip install -r requirements.txt```
8. Open main.py
9. Set VRChat avatar params properly (or use TouchOSC to map them)
 #   Params are:
   
       /Focus (0-1) (Float)
   
       /FocusLeft (0-1) (Float
   
       /FocusRight (0-1) (Float)
   
       /Blink (0,1) (Int)

Will write better docs when I get a minute. Thanks!


