# Setup guide (README)

**PAWGOTCHI**
Pawgotchi is a virtual pet game where players can adopt and name their own Cat, Dog, or Fox. Players can take care of their pets through three main actions such as Play, Eat, and Sleep. The game also displays the pet's current hunger, happiness, and energy levels, changes its appearance depending on its condition, and records every action in the status log.

**Prerequisites**

- A computer with a supported Java Development Kit (JDK).
- Apache NetBeans or another Java IDE.
- The project source files in the package com.mycompany.finals.
- The pet image resources, if the image display feature is to be used.

**Build and Run**

- Open the FINALS Maven project in Apache NetBeans.
- Make sure the Java files are under com.mycompany.finals.
- Ensure the pet and background images are in src/main/resources/images/.
- Check the Oracle database connection settings in DatabaseConnection.java.
- Select Clean and Build.
- Run FINALS.java to open the Main Menu.
- Choose a pet, enter a name, and test the Play, Eat, Sleep, and Quit buttons.

**User Guide**

- Launch the application to open the Main Menu.
- Select Start / Load Pet.
- Choose a pet species: Cat, Dog, or Fox.
- Enter a pet name. Blank names and names containing special characters are not accepted. Names must contain letters only and have a maximum of 20 characters.
- The system checks for an existing pet with the same name. If found, its saved information is loaded otherwise, a new pet is created.
- The game window displays the pet's name, species, Hunger, Happiness, and Energy. Newly created pets start with all three stats at 15.
- Use Play, Eat, and Sleep to interact with your pet and update its stats.
