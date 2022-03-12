# Keyswitch-Biscuit
This is a Kicad project outlining the desing and gerbers for a Keyboard Switch Biscuits

## What is it?

This small PCB fits a single Cherry MX style mechanical keyboard switch and exposes all the connections for easy soldering.

It's designed for those of you interested in making hand-wired custom mechanical keyboards like the [Dactyl Manuform](https://github.com/abstracthat/dactyl-manuform)

There are a bunch of of these around, but this one is different in that:

- It is designed to be used with Kailh hotswap sockets (for solderless removal of keyswitches)
- It has a slot for a [SK6812 MINI-E](https://hackaday.com/2020/01/28/new-part-day-sk6812-mini-e-a-hand-solderable-neopixel-compatible-led/) downward-facing RGB surface mounted LED (you can get a bunch of them [here](https://www.ebay.co.uk/itm/174769617449)
- Allows you to solder the entire key matrix before installing it inside the case. (no need to do this in place)

This design in particular has indentations in each corner so that melted plastic can be used to hold the PCB in place, without the need of glue or screws (though you could still use those if you wanted to)

I designed this when I was preparing to make my own Dactyl Manuform keyboard.

See.. it's layout and shape not flat and it's not possible to buy/make a single board with all the terminals for the key switches you need. This is when this small PCB comes in handy.

You could hand-wire all the key switches together but it would be messy and you would be hard pressed if you wanted to use Kailh hotswap sockets or any kind of RGB features.


## Version and Gerbers
- **v1.0** (gerbers/gerbers-v1.0.zip)

    First iteration of the desing.
    The RBG footprint used for the SK6812 MINI-E was messed up and the connections did not match.
    The board was successfully printed with JLCPCB (as 5x5 panel), the only the Rows and Cols are really usable.
    Leaving this hear for the sake of archiving.

- **v1.1** (gerbers/gerbers-v1.1.zip)

    This version was the first usable MVP and it was successfully used in my my own Dactyl Manuform build.
    Works great!
    The board was successfully printed with JLCPCB though I dont remember doing much checking tolerances.
    I used a 1.6 thickness with a 1oz copper layer and a LeadFree HASL-RoHS finish.
    Potentially improvements:
      -  Solid Pads instead of THT may allow for easier wiring (though they may require better soldering skills)
      -  The traces themselves could be a bit thicker (not sure if there is enough space)
