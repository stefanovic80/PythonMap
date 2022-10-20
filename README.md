# PythonMap
First lines of code are an easy-to-understand way to open a map in Python

Then, a .gpx file contained into a gpxFiles/ folder is going to be opened.
Data are supposed to come from a bike tour.
Row data are exported into a pandas dataframe, with the aim of figure out speed over time.
Data are noisy, as can be easily seen into the speeds plot. 
The aim of this project is to analyze such data in order to figure out
a proper algorithm which neglect wrong data and provides a reliable 
calculation of speed as space over time.
Particularly, some of the speed values overtake 100 km/h, which is clearly unreasonable for a bike.
Speed data are acquired via an iterative average over N = 5 times (you
may need to change it over larger values for a better reliability, or a lower value for
more speed values)
