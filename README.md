# WebDev-Assignments

Link: csc342-141.csc.ncsu.edu

## Assignment 1: 
Part 1: Static Newspaper Landing Page: https://csc342-141.csc.ncsu.edu/hw1/Part1/landing.html 
 - a static landing page for a hypothetical newspaper's website
 - used CSS for styling and utilized proper HTML semantics

 Part 2: Dashboard Design: https://csc342-141.csc.ncsu.edu/hw1/Part2/dashboard.html
 - Based on the provided HTML, enhancement was achieved using pure CSS without altering the original structure. 

## Assignment 2:
### Calculator
https://csc342-141.csc.ncsu.edu/hw2/
Crafted with custom HTML, styled with CSS, and used JavaScript for arithmetic operations. Features a computation history display.

## Assignment 3:
### Pay your friends
https://csc342-141.csc.ncsu.edu/hw3/
A simple application simulating payment statement with the focus on working with form and validation. The front-end features a comprehensive form allowing users to input sender and recipient details, including image preview capabilities, with rigorous client-side validation for all fields. The backend is based on Express, which handles form submissions, applying server-side validation. Specific routes are defined to serve the payment form and process post-payment outcomes, redirecting to either success or error pages based on the validation results. Successful transactions showcase detailed payment summaries, dynamically generated using Handlebars templates. 

## Assignment 4:
### Howler v1
https://csc342-141.csc.ncsu.edu/hw4/
Howler is a social network-like platform where users can share their thoughts in posts called 'howls'. The application allows users to post text entries, follow others and view posts from users they follow. The project entails both backend and frontend development, implementing a REST API using Express and a responsive frontend with Bootstrap.

To login, the username can be found from the mock data in /src/data/users.json. The password is their id.
example:
username: student
password: 1

## Assignment 5:
### Howler v2 with Authentication
csc342-141.csc.ncsu.edu

This assignment is a progression from the previous one with addition features. 
 - User Registration: Integrated user registration, which allows new users for this assignment. 
 - JWT Integration: Created functions to generate JWT tokens and verify JWT tokens. The token is stored in an HTTP-only cookie, which is used to track the user's session and prevent unauthorized access to protected endpoints and pages.
 - Security: Building on the previous assignment, user passwords are now hashed using a unique salt generated for each user during registration.