Trying to create code to process includes.






Create a function for processing the contents of an html file. The file may have FrontMatter variables. The FrontMatter variables are processed by being inserted into the relevant part of the html contents.

You are a programming assistant and tutor.
Write a function in Flutter.
The function takes two inputs. The first is "inputBaseFolder" and is the base folder for a set files. The second is "outputBaseFolder" and is the output base folder for the results of processing.  
The function loops through all the files and folders in the inputBaseFolder and replacates them in outputBaseFolder. 
However, if the file being replacted is an html file then it processes the file first. It does this by sending the file  contents to a function which rplaces the includes with content from the snippets folder.
