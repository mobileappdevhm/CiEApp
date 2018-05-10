Cross-cutting Concepts 
======================

**User Experience concepts (UX)**
-----
***User Interface***

The user interface of the app should look as native as possible, while still using Flutters opportunities for shared design. This would include not using elements like i.e. a drawer menu as it is only native to Android and not on iOS. An alternative would be a Bottom Navigation Bar.

***Localisation***

Flutter offers the opportunity to easily implement translations. The app should be developed in English and offer the opportunity to use a German translation. Further translations could be added later on.
 
 
    
**Safety and security concepts**
- 
***Safe Storage***

Due to targetting multiple operating systems, it is not possible to securely store data using Flutters own possibilies. Therefore, native code is necessary to store whatever authentification method data we need to authenticate with Nine. Please make sure to use storage especially designated for sensitive data. (On android: using the apps private directory, on iOS: using Keychain)


**Architecture and design patterns**
-

***Model-View-Controller***

If at all possible, please adhere to the Model-View-Controller Design pattern.

Otherwise, please adhere to the guidelines outlined in Architectural Constraints.

"Under-the-hood"

**Development concepts**
-
***Test-Driven Development and Continous Integration***

If possible, please use Flutters test suite to write tests for the app, to see if displaying data works in the way that it is expected. It is not neccessary to check against specific strings, but your tests should give a good overview of the apps behavior. If possible, please test your native code as well.
Please use CI to test your app as well, and, if successful, add your Apps apk file to the release tag in Github for easy overview.

