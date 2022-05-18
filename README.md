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
* cd Pitch-WebApp
* Edit the start.sh file with your secret key 
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
* SQLAlchemy

## License
[]: # License: MIT
MIT License

Copyright (c) 2022 David Musembi

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
