# RANKIFY

![image](https://user-images.githubusercontent.com/96402339/160059829-da30c6a2-551a-4d03-9b67-60dc498799bf.png)


## App Description
We're in the era where music is everywhere. While walking to work, cleaning the house, or just simply lying in bed. But do you feel that sometimes you can do more than just listen? What if you can both enjoy and learn at the same time? What if you can test your knowledge (about music) with other people and compete with them?

We present to you..... RANKIFY! An app that tests your knowledge on music based on your choice of artist(s). Given a short preview of a song, you will need to correctly guess the song within 10 seconds (multiple choice).
Earn scores by guessing the song within the time limit and challenge other people by beating their high scores. If you don't want to challenge others, you can just chill and listen to the songs that you've favorited. This app will bring out your listening abilities and your competitiveness all while vibing on your faves.

## User Stories
  - As an unregistered user, I would like to sign up with name, username, email and password
  - As a registered user, I would like to sign in with username OR email and password
  - As a signed in user, I would like to be able to change/update my password
  - As a signed in user, I would like to sign out
  - As a signed in user, I would like to navigate to my profile page
  - As a signed in user, I would like to be able to search for an artist
  - As a signed in user, I would like to see past games, past scores
  - As a signed in user, I would like to be able to play “the game” based on the artist/song I favorited..?
    - As a signed in user playing the game, I would like to be “graded” on my guesses (implement a score counter)
      - Tally up points at the end
    - As a signed in user, I can see my game history/scores on my profile page

## API
  - Spotify API

## Tech Stack
  - React
  - MongoDB
  - Express
  - Node.js
  - HTML/CSS

## Wireframes
<img width="514" alt="image" src="https://user-images.githubusercontent.com/96402339/160187401-6da0da80-6d8e-455e-89d0-0c0580a1723d.png">

## ERDs
<img width="570" alt="image" src="https://user-images.githubusercontent.com/96402339/160054457-8489690b-eefb-4b40-a889-c5a5658dafc7.png">

## RESTful Routing Chart

| VERB | URL PATTERN | ACTION (CRUD) | DESCRIPTION |
|    :---:     |     :---:      |    :---:      |    :---:      |
| POST | /register | Create (Create) | Register a new user |
| GET | /login  | Index (Read) | Check if user exists, if true, log in user |
| PUT | /forgot | Update (Update) | User can change/update their password
| GET | / | Index (Read) | Home page |
| GET | /profile  | Show (Read) | Display logged in user's profile (can also view game history here)|
| GET | /game | Show (Read) | Display game screen
| DELETE | /score/:id | Delete (Destroy) | User can delete a score
| GET | /search | Show (Read) | Display user search results
| GET| /search/:id | Show (Read) | Display selected search


## MVP Goals
- [ ] Create a registration page
- [ ] Create a login page
- [ ] Create a welcome/home page 
- [ ] Create a navbar
- [ ] Create a timer
- [ ] Create a search screen (user can search for an artist)
- [ ] Create a game play screen
- [ ] Create a user profile page 
- [ ] Create a score counter system

## Stretch Goals
- [ ] Have different game levels
- [ ] Modal that shows the score
- [ ] Create a leaderboard showing the top scores of ALL users
