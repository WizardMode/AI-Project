# American Sign Language Translator

## Introduction

Communication is a vital aspect of our daily lives. For the hearing and speaking impaired, physical communication is crucial, but unfortunately sign languages like ASL are not widely taught, which creates a big language barrier. Sign language involves fingerspelling which is the spelling of words character by character. This can provide a more universal communication mode and it can be more practically translated using visual technologies. For this project, we decided to tackle this problem and create an application that can translate ASL gestures to English in real-time.

## Design Benefits

With the help of the sign language translator that we have created, it is no longer necessary for both individuals to know sign language in order to communicate, thereby solving one of the major issues in this field. Our application will translate hand signs into English letters with a user-friendly interface that anyone can use and understand.

## Overview

The system architecture for the American Sign Language app consists of the interaction between the user, the image classification model, and the output screen. Basically, the classification model requires a hand sign by the user. This hand sign will be captured by the webcam and feed the image to the train model. And the model will output the correct letter and Accuray for the hand sign. The output information will be displayed on the laptop

In the ASL app data flows in the following order. The user performs a hand sing in front of the webcam. The hand sign is fed to the model, by entering the keyboard command scan. At this point, the model classifies the hand gesture to the corresponding letter and percentage accuracy. At this instance two things happened the output letter is saved in a variable char and the letter is display in the laptop's screen along with the percent accuracy.

As the user performs new hand signs the new classified letters get saved to the end of the string variable. This feature enables the user to build a string of characters that can represent a word. If the user wants to delete the whole string of letters, he can simply press c which stands for clear, or delete only the last letter backspace is available by pressing b. In addition, the command indentation is available by pressing s. this allows for the possibility to build sentences.

## User Interface

At launch the ASL app will display on the screen the commands available to the user. Scan and exit are position on the top corners, because they are the most basic commands. Scan is the first interaction the user will have with the app, it predicts what hand sign the user is performing and exit allows the user to close the app. The other commands such as backspace, space, and clear are displayed at the bottom left corner. They become useful once the user has output some letters.

## Technologies and Techniques

- TensorFlow
- OpenCV
- Python
- LabelBinarizer
- Data Augmentation

## Contributors

- Leoanrdo Ramirez 

  (User Interface Design)

  Implement a friendly user interface for the American Sign Language app. And user commands.

- Ashish Katuri 

  (Data Acquisition and Preprocessing)

  Performed data Preprocessing and visualization. In addition to data augmentation to prevent overfitting.

- Syed Ahmad 

  (Trained an Accurate Model)

  Trained a variety of machine learning algorithms on the dataset until a high accuracy was obtained.
