# **CMPE131 Project Team 6**
<a href=""><img src="https://i.ibb.co/cTKmRgG/StudyHub.png" alt="StudyHub" border="0"></a><br /><a target='_blank' href=''></a><br />
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

**Problem Statement:** Help users log in to use the app

**Non-functional Requirements:** Confirmation Emails should be sent within 1 hours.

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
Users enter information in section where the system displays error again until the system does not display error message

##### Alternate Sequences
1)	Username which user enter, was used
a.	The system displays an error message to the user
b.	The system prompt user to enter a valid username
2)	Password which user enter, does not meet the requirement
a.	The system displays an error message to the user
b.	The system prompt user to enter a valid password
3)	Email which user enter, was used
a.	The system displays an error message to the user
b.	The system prompts user to enter a different email

##### Alternate Postconditions
User can sign up.




## Use Case #2 Description

**Date:** 09/15/2021

**Product Name:** Study Hub

**Problem Statement:** Help users delete an account

**Non-functional Requirements:** Respond to delete confirmation within 1 minutes.

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
1)	Users change their mind, or they click on delete an account by mistake
a)	System prompts the user to confirm
b)	User click cancel (No)

##### Alternate Postconditions
Users still have an account to log in.




## Use Case #3 Description

**Date:** 09/15/2021 

**Product Name:** Study Hub

**Problem Statement:** Help users see and share flashcard easier

**Non-functional Requirements:** User can choose color for markdown file

**Use Case Name:** Input a markdown file and output flash cards.

##### Actors
All users

##### Preconditions
Users have account.
Users have flashcards.

##### Triggers
1.	With input a markdown file: Type “##” before a flashcard.
2.	With output flashcard: click option “share” on the top-right of the flashcard.

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
5.	Users confirm by clicking download/send.

##### Primary Postconditions
1.	With input a markdown file: Make flashcard easier to read

2.	With output flashcard: Can download their flashcard to phone, so users can see it everywhere. Also, users can share useful information to their friends.

##### Alternate Triggers
1.	With input a markdown file: 
a.	Users select that flashcard which user input a markdown file.
b.	Users click option “edit” on the right-top of the flashcard.
c.	Users delete “##” before the word.

2.	With output flashcard: Users turn on internet in their phone.

##### Alternate Squences
1.	With input a markdown file: 
a.	Users change their mind; they do not want to input a markdown file.

<<<<<<< HEAD
2.	With output flashcard: 
a.	Users save or share without internet
b.	System displays an error message to user.
c.	System prompts user turn on internet.
 
=======
**With input a markdown file** 
Users change their mind; they do not want to input a markdown file.

**With output flashcard**
Users save or share without internet.
System displays an error message to user.
System prompts user turn on internet.


>>>>>>> 583408df39638e5d9b3e0cfc9265e08e316d2043
##### Alternate Postconditions
1	With input a markdown file.	
a.	Uers successfully undo.
2.	With output flashcard
b.	Users successfully download/send.




## Use Case #4 Description

**Date:** 09/15/2021 

**Product Name:** Study Hub

**Problem Statement:** Help users save a useful flashcard from others to their folder

**Non-functional Requirements:** Users only can save flashcard from another user when they put their flashcard in public.

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

##### Primary Postconditions
That flashcard is saved in user’s folder

##### Alternate Triggers
1.	Users click to the flashcard and hold 
2.	System prompts the user some options
3.	Users click option “delete”

##### Alternative Squences
Users change their mind that they don’t want to save.

##### Alternate Postconditions
Less flashcard in user's folder




## Use Case #5: Change the order of flashcards based on how often user got answer correctly

**Date:** 9/15/2021 

**Product Name:** Study Hub

**Problem Statement:** calculate the percentage of how many correct and incorrect answers

**Non-functional Requirements:** efficiency requirement

**Use Case Name:** check answers

##### Actors:
 users

##### Preconditions:
 if answer is correct

##### Triggers:
 flashcard to change their position automatically

