This project was created as part of the CodeCore web development bootcamp (January 2018 Cohort). It was completed using a rails API, a react front end, and copius amounts of caffeine.

# Project Overview

This side is designed to act as a training ground for users to hone their coding development skills.

Users can compete quizzes to earn points and badges to work their way up the leaderboard.

# Setup

Start by cloning this repo to your computer and then follow the steps below to setup the frontend and backend.

## Back end

1. Navigate to the server directory and run the following commands to setup at seed your database (note: this project was designed for use with postgreSQL):

* `bundle`
* `rails db:create`
* `rails db:migrate`
* `rails db:seed`

You should now have a seeded database

## Front end

1. Navigate to the client directory in your terminal and run `$ npm i` to install all necessary modules.
2. In the client directory run `$ npm run start` to run the react client. Default configuration will open the client in your default browser on port 3002.
3. You can now log in as an admin to create, review, update and delete quizzes, with the following credentials:

* email: admin@gmail.com
* password: supersecret

4. You may also create new users via the sign up page, or check the seeded databases for other users to sign in as. By default, all seeded users have the password 'supersecret'
