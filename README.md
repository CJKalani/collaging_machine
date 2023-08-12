# collaging_machine

Note: this doesn't resize the pics, so the output might be quite large (good for printing - there's a small chance this might produce something that's nice enough to print, with the least possible degredation of niceness.. it should be mentioned that this can handle more than just 2 pic sizes/shapes (eg more than just portraits and landscapes of reversed co-ordinates))

layout() decides which orientation (up/down or left/right) to use as the main axis, and throws up the biggest pics (the expectation is that there will be a somewhat random distribution of dimensions of the individual pics - but the plan for the future is for it to be able to best handle equal-area portraits&landscapes of small sets (eg what to do with 3 irregular images) - so, different functions for eg 3-pics from 4-pics, rather than one large one size fits all approach, as  it currently is, largely.

draw() finds a good way of placing the pics on collage.
