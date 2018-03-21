# matrimony-website
online matrimony website
1.	INTRODUCTION

1.1 SCOPE OF THE WORK
Matrimonial website which will provide platform to a lot of Bride/Groom for finding perfect match. There are different sectors like Registration, Partner , Search, etc. So the Bride/Groom can get their interest for find their partner. Bride/Groom can directly search Partner according to their required criteria. 
For this application, we will provide following capabilities: 
(1) Admin Module. 
(2) User Registration Module 
(3) Image Uploading module 
(4) Creating album 
(5) Search Module.

1.2	USAGE SCENARIOS
The purposes of the Matrimonial Web Application are: 
•	The main purpose of this application is to facilitate matchmaking business by applying the information in the field. 
•	It helps the user by providing profiles of perspective “Bride” or “Groom” and other information regarding them online. 
•	User can get information regarding their dream life partner at his/her home at his/her convenience. 
•	This application also provides a search utility which helps those users who have a certain criteria of qualities in mind to make online matrimonial easier. 
•	Since internet is a pivot for modern business, our project which is based on internet paves a path for modernization in trade. 
       Matrimonial Web Application will allow a new user to register and after successfully registration user can get email confirmation, after completing registration users profile will be visible to other users. 




















2. REQUIREMENT ANALYSIS
2.1 FUNCTIONAL REQUIREMENTS
Login Module:

	Introduction: Authorized users are allowed to access.
	Input: User enters the User type, Username and password.
	Process Definition: Checks User type, Username and password is valid or not.
	Output: User is directed to next page or shows the message box “Login Failed”.

Registration module:

	Introduction: Only Admin can access the page.
	Input: Admin has the authority to provide username and password for new users
	Process Definition: Checks same username and password exists or not and also checks whether all the fields are entered.
	Output: User gets the username and password.

Report Module:

	Introduction: Only Admin can access the page and check the report.
	Input: Bride/groom
	Process Definition: It retrieve’s all the information stored from different tables.
	Output: Requested report is generated.

View module:

	Input: bride/groom name, DOB, age, religion caste, contact, address
	Process Definition: In the view module the user can view bride/grooms information which has already been saved. The user can also add new information or edit the present information.
	Output: New bride/grooms information is added to the table.

Match module:

	Input: type, bride/grooms name
	Process Definition: the user can enter bride/grooms information and on a single click can find the perfect match to the corresponding bride/groom.
	Output: The match can be found or not.

2.2	NON - FUNCTIONAL REQUIREMENTS

PERFORMANCE REQUIREMENT:
Good memory space is required. Should be Error-free. Large amount of data should be handled easily. 
SAFETY REQUIREMENT: 
Backups can be done regularly.
SECURITY REQUIREMENT:
A password is given to the SQL server. Administrator and the end user, who have their own user name and password, have only the right to open the software.

2.3	USE CASE SCENARIOS
 

User can perform several operations on the system like registration, login. He or she can also edit his or her profile, searching facility is also there. 
Flow of Events
	Basic Flow
User can perform mainly four activities
Registration
Before using this system the user must have to register in the system. He have to fill up the form and enter his/her profile in the database.
Login
The existing users are giving his/her userid & password to access their accounts. If they are successfully login then they can edit or update their accounts.
Edit profile 
The user can also edit his/her personal profile in the system but first he/she have to login in the system.
    Search 
	     He or she can search the profiles based on their requirements. 
	Alternate Flows
Invalid Password 
An invalid password is entered. The user can re-enter a password or terminate the use case.
     Invalid Username
The system informs the user that the username is invalid. The user can re-enter the username or terminate the use case.
   
2.4	OTHER SOFTWARE ENGINEERING METHODOLOGIES

          Matrimonial website project is a web application which is implemented in Asp .net platform. Matrimonial website Asp .net
          Project tutorial and guide for developing code. 



















3. SYSTEM DESIGN
3.1. DESIGN GOALS

