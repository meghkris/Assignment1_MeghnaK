# Assignment1_MeghnaK
Spam Filter

Description:
This project is a spam filter based on the Naive Bayes spam filtering method that goes through a set of ham training files and spam training files to figure out the probability of that a file is spam given that it contains a particular word, and uses those probabilities to calculate the actual probability that a file is spam  or not for a set of testing ham and spam files. The output shows the program's calculated probability that the file is spam and the actual classification of the testing file.

Screenshot of Running Application:
![image](https://user-images.githubusercontent.com/55290348/110877331-4002b280-82a7-11eb-9348-95cd1eb833f7.png)
![image](https://user-images.githubusercontent.com/55290348/110877674-c1f2db80-82a7-11eb-9548-996250b36b93.png)
![image](https://user-images.githubusercontent.com/55290348/110877749-e2bb3100-82a7-11eb-8deb-e4a9ddaf3c21.png)

Improvements:
I did make any improvements to the actual model as I got a pretty good accuracy and precision value when testing with the given data in Assignment1.zip.

How To Run:
A window will pop up with two buttons: "Choose Directory" and "Display Results". First click "Choose Directory" and select the folder that contains the training and testing folders which each contain ham and spam folders. So, for instance, the directory of the folder you choose should look like this:

data
    train
        ham
        spam
    test
        ham
        spam
       
The name of the "data" directory that you choose can be anything and located anywhere but the residing structure and the names of the folders containing the ham and spam files MUST MATCH the folder names given above.
Once you select the directory, click "Display Results" and then an output window with the accuracy and precision of the spam filter will pop up as well as the table with all the file names in the testing folder, their calculated spam probability, and their actual classification (whether they are ham or spam).
    
Resources/References:
https://docs.oracle.com/javafx/2/ui_controls/table-view.htm

https://docs.oracle.com/javase/8/javafx/api/javafx/scene/control/ScrollPane.html

https://o7planning.org/11533/open-a-new-window-in-javafx#:~:text=In%20JavaFX%2C%20to%20create%20a,initModality(Modelity)%20method.&text=When%20creating%20a%20new%20Stage,it)%2C%20via%20the%20stage.

https://www.geeksforgeeks.org/javafx-directorychooser-class/
