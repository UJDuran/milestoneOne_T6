# **CMPE131 Project Team 6**

#### Member name:

Danh Pham (https://github.com/emthangtrung)

Ngoc Tran (https://github.com/ntran12)

Ulises Duran (https://github.com/UJDuran)

Thinh Vo (https://github.com/kiemkhach2020)

#### Main Github repo:

=======
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



## Use Case #6 Description

**Date:** 9/15/2021 8:10 pm 

**Product Name:** Study Hub

**Problem Statement:**Create pdf of flash card to print

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





## Use Case #7 Description

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





## Use Case #8 Description

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





## Use Case #9 Description

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





## Use Case #10 Description

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





## Use Case #14 Description

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





## Use Case #15 Description

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
<<<<<<< HEAD
>>>>>>> aad745684d496f79d265504747623ca1a90a8e59
=======





## Use Case #16 Description

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





## Use Case #17 Description

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
>>>>>>> 208c89b9099419ff66d9e374b5546715a299769f
