# rn-assignment4-11031981

## JOBIZZ APP
The JobizzApp is a React Native application designed to help users log in and view job listings. The application features a login screen that collects user details and a home screen that displays featured and popular job cards. This project is a part of an assignment to replicate a given UI mockup from figma and implement various functionalities.

# FEATURES
I) User Authentication: Users can log in using their name and email.
II) State Management: Passing user data between screens using React Navigation.
III) Job Listings: Displays featured and popular job cards.
IV) Reusable Components: JobCard component to display job details.
V) Styled UI: Application styled to match the provided Figma design closely.

# APP SCREENSHOTS
![app screenshot 1](https://github.com/theodanielsjr101/rn-assignment4-11031981/assets/150858757/700213ed-64f3-4ea4-a2ab-47facdc10a9d)
![app screenshot 2](https://github.com/theodanielsjr101/rn-assignment4-11031981/assets/150858757/0857d808-237a-4ce4-8137-7e3acfc17828)
![app screenshot 3](https://github.com/theodanielsjr101/rn-assignment4-11031981/assets/150858757/2bafe937-658b-4b33-bb5f-6c5d0e806a30)
![app screenshot 4](https://github.com/theodanielsjr101/rn-assignment4-11031981/assets/150858757/ec0d76ff-9304-4a50-b865-565e1d0bec56)



# COMPONENTS
i) App.js
The main entry point of the application, which sets up the navigation stack. It includes the LoginScreen and HomeScreen components.

ii) screens/LoginScreen.js
A screen that allows users to input their name and email and log in. On successful login, it navigates to the HomeScreen with the user's details.

iii) screens/HomeScreen.js
A screen that displays the user's name and email along with a list of featured and popular job cards. It uses the JobCard component to display each job.
