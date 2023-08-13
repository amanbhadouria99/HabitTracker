# HabitTracker
A web application which help you to create, update, delete and track your habit on daily basis. It is user specific app, which mean a user can track their habit, and mark it as done , or not done. The project is built using a tech stack consisting of Node.js for the server-side scripting. Express for handling HTTP requests and routing. MongoDB for storing and managing the data and EJS for rendering the views and templates.

# Installation
To run this application on your local machine, please follow these steps:

Clone this repository using the following command:

$ git clone 
Install the required dependencies using the following command:

$ npm install 
Start the application using the following command:

$ npm start 
Open the application in your web browser by visiting the following URL:

$ http://localhost:8000 
# Usage
Once you have the application up and running, you can start using it by following these steps:

1. Sign-up/Sign-in into your account.
2. Click on the "Add Habit" button to create a new habit.
3. Enter the name of the habit you want to track.
4. Click on the "Save" button to save the habit.
5. To mark a habit as complete/incomplete for the day, simply click on the corresponding icon.
6. To delete a habit, click on the "Delete" icon next to it.
7. To see today's habits, click on "Show Daily" button.
8. To edit a habit, click on the "Edit" icon next to it.
# Folder Structure

Habit Tracker
    |
    |               |--->css
    |--->assets---->|--->img
    |               |---> js
    |
    |               |--->flashMiddleware.js
    |--->config---->|--->mongoose.js
    |               |--->passport_local.js
    |
    |                  |-->habit_controller.js
    |--->controllers-->|-->home_controller.js
    |                  |-->user_controller.js
    |
    |               |-->habit.js
    |--->models---->|
    |               |-->user.js
    |
    |              
    |               |-->habit.js
    |--->routes---->|-->index.js
    |               |-->user.js
    |
    |              
    |              |--->_header.ejs
    |              |--->404.ejs
    |              |--->daily_view.ejs
    |              |--->forget_password.ejs
    |--->views---->|--->home.ejs
    |              |--->layout.ejs
    |              |--->user_sign_in.ejs
    |              |--->user_sign_up.ejs
    |              |--->weekly_view.ejs
    |
    |-->node_modules
    |-->.gitignore
    |--> index.js
    |--> package-lock.json
    |-->package.json
    
    
# Screenshots
Home Page
![235321468-d96ca598-cd5b-45f4-acbe-2f5594eb4ffc](https://github.com/amanbhadouria99/HabitTracker/assets/111181618/0c186eac-a417-4cc7-b17d-9b68d4ed470d)


Sign-up Page
![235321481-07590d82-d2ae-435a-aff9-ecc9a84a188a](https://github.com/amanbhadouria99/HabitTracker/assets/111181618/5f2704e5-8238-431e-b380-a7bb0a184145)


Sign-in Page
![235321490-3973cbbd-4d22-433b-8dda-72c3d19d5236](https://github.com/amanbhadouria99/HabitTracker/assets/111181618/c5b7012c-a6f6-4529-a677-94c07793f204)


Weekly View Page
![235321501-b4b7aa59-249e-43a7-87f6-a212d92d831a](https://github.com/amanbhadouria99/HabitTracker/assets/111181618/a970ec37-6c52-4c8f-8ed5-eca0f54a8eb5)


# Contributing
Contributions are always welcome! If you have any suggestions for improving this application, please feel free to create a pull request or open an issue.
