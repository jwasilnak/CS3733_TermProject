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

  2. As a new user, I want to be able to find my email in the system so that if I am an instructor I can see the applicants for my courses

  3. As a new user, I want to be able to create a new account with my wpi email so that if I am a student I can apply for PLA positions.

Student:
  1. As a student, I want to be able to log onto the system with my WPI SSO, so that I can access the PLA application system securely

  2. As a student, I want to enter my major(s), GPA, programming languages, and any prior PLA experience so that instructors can evaluate my fit for PLA positions.

  3. As a student, I want to be able edit my profile so that if my information changes it will be up to date for any future applications.

  3. As a student, I want to be able to view the open PLA positions so that I can find positions I want to apply for.

  4. As a student, I want to be able to view reccomended PLA positions based on my profile so that I can find positions best fit for me.

  5. As a student, I want to be able to apply for multiple PLA positions, so I can send my application to multiple professors with ease.

  6. As a student, I want to be able to view the status of my applications, so that I can see if my applications are pending, accepted, or denied.

  7. As a student, I want to be able to widthdrawl pending applications, so that if I get accepted to another position or lose intrest I won't be stuck in a position.

  8. As a student, I want to be able to log out of my account, so that when I am done my account can't be accessed by anyone.

Instructor:
  1. As an instructor, I want to view PLA applicants for my courses, so that I can select students to PLA for my course.

  2. As an instructor, I want to be able to activate my account so that I can access the PLA application system.

  3. As an instructor, I want to be able to log in with my WPI sso so that I can access my account securely.

  4. As an instructor, I want to be able to view my profile, so that I can see my courses and other information.

  5. As an instructor, I want to be able to edit my profile, so that I can change courses I am instructing or any other information.

  6. As an instructor, I want to be able to add course sections, so that I can open new PLA positions for them.

  7. As an instructor, I want to be able to open new PLA positions for the courses I run, so that students can apply to them.

  8. As an instructor, I want to be able to see available applicants for my PLA positions, so that I can approve new students.

  9. As an instructor, I want to be able to see the profile of applicants so that I can approve an applicant best fit for my class.

  10. As an instructor, I want to be able to approve a PLA application so that I can send a response to the applicant and have them as my course PLA.

  11. As an instructor, I want to be able to deny a PLA applicant, so that the student can have their application status updated.

  12. As an instructor, I want to be able to log out of my account securely so that no one besides me can access it.

  As an instructor, I want the system to prevent approving students who are already assigned to another PLA position so that each student is only assigned once.

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
| Entry condition(s)     | User clicks on the register button |
| Exit condition(s)           | User submits the register form |
| Flow of events | User clicks on the register button on sign on page, user picks student register, user enters their information, user submits register form. |
| Alternative flow of events    | User clicks on the register button on the sign on page, user picks instructor register, database finds the instructor's email in db, user submits register form. |
| Iteration #         | 1 |
----

| Use case # 2      |   |
| ------------------ |--|
| Name              | Login  |
| Participating actor  | Student and Instructor |
| Entry condition(s)     | User opens application to sign on page. |
| Exit condition(s)           | User clicks the sign on button after entering info |
| Flow of events | User opens application to login page, user enters their login information, user clicks sign in button. |
| Alternative flow of events    | User opens application to login, user enters information not in db, error message is given to user. |
| Iteration #         | 1 |

| Use case # 3      |   |
| ------------------ |--|
| Name              | Display Profile |
| Participating actor  | Student, instructor  |
| Entry condition(s)     | User clicks on the profile button |
| Exit condition(s)           | student info is displayed on screen |
| Flow of events | User clicks on the display profile button, database retrieves the users information, system displays that information in html format, student gets that information displayed on their screen |
| Alternative flow of events    | Professor clicks on student's view profile button, db retrieves student's info, system formats as html, student info is displayed on screen. |
| Iteration #         | 1 |

| Use case #  4     |   |
| ------------------ |--|
| Name              | Edit profile  |
| Participating actor  | Student  |
| Entry condition(s)     | user clicks on edit profile button  |
| Exit condition(s)           | db registers update to students profile |
| Flow of events | User clicks on edit profile page on their profile, user inputs new info into form, user clicks on submit changes button, db adds and commits info to their student object  |
| Alternative flow of events    |   |
| Iteration #         | 1 |

| Use case #  5     |   |
| ------------------ |--|
| Name              |  View PLA positions |
| Participating actor  | Student |
| Entry condition(s)     | user clicks on view positions button |
| Exit condition(s)           |  system displays all open PLA positions |
| Flow of events | On index student clicks on view positions button, db retrieves all PLA positions with openings, system formats all positions, system displays positions on screen.  |
| Alternative flow of events    | Student clicks view positons button, db finds no open positions, system flashes message to user. |
| Iteration #         | 1 |

