# Face-and-Eyes-Detection-using-HAAR-Cascade-Classifier

### Goal: This mini project detects the face and eyes of famous personalities using OpenCV and HAAR Cascade Classifier.

### Brief Description:
I have used OpenCV and Haarcascade classifier in this project. 


So, what is Haar Cascade? 
It is an Object Detection Algorithm used to identify faces in an image or a real time video. 
The algorithm uses edge or line detection features proposed by Viola and Jones in their 
research paper “Rapid Object Detection using a Boosted Cascade of Simple Features” published in 2001.


The features in Haar Cascade is stored in XML files. I have used "haarcascade_frontalface_default.xml"
for detecting the face and "haarcascade_eye.xml" for detecting the eyes. I have downloaded these files
from Haar Cascade GitHub repository [[link](https://github.com/opencv/opencv/tree/master/data/haarcascades)].
Then, I loaded the image and converted it into gray scale and iterated through face, eye arrays and drawing a rectangle over each face and eye.

### Demo:
![image](https://user-images.githubusercontent.com/75041273/136523789-680c9391-e333-4a31-85bf-d98c79e4cfb6.png)
![image](https://user-images.githubusercontent.com/75041273/136542492-8773175c-8177-4f8f-83e3-08be9dfaa3ee.png)
![image](https://user-images.githubusercontent.com/75041273/136526001-e6c7f45f-c8fa-48e9-ac27-5a2b792e6ba5.png)
![image](https://user-images.githubusercontent.com/75041273/136542570-b012f6a0-5c4a-458a-8afd-227bea5f54e0.png)
![image](https://user-images.githubusercontent.com/75041273/136543537-7ce8c18b-eff6-448d-a880-7799523a8f07.png)
![image](https://user-images.githubusercontent.com/75041273/136543629-3687b217-fd9d-4a56-8983-7ad1784c98d2.png)
![image](https://user-images.githubusercontent.com/75041273/136544051-f620418a-0c53-4940-bc9e-3bf10ba5b094.png)
![image](https://user-images.githubusercontent.com/75041273/136544143-51aa8a35-5caf-4662-9604-4cd35de5731d.png)

##### 1. First create a virtual environment by using this command:
```bash
conda create -n myenv python=3.7
```
##### 2. Activate the environment using the below command:
```bash
conda activate myenv
```
##### 3. Then install all the packages by using the following command
```bash
pip install -r requirements.txt
```
##### 4. Open the .ipynb file inside Jupyter Notebook and run the cells.

##### Make sure to change the directory to the root folder. The folder structure should be same as of this repository otherwise it will throw error. 
