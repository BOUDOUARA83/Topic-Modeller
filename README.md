# Topic-Modeller

Name : Ethar Boudouara 
Date : 21 March 2022

Description : This is a Java Program that shows if a set of documents are about the same topic or not.
the program will scan the words of the documents and check ifthere are common words between the documents which should then 
declare that these documents are similar.stop words for example like the , a , of , he etc should be excluded from the analysis.

the program should open the two files first, then it should scan and read the files line by line. A catch function that allows to define a block of code to be executed, if an error occurs in the try block sould be created when reaing the files and then it should return the lines.when all of that is done the program should compare the two files.


the file reader class
this is where object of the files should be created to call the two files 


by using the isEqual function, we can check if the topics of file 1 and file2 are equal or not. we are going to use an if statement for this. if the two files has the same topics then it should print it has same topicsotherwise it should print different topics.


GUI Class
A graphic user interface is built in the GUI class. 
There should a button that user can click on to get to choose thier files from the file chooser window.
this is done by creating the file chooser functyion in the file chooser class i have created then i linked it the GUI in the control class.

the Gui class extends from the JFrame function which which inherits the java.awt.Frame class. JFrame works like the main window where components like labels, buttons, textfields are added to create a GUI.

Button 1, is the file chooser button that user should be able to click and the file chooser window should appears on the screen so that they can choose thier files from thier own PC. this is implemented nby using the JButton class.It is used to create a labeled button that has platform independent implementation. 

I add the file chooser function inside the action performed 
i used an object to pass on the file chooser class.
and i determined the path of the file chooser so user would have the ability to choose the file from.

A message should be displayed on the screen informing the user that the file is opened and i used the JOptionPane.showMessageDialog function to do that.


control class 
this is where all the testing happens.
THe static void function contain 2 objects inside it 
one for the GUI to pass on the GUI class and other one is for the Filehandler class


File Handler Class
it should be able to read both files line by line and this is done by using an array and then prints out wiether they are idntical or not
