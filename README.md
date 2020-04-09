# Unique-Senses
This application will allow people who have disabilities to connect with other individuals who may or may not have the same disability.
Group Project - README Template
===

# Unique Senses

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
This application will allow people who have disabilities to connect with other individuals who may or may not have the same disability.


### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Social Media
- **Mobile:** Yes
- **Story:** 
- **Market: An individual with a disabilty could choose to use this app. To ensure a safe web environment, users would be organized by disability an
- **Habit:**
- **Scope:**

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* [fill in your required user stories here]
[x]User can log in OR create an account
[x]User is able to change password or username
[x]User is able to use "search" tab 
[x]User is able to refresh screen and click features
[x]User is able to view other accounts on newsfeed 
[x]User can switch between different tabs such as Home and Profile 
[x]App style and functionality relates to "real life" social media


**Optional Nice-to-have Stories**

* [fill in your required user stories here]
[x]User has "add friend" functionality, up to 2+ people 
[x]User is able to "send message" to other accounts 
[x]User can search specific names in the search bar 
[x]User can upload unlimited pictures and posts 
[x]User can tag other accounts in pics/posts

### 2. Screen Archetypes

* ![] https://i.imgur.com/D6K1Lqw.png
   * Login
       * User are allowed to login with account information
   * Register - User register for a account or login
       * User is prompted to account information input. Login information 1 authentication 
   *  News feed - page that consist of being able to like, post, search other users.
       *  User will have the choice post a picture , like a picture , search for other users.
   *    Profile screen
           *    Allows you to modify your profile settings
   *    Search screen
           *    Will allow you to search for other users, see all notifications
   *    Post screen
           *    Ask for permission to enable pictures. Allow user to pick photo or video (Minimum 3 seconds). Allow users to post picture/video with a caption.
 

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* [Login/Register]
* [News Feed]
* [Profile]
*  [Search/Notification]
*  [Post]

**Flow Navigation** (Screen to Screen)
* [Login/Register]
   * Allow user to login or create a account
* [News Feed]
   * Displays images or videos being visible on the news feed from followers, allows you to double tap to  like a picture/video
   * Gives you the option to click navigaton to the post screen, notification screen, profile screen
* [Profile] 
   *    [Allows user to change profile pictures and password.]
* [Search/Notification]
    * [Allows you to tap the keyboard to search for other users, also to see the notifications]
* [Post]
    * [Ask to enable access to pictures, pick photo or video(minimum 3 seconds),]

   
   
## Wireframes

<img src="https://i.imgur.com/gPw5f7C.jpg)
)
" width=600>

### [BONUS] Digital Wireframes & Mockups
 ![Login/Register](https://i.imgur.com/jaFkWZ5.png)
 ![News Feed](https://i.imgur.com/KKS707A.png)
![Register](https:// "title")


### [BONUS] Interactive Prototype

## Schema 



| Property | Type     | Description |
| -------- | -------- | -------- |
| objectID     | string     | A unique ID for users to identify (username)
|caption   | string   |Image caption made by author
|Image     | file     | Image uploaded by author 
|CommCount |integer   |Number of comments on post by other users
|LikesCount| integer | Number of likes on post by other users
|createdAt| DateTime |Date and time that a post or image was created by author or user
|editedAt| DateTime| Time that a post or image was updated by author or user
|Author| Point-to-User| 	Author of specified post (caption/image/post)


### Sprint Planning



| Issues Created| Project Board | Tasks |
| ----          | ----- | ----- |
| API needed    |API or create data |Find API
| Gifs for README|Create Gifs | Update gifs for submission
|User story needs more|Create more user interaction    |Create Gifs and more Screens

### GIFS
![](https://i.imgur.com/rZOSuZZ.gif)

![](https://i.imgur.com/5zYGHwn.gif)
![](https://i.imgur.com/nzkRp5f.gif)
![](https://i.imgur.com/VGWUv9K.gif)





### Models
[Add table of models]
### Networking``
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
