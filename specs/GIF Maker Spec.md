# **PowerToys GIF Maker Spec**

<img src="https://hothardware.com/ContentImages/NewsItem/48038/content/Microsoft_PowerToys.jpg" alt="Figure 1-2" width="500"/>

## Users can record their screen and turn the recording into a GIF.
### Authors: Benjamin Leverette and Prudence Phillips
### Spec Status: Draft
## 1. Overview
### 1.1. Elevator Pitch / Narrative

 David loves using GIFs to add creativity ti his typical responses to messages.  His friend Amanda emails him and asks what he would like to eat for lunch today.  David recently watched a burrito video, so he uses the GIF maker to screen record a brief moment from the video in order to tell Amanda that its "Burrito Day."

### 1.2. Customers

Like all utilities from PowerToys, the GIF Maker feature is for power users and developers who are looking to tune and streamline their Windows experience for greater productivity.
  
### 1.3. Problem Statement and Supporting Customer Insights

 Power users need a way to better record their screens and use the recordings to create GIFs.  A teammate held a personal interctions with the community that validate the usefulness of a feature that provides such functionality.
### 1.4. Existing Solutions or Expectations

Users currently must use the game bar in order to record the screen, and there is no way to turn recordins into GIFs.  There are third-party resources that allow users to create GIFs online after uploading images and videos.

### 1.5. Goals/Non-Goals

 Design and develop a feature that can record screens and turn them into GIFs within an 8 week period.

## 2. Definition of Success

### 2.1. Expected Impact: Customer, and Technology Outcomes, Experiments + Measures

This feature will give users the ability to screen record and create GIFs effectively and add a new dimension to using GIFs on Windows.  As interns, we would have 8 weeks to complete the project.  Measures of success include:

- A score of an average of 3.75 stars on a new Consumer Design Satisfaction Survey
- Installed by 10% of users who have starred the PowerToys Github
- Uninstalled by less than 30% of users who installed
- Launched by over 60% of users who installed

## 3. Requirements
### 3.1.	Functional Requirements

#### 3.1.1. Initial UX/UI

Users may or may not have any program running on their screen, but they must use a shortcut to open the GIF Maker utility, which opens in the center of the screen.  The window has toolbar at the top that displays a button called 'File' in the upper left corner.

#### 3.1.2. File Button Features

Upon opening the GIF Maker utility, users must click 'File' to begin.  They will have two options: 'New' and 'Open'.

- New
  - If the user clicks 'New' then the screen recording tool appears.
- Open
  - If the user clicks 'Open' then the mini File Explorer window opens for the user to select a video.
  - Once a video is selected, it appears in the GIF Maker, below the tool bar, for the user to edit.
- Save and Save As
  - After the user has selected 'New' or 'Open', the 'Save' and 'Save As' options will also be available the next time the user clicks 'File'.

#### 3.1.3. Screen Recording Tools

- 

#### 3.1.4. GIF Editing Tools

- 

## 4. Dependencies
- Explore Internship Program limits us to an 8-week window to complete the task.

- Availability of public API's
