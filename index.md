![ci-badge](https://github.com/roommate-radar/roommate-radar/workflows/ci-roommate-radar/badge.svg)

## Table of Contents
* [Overview](#overview)
* [Deployment](#deployment)
* [Developer Guide](#developer-guide)
* [User Guide](#user-guide)
* [Mockups](#mockups)
* [Milestones](#milestones)
* [Team](#team)

## Overview
Roommate Radar is a web application designed to assist current students at the University of Hawaii at Manoa who desire to live off campus with finding roommates. It allows users to connect with other students and find people who they can co-habitate with in peace.

In order to help users connect, we present users with bite-sized views of a variety of other users' profiles which can be filtered to allow users to only see profiles relevant to them. If a user sees another user they want to learn more about, they can then go to that user's profile page, where they can acquire further information about them. If they see nothing there to dissuade them, they then can either acquire that user's information on various social media platforms to contact them, or contact them directly through the site. Furthermore, we potentially allow users to subscribe to SMS or email updates, allowing them to be informed when another user on Roomate Radar contacts them.

## Deployment
Come check out Roommate Radar [here](https://roommate-radar.com)!

## Developer Guide
This sections gives the users a guide to installing Meteor who wish to use this code as a base for their own developments.
### Installation
First, [install Meteor](https://www.meteor.com/developers/install).

Second, visit the [Roommate Radar application github page](https://github.com/roommate-radar/roommate-radar), and click the "Code" button. Then, clone the directory onto your local computer. You can download the source as a zip file or create a fork of the repo. Alternatively, using applications like [Github Desktop](https://desktop.github.com/) work well too. 

Third, cd into the roommate-radar/app directory and install libraries with:
```
$ meteor npm install
```
### Running the Application
Lastly, once the libraries are installed, you can run the application by invoking:
```
$ meteor npm run start
```
If all goes well, the application will start up and appear at [http://localhost:3000](http://localhost:3000).

## Community Feedback
"The website seems to built on a strong foundation. The cards page looks like a typical craigslist site with some features still in development like the editing profile feature. One of the most interesting features was the social media icons that show up on a user's profile depending if they filled it out in their profile. The looks of the website is a bit basic but I feel that the site has a lot of potential and I think this would be useful for UH students if fully fleshed out. " -Justin 

"The website looks good so far. I like the login features as well as the social media features as it is unique compared to other websites. I believe that the styling for the page could look better in terms of coloring as grey seems to be like a dull color. For the most part, the functionality of the webiste seems to do what it was intended to do." - Stevie 

"I feel like the website could be more lively with better coloring as grey seems to be such a boring color. Even though the website is not fully developed, most of the functionality is working and seems cool. I think that social media functionality is cool as it only shows the icon if there is a social media. I believe that this functionalize as it intends to do, but it could have a bit more functions to work with." - John 

"This website looks nice, but maybe you could use the school colors like green and white. The site looks user-friendly and easily accessible as there is a process in crerating the account with the sign up functionality. The website works well as it does what it is intended to do. Additionally, the process is easy to understand and the navigation bars is logically easy to understand" - Anthony 

"I like the design of the homepage because its pleasing to look at and easy to navigate. I think the logo is clever. I think the color of the website should be darker to match the landing page image better. I think darker colors would complement the image more.  think that when signing up and editing your user profile, it would be easier to match and sort preferences if users could select options from a check-box list or dropdown menu." - Charlotte

## User Guide
### Landing Page
The landing page is the first page any prospective user will be presented with upon loading up Roommate Radar. On this page, potential users will be informed of what Roommate Radar is, and instructed to make an account.
![](/images/landing_screenie.png)

### Sign Up and Sign In
In order to start using Roommate Radar, users must first make an account. To do so, they must select the "Sign up" button to go to the following page and sign up. They must create an account including a username, password, and associated UH email address.
![](/images/register_screenie.png)

Upon creating an account with Roommate Radar, users must then populate and create their profile so that other users can use the information within to connect with them.
![](/images/createprofile_screenie.png)

Alternatively, you can select "Sign in" to go to the following page and log in if you have an existing account.
![](/images/signin_screenie.png)

### Profiles List Page
The profiles page lists cards containing the details of all the users of Roommate Radar, and also contains a myriad of filter options to help users find others like them.
![](/images/listprofiles_screenie.png)

### User's Profile Page
The user's profile page contains the details of the users themselves when they created their own profile. Upon entering this page, they can edit their own profile with the "Edit Profile" button.
![](/images/myprofile_screenie.PNG)

### Edit Profile Page
A user can edit their own profile page and change any details which will be updated throughout the application.
![](/images/editprofile_screenie.PNG)

Several examples of potential filter options for the Profiles List Page

## Milestones
* [Milestone 1](https://github.com/roommate-radar/roommate-radar/projects/1)
* [Milestone 2](https://github.com/roommate-radar/roommate-radar/projects/2)
* [Milestone 3](https://github.com/roommate-radar/roommate-radar/projects/3)

## Team
Roommate Radar is created by:
* [Brandon Au](https://brandonow.github.io/)
* [Raphael Bumanlang](https://raphaelbumanlag.github.io/) 
* [Kristian Lazo](https://lazokris.github.io/)
* [Lily Lonborg](https://github.com/Somewha7)
* [Justin Yip](https://jyip808.github.io/)
