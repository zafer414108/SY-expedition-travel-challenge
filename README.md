# SY expedition travel challenge
It looks like you've posted a Flutter Dart code for a mobile app. The code appears to be part of a travel challenge application with various components like pages, animations, and UI elements.

Here's a brief overview of the key components in your code:

PageOffsetNotifier and MapAnimationNotifier Classes:

PageOffsetNotifier is a class that extends ChangeNotifier and is used to notify listeners about the offset and page changes in a PageController.
MapAnimationNotifier is another class that extends ChangeNotifier and is associated with an AnimationController.
# Utility Functions:

Several utility functions like startTop, endTop, oneThird, topMargin, mainSquareSize, dotsTopMargin, and bottom are defined to calculate layout parameters based on the device's screen size.
# MainPage Class:

_MainPageState is the state class for MainPage.
initState and dispose methods are used to initialize and dispose of animation controllers.
The build method returns the main widget tree, including a Stack with various UI elements.
# UI Components:

The UI components include a map image, page view, app bar, images of a leopard and vulture, buttons, labels, indicators, icons, and other elements.
# Providers:

The code uses ChangeNotifierProvider and ListenableProvider for managing state and animations.
GestureDetector:

A GestureDetector is used to handle vertical drag gestures, presumably for scrolling through the pages.
# Animation Controllers:

Two animation controllers (_animationController and _mapAnimationController) are used for controlling animations.


## Design
![design](https://user-images.githubusercontent.com/16286046/64514994-09339100-d2ec-11e9-9fde-2b48aa5c222b.gif)
## Implementation
![ezgif com-resize (3)](https://github.com/zafer414108/SY-expedition-travel-challenge/assets/147662873/57a7a811-3a55-4af9-85c2-838e39ab4d2c)

# SY-expedition-travel-challenge
