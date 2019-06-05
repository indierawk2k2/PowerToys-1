# **Terminate Program Spec**

![MS PowerToys](https://hothardware.com/ContentImages/NewsItem/48038/content/Microsoft_PowerToys.jpg "PowerToys")
## Shortcut for users to quickly terminate a running program
### Authors: Benjamin Leverette and Prudence Phillips
### Spec Status: Draft
## 1. Overview

### 1.1. Elevator Pitch / Narrative

Mike is debugging his code in Visual Studio and the program freezes with the "App not responding" text displaying on the title bar, informing him that he cannot continue his work without closing the program and restarting it. Mike has tried to close the program using the close button and end task via the task manager, but none of these mechanisms work in helping him terminate the process so he can proceed with his work. With this PowerToy installed, Mike now has a visual and accessible last-resort method to help him kill the process.

### 1.2. Customers

PowerToys is mainly targeted towards Windows Power Users though it is available to users who want to experience using windows in a more efficient and productive way.
 
  
### 1.3. Problem Statement and Supporting Customer Insights

Windows users need an accessible mechanism to completely kill a process when it is being unresponsive and hindering work flow. The team is still required to find solutions for:

- A public name for this PowerToy.
- The degree to which the process will be terminated.

### 1.4. Existing Solutions or Expectations

The current methods a user can close a running program in Windows include:
- Clicking on the close button in the program
- Closing the program via task manager
- Using the keyboard shortcut Alt + F4 to close the program

### 1.5. Goals/Non-Goals

- Develop this PowerToy and have sufficient time for testing and integration within our assigned 8 weeks for the project. 

- Meet customers expectation with end result of project.

## 2. Definition of Success

### 2.1. Expected Impact: Customer, and Technology Outcomes, Experiments + Measures

The PowerToys repo currently has 200+ people watching, over 4000 stars and 109 forks on github despite having an empty repo. Also, this particular PowerToy received a rating of 3.44/5 in the survey we sent out to the community asking them to rate how useful they think it will be. after the release of this PowerToy, the following will be used to measure our success rate: 

- At least a 5% increase in Github stars within a month of release
- A 3.75/5 rating on a post-completion Consumer Satisfaction Survey on this PowerToy.
- 100 downloads & installs within the first month of release.
- Less than 40% of unistalls by users who install this PowerToy

## 3. Requirements

### 3.1.	Functional Requirements

To use this PowerToy, a user will:

- Click the chosen keyboard shortcut and cursor morphs to indicate that user is in 'Terminate' mode.
- In Terminate mode, whenever a user clicks on a window, it displays a yes/no prompt for the user to confirm that they want to close said window.
    - Note: users can configure in their options to disable the yes/no prompt and just terminate apps instantly.
- Once they are done terminating their apps, user presses keyboard shortcut again to leave terminate mode.

![Terminate](https://raw.github.com/indierawk2k2/PowerToys-1/master/PT%20Images/Terminate%20Blurred.png "Terminate")

- Keyboard shortcut suggestions
    - Alt + Z
    - Alt + Shift + X 

### 3.2 Public Name

The initially proposed name for this app is Terminate App. However, there are multiple other alternative names that we are also considering:

 - Destroy App
 - Knockdown Program
 - Dismantle App

## 4. Dependencies
- The 8 week time limit of the explore internship

- Availabilty of public APIs, since we intend to make this project open source.