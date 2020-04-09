# Neural-Style-Transfer

This is the results I get following the tips given by the Neural Style Transfer article: https://towardsdatascience.com/how-to-get-beautiful-results-with-neural-style-transfer-75d0c05d6489, which I have modified to add the incorporation of several style images (e.g several paintings) instead of a single one. 

The network therefore learns the style of an exponentially weighted average of the style images, and ultimately keeps the style image which matches the most with the image to be modified.
