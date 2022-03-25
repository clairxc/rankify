# RANKIFY

![image](https://user-images.githubusercontent.com/96402339/160059829-da30c6a2-551a-4d03-9b67-60dc498799bf.png)


## App Description
We're in the era where music is everywhere. While walking to work, cleaning the house, or just simply lying in bed. But do you feel that sometimes you can do more than just listen? What if you can both enjoy and learn at the same time? What if you can test your knowledge (about music) with other people and compete with them?

We present to you..... RANKIFY! An app that tests your knowledge on music based on your choice of artist(s). Given a short preview of a song, you will need to correctly guess the song within 10 seconds (multiple choice).
Earn scores by guessing the song within the time limit and challenge other people by beating their high scores. If you don't want to challenge others, you can just chill and listen to the songs that you've favorited. This app will bring out your listening abilities and your competitiveness all while vibing on your faves.

## User Stories
  - As an unregistered user, I would like to sign up with name, username, email and password
  - As a registered user, I would like to sign in with username OR email and password
  - As a signed in user, I would like to sign out
  - As a signed in user, I would like to navigate to my profile page
  - As a signed in user, I would like to be able to search for an artist
  - As a signed in user, I would like to be able to favorite an artist
  - As a signed in user, I would like to be able to favorite a song
  - As a signed in user, I would like to see past games, past scores, favorited artists & songs
  - As a signed in user, I would like to be able to play “the game” based on the artist/song I favorited..?
    - As a signed in user playing the game, I would like to have the ability to choose music from different categories
    - As a signed in user playing the game, I would like to be able to choose from multiple answers (multiple choice)
    - As a signed in user playing the game, I would like to be “graded” on my guesses (implement a grading system)
      - Tally up points at the end
    - As a signed in user, I can see my and other users’ scores on the leaderboard
      - Leaderboard PER artist


## API
  - Spotify API
# Backup APIs
  - Apple Music API
  - Deezer Api

## Tech Stack
  - React
  - MongoDB
  - Express
  - Node.js
  - HTML/CSS

## Wireframes
<img width="577" alt="image" src="https://user-images.githubusercontent.com/96402339/160054518-071aaf4c-a545-453f-b8cb-bd686f0b3e59.png">

## ERDs
<img width="570" alt="image" src="https://user-images.githubusercontent.com/96402339/160054457-8489690b-eefb-4b40-a889-c5a5658dafc7.png">

## RESTful Routing Chart

| VERB | URL PATTERN | ACTION (CRUD) | DESCRIPTION |
|    :---:     |     :---:      |    :---:      |    :---:      |
| POST | /register | Create (Create) | Register a new user |
| GET | /login  | Index (Read) | Check if user exists, if true, log in user |
| GET | / | Index (Read) | Home page |
| GET | /profile  | Show (Read) | Display logged in user's profile |
| POST | /profile  | Create (Create) | Create a profile page (unique to user) |
| GET | /artist/:id | Show (Read) | Display favorited artist details |
| POST | /artist/:id/add | Create (Create) | Add artist to user's favorites |
| DELETE | /artist/:id | Destroy (Delete) | Delete a favorited artist |
| POST | /artist/:id/comment | Create (Create) | User is able to create a comment for a specific artist |
| PUT | /artist/:id/comment/:commentID | Update (Update) | User can update their comment |
| DELETE | /artist/:id/comment | Destroy (Delete) | User can delete the comments they wrote about the artist |
| GET | /song/:id | Show (Read) | Display favorited song details |
| POST | /song/:id/add | Create (Create) | Add song to user's favorites |
| DELETE | /song/:id | Destroy (Delete) | Delete a favorited song |
| POST | /song/:id/comment | Create (Create) | User is able to create a comment for a specific song |
| PUT | /song/:id/comment/:commentID | Update (Update) | User can update their comment |
| DELETE | /song/:id/comment | Destroy (Delete) | User can delete the comments they wrote about the song |
| GET | /game | Show (Read) | Display game screen


## MVP Goals
- [ ] Create a registration page
- [ ] Create a login page
- [ ] Create a welcome/home page 
- [ ] Create a navbar
- [ ] Create a timer
- [ ] Create a search screen 
- [ ] Create a game play screen
- [ ] Create a user profile page 
- [ ] Create a song details page
- [ ] Create an artist details page
- [ ] Allow a user to add personal comments to their favorited artist(s)
- [ ] Allow a user to edit their comments to their favorited artist(s)
- [ ] Allow a user to delete their comments to their favorited artist(s)
- [ ] Allow a user to add personal comments to their favorited song(s)
- [ ] Allow a user to edit their comments to their favorited song(s)
- [ ] Allow a user to delete their comments to their favorited song(s)
- [ ] Create a leaderboard (per artist)
- [ ] Create a grading/point system

## Stretch Goals
- [ ] Modal that shows the score
- [ ] Leaderboard per genre
