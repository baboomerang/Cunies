# Rocketship

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Using [Polygon API](https://polygon.io/), Rocketship

### App Evaluation
- **Category:** Productivity and Education
- **Web/Mobile:** This app takes a web first approach, but is fully viable for usage with full functionality as a mobile app. 
- **Story:** CUNY's course management system - Blackboard  - is not a favorite among CUNY students. This app relieves the difficulties of tracking assignment due dates and course info by pulling the data and making it more presentable, with live reminders that will help you keep on track. Users may also add and edit custom courses and assignments.
- **Market:** This app is mainly for use by students of CUNY schools that use Blackboard, but can technically be used by any student.
- **Habit:** This app is a low-interaction app and will not take up much user screen time.
- **Scope:** First we would like to target John Jay students and potentially expand to inter-college. Large potential for social media integration.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User will signup/login using their blackboard/cunyfirst credentials.
* User views course assignments in a calendar or chronological list.
* User adds any missing courses/assignments that are not on Blackboard.
* User gets reminders for assignments based on alert preference.
* User save select courses to be on alert for class openings.
* User can edit settings (General, Accessibility, Notifications)


**Optional Nice-to-have Stories**

* Social Media aspect where students can meet other users (friend requests, in-app messaging) from mutual courses. (This is possible in BB but only through snail-mail)


### 2. Screen Archetypes

* Login/Register
   * The first screen after launch will be the Login/Register
* Home
   * Here, the user sees a overview of what is of priority for the current day and near future. It will include a mini-calendar and notifcation banners.
* Courses
    * Here, the user has CRUD access to a simple list of currently enrolled courses, room \#, professor, and course overview.
* Schedule
    * Here, the user sees a full-page calendar of what is of due for a given date.
* Assignments
    * Here, the user has CRUD access to a list of what is of all assignments, either chronogical or categorical by course.
* Settings
    * Here, the user can edit their alert preferences, name, display style.

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Home: Front page with "Today's" plant watering schedule, optional reminder notepad
* Add Plant: Access to camera (OCR API) that allows users to take a picture of their plant or add their own plant details
* Plant Diary: Collection of all plant data and inputs as a gallery

**Flow Navigation** (Screen to Screen) 


## Low Fidelity Wireframes
<img src="https://i.ibb.co/DLbKwrm/cunies-web-app.png" width=600>


## Schema 

### Models
| Property      | Type     | Description |
   | ------------- | -------- | ------------|
   |               |          |             |
   |               |          |             |
   |               |          |             |
   |               |          |             |
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each network request]
- [OPTIONAL: List endpoints for Blackboard API]
