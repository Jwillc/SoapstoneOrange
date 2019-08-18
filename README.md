# Soapstone Orange

This repositiory is dedicated to the ongoing work of Soapstone Orange. The source code for the app will not be available here. I'll be using this to post about what I'm working on within the app and users can post issues or feedback for the app in the issues section.

https://github.com/Jwillc/SoapstoneOrange/issues

# What is Soapstone Orange?

Soapstone Orange is an app inspired by the Dark Souls "Soapstone" messaging system. Where players in the game can leave messages in the world for other players to see. These messages can be rated up or down. Messages can have many purposes such as to warn a player or to trick them and many other uses.

In the app users can leave soapstone like messages in the real world using the built in message builder similar to that in Dark Souls. Messages like "I did it!" on top of a mountain, or funny messages like "Resignation Ahead" while at work.

Users can only read messages when they're close enough in the real world from where the message was created and placed. Messages can be rated up or down and the app will keep a list of all the messages users have interacted with, as well as a list of all the users created messages and it's ratings.

Ratings a permanent, users can not rate their own messages but they can delete them. To avoid over clustering the map with Soapstone messages, users will only be able to place one message within a given area at a time. 

The app uses Google Maps API's and Firebase to store and sync data. 

# Why do I need an account?

In order to keep track of which messages belong to which users we require that users create an account. No information will be shared and it's completely okay to use fake credentials when signing up. We do not require email varification.

# Progress

We have notifications! Using Firebase functions users will now be notified when one of their messages gets rated. This will work even if the app is closed.

Now considering adding an achievements system. Example: User places a message at high elevation, they will receive the "Sky High" achievement. Achievements like this based on location, I think that would be fun.

Also need to deal with app crashes.

# Feedback 

Feedback is not only very much appreciated, it's a vital part making the app a success. If you have feedback or issues please share them here: https://github.com/Jwillc/SoapstoneOrange/issues
