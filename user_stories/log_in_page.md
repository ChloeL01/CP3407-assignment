
# Login page

## Priority: 10 
It is very important for the user to be able to sign in to allow all of their data to be collated under a single user profile.

## Estimation: 5 days 

* Chloe: 3 days
* Keziah: 5 days
* Jess: 8 days

## Assumptions: 

## Description: 
Description-v1: The user can log in to save their details.

## Tasks:

1. User interface, Estimation 2 days
2. Integration with database, Estimation 3 days


# UI Design:
Low-fi version drawn on miro. Miro can be accessed from the link in the README.md

![image](/images/log_in.png)

# Completed:
![image](/images/Login_Page.png)

## Iteration 1
![image](/images/login_finished.png)
## Iteration 2

During this iteration, the Login Page underwent major changes regarding logging using Firebase Authentication. Allowing for app to check if the user has logged into the app previously, if so they would be directly immediately to the homepage. If not then they would be required to log in.

![image](/images/Login_Page.png)

# Key Features:
* Covering of sensitive information (Hiding Password)
* Link to Signup page
* If you have logged in on the device previously it will automatically log you in and take you directly to the home page (unless you log out)
* Checks that fields have been filled in, if not the user is prompted to enter their details
* Compares inputted information against database to check if user exists 
