textloc
=======

textloc generates a location for a bit of text. It was created to 
tag tweets with random locations for Noe Alerts:
https://twitter.com/Noe_Alerts

Usage:

    $ textloc --kml "textloc example.kml" "Blah blah Wilder Ranch."
    36.9795928148,-122.0876845766

Any polygons named in the KML file are potential locations for the
text. textloc will choose a random one whose name is found in the
text, then generate a random point in the polygon.

Here's the map that exported "textloc example.kml":
https://www.google.com/maps/d/edit?mid=zFuwbvu-ufqE.kFWZ6c240y8Q&usp=sharing

textloc only supports KML, not KMZ.
