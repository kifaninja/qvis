# qvis
Quantum Vector Illustration Software ! An All-purpose artistic vector illustration sofware made with love, Qt and a lot of QGIS algorithms so that your maps (and all other beautiful works) become worthy of the Louvre's collections.

Welcome to the QVIS main repository ! Or as I like to call it in its current state, more or less an empty spreadsheet, or a preprepreprepre-Alpha.

# The why
I'm a student in geography/cartography, and QGIS is my main work software. However, as powerful as QGIS gets, it still doesn't have the most powerful post-prod functionalities, which leaves me and my fellow classmates dependent on a very niche software calles Adobe Illustrator. This isn't free, and even less open-source. As a result, we're forced to deal with Adobe's anti-consummer policies and we can't afford the software outside of a specific room in our university. Not fun. But the good news is that QGIS is based on Qt, is extremely portable and already has an awesome load of functionalities which could, in fact, also be used for general purpose vector edition. So, why restricting it to maps ? As a matter of fact, you can already use QGIS to make illustration stuff... because the definition of fun in software is all about not using it for its original purpose :)

Thus, QVIS aims to pack those QGIS functionalities + many more in an independent software, so you can :
- Do any kind of art on it, and not just maps, without requiring QGIS on the side
- Edit QGIS maps instantly in live cross-compatibility, allowing you to switch dynamically between both software, as well as turning your maps in the next Van Gogh completely for free

Why not just use another alternative like Inkscape ? Inkscape is really good, but it's made on Gtk, and thus I've had a lot of issues with incompatibilities between Gtk and Qt (not just with QGIS... we all know the problems with svg formating, and don't get me started on issues with other Qt based software like KDE Plasma... I've had my fair share of crashes). Inkscape is also very different from Illustrator, and as yet another kid trapped in Adobe dependence, I'm about as competent with it as wet cardboard would be if you gave it a keyboard). On a more cartographer-minded vision Inkscape also doesn't have the level of integration with QGIS that QVIS aims to have. Thus, as a cartographer, it makes even more sense for me to want a software like QVIS which works even better than just out-of-the-box together with QGIS. 

# What you should find in here if this were a finished product

- A friendly customisable UI based on Qt which by default tries to mix QGIS and Adobe Illustrator UIs, so you're not lost if you know any of those, and already fluent if you know both
- Illustrator-like keyboard shortcuts, so you don't need to learn everything again
- An alternative to most of Illustrator CC2019 effects and functions; those which already exist in QGIS will be used here, for maximum compatibility between both software
- Possibility for plug-ins
- QGIS APIs and libraries, so if you're editing maps from QGIS, you'll be able to correct them all on the spot (though of course, it's better to correct them
- And much more to be added whenever ideas pop up