•	The primary goal of this website is to install, develop and deliver readymade solutions for matrimonial & match making website for business owners, who are targeting general audience for matrimonial service through online. 
•	This website has been specializing in php matrimonial website development and php matrimonial script for long time. The member profile are updated with simple navigation admin back end tool. Requirement will be PHP with MySql database. 
•	Our PHP matrimonial web developers analyse the customer requirement, highlight the features, develop the layout and complete the site as per the needs. 
•	The matrimonial website is  one of the profitable online business. Most of the people are not only know the advantages of the Internet. And also they are appreciating to select their Partners. 
•	The Matrimonial World has become a long way process. In previous days mostly life partner are choosing by the parents, relatives, or some other elder members of the family. This important decision is taken by entire family member including the potential Bride and Grooms. But now a days, all educated or non educated all are known the use of internet. 
•	It will connect to people one end to another end of the world. Through the Matrimonial website we can search the suitable character and suitable Life partner to the Bride / Groom. By the Matrimonial Websites we can get the full details of the life partner.






3.2. SYSTEM ARCHITECTURE

 
Fig 1: Showing system architecture of matrimony website

3.3. DETAILED DESIGN METHODOLOGIES

•	When we open our website, index page will appear for that we designed a php file .
•	In index page, all options will be displayed on the navigation bar they are:
o	Home
o	About
o	Search
	Regular search 
	Search by Profile Id: User can search bride/groom by entering their Id.
	Faq
o	Contacts
•	In index page, a new user can create his/her profile by clicking on it for that we designed a register.php file.
•	To display the details of the website we designed about.php file.
•	After login into the account, we will providing four options they are:
o	View profile : In this, the user can see his/her profile(in About Myself), Family details, Patner preference.
o	Partner preference: In this, the user can give preferences of bride/groom.
o	Profile
	Upload photos: Here user can upload his/her photos. 
	View profile: User can view his/her profile.
	Edit profile : User can edit his/her profile.
o	Search
	Regular search : User can search bride/groom by entering his preferences.
	Faq 


3.4. DEVELOPMENT ENVIRONMENT

1.	Download the XAMPP for Windows Installer.
2.	After successful installation, you should find an XAMPP icon on your desktop, double-click it to launch the XAMPP Control Panel .
3.	On the XAMPP Control Panel, click the Start buttons for Apache and MySQL.
4.	Place your file in htdocs C:\xampp\htdocs
5.	Enter http://localhost/matrimony into the address bar.
6.	Open index.php file




4. CONCLUSION AND FUTURE WORK

4.1. PROPOSED WORKPLAN OF THE PROJECT 
Our Matrimonial Web Application is to provide Grooms and Brides with excellent matchmaking experience by exploring the opportunities and resources to meet true potential partner.

Matrimonial website which will provide platform to a lot of Bride/Groom for finding perfect match. There are different sectors like Registration, Partner Search, etc. So the Bride / Groom can get their interest for find their partner. Bride/Groom can directly search Partner according to their required criteria.

Matrimonial web application provide facility to change preference about partner. This application provide facility like edit profile, update photo and delete photo, hide profile, create album, send express interest, send personal message, apply for loan to the user.

FUTURE WORK:

	It is possible to provide the web space to the users for creating his portal.
	It is possible to create our own mail server.
	It is possible to create chat server so that user can communicate with each other.
	It is possible to provide facility like create video album. 

  



















5 REFERENCES
 
  [1] https://en.wikipedia.org/wiki/Matrimonial_website 
   [2]https://www.makeyoursoftware.com/php-script-solutions/matrimonial-                            software-in-php/
   [3] http://phpmatrimonialcode.com/
   [4] https://www.slideshare.net/kaiwren/bureaubuilder-promo
   [5] http://www.phpmatrimonialscript.com/
   [6]https://www.brainpulse.com/web-development/matrimonial-portal-development.php 
