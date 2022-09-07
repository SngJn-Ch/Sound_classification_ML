# Sound_classification_ML
  Implement Supervised learning to classify the sound.

# Why CNN?
   In order to achieve sound classification based on the Mel Spectrogram Array, usually it requires a great level of expertise. However, CNN only requires data and labels with consistency. 
  
# Procedure

1. Change the wav file into Mel Spectrogram Array

  ![image](https://user-images.githubusercontent.com/111392592/185056127-f5ceb378-625d-4ff7-8e8b-237dd27b7a32.png)
  ![image](https://user-images.githubusercontent.com/111392592/185056295-7f35d39c-8112-4a82-a336-a3a62bd21268.png)
  
2. Label the Mel Spectrogram

  0 = Air Conditioner       1 = Car Horn           2 = Children Playing         3 = Dog Bark         4 = Drilling        5 = Engine Idling    
   
  6 = Gun Shot              7 = Jackhammer          8 = Siren        9 = Street Music
  

3. Put Mel Spectrogram Array and Label into CNN

4. Get the Result

  ![image](https://user-images.githubusercontent.com/111392592/188503725-8a5068ef-19b4-4160-bc91-b6668868b26d.png)
 
  

  

# Why Mel Spectrogram?

  <img src = "https://user-images.githubusercontent.com/111392592/188503440-9efd1e6b-fed2-4c60-b31c-a77ce8f93a1b.png" width = "400" height = "300">  <img src = "https://user-images.githubusercontent.com/111392592/185056295-7f35d39c-8112-4a82-a336-a3a62bd21268.png" width = "400" height = "300">
       
  Sound intensity image only has sound intensity by time
  
    Mel Spectrogram has pitch information, and intensity information by time. Furthermore, Mel Spectrogram from **librosa** library also provides a constant return size regardless of the length of data. The constant return size is significant in machine learning since the layer can't handle data of different sizes.
  
  


# Where to get Data
  
  https://www.kaggle.com/code/prabhavsingh/urbansound8k-classification/notebook
  
# Reference link

  https://www.kaggle.com/code/prabhavsingh/urbansound8k-classification/notebook
  
  https://medium.com/analytics-vidhya/understanding-the-mel-spectrogram-fca2afa2ce53
  
  
