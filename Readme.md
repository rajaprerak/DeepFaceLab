#### DeepFaceLab - Software for creating deepfake videos
[Google Colab Project Link](https://colab.research.google.com/drive/1AxtdZNWsqDoJRzN2okuPr_gVEJkK6otu?usp=sharing)

#### Main Highlights of the project
* Clone project
* Upload your data source and destination files.
* Train on your dataset
* Get resultant deepfake video.

#### Steps included in project
1. Clone DeepFaceLab github repository.
2. Upload source video and destination video.
    * Upload zip files of video on your google drive.
    * Write zip file name on file_name textbox.
    * This section will generate workspace folder for your dataset which will store further processed images. And during training our model will read all images from the workspace folder.
3. Extract frames of video
    * This option will also like you things like frames, image format,etc.
4. Remove noise from frames.
5. Detect faces from frames.
6. Align and Enhance the face data.
7. Train the model
    * There are many settings which you can tweak while training. If you want to just skip particular setting. Just press enter.
8. Get output
    * Output will be stored in workspace folder.
    * Output file name will be 'result.mp4'
