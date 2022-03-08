To convert a colored image to grayscale, we need to apply some function on each pixel/point of the image such that we get a single value which will represent the shade of gray at that pixel. There are three methods:

1) Lightness Method: The lightness method averages the most prominent and least prominent colors: (max(R, G, B) + min(R, G, B)) / 2.

2) Average Method: The average method simply averages the values: (R + G + B) / 3.

3) Luminosity Method: The luminosity method is a more sophisticated version of the average method. It also averages the values, but it forms a weighted average to account for human perception. We’re more sensitive to green than other colors, so green is weighted most heavily. The formula for luminosity is 0.21 R + 0.72 G + 0.07 B.
