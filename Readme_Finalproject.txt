In order to run the training and testing file, 
you first need to download the training(400 images) and testing(250 images) dataset. (Dataset.zip)
Annotation is provided in the file annot.txt 
Each line in the file contains name of the image followed by the list of
annotation rectangles in the [xmin, ymin, xmax, ymax] format.

Also, if you want to run the test file without training the model, 
you can just load the trained parameters (recent.pth) from the training model.

When you are trying to run this on google colaboratory, make sure the path of the data and the model is correct.

When running a model with a different dataset, you must first make an annotation file with the box coordinates.
Otherwise the model won't work.

Have fun!

27.02.2021 Taehyoung Kim

