# flutter_book


## Work breakdown structure
![alt text](./docs/images/FlutterBookWBS.PNG)


### Dependencies
        dependencies:
        flutter:
        sdk: flutter
        scoped_model: 1.0.1
        sqflite: 1.1.2
        path_provider: 0.5.0+1
        flutter_slidable: 0.4.9
        intl: 0.15.7
        image_picker: 0.4.12+1
        flutter_calendar_carousel: 1.3.15+3
        cupertino_icons: ^0.1.2

    There are quite a few plugins here, and you will, of course, learn a little about them
    as they are encountered in the code, but just to give you a basic overview, they are
    • scoped_model – This will provide us a very nice way to manage state
    throughout the app.
    • sqflite – Since data storage is a requirement of this app, we have
    to choose how to do so, and I decided to go with the popular SQLite
    database, which this plugin provides us access to (and no, the name
    is not a typo!).
    • path_provider – For the contacts, we’ll have to store the avatar
    image, if any, for the contact, and SQLite turns out to not be the best
    place to do that. Instead, we’ll use the file system. Each app gets its
    own documents directory where we can store arbitrary files, and this
    plugin helps us get to that.
    • flutter_slidable – For contacts, notes, and tasks, the user can slide
    them on the list screen to reveal a delete button. This is a widget that
    gives us that capability.
    • intl – We’ll need some date and time formatting functions from this
    since some of our entities deal with dates and times.
    • image_picker – This plugin provides the infrastructure the app will
    need to let the user add avatar images for contacts from either their
    gallery or by taking a picture with the camera of their device.
    • flutter_calendar_carousel – This widget provides the calendar
    and functionality for the appointments list screen.
## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
