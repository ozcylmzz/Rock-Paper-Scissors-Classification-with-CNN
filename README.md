# Rock Paper Scissors Classification with CNN

The “Rock Paper Scissors Classification with CNN” project is a mobile-based application project that analyzes and appropriately classifies the image taken from the phone camera. Within the scope of the project, the application will decide which move the image received from the user corresponds to the format of rock paper scissors. In addition, it will generate a random move and determine the winner of the game.

The data set includes images that a project developer shares online to encourage handgesture recognition and photos that we take has been created. A total of up to 2500 photos have been increased to 10201 with data replication algorithms. 60% of the total photos in our data set are reserved for training process, 20% of course tracking with validation and 20% for testing the accuracy of the model at the end of training.

For our project, we need to determine which type of move belongs to our CNN model of rock paper scissors images to be taken from the user via the phone camera. For this, a CNN model with photos of rock, paper, scissors was trained. Keras model file that works with high accuracy on the desktop can be used on the mobile platform , their weights had to be saved and converted to the file type “.tflite” with Tensorflo. Alternate conversion operations found were implemented via Google Colab due to Tensorflow release and developer platform incompatibilities.



Comparison of model.h5 and model.tflite



Project will be developed on the android platform. So we decided to use SQLite.  3 tables in database will be stored:
1 USERS: Users information will be stored.
2 SCORES: Users points table.
3 GAMES: Users have previously played games is the table that holds the history.



Register and Login screens

 











Main Screen



Game History







Result of Game


