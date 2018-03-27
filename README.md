# Priezor

Quick guide for building DIY Priezor – open source electromagnetic antenna.

Essentially, Priezor is a very long loop of enameled copper wire wound on a heptagonal antenna with a handle.

Its construction is made from PMMA, also known as acrylic, which is easily cut on a CO<sub>2</sub> lasers and couple of screws. For cutting acrylic, you might contact your local makerspace/hackerspace or a sign-making company.

## Ingredients
* ~ 14 grams of enameled 0.118mm wide copper wire
* at least 45 x 20 cm piece of 3mm acrylic
* 7 M3 x 12mm screws (metal or plastic) – for the antenna
* 7 M3 x 18mm screws (metal) – for the handle and connection points
* 10 M3 plastic spacers
* 7 M3 plastic nuts
* 7 M3 metal nuts
* 1.5m microphone cable
* XLR connector

## Tools

* laser cutter for cutting the parts from PMMA
* basic screwdrivers, depending on the screws and nuts used
* hot-glue gun

## Building procedure

1. Use laser cutter to cutout all the parts in `priezor.dxf` file. You will need two antenna pieces, two of each handle part except the middle one (with the teeth – those are for cable strain relief)
2. Assemble antenna by connecting two cutouts with screws with the plastic spacer in the middle. This should create a 3mm hole between the plastic parts for winding the coil itself.
3. Wind the copper wire on the antenna. We do 333 turns, but you can experiment with more or less – generally, more turns = more sensitivity, but the frequency response changes too. Fix the windings with a hot glue gun, leaving the two ends of the loop at the side with three holes.
4. Assemble the handle in "sandwich" fashion (the widest part with the teeth goes in the middle). Antenna is attached through the three holes present in the front and bottom cover piece. Fit the cable in the hole.
5. Solder the ends of the enameled wire coming from the antenna to the microphone cable to its *signal conductors*. Use higher temperatures to melt of the protective coating of the wire, because otherwise the solder won't stick to it. You can also use a bit of sandpaper to remove it. Leave its shield unconnected at this end. Cable shielding is *only* connected to pin 1 at the XLR connector.
6. Finish the construction with mounting the final cover plate.

![Side-view of the Priezor sandwich](https://i.imgur.com/30mo3tf.jpg)
