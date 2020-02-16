# swipe_gesture_recognizer

A simple and lightweight swipe gesture recognizer for a Flutter widget.

## Features

Detects the 4 swipe gestures i.e `swipe up`, `swipe down`, `swipe left` and `swipe right`.

## Getting Started

To enable this widget, pass your widget as the child. Declare the callback function for each swipe direction and you are good.

```dart

    SwipeGestureRecognizer(
        child: MyWidget(),
        onSwipeLeft: () {
            // DO STUFF WHEN LEFT SWIPE GESTURE DETECTED
        },
        onSwipeRight() {
            // DO STUFF WHEN RIGHT SWIPE GESTURE DETECTED
        },
        onSwipeUp: () {
            // DO STUFF WHEN UP SWIPE GESTURE DETECTED
        },
        onSwipeDown() {
            // DO STUFF WHEN DOWN SWIPE GESTURE DETECTED
        },
    );

```
