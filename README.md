# Passport Automation System

*Web application developed using HTML, CSS, Javascript, PHP and MySQL*

## Table of Contents

- [About](https://github.com/cfts-mkb/pas#about)
- [Scope](https://github.com/cfts-mkb/pas#scope)
- [Use Cases Implemented](https://github.com/cfts-mkb/pas#use-cases-implemented)
- [Actors Involved](https://github.com/cfts-mkb/pas#actors-involved)
- [Technologies Used](https://github.com/cfts-mkb/pas#technologies-used)
- [Tools Used](https://github.com/cfts-mkb/pas#tools-used)

## About

Passport Automation System is used in the effective dispatch of passport to all of the applicants. This system adopts a comprehensive approach to minimize the manual work and schedule resources, time in an effective  manner. The core of the system is to get the online registration form (with details such as name, address etc.,) filled by the applicant whose testimony is verified for its correctness by the Passport Automation System with respect to the already existing information in the database. This forms the first and foremost step in the processing of passport application. After the first round of verification done by the system, the information is in turn directed to the regional administrator's  office. The application is then processed manually based on the report given by the system, and malpractice of any kind  identified can make the applicant liable to penalty as per the law. The system also provides the applicant the list of available dates for appointment to 'document verification' in the administrator's office, from which they can select one. The system forwards the necessary details to the police for its separate verification whose report is then presented to the administrator. The administrator will be provided with an option to display the current status of application to the applicant, which can be viewed in their online interface. After all the necessary criteria have been met, the original information is added to the database and the passport is sent to the applicant.

## Scope

- The system provides an online interface to the user where they can fill in their personal details and submit the necessary documents. 
- The authority concerned with the issue of passport can use this system to reduce their workload and process the application faster.
- The transfer of applicant details between various parties involved in evaluating the passport application.
- Users can check their application status and setup appointment date for police verification.

## Use Cases Implemented

- **Login** :- The applicant logins to the system to apply for a new passport or check status of applications submitted earlier.
- **Registration** :- The Applicant enters their name and details for applying a Passport .The applicant initially give their details of registration.
- **Get Details** :- The applicant details are passed on to the appropriate people for the purpose of verification.
- **Check status** :- The applicant checks the status regularly to know about the stage of processing being done to their passport.
- **Verify** :- The system verifies the applicant mandatory information given by them.
- **Store Verification** :- After the verification process is over, the applicant is approved as a legal citizen of the country and the status of processing is changed to ‘C’ denoting completion.
- **Issue Passport** :- Approved passport being issued back to the applicant.

## Actors Involved

- Applicant
  Refers to the user who wishes to apply for a passport and submits an application in the system.
  
- Passport Officer
  They are responsible for ensuring all required document have been submitted by the applicant and if the details entered by the user match the details already available in the system. Once an application is validated successfully, they forward it to the regional administrator for manual verification. He ha
  
- Regional Administrator
  They are responsible for verifying the details submitted by the applicant and confirm if the application can be approved for manual verification. 
  
- Police
  They are responsible for performing a personal verification of the applicant and see if they have any criminal case against them before or at present. In this case, the police have been assigned with the power to decline an application by suggesting it to the Administrator. The communicate with the other actors via the Passport Automation System.
  
 ![Use Case Diagram](/images/Use-Case-Diagram.jpg)

## Technologies Used

- Hyper Text Markup Language (HTML)
- Cascaded Stylesheets (CSS)
- Javascript
- Wamp Server
- Hypertext Preprocessor (PHP)
- MySQL

## Tools Used

- Visual Studio Code
- MySQL Workbench