| Use case # 6      |   |
| ------------------ |--|
| Name              | Recommended Positions  |
| Participating actor  | Student |
| Entry condition(s)     | Student filters positions by recommended |
| Exit condition(s)           | system displays recommended positions, system displays message |
| Flow of events | Student is on positions page, student uses filter by recommended button, db finds positions with similar tags to student's experience tags, system formats positions, system displays the positions |
| Alternative flow of events    | Student uses filter by recommended button, db can not find any positions with similar tags, system flashes error message |
| Iteration #         | 2 |

| Use case # 7      |   |
| ------------------ |--|
| Name              | Apply |
| Participating actor  | Student |
| Entry condition(s)     | Student clicks on PLA position apply button |
| Exit condition(s)           | system displays a success message |
| Flow of events | Student clicks on apply button, db retrieves positions attributes, student clicks submit application button, db retrive's students info, system sends student info to instructor's application list, system displays success message. System displays relevant student information.|
| Alternative flow of events    |   |
| Iteration #         |1|

| Use case #8 | |
|-------------|--|
| Name | View Application Status |
| Participating actor | Student |
| Entry condition(s) | Student is logged in |
| Exit condition(s) | Student sees the list of their applications and current statuses |
| Flow of events | Student clicks on “My Applications”. System displays all PLA applications with status (Pending, Accepted, or Denied). |
| Alternative flow of events | If the student has no applications, system displays a message saying no applications exist. |
| Iteration # | 1 |

| Use case #9 | |
|-------------|--|
| Name | Withdraw Application |
| Participating actor | Student |
| Entry condition(s) | Student is logged in and has a pending application |
| Exit condition(s) | The selected application is withdrawn |
| Flow of events | Student selects a pending application and clicks “Withdraw”. System removes the application and updates the status list. |
| Alternative flow of events | If the application is already accepted or denied, system displays an error message. |
| Iteration # | 1 |

| Use case #10 | |
|--------------|--|
| Name | Create PLA Position |
| Participating actor | Instructor |
| Entry condition(s) | Instructor is logged in |
| Exit condition(s) | A new PLA position is created and visible to students |
| Flow of events | Instructor selects a course and enters PLA requirements. System saves the position and marks it as open. |
| Alternative flow of events | If required fields are missing, system displays an error message. |
| Iteration # | 1 |

| Use case #11 | |
|--------------|--|
| Name | View Applicants |
| Participating actor | Instructor |
| Entry condition(s) | Instructor is logged in and has a PLA position |
| Exit condition(s) | Instructor sees the list of applicants |
| Flow of events | Instructor opens a PLA position. System displays all student applicants for that position. |
| Alternative flow of events | If no students have applied, system displays a message saying no applicants yet. |
| Iteration # | 1 |

| Use case #12 | |
|--------------|--|
| Name | Approve PLA Application |
| Participating actor | Instructor |
| Entry condition(s) | Instructor is viewing an applicant |
| Exit condition(s) | Application status is updated to Accepted |
| Flow of events | Instructor selects an applicant and clicks “Approve”. System updates the application status and notifies the student. |
| Alternative flow of events | If the PLA position is full or the student is already assigned to another PLA position, the system prevents approval and displays an error. |
| Iteration # | 1 |

| Use case #13 | |
|--------------|--|
| Name | Deny PLA Application |
| Participating actor | Instructor |
| Entry condition(s) | Instructor is viewing an applicant |
| Exit condition(s) | Application status is updated to Denied |
| Flow of events | Instructor clicks “Deny”. System updates the application status and notifies the student. |
| Alternative flow of events | None |
| Iteration # | 1 |

here: Put them after Use case #10 or anywhere in the instructor block.

| Use case #14 | |
|--------------|--|
| Name | Activate Instructor Account |
| Participating actor | Instructor |
| Entry condition(s) | Instructor is on the activation page and their email exists in the system’s instructor list |
| Exit condition(s) | Instructor account is activated |
| Flow of events | Instructor enters their email and clicks “Activate”. System sends a verification email. Instructor clicks the verification link. System activates the account and confirms success. |
| Alternative flow of events | If the email is not in the instructor list, system shows an error and does not activate the account. |
| Iteration # | 1 |

| Use case #15 | |
|--------------|--|
| Name | Add Course Section |
| Participating actor | Instructor |
| Entry condition(s) | Instructor is logged in |
| Exit condition(s) | A course section is added and can be used to create PLA positions |
| Flow of events | Instructor selects “Add Course Section”, chooses a course, enters section and term, and submits. System saves the course section and shows it in the instructor’s course list. |
| Alternative flow of events | If the same course+section+term already exists, system shows an error message. |
| Iteration # | 1 |



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
https://github.com/jwasilnak/CS3733_TermProject/issues

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