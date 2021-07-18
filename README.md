# SoC2k21 Facial Recognition Project
***Repository for SoC project done in Summer 2021***<br />
Theme : to develop a face recognition app capable of detecting all faces included in the image, cropping the faces and extracting their features, and comparing the faces for clustering pictures with same faces. The app would also be capable to detecting faces and objects in videos.
<br />
## Phase 1
- Learnt basics of Python and working with Google Colab. [Link to Python tutorials](https://www.youtube.com/watch?v=QXeEoD0pB3E&list=PLsyeobzWxl7poL9JTVyndKe62ieoN-MZ3);  [Link to Google Colab tutorial](https://www.youtube.com/watch?v=i-HnvsehuSw&t=359s)<br />
- Setted up Anaconda with help from *Python for Deep Learning* course and learnt working with Jupyter notebooks
- Learnt basics of Machine Learning from *Python for Deep Learning* course.
- Learnt to work with NumPy, Pandas and Matplotlib libraries. Did exercises in the course folder related to Pandas and Matplotlib. Practice notebooks uploaded. 
###  Checkpoint 1 (11th April, 2021)
- **Task 1** : Learnt to import  pandas and numpy and used library functions to extract information about the dataset
- **Task 2** : Learnt to use Matplotlib, tried to get statistical information about the different columns of the dataset, also used various library functions to plot graphs such as histogram and box type.
## Phase 2
- Learn basics of computer vision and working with OpenCV. Learnt how images are stored in computers, and how OpenCV functions can be used to edit the images. Did a mini-project of the course on creating live pencil sketches. Jupyter notebook uploaded. 
###  Checkpoint 2 (8 June, 2021)
- **Task 4** : Used OpenCV and pre-trained Caffe models to detect age and gender from live webcam feed. Models can be downloaded from [here](https://github.com/pydeveloperashish/Age-and-Gender-Recognition/tree/main/models)
- **Task 5** : Similar to task 4, used OpenCV and pre-trained Caffe models to detect age and gender on a youtube video. The same models were used as in task 4. They can be downloaded from [here](https://github.com/pydeveloperashish/Age-and-Gender-Recognition/tree/main/models)
## Phase 3
- Learnt how facial recognition works by training the neural network using 128-d vector measurements.
###  Checkpoint 3(18 July, 2021)
- **Task 7** : Final application.
  - Trained neural network on images downloaded from the web through construction of facial embeddings using the dlib library. 
  - The application allows us to download online images to create a database or we can provide the database ourselves. 
  - We create 128-d embeddings for each face in the dataset and then use that to recognize the faces in images and videos.
  - Application can also create a montage of similar faces in the database, this can be used to sort and rename the files in the database.
  - The application also has object detection. Application uses pretrained YOLO model to detect objects in images and videos. 
  - The video used for testing was [this](https://drive.google.com/file/d/1r7A5Nnbad-t68xwXWXt8Jjy9ji8vmI_5/view?usp=sharing) and [this](https://drive.google.com/file/d/1BkNqGltWjPpISnan32VFT-giJOhFkBJm/view?usp=sharing) is the result I got.
  - For object detection, the model can be downloaded from 
