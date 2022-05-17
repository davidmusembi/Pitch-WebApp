# Pitch-WebApp
A web application that gives the user an opportunity to pitch ideas, login, comment and vote on pitches:

## By David Musembi

## live link
 : # Link: https://pitch-webapp.herokuapp.com/

## Description
Pitch is a web application that users can pitch ideas, comment and vote on other pitches. It requires for a new user to register and login to access some of the functions like add a pitch, comment and vote

## Specifications
* Users can view other people pitches
* Users can vote on other pitches
* Users can register and login to add new pitches and comment
* Users can submit pitches in four different categories

## Prerequisites
* Python 3.10.4 required

## Setup/Installation Requirements
Follow the following commands to run the project
* git clone/download ```git@github.com:davidmusembi/Pitch-WebApp.git```
* cd Pitch
* Edit the start.sh file with your api key from the news.org website
* Install python 3.10.4
* Run ```chmod a+x start.py```
* Run ```./start.py```

### Behaviour Driven Development
| Behavior            | Input                         | Output                        |
| ------------------- | ----------------------------- | ----------------------------- |
| Index Page loads as default | Home link | Loads the home page. |
| View Business Pitch | Click on Business | Business Pitches are displayed|
| View Interview | Click on Interview | Interview Pitches are displayed|
| View Promotion | Click on Promotion| Promotion Pitches are displayed|
| Add new pitch | Click on New Pitch | Authentication page is displayed and users can add new pitches|
| Add Comment | Click on Comment | Form where user can fill in is displayed after login|



## Known Bugs
None known at the moment.

## Technologies Used
* Python
* HTML
* BOOTSTRAP
* Flask


