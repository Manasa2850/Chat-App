# README
This is a full-stack chat application.
The technology stack is 
- **Backend:** Ruby on Rails
- **Frontend:** Semantic UI

## How to run the app?
1. Clone the repository
2. Go to the Chat-App directory
3. Ensure that your rails version is 5.2.1
4. Set up the database by running `rails db:migrate`
5. Start the rails server by running `rails s`
6. The app will be visible on localhost:3000

## How to add users to the database?
1. Open `rails console`
2. Add users by entering the command User.add(username: "`name_you_want`", password: "`password_you_want`")
3. A secure password will be created by the app

## What does the app do?
1. Authentication - Only registered users can enter the chat room
2. Users can type in messages and this will be stored in the database. This will also be displayed in the chatbox
3. Person who logs in next can view these messages and can chat using the app

*Reference: Online tutorials*
!(chat.gif)
