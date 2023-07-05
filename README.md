# Elect-Application
This is a project for the course Human- Computer Interaction. It is an android application (we used Android Studio), developped in Dart, using Flutter. Only the UI part of the app is developped; there is no database or internal algorithm and only dummy data is used.
A link to a Figma page, where the prototype of the app is presented, is included.

The app is called 'Elect'. It is a social media, where the basic user-to-user interaction is throuh polls. To be more specific, each user maintains a profile and has a list of followers and a score of points, in the form of 'gems'. The user is supposed to upload dilemmas he is facing in his everyday life, i.e. a photo, a question and the possible actions to take in this dilemma. His followers then have a certain amount of time to vote for a specific choice in the poll. Afterwards, the user has to upload a photo, showing him doing the thing his followers voted for and they can react to this photo with a 'heart' reaction. Depending on the number of followers, votes and hearts, the algorithm calculates an amount of 'gems' to be added to the user's score. Users with higher scores are promoted more to other users, in order to increase their followers. The user has a profile page, where he can see his previous polls, upload a new one, or upload a resolution to a current poll. He also has a main page, where he can see active dilemmas or resolution posts of the people he follows.



HOW TO RUN:

Download android studio and create a device. Download the repo and perform 'dart pub get' in IDE terminal. Instead of Windows, select in the IDE the device you created and wait for it to start. Then run the program (this might take a while the first time). 
You can also see how the app works in your android device: connect the device with a USB cable, enable Developer Options and USB Debugging from Settings, select as a devive from the IDE your phone and run the app.
