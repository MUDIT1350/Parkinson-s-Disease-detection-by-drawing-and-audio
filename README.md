Prerequisites and steps to run the repository for real time application -:

1. Unzip Image_Dataset
2. Run Voice_Detection on Google Colab , upload all .wav audio files want to run in it
3. Run Drawing_Detection on Visual Studio , download tensorflow in the that folder 

How does the repository works for real time application?

Drawing_Detection model creates parkinson_disease_model.h5 using libraries tensorflow.keras.models , tensorflow.keras.layers , tensorflow.keras.preprocessing.image
Voice_Detection model uses Random Forest Classifier and libraies pydub , pandas , numpy