##### Primary Sequence: 
1. get answer from user
2. check answer
3. if answer is corrected -> trigger flashcard to change
4. else -> no change

**Primary Postconditions**: answer must be filled

##### Alternate Trigger:
 prompt user to answer the questions

##### Alternative Sequences:
1. if answer is blank -> prompt a message
2. else -> trigger to check answer

##### Alternate Postconditions:
 save log



## Use Case #6: Create pdf of flash card to print

**Date:** 9/15/2021 8:10 pm 

**Product Name:** Study Hub

**Problem Statement:**  a button to print

**Non-functional Requirements:** quality

**Use Case Name:** create pdf file

##### Actors:
 users

##### Preconditions:
 a "Print" button

##### Triggers:
 create pdf method


##### Primary Sequence: 
1. when button is clicked -> trigger to print

##### Primary Postconditions:
 answer can be filled or unfilled

##### Alternate Trigger:
 prompt user to [Yes] to print [No] to cancel

##### Alternative Sequences: 
1. if button is clicked -> prompt a message
2. if user choose [Yes] -> trigger to print
3. else -> trigger to cancel

##### Alternate Postconditions:
end case: go back to home





## Use Case #7: Mind map of flash cards

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

**Date:** 09-15-2021 

**Product Name:** Study Hub

**Problem Statement:**

**Non-functional Requirements:**

**Use Case Name:** Share Notes With Other People 

##### Actors
Users

##### Preconditions
1. User must have an account to share Notes 
2. User must have notes to share

##### Triggers
1. User clicks on "Share Note"

##### Primary Sequence
1. User goes to desired note they want to share
2. User clicks on "Share Notes"
3. User will confirm if they want to share

**Primary Postconditions**
1. User has shared their notes

##### Alternate Trigger
1. User clicks on "View Notes"

##### Alternative Sequences
1. User goes to desired Note
2. User clicks on "View Notes"

##### Alternate Postconditions
1. Notes must be shared either by them or another user




## Use Case #12 Description

**Date:** 09-15-2021 

**Product Name:** Study Hub

**Problem Statement:**

**Non-functional Requirements:**

**Use Case Name:** Quickly rename files using regular expressions

##### Actors
User 
Website

##### Preconditions
File must exist
File cannot be renamed the same name

##### Triggers
1. User will click on the “Rename” button

##### Primary Sequence
1. User clicks on the three dot icon next to the file
2. User clicks on “Rename” button 
3. User will write the expression
4. The website will convert the expression
5. The user will confirm the conversion

**Primary Postconditions**
1. File has been renamed

##### Alternate Trigger
1. User did not type the Expression correctly

##### Alternative Sequences
1. Website will give user an error
2. User will fix error

##### Alternate Postconditions
1. File has been renamed





## Use Case #13 Description

**Date:** 9/15/2021

**Product Name:** Study Hub

**Problem Statement:** organize time flow 

**Non-functional Requirements:** user

**Use Case Name:** Create time block

**Actors**: User

**Preconditions:** no need 

**Triggers:** 

- Click and drag to create time block

##### Primary Sequence

- User can edit color
- Set reminder if need

**Primary Postconditions**

- Attracted interphase
- Increase concentration

**Alternate Trigger:**

- User can click and drag time block to another time frame if want make change

**Alternative Sequences:**

- User click on view time block to add description if need

**Alternate Postconditions:**

- User can view their creation





## Use Case #14 Description

**Date:** 9/15/2021

**Product Name:** Study Hub

**Problem Statement:** feature that user can track there time while studying

**Non-functional Requirements:** timer can be display or non display for user

**Use Case Name:** use pomodoro timer

**Actors:** all user

**Preconditions:** no need so user can use it asap and no annoy

**Triggers:** 

- Timer must be input amount of time they want to remind

- Timer can be start when user hit "SPACE"

**Primary Sequence:** 

- Timer automatically alert when time ran out (No need human contact)

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
