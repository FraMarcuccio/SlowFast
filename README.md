# SlowFast
Video categorization with customized versions of SlowFast

## Index
1. [What is SlowFast](#what-si-slowfast)
2. [How to run the code](how-to-run-the-code)

## What is SlowFast
SlowFast is a Neural Network which permise to classify a video with a model created after a traning. 

## How to run the code
For simplicity and to avoid collision with different versions of libraries, run the code on the Google Colab platform.
1. First, upload the dataset you want to use on Google Drive and create the subfolders, one for each category of videos in the dataset.
2. Upload the "code" folder to the colab folder in the Drive
3. Upload the .ipynb code to Google Colab
4. Connected to the Drive dataset
5. Add the paths of the folders in the drive, note that the code indicates "path" as the input path and "res" as the output path
6. Each section of the code will have as input the output path of the previous section, so change them appropriately according to your needs
7. In the "train network" section, move to the colab folder where you entered the code
8. In the "testing" phase the "path" path will contain the folder with the weight model created in the previous phase, do not change the selected file but only the path
9. Execute each section of the code one by one
10. See the results
