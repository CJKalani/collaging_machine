# collaging_machine

Note: this doesn't resize the pics, so the output might be quite large (good for printing - there's a small chance this might produce something that's nice enough to print, with the least possible degredation of niceness.. it should be mentioned that this can handle more than just 2 pic sizes/shapes (eg portrait and landscapes of the reversed co-ordinates))

layout() decides which orientation (up/down or left/right) to use as the main axis, and throws up the biggest cases (the expectation is that there will be a somewhat random distribution of dimensions of the individual pics).

draw() finds a good way of placing the pics on collage
