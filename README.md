## IDENTIFYING DOG BREEDS FROM IMAGE DATA

Our project seeks to classify dog breeds based on images. This task presents unique challenges because different breeds can have subtle visual distinctions, such as fur texture, ear shape, and size. Our project aims to use a Convolutional Neural Network (CNN) to identify intricate visual patterns to build a robust model that accurately distinguishes among a diverse range of dog breeds. 

This model can have practical applications, such as aiding animal shelters in identifying mixed-breed dogs, supporting veterinary practices with breed-specific health issues, and enhancing user experience in pet focused mobile apps. Through this project, we hope to contribute insights into the strengths and limitations of CNNs in specialized image classification tasks. 




Caroline Hagood, Maggie Welch, Emmanuella Cann


## Software and Platform

This project was developed using Python and the University of Virginia's supercomputer, Rivanna. It includes key functionalities such as data preprocessing and normalization, visualization, merging, splitting, convolutional neural network design, model training and tuning, and model evaluation. A range of python packages were used to achieve these tasks:
   - pandas
   - numpy
   - matplotlib
   - sklearn
   - tensorflow
   - requests
   - gzip
   - io.BytesIO


## Map of Documentation

1. Data
   - data/n02085936-Maltese_dog.csv.gz
   - data/n02088364-beagle.csv.gz
   - data/n02099601-golden_retriever.csv.gz
   - data/n02106662-German_shepherd.csv.gz
   - data/n02110958-pug.csv.gz
   
2. Scripts
   - scripts/new_loadingdata.ipynb
   - scripts/CNN-40.ipynb
   
3. Output
      - output/Accuracy_train_val.png
      - output/Breed_dist.png
      - output/Breed_dist_clean.png
      - output/Confusion_Matrix.png
      - output/Epochs_Accuracy.png
      - output/Maltese_dog.png
      - output/Mean_SD_pixelValues.png
      - output/Test_Accuracy.png
      - output/Train_Accuracy.png
   


## Reproducing Results

- Fork this repository, and clone forked repository in terminal of workspace

  ```! git clone https://github.com/carolinehagood/ds4002-project3.git```

- Install and load packages and all dependencies

  ```pip install -r requirements.txt ```
  
- Download [original dataset](http://vision.stanford.edu/aditya86/ImageNetDogs/), and run [new_loadingdata.py](https://github.com/carolinehagood/ds4002-project3/blob/main/scripts/new_loadingdata.ipynb) script to get image files relating to chosen dog breeds (pug, maltese, beagle, golden retriever, and german shepherd). Since this step is computationally expensive and time consuming, see data folder for [output](https://github.com/carolinehagood/ds4002-project3/tree/main/Data). 

- Run [CNN-40 script](https://github.com/carolinehagood/ds4002-project3/blob/main/scripts/CNN-40.ipynb) to select images, normalize data, visualize, design, build, and evaluate model. 





## References

[1] Deepanshi, “Convolutional Neural Network with Implementation in Python,” Analytics Vidhya, Aug. 14, 2021. https://www.analyticsvidhya.com/blog/2021/08/beginners-guide-to-convolutional-neural-network-with-implementation-in-python/

‌[2] IBM, “What are Convolutional Neural Networks? | IBM,” www.ibm.com, 2024. https://www.ibm.com/topics/convolutional-neural-networks

[3] K. Marshall, “How does epoch affect accuracy?,” Deepchecks, May 26, 2024. https://www.deepchecks.com/question/how-does-epoch-affect-accuracy/

‌[4] Rob Mulla, “Image Processing with OpenCV and Python,” YouTube, Mar. 20, 2022. https://www.youtube.com/watch?v=kSqxn6zGE0c (accessed Oct. 18, 2024)

‌[5] “Stanford Dogs dataset for Fine-Grained Visual Categorization,” vision.stanford.edu. http://vision.stanford.edu/aditya86/ImageNetDogs/



‌
