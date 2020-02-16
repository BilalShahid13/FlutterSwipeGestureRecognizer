# swipe_gesture_recognizer

A simple and lightweight swipe gesture recognizer for a Flutter widget.

## Features

Detects the 4 swipe gestures i.e `swipe up`, `swipe down`, `swipe left` and `swipe right`.

## Getting Started

Pass your widget as the child of this widget. Declare the callback function for the desired swipe direction.

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
