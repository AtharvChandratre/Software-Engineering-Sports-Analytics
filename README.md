# Software-Engineering-Sports-Analytics

Software Engineering Course Project (BITS Pilani K. K. Birla Goa Campus) IS F341

Made By: <br>
Atharv Chandratre - 2017A7PS0009G<br>
Aditya Ketkar - 2016A7PS0081G

The whole code base is extensively commented for the user to understand.<br>
Please find the presentation we made as a demonstration [here](https://drive.google.com/open?id=1iUKAe-FciQwLEO7u4xrviWrpK8NAjZwY).
## Dependencies:

Python 3, YOLO Object Detection Algorithm, ImageJ

## Instructions for detecting player using YOLOv3:

1. Open the Jupyter Notebook 'Yolo_Darknet_Video_Refactored.ipynb' in Google Colab.
2. Run the cells in the notebook upto the point where the code says it will begin analysis (will take around 10 minutes).
3. Give it the required Google Drive Access Permissions when prompted.
4. Choose the video you want to run analysis on, and save it as "input.mp4" into the MyDrive/darknetProject/darknet/data.
5. Now run all the remaining cells.
6. The output file will be generated and stored into the MyDrive/darknetProject/darknet/data folder.

## Instructions for Analysing and plotting player movement data using MatPlotLib:

1. Open the Jupyter Notebook 'plotPlayer.ipynb' present in plotSE folder in Google Colab.
2. The input to this notebook should be the .csv file obtained from previous player tracking module.
3. Run the whole notebook. The output plots of player position for each frame is stored in the folder 'points'
4. Use ImageJ to combine all the frames to one video, typically 30 FPS.

## Workflow Overview:
The received CSV file from YOLOv3 will contain all the required data points of the centre of the player whose positions are to be analysed. We can infer any analysis we want using MatPlotLib.
We can create the density plots, as well as the point plots, and then combine all the point plots into the movement video using ImageJ.
