# Your Game, on Sprig ... in a Flash!

So you have it, resting on your desk in front of you, in all of its spriggy glory: the handheld Sprig console!

You created an incredible game to earn this thing, but uh ... you're not sure how to run that game on the device ...

Fortunately, there isn't too much that you have to do:

- Download a copy of the operating system we made for the device
- Hold down the "BOOTSEL" button on the back of the device, and plug it in
- Drag and drop the operating system onto the device ("flash" the OS onto it)

That's all!

## Have no fear, UF2 is here!

Click on [this link](https://sprig.hackclub.com/pico-os.uf2) to download Spade, the operating system for the Sprig console.

## BOOTSEL

![sprig!](./assets/sprig.png)

Hold that button right there, and plug in the sprig!

## Drag n Drop

It should appear in your file menu as a separate drive, much like a USB.
![drop!](./assets/drag_n_drop.png)

Just drop the .uf2 in there, and you're good to go! The device should immediately restart, and a message should appear on the screen.

> **Note:** If you're having trouble getting the .uf2 file onto the Pico using the macOS Finder, try using the command line tool `cp` instead.
> For example, if you downloaded the .uf2 file to your Downloads folder, you could run the following command in your terminal to copy the file to the Pico.

```sh
cp -X ~/Downloads/pico-os.uf2 /Volumes/RPI-RP2
```

![upload a game screen](./assets/default_screen.jpg)

## Okay but how do I upload MY game?

![drop!](https://doggo.ninja/lRotxY.png)

Open up your game in the editor, click the "Run on Device" button in the top right, and select the Sprig from the menu (again, like a USB device.)

*Note: Make sure you're using a Chromium-based browser such as Edge or Chrome. On Linux you will also need to add your user to the `dialout` group*

That's it! You're done :)
