Fork the exercise and complete each TODO in the project - This will remove the errors currently residing in the project.  In this exercise you will get some experience with reference and value types, enums, arrays, strings, and making value types nullable.

The provided C# code is part of a simple program encapsulated within two namespaces, ChristmasWithTypes, which is meant to simulate managing Christmas-related information. The program uses a class named Christmas to store details about Christmas presents, Santa's name, the height of the Christmas tree, and the day of the week Christmas falls on (represented as an enum).

The Program class contains the Main method which acts as the entry point for executing the program. This method initializes a new instance of the Christmas class, sets properties related to Christmas presents, the height of the tree, and Santa's name. It outputs these details to the console, providing a user-friendly display of the Christmas settings.

Steps to Complete
To fully implement and run the provided program, follow these steps:

   - Define the Enum for Days:
     The Day enum has already been correctly defined within the Christmas class. This enum includes all days of the week from Sunday to Saturday.

   - Make the Tree Height Nullable:
     The TreeHeight property is already defined as nullable (int?) which allows it to represent a missing value (null) if the height is not set.

   - Set Santa's Name:
     The Santa property of the Christmas class is designed to hold Santa's name as a string. In the Main method, set this property to "Kris Kringle".

   - Insert Presents:
     The Presents array should be initialized with three strings representing the presents. This can be done by creating a new string array and assigning it to the Presents property.

   - Set the Tree Height:
     Assign the TreeHeight property a value of 10 to represent a tree height of 10 feet.

   - Output the Christmas Information:
     Utilize Console.WriteLine to display the day Christmas falls on, the height of the Christmas tree, the list of presents, and the name used for Santa.

   - Compile and Run the Program:
     Use a C# compiler to compile the program. Run the compiled program to see the output which details the configured Christmas settings.
     
This step-by-step guide ensures that the Christmas class is fully utilized within the Main method to set and display the intended Christmas details, matching the behavior and structure outlined in the initial program setup.
