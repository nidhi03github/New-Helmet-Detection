# New-Helmet-Detection
Nidhi Subbmission



To run the files :
If GPU is availaible,code can run on anaconda jupytor notebook.
Download following datasets from kaggle:
1. hard-hat-detection
2. haarcascades
3. lfwpeople
4. My-training
Then run on Jupitor notebook.  

Else
1. We can import above dataset in kaggle account 
2.Turn its GPU on and then run the code in notebook of kaggle

--------------------------------TASK 2---------------------------------------------------------------
 
1.	What type of object detectors are there? 

       a)	Fast AI object detection has been used with anotated dataset (using PASCAL VOC ) to extract hats 
       b)	Histogram of Oriented Gradient (HOG) feature descriptor for object detection
       c)	Convolutions.
	
2.	What are some SOTA methods available?

       a)	RetinaNet :
         The RetinaNet is a one-stage object detector, meaning that the localization and classification tasks are done at the same time. The main contribution given by FAIR is            the loss function of the network: The Focal Loss. Lower loss is contributed by “easy” negative samples (bounding boxes where there is no object) so that the loss is              focusing on “hard” positive samples (bounding boxes that actually contains boxes). The focal loss solves the class imbalance issue of one-stage detectors :
               This network consist of :
       •	A feature extractor (usually CNN) to obtain a feature map of the whole image. We used a Resnet101 pretrained on ImageNet as backbone.
       •	A feature pyramid network (FPN) to obtain high-level features at each scale, in order to get objects from different sizes and shapes. It uses skip-connection to                 establish a link with the layers from the backbone.
       •	2 sub networks: One that classifies the bounding-boxes at each level and another that gets a more precise version of their coordinates


3.	 What are the datasets that are publicly available? 

       1.	hard-hat-detection
       2.	haarcascades
       3.	lfwpeople
       4.	My-training 


4.	Can we create our own dataset?

        We can create our own dataset using vedio scene followed by facedetection and then croping the face.

5.	What are some software or techniques that we can use to label the dataset?

        Pascal Voc , haarcascades

6.	Has someone done similar work in this area?

        Yes , lots  of work has been done and links are attached for same in next answer.

7.	What are some open-source codebases that people reading the document can refer to?

        1)	https://github.com/topics/helmet-detection
        2)	https://pythonawesome.com/helmet-detection-on-construction-sites/
        3)	https://www.mathworks.com/matlabcentral/fileexchange/72381-helmet-detection-by-deep-learning
	
8.	Provide more links to blogs, articles, videos, etc. to learn more about the topic.
        1)	https://www.fast.ai/
        2)	https://www.researchgate.net/publication/344109522_Live_Helmet_Detection_System_for_Detecting_Bikers_without_Helmet
        3)	https://medium.com/@vijaysingh_60587/train-your-own-custom-model-for-helmet-detection-object-detection-using-yolo-f53a48066d7a





Warm Regards
Nidhi

