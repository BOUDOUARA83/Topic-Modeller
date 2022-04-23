# Topic-Modeller

Name : Ethar Boudouara 
Date : 21 March 2022

Description : This is a Java Program that shows if a set of documents are about the same topic or not.
the program will scan the words of the documents and check ifthere are common words between the documents which should then 
declare that these documents are similar.stop words for example like the , a , of , he etc should be excluded from the analysis.

the program should read the files line by line which i did by using an array and then it should print out weihter both files are identical or not.

GUI Class
A graphic user interface is built in the GUI class. 
There should a button that user can click on to get to choose thier files from the file chooser window.
this is done by creating the file chooser function in the file chooser class i have created then i linked it the GUI in the control class.

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
