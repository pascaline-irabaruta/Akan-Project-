# Akan-Project-
#### Description
Akan project is a web application that is going to take in users birthday and calculates the day of the week they were born
and then depending on their gender it gives them a corresponding Akan Name.Akan names are derived from Ghanian culture.

### Author
* **Pascaline Irabaruta**
## Project Set up instructions
 
 1. you need to have git installed to be able to clone
 2. you need to have a github account for you to clone and have the project in your local computer. 
 3. open your github account.
 4. follow this link https://github.com/pascaline-irabaruta/Akan-Project- to go to the project.
 5. click on the the green button and copy the link given.
 6. go to terminal and create folder
 7. enter this command: git init , to initialize the git repository.
 8.enter the command : git clone and paste the link you copied.
    example: git clone https://github.com/pascaline-irabaruta/Akan-Project- 

## BDD(Behavior Driven Development)
In this project we are going to take the user's birthday and find the day of the week they were born on and give the corresponding akan name.Here's what the page looks like when you open the page.
# <img src ="https://github.com/pascaline-irabaruta/Akan-Project-/blob/master/1.jpeg" width=300px height=300px>
And after hitting the check Akan name button the page looks like this
# <img src ="https://github.com/pascaline-irabaruta/Akan-Project-/blob/master/2.jpeg" width=300px height=300px>
The project takes in the user's credentials that are entered through the form and then first calculates the day of the week that the user were born but the calculations will be made only when the entered credentials are correct. and then displays the akan name corresponding to the week day.
##### Specifications
* The program checks if the day entered is not less or equal to zero and not greater than 31
* The program ckecks if the month entered is not less or equal to zero and not greater than 12
* The program uses this formula ( ( (cc/4) -2*cc-1) + ((5*yy/4) ) + ((26*(mm+1)/10)) + dd )%7 to calculate the day.
   where cc: is the century,mm: the month number,yy: the year and dd: the day of the month.
* Then the program uses arrays containing names to give a name to the corresponding day of the week.
   
   
## Technologies used
The project uses :
 1. Html language
 2. Css stylesheet
 3. Bootstrap css framework
 ### Contact information
 Email: pascyirabaruta456@gmail
 ### License
 This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details
 #### copyright (c) 2020 Pascaline Irabaruta
