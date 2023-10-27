
# Create database

Keep any other version here as well, e.g. Display current deals, Let user to click on "show-current-deals".

## Priority: 10 

## Estimation:  8 days

* Chloe: 8 days 
* Keziah: 8 days
* Jess: 8 days

## Assumptions:
Database will store sensitive information securely. 

Authentication required when changing personal details. 

## Description:
Description-v1: Create a database to record users and user info

Description-v2: Create a database to store information about users, and dogs listed for hire.

## Tasks, see chapter 4.
Initial tasks when using ROOM database
1. User Data entry, Estimation 1 day
2. User Data access object (DAO), Estimation 1 day
3. User database, Estimation 1 day
4. Item Data entry, Estimation 1 day
5. Item Data access object (DAO), Estimation 1 day
6. Items database, Estimation 1 day

_**We soon discovered that storing and image was too difficult so we changed to using Firebase**_

NEW TASKS
1. User database, Estimation 3 days
2. Doggo database, Estimation 3 days


# UI Design:
* No low-fi UI design as it's a database.

# Completed:
Example of a dog document stored in the firestore database

![image](/images/database.png)

Later in Iteration 2 we found that the database needed to be updated so that the current user could be tracked. 
![image](/images/Firebase_Authentication_database.png)
