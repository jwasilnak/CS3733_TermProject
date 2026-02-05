# Software Requirements and Use Cases

## Your Project Title
--------
Prepared by:

* `<author1>`,`<organization>`
* `<author1>`,`<organization>`
* `<author1>`,`<organization>`
* `<author1>`,`<organization>`

---

**Course** : CS 3733 - Software Engineering

**Instructor**: Sakire Arslan Ay

---

## Table of Contents
- [1. Introduction](#1-introduction)
- [2. Requirements Specification](#2-requirements-specification)
  - [2.1 Customer, Users, and Stakeholders](#21-customer-users-and-stakeholders)
  - [2.2 User Stories](#22-user-stories)
  - [2.3 Use Cases](#23-use-cases)
- [3. User Interface](#3-user-interface)
- [4. Product Backlog](#4-product-backlog)
- [4. References](#4-references)
- [Appendix: Grading Rubric](#appendix-grading-rubric)

<a name="revision-history"> </a>

## Document Revision History

| Name | Date | Changes | Version |
| ------ | ------ | --------- | --------- |
|Revision 1 |2026-1-30 |Initial draft | 1.0        |
|      |      |         |         |
|      |      |         |         |

----
# 1. Introduction


Our project aims to create an online application system for students to apply to teaching assistant positions and have professors for those courses accept or deny applications. The purpose of creating this application is to streamline the process for finding PLAs, a process that as of now is mostly manual. In the application we hope to provide a simple way for students to enter their info and help to match them to a PLA postition best suited for them. Once the student choses positions to apply to professors will be able to look through applicants for their courses and chose to accept or deny them. 

----
# 2. Requirements Specification

This section specifies the software product's requirements. Specify all of the software requirements to a level of detail sufficient to enable designers to design a software system to satisfy those requirements, and to enable testers to test that the software system satisfies those requirements.


## 2.1 Customer, Users, and Stakeholders



The customers/users for our software will be the students of WPI and the professors of WPI. They will be the only users as you will need a wpi email to sign onto the software. The main stakeholders in the software would be WPI administration as this would add a better process for PLA applications and would be better for the students and professors.

----
## 2.2 User Stories
This section will include the user stories you identified for your project. Make sure to write your user stories in the form : 
"As a **[Role]**, I want **[Feature]** so that **[Reason/Benefit]** "

New User:
  1. As an new user, I want to register for an account so that I can access the PLA application system.
  1. As a new user, I want to be able to find my email in the system so that if I am an instructor I can see the applicants for my courses
  1. As a new user, I want to be able to create a new account with my wpi email so that if I am a student I can apply for PLA positions.

Student:
  2. As a student, I want to be able to log onto the system with my WPI SSO, so that I can access the PLA application system securely

  2. As a student, I want to be able to input my relevant experience to my profile, so that when finding courses I can find them relating to my experience.

  2. As a student, I want to be able edit my profile so that if my information changes it will be up to date for any future applications.

  2. As a student, I want to be able to view the open PLA positions so that I can find positions I want to apply for.

  2. As a student, I want to be able to view reccomended PLA positions based on my profile so that I can find positions best fit for me.

  2. As a student, I want to be able to apply for multiple PLA positions, so I can send my application to multiple professors with ease.

  2. As a student, I want to be able to view the status of my applications, so that I can see if my applications are pending, accepted, or denied.

  2. As a student, I want to be able to widthdrawl pending applications, so that if I get accepted to another position or lose intrest I won't be stuck in a position.

  2. As a student, I want to be able to log out of my account, so that when I am done my account can't be accessed by anyone.

Instructor:
  3. As an instructor, I want to view PLA applicants for my courses, so that I can select students to PLA for my course.

  3. As an instructor, I want to be able to activate my account so that I can access the PLA application system.

  3. As an instructor, I want to be able to log in with my WPI sso so that I can access my account securely.

  3. As an instructor, I want to be able to view my profile, so that I can see my courses and other information.

  3. As an instructor, I want to be able to edit my profile, so that I can change courses I am instructing or any other information.

  3. As an instructor, I want to be able to add course sections, so that I can open new PLA positions for them.

  3. As an instructor, I want to be able to open new PLA positions for the courses I run, so that students can apply to them.

  3. As an instructor, I want to be able to see available applicants for my PLA positions, so that I can approve new students.

  3. As an instructor, I want to be able to see the profile of applicants so that I can approve an applicant best fit for my class.

  3. As an instructor, I want to be able to approve a PLA application so that I can send a response to the applicant and have them as my course PLA.

  3. As an instructor, I want to be able to deny a PLA applicant, so that the student can have their application status updated.

  3. As an instructor, I want to be able to log out of my account securely so that no one besides me can access it.

----
## 2.3 Use Cases

This section will include the specification for your project in the form of use cases. 

Group the related user stories and provide a use case for each user story group. You don't need to draw the use-case diagram for the use cases; you will only provide the textual descriptions.  **Also, you don't need to include the use cases for "registration" and "login" use cases for both student and faculty users.**

  * First, provide a short description of the actors involved (e.g., regular user, administrator, etc.) and then follow with a list of the use cases.
  * Then, for each use case, include the following:

    * Name,
    * Participating actors,
    * Entry condition(s) (in what system state is this use case applicable),
    * Exit condition(s) (what is the system state after the use case is done),
    * Flow of events (how will the user interact with the system; list the user actions and the system responses to those),
    * Alternative flow of events (what are the exceptional cases in the flow of events and they will be handles)
    * Iteration # (which sprint do you plan to work on this use case) 

Each use case should also have a field called "Iteration" where you specify in which iteration you plan to implement this feature.

You may use the following table template for your use cases. Copy-paste this table for each use case you will include in your document.

| Use case # 1      |   |
| ------------------ |--|
| Name              | "enter your reponse here"  |
| Participating actor  | "enter your reponse here"  |
| Entry condition(s)     | "enter your reponse here"  |
| Exit condition(s)           | "enter your reponse here"  |
| Flow of events | "enter your reponse here"  |
| Alternative flow of events    | "enter your reponse here"  |
| Iteration #         | "enter your reponse here"  |



| Use case # 1      |   |
| ------------------ |--|
| Name              | Register |
| Participating actor  | New User |
| Entry condition(s)     |  |
| Exit condition(s)           | "enter your reponse here"  |
| Flow of events | "enter your reponse here"  |
| Alternative flow of events    | "enter your reponse here"  |
| Iteration #         | "enter your reponse here"  |
----
# 3. User Interface

Here you should include the sketches or mockups for the main parts of the interface.
You may use Figma to design your interface:

  Example image. The image file is in the `./images` directory.
  <kbd>
      <img src="images/figma.jpg"  border="2">
  </kbd>
  
----
# 4. Product Backlog

Here you should include a link to your GitHub repo issues page, i.e., your product backlog. Make sure to create an issue for each user story.  

----
# 5. References

Cite your references here.

For the papers you cite give the authors, the title of the article, the journal name, journal volume number, date of publication and inclusive page numbers. Giving only the URL for the journal is not appropriate.

For the websites, give the title, author (if applicable) and the website URL.

----
----
# Appendix: Grading Rubric
(Please remove this part in your final submission)

Please see Canvas for the grading rubric. 