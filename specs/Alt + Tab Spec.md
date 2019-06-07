# **PowerToys Alt+Tab Spec**

![MS PowerToys](https://hothardware.com/ContentImages/NewsItem/48038/content/Microsoft_PowerToys.jpg "PowerToys")
## Users can quickly access and organize open programs and tabs.
### Authors: Benjamin Leverette and Prudence Phillips
### Spec Status: Draft
## 1. Overview

**1.1. Elevator Pitch / Narrative** 

David loves to multitask and wants to be able to organize and group all of the programs he likes to run at the same time.  He downloads the Alt+Tab PowerToy that allows him to search through all his running programs, group similar programs, and traverse the tabs of programs.

**1.2. Customers**

Like all utilities from PowerToys, the Alt+Tab feature is for power users and developers who are looking to tune and streamline their Windows experience for greater productivity.
  
**1.3. Problem Statement and Supporting Customer Insights**

Power users need a way to better search, traverse, and organize the multitude of programs they may have running at the same time.  Our PowerToys Consumer Survey received feedback validating the usefulness of a feature that provides such functionality.

**1.4. Existing Solutions or Expectations**

Users currently must traverse program by program using the mouse, Tab, or arrow keys to search and select the program they want to access.  Alternatively, they can access running programs from the taskbar.  There are also third-party resources that allow users to switch tasks similarly.

We expect users to install and enable PowerToys for Windows in order to access the new Alt+Tab utility.

**1.5. Goals/Non-Goals**

Design and develop a feature that can search, traverse, and group running programs within an 8 week period.

## 2. Definition of Success

**2.1. Expected Impact: Customer, and Technology Outcomes, Experiments + Measures**

Our PowerToys Consumer Survey received an abundant amount of particiaption and feedback from a community of passionate power users.  This feature will give them the ability to search, traverse, and group tasks in a way that makes their virtual environment more organized and efficient.  As interns, we would have 8 weeks to complete the project.

## 3. Requirements

**3.1.	Functional Requirements**

- Users must use a shortcut to open the Alt + Tab utility, which provides the following features:
  - Searches through active programs after the user types the name of the program they are seeking in the search bar.
  - Groups running programs into expandable stacks as the user clicks, holds and drags windows on top of another.
  - Stacks expand when user hovers mouse cursor over a stack.
  - Opens a running program after the user selects it by clicking the window with a mouse or using the directional keys and hitting the Enter key.
- Shortcut should take accessibility into account.
  - Shortcut can remain as Alt + Tab keys.

![Figure 1-1](https://raw.github.com/indierawk2k2/PowerToys-1/images/PT%20Images/Alt%20+%20Tab%20Blurred.png "A+T")

**3.2. Measure Requirements**

- Survey what power users want out of the Alt+Tab feature through forms and Github.

## 4. Dependencies

- Explore Internship Program limits us to an 8-week window to complete the task.

- Availability of public API's
