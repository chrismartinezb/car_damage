For this to work you must execute the following commands and generate your own weight for the model:


Edit the file custom.py with your own parameter, change epochs and steps.

You can use the current train and test images, or you can add more.

Execute on terminal: python3 custom.py train --dataset=/path/to/datasetfolder --weights=coco , this will generate a file with logs and weights.

With the new weight file execute the notebooks to predict and test.



