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
|Revision 1 |2026-1-30 |Initial draft     | 1.0    |
|Revision 2 |2026-2-5  |Submission Version|2.0     |
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


New User:
  1. As an new user, I want to register for an account so that I can access the PLA application system.

  2. As a new user, I want to be able to find my email in the system so that if I am an instructor I can see the applicants for my courses

  3. As a new user, I want to be able to create a new account with my wpi email so that if I am a student I can apply for PLA positions.

Student:
  1. As a student, I want to be able to log onto the system with my WPI SSO, so that I can access the PLA application system securely

  2. As a student, I want to be able to input my relevant experience to my profile, so that when finding courses I can find them relating to my experience.

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

----
## 2.3 Use Cases


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
| Flow of events | Student clicks on apply button, db retrieves positions attributes, student clicks submit application button, db retrive's students info, system sends student info to instructor's application list, system displays success message |
| Alternative flow of events    |   |
| Iteration #         |1|


| Use case # 8      |   |
| ------------------ |--|
| Name              |  View applications |
| Participating actor  | Student  |
| Entry condition(s)     | Student clicks check applications button |
| Exit condition(s)           | System displays up to date status of student's applications |
| Flow of events | user clicks check applications button, db retrieves data for student's applications latest version, system formats the applications, system displays applications |
| Alternative flow of events    |   |
| Iteration #         | 1 |


| Use case # 9      |   |
| ------------------ |--|
| Name              | View applicants |
| Participating actor  | Instructor |
| Entry condition(s)     | Instructor clicks on button for a courses applicants |
| Exit condition(s)           | System displays all the applicants |
| Flow of events | User clicks on view applicants button for a desired course, db retrieves all the application data associated with the course, system formats the applicants, system displays applicants |
| Alternative flow of events    |   |
| Iteration #         | 2 |

| Use case # 10      |   |
| ------------------ |--|
| Name              | View profile |
| Participating actor  | Instructor |
| Entry condition(s)     | Instructor clicks on view profile button from index |
| Exit condition(s)           | System displays instructor's profile |
| Flow of events | User clicks on view profile, db looks for user's information in instructors table, system formats information, system displays profile |
| Alternative flow of events    |   |
| Iteration #         | 1 |

| Use case # 11      |   |
| ------------------ |--|
| Name              | Edit profile |
| Participating actor  | Instructor |
| Entry condition(s)     | Instructor on profile page clicks edit profile  |
| Exit condition(s)           |  System flashes success message |
| Flow of events | Instructor clicks edit profile button on their profile, instructor fills out edit profile form, instructor hits submit button, db adds adn commits new info to the instructor's profile, system flashes success message |
| Alternative flow of events    |   |
| Iteration #         | 1 |

| Use case # 12      |   |
| ------------------ |--|
| Name              | Add course  |
| Participating actor  | Instructor |
| Entry condition(s)     | Instructor clicks add course on profile button |
| Exit condition(s)           | System flashes success message |
| Flow of events | User clicks add course button, user fills out course form, user submits form, db adds new course to course table, system flashes success message |
| Alternative flow of events    |   |
| Iteration #         | 2 |

| Use case # 13      |   |
| ------------------ |--|
| Name              | View applicants |
| Participating actor  | Instructor |
| Entry condition(s)     |  On a course instructor will click view applicants button |
| Exit condition(s)           | List of applicants displayed |
| Flow of events | User clicks on the view applicants button for a course, db retrieves all the stored applications for that course, system formats the applicants, system displays applicants  |
| Alternative flow of events    |   |
| Iteration #         | 2 |


| Use case # 14       |   |
| ------------------ |--|
| Name              | Accept |
| Participating actor  | Instructor |
| Entry condition(s)     | Instructor clicks accept for an applicant |
| Exit condition(s)           | System flashes a success message |
| Flow of events | User finds an applicant they accept, db updates the application info to accepted, system flashes a success message |
| Alternative flow of events    |   |
| Iteration #         | 2 |


| Use case #  15      |   |
| ------------------ |--|
| Name              | Deny |
| Participating actor  | Instructor |
| Entry condition(s)     | Instructor clicks deny button |
| Exit condition(s)           | a flash message is displayed |
| Flow of events | The user clicks the deny button a applicant, the db updates the application with the denied status, the system flashes a success message |
| Alternative flow of events    |   |
| Iteration #         |  |


| Use case # 16        |   |
| ------------------ |--|
| Name              | Logout |
| Participating actor  | Student, Instructor |
| Entry condition(s)     | User clicks logout button |
| Exit condition(s)           | System reroutes to sign in page |
| Flow of events | User clicks the logout button, system re routes and displays the sign in page |
| Alternative flow of events    |   |
| Iteration #         |  |


| Use case # 17       |   |
| ------------------ |--|
| Name              | Widthdrawl |
| Participating actor  | Student |
| Entry condition(s)     | Student clicks widthdrawl application on one of their applications |
| Exit condition(s)           | Flash message is sent |
| Flow of events | User clicks widthdrawl application button on one of their applications, confirmation button is displayed, user confirms, db removes the application, system displays a success flash message |
| Alternative flow of events    |   |
| Iteration #         | 2 |





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


----
----
# Appendix: Grading Rubric
(Please remove this part in your final submission)

Please see Canvas for the grading rubric. 