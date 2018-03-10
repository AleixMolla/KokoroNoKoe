# KokoroNoKoe ( "A void of heart" ) 
### Design and Implement a mini version of Twitter (GUI)

## INSTRUCTIONS:

  Centralized admin control panel to create users and user groups.

#### User:

  1. Unique ID.
  2. List users IDs following this user (followers).
  3. List users IDs being followed by this user(following).
  4. News feed list containing a list of KokoroNoKoe message.
  
#### User group:

  Unique ID, which can be used to group users. Contains any number of users. The same user can only be included in one group. A user groups can contain other user groups recursively. Always a root group called Root to include everything.
  
  - Users can choose to follow other users ( not user groups ) by providing the target user ID.
  
  - Users can also post a short Tweet message (a String), for all followers to see in their news feed lists. Of course, the user can also see his or her own posted messages.
  
#### Admin control panel summary stats:

  1. Total number of users.
  2. Total number of groups.
  3. Total number of Tweet messages in all the user's news feed.
  4. Percentage of the positive Tweet messages in all the user's news feed (the message containing positive words, such as good, great, excellent, etc.). You can decide what the positve words are.

  
