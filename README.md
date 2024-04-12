# ===  St. GEORGE Presence detection PROJECT====

 This Project detects the presence of St. George in a photo. The photos where St. George is not present nothing detected by this project. It is based on a ***YOLOv8 model*** trained by data ( Pictures of St. George ). 

 ***Technology used:     Computer Vision, Machine Learning, Neural Network.***
 
 ***Language Used:       PYTHON***
 
 ***Environment:        Jupyter Notebook, Google Colab*** 

# Goal Of The Project:
To detect Accurately If St. George is present or Not in a Picture.

 # Total Process :
   Collect Data ----> Manually Label the Data ----> preprocessing (PASCAL VOC .XML format to YOLO .TXT format)
   ---->Training the model----> Evaluate and Testing the model----> Export the model ----> Running the Streamlit
   App Using the model.
   
 # Approch to Train The model
 The Google Colab link for Training the Model :
 https://colab.research.google.com/drive/1BMNo0wyzvzZ0vvTflUhHZK7AIuczUvfu#scrollTo=JnKX-M-SV7Ja
 
 steps followed in the above process of training:
 1. Downloading Ultralytics to use YOLOv8 model.
 2. importing the Train, validation dataset on working directory
 3. follow the rules for training and evaluation mentioned in refrence [1].
 
 # Running the Streamlit App
 # Step 1 :
      1. Download this repository.
 # step2 :
      pip install -r requirements.txt
 # Step 3 :
      2. streamlit run DetectionAPP.py 

# Results :
![1f22db87f2fa9ba932836d7969d97726](https://github.com/Sid-DevZo/St.GeorgePresenceDetection/assets/91316695/e43cfa66-9bf0-407c-b0e1-0eab0e197634)
![1f22db87f2fa9ba932836d7969d97726](https://github.com/Sid-DevZo/St.GeorgePresenceDetection/assets/91316695/aa746c7f-d6dc-4c7a-9ca4-8ea65210e6f6)
![2f14e0e078283cd5e632e311d76ad890](https://github.com/Sid-DevZo/St.GeorgePresenceDetection/assets/91316695/c9135c8a-183e-4cd7-a3b6-0512ed489103)
![3c3dc164799ebd705ba07d15f9ddc56f](https://github.com/Sid-DevZo/St.GeorgePresenceDetection/assets/91316695/00f51819-66d5-4415-b162-b41d0aea8a56)
![63fde4d3613004979b06e49679c419ab](https://github.com/Sid-DevZo/St.GeorgePresenceDetection/assets/91316695/59a7da8e-93f4-42b2-b0db-79d2378131b3)
![90a4a90aebf219cb5762e0150c687bca](https://github.com/Sid-DevZo/St.GeorgePresenceDetection/assets/91316695/d0658a41-a50c-4bcf-aabe-6ec381234868)

# interface of APP and detection:

**----------------------------------------------------St. GEORGE PRESENT-------------------------------------------------------------------**




![Screenshot 2024-04-11 225013](https://github.com/Sid-DevZo/St.GeorgePresenceDetection/assets/91316695/b2c25d4e-0309-4e6f-840d-9ef435a72ebc)
![Screenshot 2024-04-11 225059](https://github.com/Sid-DevZo/St.GeorgePresenceDetection/assets/91316695/31461eb9-040a-433d-b712-550248d2fd4c)





**--------------------------------------------------------- St. GEORGE is NOT PRESENT-----------------------------------------------**







![Screenshot 2024-04-11 225136](https://github.com/Sid-DevZo/St.GeorgePresenceDetection/assets/91316695/9805998f-5808-47e7-b556-8b28b55ec9c8)
![Screenshot 2024-04-11 225535](https://github.com/Sid-DevZo/St.GeorgePresenceDetection/assets/91316695/2afd0821-7d71-478f-bfd4-4716874e791c)






# Limitation :
 
Detecting the presence of St. George in an image specifically is a challenging task due to the artistic variations in his depiction. However, you can approach this project as an object detection problem with some adaptations. 


**Problem-----There are some picture where this model can't detect St. George and There are Wrongly detected pictures also-----**

Challenges:

1. Variability in Depiction: St. George is portrayed differently across art styles and periods. He might wear various armor, ride different horses, and have the dragon in diverse forms.

2. Lack of Specific Data:  Training data specifically for St. George might be scarce.

 
# Future Works :
It is not a very accurate model because the data used to train the model are artistic which has very different and has many varieties.
Though there are some ways to Improve it.
1. Increasing The dataset
2.  fine tuning data, augmentation
3.  particularly collect data to differentiate between a normal Horse ridder and St. George.
4.  It can be also possible to detect and recognize the spear, the dragon associated with St. George.


# References:
1. https://github.com/ultralytics/ultralytics

2. https://arxiv.org/abs/2102.06529

3. https://github.com/roboflow/notebooks/blob/main/notebooks/train-yolov8-object-detection-on-custom-dataset.ipynb







