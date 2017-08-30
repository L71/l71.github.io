
## Notes about hardware and tools used 

### Circuit boards

I'm using Eagle by Autodesk (formerly Cadsoft) for schematics and PCB CAD. 

Until now I have used [OSH Park](https://oshpark.com) for PCB manufacturing but may swap to PCBway in the future - we'll see. Because of this most (all?) Eagle board files until now include OSH Park's design rules.

All PCBs are designed with industrial production in mind and might not be suitable for etching in ones kitchen.


### Eurorack Module Panels

All panels until now (mid 2017) have been drawn using [Inkscape](https://inkscape.org/) and manufactured by [ponoko](https://www.ponoko.com). The panel .svg files should be copied onto a Ponoko template before uploading it to them, and make sure to read their submission guidelines - and in particular adjust line widths if necessary. Also make sure the "knob outlines" layer in the drawings is hidden.

The panels are intended to be laser cut and engraved on 1.6mm acrylic, black surface on white core. This gives a quite nice panel, matte black with engraved white text on it. Not exactly bullet proof but usually solid enough when the PCB is attached with all jacks and additional support screws.

The typeface used is [My Underwood](https://www.fontsquirrel.com/fonts/my-underwood) which you might need to install if you want to edit the text labels on the panels. 

A recent experiment with panels on PCBs manufactured by PCBway.com turned out great so this method for panel creation may be used from now on instead. 

**note** the earliest modules (the 0xNN named ones) were used with a rack that had M2.5 screws instead of M3. Because of this the panels holes are a bit too close - you might need to adjust these (about 1/40" IIRC) to make your panels fit the rack if using M3s. 


### Mechanical details

**note** the early 0xNN named modules do not adhere to this

The modules use "Thonkiconn" PJ301M-12 jacks, available from [Thonk](https://www.thonk.co.uk/). These are 10mm high from the PCB to the top of their body (and the panel).

Potentiometers used are (usually) Alpha 9mm types from the same source or from Tayda Electronics. These are - as are the jacks - 10mm high from the PCB to the panel. (note: if there is a small metal tab sticking up from the body into the panel, this needs to be cut off before use.) 

Any other potentiometer with the same PCB footprint (ALPS etc. ...) should work but some may not adapt as well (or at all) with the panels. Some of the modules structural integrity will depend on the potentiometers being screwed tightly to the panel - when using the mentioned plastic panel the whole thing will be a bit too flexible if this is not done. 

In some places "tall trimmer" type pots [like these](https://www.thonk.co.uk/shop/ttpots/) are used instead of the common ones with a separate larger knob. This is not noted in the schematics. 

Some modules also have holes in both panels and PCBs for 10mm spacer screws to help with mechanical stability. Use these when available!

About knobs: Use any that you find attractive and that fits the shaft of your favourite potentiometers. 
If you use pots with "D" type shafts, be aware that not all knobs have the flat "D" shape in the hole in the same direction. Also, my SMD 2xVCA and 3xCV modules actually have their pots backwards compared to the other modules since I had a bunch of such backwards D-knobs that I wanted to use. 

The approximate intended knob size can be seen in the (possibly hidden) "knob outlines" layer in the panel SVG files (if present). 

### Components

Most modules use regular thru-hole components but a few are built with 0603/1206 SMDs and there are even one or two that use a mix. 
Most of the SMD boards have the user facing components (jacks, pots, switches) on one side and the actual electronics on the other side of the PCB. 

Sources: 
- [Thonk](https://www.thonk.co.uk/) - jacks, potentiometers, knobs
- [Tayda](http://www.taydaelectronics.com/) - potentiometers, some knobs, bulk components
- [TME](http://www.tme.eu/en/) - LEDs and photoresistors for homemade vactrols, bulk components

I also occasionally buy from Electrokit.com, Mouser, Farnell and Digikey. 









