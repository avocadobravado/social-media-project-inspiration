##Layout inspiration

https://dribbble.com/shots/3115198-Friendster-Social-Media-Redesign
https://dribbble.com/shots/2340496-Facebook-Redesign-Concept
https://dribbble.com/shots/2276325-Debut-Fishprep-com-Stream
https://dribbble.com/shots/3069016-Social-Media-Activity-Feed-UI

Login screen:
https://dribbble.com/shots/3522742-South-Down-National-Park-Redesign
https://dribbble.com/shots/2144475-1-Daily-UI-Elements-Dandelion-Login-Form
https://dribbble.com/shots/2875260-Login-screen-and-wordmark
https://dribbble.com/shots/3315569-GA-Landing-Page
https://dribbble.com/shots/3315569-GA-Landing-Page



stuff from guy:

## Specs
| Behavior | Input | Output |
|---|---|---|
| Program will display home landing page  | none | Welcome to socialCodus, account sign up, account login  |
| Program will take 6 user inputs to create a new account | Text: first name, last name, username, email, PW, confirm PW  | Joe, Schmoe, Jsmoe, jsmoe@gmail.com, password, password |
| Program will save user entries to database for later use | see above | see below |
| At account creation, program will check for previously used usernames. | duplicate 'jsmoe' names | 'That username is already in use.' |
| At account creation, program will check for matching PWs. | password/wordpass | 'Both passwords must match.' |
| At account creation, program will check for valid email format. | jsmoegmail.com | 'Please include an @ in the email address.' |
| Program will take 2 user inputs to log in to an existing account | username/password| Jsmoe/password |
| At account log in, program will check for valid username. | Joe/ Jsmoe | No account with that username exists. |
| At account log in, program will check for valid | wordpass/password | 'Invalid password.' |
| Program will take user to news view from login screen | button click/Sign Up, button click/Log in (assuming no errors found, see above) | News view |
| Program will display news view. | see above | Links to My Profile, Friends, Edit Profile, search bar, Hi [user], Write a post, posts from friends, Sign out |
| News view will display all posts created by the user and the users friends. | Bob: 'What a beautiful morning!' -or- user and friends have made no posts | 'What a beautiful morning!' -or- 'Your timeline is empty.' |
| News view will have a link to My Profile | click | user profile view |
| Program will display Profile view. | none | Links to Home, Friends, Edit Profile, Search bar, Upload photo, Friends list,  all posts made by the user, Hi [user], Write a post, Sign out, user name, username, date joined, email, |
| Program will allow user to upload a picture to use as their profile picture | copy URL of a picture from the internet, paste in text box for entry, click upload button | Selected image will display where user image is used.|
| On profile view and news view, program will display a text box for entering a post, and a button to commit the update | text - Good morning! /click | Good Morning! |
| Posts will have the ability for users to like or dislike. | click like -or- dislike | like -or- dislike counter display + 1 |
| Likes and dislikes can only be made to posts and comments of users that are followed. | Click | like -or- dislike counter display + 1 |
| Posts will have a text box for users to enter a reply. | Text - Yes it is! / Click submit | "Good morning!" / Yes it is! |
| Pages other than landing page will have a Friends link | Click | Return friends view |
| Friends view | none | List and links to all friends -or- 'Uh-oh, it appears you have no friends!', if you have no matched friends yet. |
| Pages other than landing page and news view will have a Home link | Click | Return to News feed view. |
| All views will display a Sign out link. | click | log out, return to socialCodus landing page. |
| All views will display a Search window. Program will search database for matches to first name, last name, and username. | Bob | list of all users where 'Bob' is found in the first, last and username. |
| Program will display the results of a search query, results will be links to the found users page | click | Bob's profile page |
| Profile page of non-friends will have a button to 'Follow'  | click | Accounts are now linked as friends |
| Users may not post on the profile page of non-friends | none | none |
| Profile page of non-friends will have a button to 'Unfollow' | click | Accounts are now unlinked as friends |
| Previous posts on user newsfeed made by Unfollowed users will be removed | none | none |
| All views will display an Edit Profile link. | Click | Take user to Edit Profile view |
| Edit Profile view will display an entry for first name, last name, username, email, password, and confirm password | Entry field - Name: Joe, User entry - Joey |  (Name Joe updated to) Joey |
| Edit Profile view will display a Delete Account button | CLick | Account will be deleted, user will be returned to the account socialCodus landing page
