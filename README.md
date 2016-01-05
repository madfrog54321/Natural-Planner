# Natural-Planner
A goal/project tracking Android app

This app's idea came from David Allen's Natural Planning Model. This TEDx talk he gave explains the idea. http://tedx.amsterdam/2014/12/david-allen-getting-things-done-natural-planning/

The main goal of this app is to help users make a goal/project into a easy to follow to-do list, or "action list". The app needs to provide a easy to use interface for the user. The visual design is recommend to be inline with the Google Material Design guidelines.

These guidelines can be found here:
https://www.google.com/design/spec/material-design/introduction.html

This design system will provide a coherent experience for the user.

A simple starting interface needs to be created. This simple interface should only inplement the basics of the Natural Planning Model.

It is recommend that the interface's activity should not be the MainActivity class. The MainActivity class should open another activity to hold the interface, to allow later modifications to the app's startup order. Example code:

Intent intent = new Intent(this, HomeScreen.class); //create intent

startActivity(intent); //launch interface activity

finish(); //destroy main activity
