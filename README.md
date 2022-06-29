# Backend, Sprints 1-3: BloomBurger Kiosk Code-Along Setup Instructions

### Description of BloomBurger and Goals

Each of the Unit 1 Code-Alongs will be implementing different functionality into the *BloomBurger* project. Each session will solve different problems of the BloomBurger backend code, ultimately ending with a project which can be utilized in a variety of different applications.

What is *BloomBurger*? This is a food ordering platform to be used by a fictional company, *BloomBurger*, which is selling drinks, fries, and burgers (vegan *"Bloomer"* and non-vegan). Each of the products will have prices with different options and the backend part of the program will ultimately take in separate parts of an order, keeping track of the entirety of the items of the order including any options, and handling the final receipts, discounts, and payments.

### Setting up the Project

Clone this project to your harddrive then open on IntelliJ. Recommended location: BloomTech/Unit_1/CodeAlong.
Each Code Along is a continuation of the prior project, but separate repositories exist for each to ensure a clean, working starter project.

The project will use Processing so make sure your Java 1.8 JDK is loaded on IntelliJ.

If you need additional instructions for cloning a project please refer to the lessons on Git (Sprint 1, Module 2) or the Testing Your Environment section under the Tech Check on the Backend Orientation course.

### Test your Setup

After cloning your project and opening it in IntelliJ open the **App.java** class. You can quickly find this by typing "*shift-shift*" and then "*App*".
The Kiosk can be run in three different ways:
* GUI - Graphical User Interface with buttons to interact with
* TEXT - A console Interface, using regular print statements and typed in user input
* FILE - An automated interface which loads the details of an order from files

The value shown here can be changed from .GUI to .TEXT or .FILE to run a different interface:
``` java
private static final KioskType KIOSK_TYPE = KioskType.GUI;
```

Test your setup by clicking either of the green play buttons in gutter on the App class and choosing ```Run 'App.main()'```.

### CodeAlong Goals:

Each CodeAlong will have you clone a separate project and each will include the same beginning README as this, but with separate goals identifying what you will be working on during that CodeAlong.


