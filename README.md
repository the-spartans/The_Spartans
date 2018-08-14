# The_Spartans
Implementation of a interactive module for agriculturists

This is the implementation of a module, to interact with a user, to actively reply to their queries, from a set of questions provided in the database in a particular topic.
This module has been specifically designed to respond to the general queries about a tomato plant.

Questions Database:
A database has been provided to the module with all possible phrases of questioning about the topic.
The module can be further developed to be responsive to specific keywords and phrases rather than complete sentences.
The database has a trained set of samples about various parameters of tomato plant. The various parameters include height of a plant, colour, length and width of both normal and affected leaves of the plant.
 
Alogorithm:
The chatbot package is installed and imported.
The necessary trainer packages are also imported.
Database is extracted from the files and the bot is trained with the datasets.
The module reads the user input and stores it, if it is not the terminator phrase it continues. 
Then the appropriate response is predicted and printed as the chatbot output.
This loop continues till the terminator phrase is read as input.
