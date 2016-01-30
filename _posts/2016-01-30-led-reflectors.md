---
layout: post
title: LEDs could be cheaper and just as bright without a common component
author: RaoOfPhysics
---

_Simulations show reflectors used in LED emitters may be unnecessary_

Low-cost and low-power light-emitting diodes (LEDs), especially white LEDs, have revolutionised lighting.
In fact, the inventors of blue LEDs &mdash; a crucial element for producing white light &mdash; [won the 2014 Nobel Prize in Physics](http://www.nature.com/news/nobel-for-blue-led-that-revolutionized-lighting-1.16092).
Now, [researchers have demonstrated](http://dx.doi.org/10.1186/s40539-015-0031-z) that there may be even better ways to optimise how white LEDs are made, by eliminating one commonly used component.
Changing the manufacturing process based on this work can further reduce the costs of white LEDs by 5–10%.

Unlike filament-based lighting devices or ones that use fluorescent gases, LEDs rely on [semiconductors](https://en.wikipedia.org/wiki/Semiconductor).
Layers of semiconducting materials are combined together in such a way that electricity passing through them cause photons to be emitted.
These layers and other components of a single LED must be assembled very precisely.
To secure the LED chip itself to the base of the final emitter package, a special adhesive or glue is used.
Conventionally used adhesives are made with silver and happen to absorb light that falls on them.
This reduces the final light output of the LED.
To combat this absorption, so-called backside reflectors are added between the LED chips and the adhesive layer, in order to allow higher light output.
When LED chips were tested before they were assembled into the final devices, backside reflectors boosted the light output by up to 50%, encouraging their continued use.

However, laboratory testing can vary from real-world performance.
In fact, it wasn't clear if assembled LEDs would also have increased light output with reflectors, because this had not been tested.
Further, the materials used for backside reflectors in low-cost LEDs happen to reflect certain wavelengths much less, casting doubt on the overall effectiveness of the reflectors.
To add to this, using a newly developed, optically clear adhesive instead of the silver-based ones might even remove the need for including the reflectors in the first place, but this had not been verified before.

![White LEDs]({{ site.url }}/images/2016-01-30-led-reflectors.jpg)

> _White LEDs. [Image](https://www.flickr.com/photos/oskay/2230059807/) by Windell Oskay / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0/)_

The researchers wanted to test how the reflector and clear glue affected light output; they experimented on the following combinations: (1) LED chips without backside reflectors, (2) the most-commonly used LED chips &mdash; ones with low-cost backside reflectors (which have low reflectance), and (3) LED chips with high-reflectance backside reflectors (which are more expensive and hence not used widely).
The data showed that reflector-free chips performed considerably better than chips that used low-cost reflectors, although chips with the expensive reflectors out-performed both others.
This suggests that merely replacing the silver-based adhesives with the optically clear alternative can improve the light output and backside reflectors can be left out.

To test the real-world performance fo the final LED devices, the researchers studied the effect of the packaging process on the devices' light output
They did so using [Monte Carlo](https://en.wikipedia.org/wiki/Monte_Carlo_method) software ([*LightTools*](https://optics.synopsys.com/lighttools/lighttools-feature-details.html)) to simulate models of packaged devices and naked LED chips, both of which used reflectors of varying reflectance.
Even though the light output of the naked chips benefited from the backside reflectors, the simulations showed that backside reflectors didn't make the final LEDs brighter.
Experimental measurements also backed up the data from the simulations; this indicates the simulation method was valid.

These new results illustrate how expectations of how something *should* work are not always met and that testing in real-world situations as well as simulations are often needed.
The authors of the work show that by modifying the production techniques of LEDs, we can get better-performing devices at even lower costs.

---
Citation:

> Kim, G., Shih, Y.-C., You, J.-P., & Shi, F. G. (2015). Optical role of die attach adhesive for white LED emitters: light output enhancement without chip-level reflectors. _Journal of Solid State Lighting_, 2:11. DOI: [10.1186/s40539-015-0031-z](http://dx.doi.org/10.1186/s40539-015-0031-z)
