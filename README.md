peda-output-monitor
===================

Using a webpage in a fullscreen browser. Or something similar. Also displays the time in the style of a Braun clock, brought to you by Dieter Rams or a simple digital clock.

The Output receiver will receive simple http, so every logic plugin can decide on itself how it displays the data. 

The default-view will be the clock.
As soon as an output-message arrives, the data will blend over the clock. 

# Colors
The colors will only be black and white (maybe also changeable, but only a foreground an a background color).
At day, the foreground will be black and the background will be white. At night, those things get switched out.

# Helper classes
logic plugins who use html will get help with some helper classes. At the moment, those should be:
* text-small
* text-medium
* text-large
* pull-right
* pull-left
* list (with border etc)
