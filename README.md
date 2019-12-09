# Snowflakes as a Service – Generate vector snowflakes for your plotter

This is my first experiment with p5. I wanted to generate a grid of nice snowflakes that I could use with my plotter to make Christmas cards. 

This sketch is optimised to make efficient line art for plotters, not for the beautiful display of snowflakes on screen. 

My workflow is:

* Generate a pleasing field of snowflakes and save as SVG
* Open the SVG in Inkscape, scale and tidy up as necessary.
* Use the [J Tech Inkscape Laser Plug-In](https://jtechphotonics.com/?page_id=2012) to generate a G Code file from the SVG
* Use CNCJS to send the GCode to my plotter
