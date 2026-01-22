# id_app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
- - - - - - - - - - - - - 
arlight so I made this very rudimentary id app with a qr code.
here's how it works:

## Widgets
# MaterialApp
basecially the root widget of the app. Gives app-level settings like title.

# Scaffold
Just basic visual stucture nothing special. appBar. body, backgroundColor

# AppBar
pretty much the header. Just displays "Student ID Card (real)" to prove its authenticity.

# Card
gives this cool effect where the corners are all rounded upp, and stuff... also has shadows!

# CircleAvatar
Displays a jpg but in a circular manner. uses: "AssetImage('assets/profile.jpg')"

# Text
Shows text visually.

# SizedBox
yeah this just adds some space between widgets

# Image.asset
this displays the QR code that is resized as 200x200.

# other functionallity aka how this works
The MaterialApp starts the app with a very clean and cool design.
IdCardPage uses Scaffold for layout
Then it loads like a gradient in the title.
Card which is centered has a circular pfp, student id (name, ID, grade, School) and A qr code
All elements are arranged vertically using a column and a spaced witj SizedBox

![Screenshot of the app](id_app.png)
