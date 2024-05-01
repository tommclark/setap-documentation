Elements of Implementation
==================

Technologies used
-----------------

Flutter
^^^^^^^^^^^^^^^

The app has been programmed using the Dart and Flutter programming languages. Flutter is a modern and versatile framework for building many different types of apps or programs. It is a cross-platform framework, meaning that it can be used to build apps for both Android and iOS devices, as well as for web-based applications. Our event app is a web-based application, so it can be run in a web browser on any device. The key feature of Flutter that makes the functionality of our app is its ability to have a dynamic state. This means that the page can be dynamically updated and changed based on user input or other events. This is particularly useful for our app, as it allows us to display the event information on the page, allowing the user to interract with it and, for example, book an event.

Dart
^^^^^^^^^^^^^^^^

Dart is the programming language that is used to write Flutter apps. It is a modern language that is easy to learn and use, and it is designed to work well with Flutter. It has many similarities to other popular programming languages, particularly Java, which makes it easy for developers to pick up and learn quickly. This was particularly useful for this project as the developers in our team had encountered Dart before, so we were able to enhance our knowledge of the language and apply it successfully to make the event app fully functional and user-friendly.

Hive
^^^^^^^^^^^^^^^^

Hive is a the key-value based database that we used to store data our Flutter app. It is particularly useful for storing small amounts of data, in our case, event details (name, price, location, etc.). We then use the methods available to us in Dart to retrieve this data and display it to the user, making the app more interractive and responsive.

Firebase
^^^^^^^^^^^^^^^^

Firebase is a system that enables us to store user data. We used Firebase to store data such as the user's email address, and password. This data is stored securely in the cloud, and can be accessed by the app whenever the user logs in. This allows the app to provide a personalised experience for the user, such as displaying their name on the home page, and allowing them to book events. We use Firebase authentication for our login system, which allows us to provide feedback on whether the entered email is correct, and whether the password is correct. This allows us to provide a secure and reliable login system for the user.