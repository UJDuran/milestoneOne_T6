# **CMPE131 Project Team 6**

#### Member name:

Danh Pham (https://github.com/emthangtrung)

Ngoc Tran (https://github.com/ntran12)

Ulises Duran (https://github.com/UJDuran)

Thinh Vo (https://github.com/kiemkhach2020)

#### Main Github repo:


https://github.com/UJDuran/milestoneOne_T6.git



## Use Case #1 Description

**Date:** 09/15/2021

**Product Name:** Study Hub

**Problem Statement:**

**Non-functional Requirements:**




**Use Case Name:** Create an Account

##### Actors
Everyone

##### Preconditions
New User
Have email account to sign up.
##### Triggers
New user clicks on option “Join us”

##### Primary Sequence
1.	New users click on option “Join us”.
2.	New users fill out some information such as first name, last name, date of birth, sex.
3.	New users create their username .
4.	System checks the username is available or not.
5.	New users create their own password.
6.	System check password meet the requirement or not.
7.	New users enter their email.
8.	System check email was used or not.
9.	New users click summit option at the end of platform.
10.	System creates a new user. 
11.	System sends a confirmation email to the user’s email.

##### Primary Postconditions
Users can log in to use the app.

##### Alternate Triggers
Users enter information until the system does not display erroe message.

##### Alternate Sequences
•	Username which user enter, was used
o	The system displays an error message to the user
o	The system prompt user to enter a valid username
•	Password which user enter, does not meet the requirement
o	The system displays an error message to the user
o	The system prompt user to enter a valid password
•	Email which user enter, was used
o	The system displays an error message to the user
o	The system prompts user to enter a different email

##### Alternate Postconditions
User can sign up.




## Use Case #2 Description

**Date:** 09/15/2021

**Product Name:** Study Hub

**Problem Statement:**

**Non-functional Requirements:**




**Use Case Name:** Delete an Account 

##### Summary
Users can delete an account if they want.

##### Actors
All users

##### Preconditions
Users must have an account.

##### Triggers
Users click on option "Delete"

##### Primary Sequence
1.	The user clicks on “setting” on menu bar.
2.	The use clicks on “delete an account”
3.	The system ask user again to confirm they want to delete an account.
4.	Users click confirm (Yes)
5.	System sends a confirmation to user’s email.

##### Primary Postconditions
Users cannot log in to system anymore.

##### Aternate Squences
Users click on option "Cancel"

##### Alternate Sequences
•	Users change their mind, or they click on delete an account by mistake
o	System prompts the user to confirm
o	User click cancel

##### Alternate Postconditions
Users still have an account to log in.




## Use Case #3 Description

**Date:** 09/15/2021 

**Product Name:** Study Hub

**Problem Statement:**

**Non-functional Requirements:**




**Use Case Name:** Input a markdown file and output flash cards.

##### Actors
All users

##### Preconditions
Users have account.
Users have flashcards.

##### Triggers
With input a markdown file: Type “##” before a flashcard.

With output flashcard: click option “share” on the top-right of the flashcard.

##### Primary Sequence
With input markdown file:
1.	Users click option “create”
2.	System prompts 2 text boxes (front and back card) for user to fill out. 
3.	In the text box (front card), user type “##” before type word in flashcard.
4.	System automatically make flashcard into markdown file.

With output flashcard:
1.	Users click on flashcard which users want to share.
2.	Users click option “share” on the top-right of that flashcard.
3.	System prompts some options such as download to user’s phone or share to their friends via message, Facebook, email, etc.
4.	Users click on option they choose.

**Primary Postconditions**
With input a markdown file: Make flashcard easier to read

With output flashcard: Can download their flashcard to phone, so users can see it everywhere. Also, users can share useful information to their friends.

##### Alternate Triggers
**With input a markdown file:** 
Users select that flashcard, click option “edit”
Users delete “##” before the word.

**With output flashcard:**
Users turn on internet in their phone

##### Alternate Squences

**With input a markdown file** 
Users change their mind; they do not want to input a markdown file.

**With output flashcard**
Users save or share without internet.
System displays an error message to user.
System prompts user turn on internet.


##### Alternate Postconditions





## Use Case #4 Description

**Date:** 09/15/2021 

**Product Name:** Study Hub

**Problem Statement:**

**Non-functional Requirements:**




**Use Case Name:** Share flash cards (add to their account) 

##### Actors
All users

##### Preconditions
User must has at least one flashcard.

##### Triggers
User click on heart icon on the front-right of that flashcard.

##### Primary Sequence
1.	Users choose which flashcard they want to share (save) to their account
2.	System prompts the users which folder they want to save the flashcard in
3.	Users choose folder to save in
4.	System prompts the users confirm
5.	Then users click option “Yes”
6.	System saves that flashcard to the user’s folder

**Primary Postconditions**
That flashcard is saved in user’s folder

##### Alternate Triggers
Users click to the flashcard and hold 
System prompts the user some options
Users click option “delete”

##### Alternative Squences
Users change their mind that they don’t want to save.

##### Alternate Postconditions
Make user's folder clearly.




## Use Case #5 Description: Change the order of flashcards based on how often user got answer correctly

**Date:** 9/15/2021 

**Product Name:** Study Hub

**Problem Statement:** calculate the percentage of how many correct and incorrect answers

**Non-functional Requirements:** efficiency requirement

**Use Case Name:** check answers

##### Actors: users

##### Preconditions: if answer is correct

##### Triggers: flashcard to change their position automatically

##### Primary Sequence: 
1. get answer from user
2. check answer
3. if answer is corrected -> trigger flashcard to change
4. else -> no change

**Primary Postconditions**: answer must be filled

##### Alternate Trigger: prompt user to answer the questions

##### Alternative Sequences:
1. if answer is blank -> prompt a message
2. else -> trigger to check answer

##### Alternate Postconditions: save log



## Use Case #6 Create pdf of flash card to print

**Date:** 9/15/2021 8:10 pm 

**Product Name:** Study Hub

**Problem Statement: a button to print

**Non-functional Requirements:**quality

**Use Case Name:** create pdf file

##### Actors: users

##### Preconditions: a "Print" button

##### Triggers: create pdf method


##### Primary Sequence: 
1. when button is clicked -> trigger to print

**Primary Postconditions**: answer can be filled or unfilled

##### Alternate Trigger: prompt user to [Yes] to print [No] to cancel

##### Alternative Sequences: 
1. if button is clicked -> prompt a message
2. if user choose [Yes] -> trigger to print
3. else -> trigger to cancel

##### Alternate Postconditions:
end case: go back to home





## Use Case #7 Mind map of flash cards

**Date: 9/15/2021

**Product Name:** Study Hub

**Problem Statement:** 

**Non-functional Requirements:**

**Use Case Name:** 

##### Actors: user

##### Preconditions

##### Triggers


##### Primary Sequence

**Primary Postconditions**

##### Alternate Trigger

##### Alternative Sequences

##### Alternate Postconditions





## Use Case #8 Render markdown notes

![alt text](https://ataglanceanimehome.files.wordpress.com/2021/06/mugentrain.jpg)

**Date:** 9/15/2021

**Product Name:** Study Hub

**Problem Statement:**

**Non-functional Requirements:**

**Use Case Name:** 

##### Actors: users

##### Preconditions

##### Triggers


##### Primary Sequence

**Primary Postconditions**

##### Alternate Trigger

##### Alternative Sequences

##### Alternate Postconditions





## Use Case #9 Description

**Date:** 09-15-2021 

**Product Name:** Study Hub

**Problem Statement:**

**Non-functional Requirements:**

**Use Case Name:** Converts marked down notes to pdf 

##### Actors
User

##### Preconditions
Notes must exist (either from another user or ther own)
Notes must me marked

##### Triggers
User clicks on "Conver to PDF"

##### Primary Sequence
1. User confrims the pdf conversion
2. System asks user to pick a destination for PDF
3. User picks destination for PDF
4. Message displays that file has been downloaded

##Primary Postconditions
Pdf has been created in users desired destination

##### Alternate Trigger
User clicks on "Print" button when asked to convert to pdf

##### Alternative Sequences
1. User confirms the pdf 
2. User has an option to print instead of saving
3. User picks printer destination
4. Message displays that file has been printed

##### Alternate Postconditions
A hard copy of pdf has been printed 





## Use Case #10 Description

**Date:** 09-15-2021 

**Product Name:** Study Hub

**Problem Statement:**

**Non-functional Requirements:**

**Use Case Name:** Create graph (nodes and edges) of connection between notes

##### Actors
Notes
User

##### Preconditions
1. Must have notes saved on their account

##### Triggers
1. User clicks on "Connections Between Notes" tab
2. User click on "New Graph"

##### Primary Sequence
1. User goes to designated tab 
2. User creates new graph by clicking "New Graph"
3. User will select notes to draw connection to eachother                                                               4. User clicks on create graph                                                                                          5. System will prompt user to name graph
4. User clicks on create graph                                                                                          5. System will prompt user to name graph
5. System will prompt user to name graph
6. User names and confirms it 
 
**Primary Postconditions**
1. A graph is created between selected notes 

##### Alternate Trigger
1. User clicks on "Connections Between Notes" tab
2. User clicks on "View graphs"

##### Alternative Sequences
1. User goes to designated graph
2. User clicks on "View Graphs"
3. User will pick a presaved graph 

##### Alternate Postconditions
1. User can view their previous saved graph




## Use Case #11 Description

**Date:** 

**Product Name:** Study Hub

**Problem Statement:**

**Non-functional Requirements:**

**Use Case Name:** 

##### Actors

##### Preconditions

##### Triggers


##### Primary Sequence

**Primary Postconditions**

##### Alternate Trigger

##### Alternative Sequences

##### Alternate Postconditions





## Use Case #12 Description

**Date:** 

**Product Name:** Study Hub

**Problem Statement:**

**Non-functional Requirements:**

**Use Case Name:** 

##### Actors

##### Preconditions

##### Triggers


##### Primary Sequence

**Primary Postconditions**

##### Alternate Trigger

##### Alternative Sequences

##### Alternate Postconditions





## Use Case #13 Description

**Date:** 9/15/2021

**Product Name:** Study Hub

**Problem Statement:**

**Non-functional Requirements:**

**Use Case Name:** Create time block

##### Actors

##### Preconditions

##### Triggers


##### Primary Sequence

**Primary Postconditions**

##### Alternate Trigger

##### Alternative Sequences

##### Alternate Postconditions





## Use Case #14 Description

**Date:** 9/15/2021

**Product Name:** Study Hub

**Problem Statement:**

**Non-functional Requirements:**

**Use Case Name:** use pomodoro timer

##### Actors

##### Preconditions

##### Triggers


##### Primary Sequence

**Primary Postconditions**

##### Alternate Trigger

##### Alternative Sequences

##### Alternate Postconditions





## Use Case #15 Description

**Date:** 9/15/2021

**Product Name:** Study Hub

**Problem Statement:**

**Non-functional Requirements:**

**Use Case Name:** visualize time blocks

##### Actors

##### Preconditions

##### Triggers


##### Primary Sequence

**Primary Postconditions**

##### Alternate Trigger

##### Alternative Sequences

##### Alternate Postconditions

## Use Case #16 Description

**Date:** 9/15/2021

**Product Name:** Study Hub

**Problem Statement:**

**Non-functional Requirements:**

**Use Case Name:** add to do tracker

##### Actors

##### Preconditions

##### Triggers


##### Primary Sequence

**Primary Postconditions**

##### Alternate Trigger

##### Alternative Sequences

##### Alternate Postconditions





## Use Case #17 Description

**Date:** 9/15/2021

**Product Name:** Study Hub

**Problem Statement:**

**Non-functional Requirements:**

**Use Case Name:** visualize hours worked and project

##### Actors

##### Preconditions

##### Triggers


##### Primary Sequence

**Primary Postconditions**

##### Alternate Trigger

##### Alternative Sequences

##### Alternate Postconditions
