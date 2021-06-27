# cs360 Dylan Jeffery

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

This application required a login screen with password functionality, and mainly an inventory functionality that allowed event tracking of quantities of goods consistent across multiple users, some with the capability of modifying quantity values.  The intention was to provide users with a method of tracking an inventory of supplies, as well as receive notifications when supplies are running low.

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

My intention is to bring this application to life with several screens and fragments.  A login screen, a register screen (to mostly handle a user mis-typing a password when setting one).  This is handled in the re-type password field.  As well as the inventory screen, which displays the contents of a database of items.  Either a fragment or a pop-up box will handle inventory+ permission requests.  Unfortunately my designs were unsuccessful as I ran out of time.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?
My initial step was to think about the user requirements, and how I would translate them into individual screens and services/activities.  Requirements are broken down into smaller problems that can be addressed individually.  Once a rough design exists you try to bring functionality to each piece one step at a time.  SQL is used to handle databases, and an intent is used to move between login and inventory.  These are all important methods and steps when developing Android applications and are practices I will use in future application development.

How did you test to ensure your code was functional? Why is this process important and what did it reveal?
To ensure my code was functional I would constantly test during development.  Running the application on the Android emulator revealed issues that left my trying new iterations of the program.  I ended up running out of time during development but I intend to finish this project on my personal time after next semester.

Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?
As I am not finished, I will be adding to this section.  The first major challenge came from implementing SQL to create a user login system.  This required implementing a User() class to define qualities that a user has, to define the contents of our first database that handles login authentication.  I plan to use intents to move to the inventory screen that handles the main user experience.  I am sure I will need to make a new iteration of the screen proposed in the design phase to display a clean grid of the inventory contents (to make the grid sit properly with the buttons there was an odd column layout).

In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
I think that my best aspect so far is that my login screen looks great, and the database for Users is set up and well-designed although not entirely implemented yet.
