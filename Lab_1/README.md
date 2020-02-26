# Lab One: CNN Visualization

In this lab you will implement the DeepDream architecture for a neural network. A blog post describing the mechanisms behind this can be found here: 

<a href="https://ai.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html" target="_blank">https://ai.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html</a> (Links to an external site.)

- [<strong>10 Points</strong>] Based on the blog post above, create and argue for one reason you might use DeepDream to analyze a CNN visually. Write out this argument in text for the lab using your own words. Alternatively, you can also argue for a counter argument (that is, why this is only artistic, not useful). 
- [<strong>10 Points</strong>] In groups, you should select a convolutional neural network model that has been pre-trained on a large dataset (preferably, ImageNet). These already trained models are readily available online through many mechanisms, including the keras.application package (Inception, Xception, VGG etc.). Explain the model you chose and why.
- [<strong>20 Points</strong>] Manipulate the code from the CNN visualization notebook to implement the DeepDream process. This includes:
	- Using L1 gradient normalization for gradient updates
	- Adding random shifts/resizing in the process (as described in DeepDream)
	- If using code from another source, you must heavily document the code so that I can grade your understanding of the code used. 
- [<strong>20 Points</strong>] Choose an image to seed the DeepDream visualizations and run the DeepDream process. Save out the image at various steps so that you can visualize the iterative process (a video or GIF would be a nice addition). Explain any clues that the iterative process gives for how the CNN discerns different classes, if any. 
- [<strong>10 Points</strong>] Exceptional work: hypothesize another type of noise to introduce in the DeepDream process and implement it. Run the same image through as before and compare/contrast the result. 

Turn in the rendered jupyter notebook (exported as HTML) to canvas. Only one notebook per team is required, but team names must be on the assignment. 