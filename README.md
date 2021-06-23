# Fast-Oriented-Text-Spotting-FOTS
FOTS is used for faster text detection and Recognition 

Text detection in natural scenes is a challenging task and more complicated than text extraction in document text images, where there is a clear distinction between background and foreground and each character is separated from the context. In natural scenes, text can be appear in numerous states; dark text in light background and vice versa, with wide variety of fonts, even for characters of the same word, part of words can be overlapped by object of the environment and as a result the detection of these parts can be impossible. Other factors, like camera settings, may cause blurry images or perspective distortions. A major factor that makes the text detection and recognition in natural scenes difficult, are the illumination conditions. The light of the environment may create reflections on the text surfaces, object of the environment may cast shadows on the text surface, and also the intensity of the objects depends on the light source.				                                          
Some of the applications are Passport recognition, automatic number plate recognition, converting handwritten texts to digital text, converting typed text to digital text, scene text detection etc.

![image](https://user-images.githubusercontent.com/60176731/123038865-cb472480-d40e-11eb-9dbb-cd03e7335afc.png)

Data Sources : 
Numerous datasets are available for scene text detection and recognition Since ICDAR 2015 dataset is not enough to train FOTS end to end model, as suggested by research paper, hence we are using following datasets for our problem

1.	SynthText Dataset : This is a synthetically generated dataset, in which word instances are placed in natural scene images, while taking into account the scene layout.The dataset consists of 800 thousand images with approximately 8 million synthetic word instances. Each text instance is annotated with its text-string, word-level and character-level bounding-boxes. This is useful for Exploratory Data Analysis and help our Machine learn details of scene texts. 
2.	ICDAR 2015 : This is real world dataset having images from wearable cameras. This dataset is comparatively very small (only 1000 training images) as compared to SynthText dataset.
We are directly downloading the dataset in the notebook itself

All the ipython notebook can be run independently

Text Recognition to be added
