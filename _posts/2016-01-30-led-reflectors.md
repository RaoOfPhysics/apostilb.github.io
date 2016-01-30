---
layout: post
title: Reflectors in white LEDs may be unnecessary
author: RaoOfPhysics
---

_Simulations packaging processes used in LED manufacture may reduce the impact of reflectors_

Low-cost and low-power light-emitting diodes (LEDs), especially white LEDs, have revolutionised lighting.
In fact, the inventors of blue LEDs &mdash; a crucial component for producing white light &mdash; [won the 2014 Nobel Prize in Physics](http://www.nature.com/news/nobel-for-blue-led-that-revolutionized-lighting-1.16092) for their work.
Now, [researchers have demonstrated](http://dx.doi.org/10.1186/s40539-015-0031-z) that one of the parts used in white-LED packages may not be needed.
The authors of the research estimate that changing the manufacturing process based on their conclusions will further reduce the costs of white LEDs by 5–10%.

LEDs, tiny though they are, have a multitude of components that must be precisely assembled.
As part of the process of packaging LED emitters, the LED chip itself must be attached to the base securely.
This is commonly done using an adhesive.
Since a conventionally used silver-based adhesive also happens to absorb light that falls on it, so-called backside reflectors were developed to reduce this absorption, allowing more light to leave the emitter.
When naked LED chips were tested before they were assembled, the use of backside reflectors gave an enhancement of up to 50%, encouraging their continued use.

However, and crucially, tests hadn't been conducted on whether this enhancement also applied to the final LED emitter.
Further, the materials used for backside reflectors in low-cost LEDs happen to have a lower reflectivity at certain wavelenghts, casting doubt on the overall effectiveness of the reflectors.
To add to this, using a newly developed, optically clear adhesive instead of the silver-based ones would remove the need for including the reflectors in the first place.

![White LEDs]({{ site.url }}/images/2016-01-30-led-reflectors.jpg)

> _White LEDs. [Image](https://www.flickr.com/photos/oskay/2230059807/) by Windell Oskay / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0/)_

To test the effect of the packaging process on the light output of LED emitters, researchers used [Monte Carlo](https://en.wikipedia.org/wiki/Monte_Carlo_method) simulation software ([*LightTools*](https://optics.synopsys.com/lighttools/lighttools-feature-details.html)) on models of packaged LED emitters and naked LED chips, both with reflectors of varying reflectance.
The simulations showed that the enhancement from better reflectors was not as high in the packaged product as in the naked chips.
The simulation data on the naked chips were also in good agreement with experimental observations, showing strong support for the simulation methods.

The researchers also tested whether using the newer optically clear adhesives in place of the silver-based ones reduced the usefulness of backside reflectors. To do this, they tested three configurations using the optically clear adhesives: (1) LED chips without backside reflectors, (2) LED chips with low-cost backside reflectors (which have low reflectance but are widely used in LEDs), and (3) LED chips with high-reflectance backside reflectors (which are more expensive and hence not used widely).
The data from measurements conducted on blue LEDs and white ones showed that reflector-free chips performed considerably better than chips that used low-cost reflectors, although chips with the expensive reflectors out-performed both others.
Simulations also showed that thicker layers of the optically clear adhesive slightly improved the light output from reflector-free chips, but showed no difference in the chips containing reflectors.

These new results illustrate the importance of experimentally testing manufacturing processes.
The authors of the work show that by modifying the production techniques of LEDs, we can get better-performing devices at even lower costs.

---
Citation:

> Kim, G., Shih, Y.-C., You, J.-P., & Shi, F. G. (2015). Optical role of die attach adhesive for white LED emitters: light output enhancement without chip-level reflectors. _Journal of Solid State Lighting_, 2:11. DOI: [10.1186/s40539-015-0031-z](http://dx.doi.org/10.1186/s40539-015-0031-z)
