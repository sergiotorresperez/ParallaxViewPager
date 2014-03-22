ParallaxViewPager
=================

This is a library to easily implement a trendy ViewPager with a parallax effect.
More specifically, the idea is that you place a ViewPager, and below it, some layers that are potentially wider than the width of the screen.

As the user swipes the ViewPager, the layers bellow it will move horizontally at a pace governed by the scroll of the ViewPager.

If the layers have diferent widths, a parallax effect governed by the gesture of the user will be created.

Usage
-----

Have a look at the code in the example application included.

In summary:

* In the layout, stack some "layers", and on top of them place the ParallaxViewPager.
* This layers have to be placed in a HorizontalScrollView.
* In java code, get a reference to the layers and add them to the ParallaxViewPager using ParallaxViewPager#add(HorizontalScrollView layer)
* Obviously, the pages shown in the view pager need to have some degree of transparency so that the layers below can be shown.

Developed by
------------

Sergio Torres GaRRaPeTa

