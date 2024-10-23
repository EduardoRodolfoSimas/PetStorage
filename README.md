Overview
The Contoso PetFriends app is a simple console application designed to manage information about pets available for adoption. It allows you to list, add, and edit pet information during runtime, but the data is not persisted after the program ends.

Features
List all current pet information
Displays all pets with their ID, species, age, nickname, physical description, and personality.

Add a new pet
Allows the user to add a new pet by specifying details like species, age, physical description, personality, and nickname.

Ensure pet ages and physical descriptions are complete
(Feature in development)
Ensures that all pets have their age and physical description filled out.

Ensure pet nicknames and personality descriptions are complete
(Feature in development)
Ensures that all pets have their nicknames and personality descriptions filled out.

Edit a pet's age
(Feature in development)
Allows editing the age of an existing pet.

Edit a pet's personality description
(Feature in development)
Allows editing the personality description of an existing pet.

Display all cats with a specified characteristic
(Feature in development)
Lists all cats that match a given characteristic.

Display all dogs with a specified characteristic
(Feature in development)
Lists all dogs that match a given characteristic.

How to Use
Upon running the program, you'll be greeted with a main menu that offers numbered options. To select an option, enter the corresponding number and press Enter.

Example
To list all available pets, enter 1 and press Enter.
To add a new pet, select option 2 and follow the on-screen prompts.
Adding a New Pet
When you choose to add a new pet:

Enter the species (dog or cat).
Enter the age of the pet (or "?" if the age is unknown).
Provide a physical description (size, color, etc.).
Provide a personality description (behaviors, traits, etc.).
Enter a nickname for the pet.
You can keep adding pets until the array reaches its maximum capacity of 8 pets.

Data Structure
The app uses a two-dimensional array ourAnimals to store up to 8 pets' information. Each pet's data is stored across the following fields:

ID: Unique ID for each pet (auto-generated).
Species: Either dog or cat.
Age: The pet's age (or "unknown").
Nickname: A nickname for the pet.
Physical Description: Size, color, weight, and other physical attributes.
Personality: Descriptions of the pet's temperament or behavior.
Running the Program
To run the program, simply execute the console application. The menu will guide you through various operations.

Future Development
Several features, such as editing pet details and searching for pets by characteristics, are currently under development and will be available in future versions.
