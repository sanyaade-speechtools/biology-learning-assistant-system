

# Software Requirement Specification #

## 1.Introduction ##

### 1.1 Purpose ###
The main purpose of SRS is to describe and collect functional and non functional requirements that have not been described in the Use-cases for release 1.0 of Gene Expression Learning Assistant System. Such as the nonfunctional requirements like: usability, reliability, performance, and support ability.

### 1.2 Project Scope and Product Features ###
Gene Expression Learning Assistant System helps the biology students to better understand the gene knowledge by non-traditional ways, such as playing games, and provides feedback by the professors to accomplish the aims of learning Gene knowledge. A detailed project description is available in Project Description and TeamSkill3.

### 1.3 Reference ###
Project Description
<p>
Team Skill 3<br>
<br>
<h2>2.Overall Description</h2>

<h3>2.1 Product Perspective</h3>
The Gene Expression Learning Assistant System can be a great alternative of using traditional methods in learning and understanding biology. It acts like a personal tutor in order to achieve learning biology plus saving time and efforts for both students and professors.<br>
<br>
<h3>2.2	User Classes and Characteristics</h3>
<img src='http://biology-learning-assistant-system.googlecode.com/svn/contextD.jpg' />
Students: The biology students who use Gene Expression Learning Assistant System. The students will login the system, update their information including email address or contact method. They are the normal users for the system: watch video, play game, take quiz and ask online question.<br>
<p>
Professors: The biology professors who are stakeholders of project. They give some information to students and get some information: quiz report/question from students. The project is developed to improve professors teaching effective.<br>
<p>
Administrators: Some of professors who manage the system. Manage the resource: upload, modify, delete the video/flash, paper, book list and quiz question. Manage the database of system and set database recovery or security rules. They could check system log from system.<br>
<h3>2.3	Operating Environment</h3>
<br>SRS-1 The Gene Expression Learning Assistant System requires the user to have a  computer connecting to the Internet. </br>
<br>SRS-2 The Gene Expression Learning Assistant System operates with any web        browser like: Firefox, Internet Explorer, and Google Chrome.</br>
<br>SRS-3 The Gene Expression Learning Assistant System will operate on a server like: Red Hat 6.0 or, Apache HTTP Server.</br>

<h3>2.4 Design and Implementation Constraints</h3>
<br>SRS-4system. The system will use the current educational institution database that uses</br>
<br>SRS-5 The system will use Flash 8.0 and Action Script 3.0 for the games.</br>
<br>SRS-6 All scripts will be written in PHP.</br>

<h3>2.5	User Documentation</h3>
<br>SRS-6 The first time a new user accesses the system by his or her authorized username, the system will provide an online tutorial to make sure that users can use the system in the right way, showing some examples after that to better understanding. Users can skip any part of the tutorial or skip it all.</br>

<h3>2.6	Assumptions and Dependencies</h3>
SRS-7 The system should be working 24/7 unless it is under maintenance.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-8 Any user being authorized of using the Gene Expression Learning Assistant System can use it unless he is blocked or suspended by the administrator of the system.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-9 Some operations need to be approved by the person having the authority in order to be achieved.<br>
<br>
<h2>3.System Features</h2>
<h3>Function Requirements</h3>
<img src='http://biology-learning-assistant-system.googlecode.com/svn/fr1.jpg' />
<img src='http://biology-learning-assistant-system.googlecode.com/svn/fr2_1.jpg' />
<h2>4.External Interface Requirements</h2>
<h3>4.1	User Interfaces</h3>
SRS-10 The Biology Learning System displays shall conform to the Process Impact Internet Application User Interface Standard, Version 2.0 <a href='4.md'>4</a>.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-11 The Web pages shall permit students and professors to selection activities using the keyboard alone, in addition to using mouse and keyboard combinations.<br>
<h3>4.2 Hardware Interfaces</h3>
No hardware interfaces have been identified.<br>
<h3>4.3	Software Interfaces</h3>
4.3.1 Gene Expression Learning System- Student Learning System<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-12 The GELS will have a welcome page to allow students to enter student ID and password to log in.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-13 The GELS will allow students to watch animations about Gene Expression by clicking Study Materials.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-14 The GELS will allow students to play flash games to enhance understanding the knowledge about Gene Expression by clicking Play Games.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-15 The GELS will allow students to take quiz to check whether they understand the knowledge about Gene Expression and the score will be automatically displayed when students finish the quiz..<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-16 The GELS will allow students to see the feedback professor gives by clicking Feedback.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-17 The GELS will allow students to ask professor questions online if they are confused something by clicking Online Question.<br>
<br>
<br>
<P><br>
<br>
<br>
4.3.2 Gene Expression Learning System- Professor System<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-18 The GELS will have a welcome page to allow professor to enter professor ID and password to log in.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-19 The GELS will allow professor upload materials such as animation video to help students to understand the knowledge about Gene Expression by clicking Upload Materials .<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-20 The GELS will allow professor to upload quiz and set answers to test students whether they understand the knowledge by clicking Upload Quiz.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-21 The GELS will allow professor to see all the students' scores and give feedback by clicking Quiz Result.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-22 The GELS will allow professor to answer the questions from students by clicking Online Question.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-23 The GELS will allow professor to manage materials such as modifying or deleting materials by clicking Manage Materials.<br>
<h3>4.4 Communications Interfaces</h3>
SRS-24 The Cafeteria Ordering System shall send an e-mail message to the Patron to confirm acceptance of an order, price, and delivery instructions.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-25 The Cafeteria Ordering System shall send an e-mail message to the Patron to report any problems with the meal order or delivery after the order is accepted.<br>
<br>
<h2>5.Other Nonfunctional Requirements</h2>
<h3>5.1	Performance Requirements</h3>
SRS-26 The system shall accommodate 400 users during the peak usage time window of 8:00am to 10:00am local time, with an estimated average session duration of 8 minutes.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-27 All Web pages generated by the system shall be fully downloadable in no more than 10 seconds over a 40KBps modem connection.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-28 Responses to queries shall take no longer than 7 seconds to load onto the screen after the user submits the query.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-29 The system shall display confirmation messages to users within 4 seconds after the user submits information to the system.<br>
<h3>5.2	Safety Requirements</h3>
No safety requirements have been identified.<br>
<h3>5.3	Security Requirements</h3>
SRS-30 All network transactions that involve financial information or personally identifiable information shall be encrypted per BR-33.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-31 Users shall be required to log in to the Cafeteria Ordering System for all operations except viewing a menu.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-32 Patrons shall log in according to the restricted computer system access policy per BR-35.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-33 The system shall permit only cafeteria staff members who are on the list of authorized Menu Managers to create or edit menus, per BR-24.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-34 Only users who have been authorized for home access to the corporate Intranet may use the COS from non-company locations.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-35 The system shall permit Patrons to view only their own previously placed orders, not orders placed by other Patrons.<br>
<h3>5.4	Software Quality Attributes</h3>
SRS-36 The Cafeteria Ordering System shall be available to users on the corporate Intranet and to dial-in users 99.9% of the time between 5:00am and midnight local time and 95% of the time between midnight and 5:00am local time.<br>
<br>
<br>
<P><br>
<br>
<br>
SRS-37 If the connection between the user and the system is broken prior to an order being either confirmed or canceled, the Cafeteria Ordering System shall enable the user to recover an incomplete order.