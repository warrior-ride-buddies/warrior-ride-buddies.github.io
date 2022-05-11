# Warrior Ride Buddies

![ci-badge](https://github.com/warrior-ride-buddies/warrior-ride-buddies/workflows/ci-warrior-ride-buddies/badge.svg)

## Table of contents

* [Overview](#overview)
* [User Guide](#user-guide)
* [Deployment](#deployment)
* [Development History](#development-history)
* [Developer Guide](#developer-guide)
* [Community Feedback](#community-feedback)
* [Contact Us](#contact-us)

## Overview
The goal of Warrior Ride Buddies is to connect UH Manoa students with similar commutes, enabling them to organize car-pools. 
This application will help students save money on gas and parking.

Here is the link to our [organization](https://github.com/warrior-ride-buddies) and the [team contract](https://docs.google.com/document/d/1JwVIlZwdnLveOPWr_WfwH-5iD-kGBiF5fv1-mwz5sEc/edit?usp=sharing) we created at the beginning of this project.

Here is a link to our project [Warrior-Ride-Buddies](https://warriorridebuddies.ddns.net/#/)

## User Guide
- Start off by creating your profile including your name, profile photo, UH email address, and address (don't worry, where exactly you are located won't be shared to other users).
- Categorize yourself as a driver, rider, or both if you’re willing.
- Drivers must include the following information about their car: year, make/model, and license plate.
- Adjust your desired arrival times for each day of the week (aka "trips").
- Once your profile is completed, it will be visible on the app’s home page, which is a map populated with other commuters shown in their general starting locations. Users can interact with the map by clicking on other’s profiles and filtering them by various categories.
- Coordinate with other users that have similar commutes by clicking their profile and using our in-app messaging system.

### Deployment
Here is our [deployed app](https://warriorridebuddies.ddns.net/).

### Screenshots of Mockups
<p>
<img src="images/LandingPage.png">
On the landing page, the user can gain more insight about how the application works.
</p>

<p><img src="images/HomePage.png">
Using the filters on the left, users can search for other users (driver/riders) that are suitable for their schedule. Specifically, users can filter by time, day of the week, and driver/rider. Additionally, they can clear the filter by clicking on the bottom right erase icon.</p>

<p><img src="images/MapPin.png">
Clicking on users will reveal a modal that gives more information about the user. From here, users can click on the "message" button to message this user to carpool or press the red report button if needed.</p>

<p><img src="images/Report.png">
If a user is behaving inappropriately on the application, people can report them. Additionally, the reporter can include a message about why this person is being reported for the admin to read. 
</p>

<p><img src="images/InboxPage.png">
Once riders or drivers discover people that they can carpool with, they can message people through the application. This page keeps track of users this user has messaged. At the top there's a selector and "Create Pool!" button for users to create a conversation with one or more people in the application to arrange a car pool.</p>

<p><img src="images/Messages.png">
After clicking on a user on the inbox page, past messages are displayed on a modal. The user can continue the conversation by sending messages through the input area at the bottom.</p>

<p><img src="images/ProfilePage.png">
Every user has a profile page that contains information about themselves that are pertinent to the application (i.e. Name, location, car information, and up-to-date schedule). To access it, users need to navigate to the right of the navbar and click their profile picture or email to open a dropdown and then click "view profile". The user can edit his/her own schedule (aka trips) directly on this page. </p>

<p><img src="images/Trip.png">
This page allows new users to create new trips (to or from UHM) in their schedule for other users to see.</p>

<p><img src="images/OtherProfilePage.png">
When viewing another user's profile, pertinent information is shown (i.e. location, car info, schedule) and a button to message the user.
</p>

<p><img src="images/RegisterPage.png">
This page allows new users to create an account for this application.</p>

<p><img src="images/CreateProfilePage.png">
Upon registering, the user will complete this form to fully setup their account. Specifically, users need to enter relevant, personal information about themselves such as their name and address.</p>

<p><img src="images/EditProfilePage.png">
If needed, users can edit information about themselves through this form. To access this form, users need to navigate to the right of the navbar and click their profile picture or email to open a dropdown and then click "edit profile".</p>

<p><img src="images/ViewProfilesPage.png">
This page allows users to view all of the profiles available in the application.</p>

<p><img src="images/AdminPage.png">
If anyone is reported, the report is displayed here for admin users to review and take action. Additionally, the admin can view conversations between the reportee and reporter to help reach a decision.</p>

## Development History
### Milestone #1:
[M1 project page](https://github.com/warrior-ride-buddies/warrior-ride-buddies/projects/1)

For this milestone, our teammates dedicated around a week and half. In this time we:
* Brainstormed what we wanted this application to do.
* Created mockup pages of what the application should look like and what functionality the application will have.
* Created issues and came up with future "quality of life" updates to be done to the application in the future.
* Divided the issues up so that each member has at least 2 issues.

### Milestone #2:
[M2 project page](https://github.com/warrior-ride-buddies/warrior-ride-buddies/projects/2)

For this milestone, our teammates dedicated around a week and half. In this time we:
* Allowed users to create and edit accounts that are usable in the application
  * Location and time per day can be specified per person
  * Car information can be recorded
* Allowed users to filter pins on the main page to find riders or drivers suitable for their schedule
* Gave users the ability to message other users through the application

### Milestone #3:
[M3 project page](https://github.com/warrior-ride-buddies/warrior-ride-buddies/projects/3)

For this milestone, our teammates dedicated around 2 weeks. In this time we:
* Improved the user's profile functionality by
  * Implementing a way to upload personal photos
  * Not requiring the user to input the make of their car
  * Created a scheduling form
* Updated the messaging feature to allow for group chatting
* Implemented the map pins to have functionality.
* Created the report functionality.
* Added more automated testing features to make sure our site ran correctly.
* Got community feedback on our site.

## Developer Guide
This section provides information of interest to Meteor developers wishing to use this code base to expand upon.

### Installation
First, install Meteor.

Second, visit the this application's github page, and click the “Code” button to create a local copy. Alternatively, you can download the sources as a zip file or make a fork of the repo. However you do it, download a copy of the repo to your local computer.

Third, cd into the warrior-ride-buddies/app directory and install libraries with:

`$ meteor npm install`

Fourth, run the system with:

`$ meteor npm run start`

If all goes well, the application will appear at [http://localhost:3000](http://localhost:3000).

## User Interface Quality Assurance and Usability Testing 
Before conducting the test, please google a location on the island of Oahu and find longitude and latitude coordinates for that location. Provide this information to test subjects before the examination. 

Please take notes on what test subjects struggle to complete on the first attempt. Also, note where they navigated or attempted to do to complete said task. Also, log in as Young-Sung Masuda (admin@foo.com). 

Script:

Thank you very much for participating in the Warrior Ride Buddies User Interface Quality Assurance and Usability testing. Today you will be testing the Warrior ride buddies application for practicality, ease of use, and user interface design. This means you will be interacting with the application, attempting to complete a set of tasks. Please note that we are testing the application, not the participant. There are no incorrect answers for any portion of this exercise. 

Task 1: Please navigate to the https://warriorridebuddies.ddns.net and create an account, we have provided longitude and latitude. We will be registering as a Rider; doing so also means that car information is not required. Please leave the profile picture as default. <br/>
Task 2: You will travel to UH Manoa on Tuesdays and need to arrive on campus by 10:30am, add a "trip" to your schedule to let people know your intentions. <br/>
Task 3: Find a Driver and send them a message asking if they can pick you up, taking you to UH Manoa on Tuesday. You will need to arrive on campus by 10:30 am. <br/>
(Send a message saying no to the test subject in a rude tone such as "why would I help someone like you?", this will be used for the next task)<br/>
Task 4: Oh my gosh, Yong-Sung is being so rude! Please report him to an admin and explain why you are reporting him. <br/>
Task 5: You decide that the picture provided for the profile did not suit you well. Please change your picture to something else. Use a photo on your computer or find one online, download it, and upload it. <br/>
Task 6: You have successfully used the application. Please go ahead and log out. <br/>

Ask if the user has any questions, comments, or concerns about the project. 

Thank them for their participation and end test. 

## Community Feedback

After milestone 2 we collected feedback from the community to see what they thought about our site and how we improve user experience. Here's some of the suggestions people had to say about our site:
* The "Find your buddy" header on the main page looks like a button which is misleading.
* Have some way to indicate that a new message was sent.
* Having to input latitude and longitude is unnecessary.
* Edit/remove the footer.
* Have a way to view the profile of the person you're messaging from the main page instead of having to click around the site.
* Overall functionality and look was great.
* Filtering by location would have been nice.
* Slightly confusing way to work web application for the first time.
* Reporting a user only goes so far, i.e. if anything happens in person and not through messages, admin will have no proof to act upon.
* For "add people" search bar, it would be cool to have user's profile show up next to name.

## Contact Us
Here are the developers of this application. If you want to get in contact with them, here are their professional portfolios:
* [Kobey Arai](https://kobeyarai808.github.io/)
* [Alyssia Chen](https://alyssia-chen.github.io/)
* [William Liang](https://william-liang808.github.io/)
* [Yong-Sung Masuda](https://yongsungm.github.io/)
* [Scott Yuk](https://scott-yuk.github.io/)

Here is our [team contract](https://docs.google.com/document/d/1JwVIlZwdnLveOPWr_WfwH-5iD-kGBiF5fv1-mwz5sEc/edit?usp=sharing)

## Future ideas to implement
* Deal with Unsolicited Interactions (Blocking, etc.)
* Convert Web app to React Native
* Provided a recommended tip/gratuity
* Implement safety features
