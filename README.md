# Checking the validity of a policy in the event of an accident

## Table of contents
* [Description](#Description)
* [Steps](#Steps)
* [Robotic Enterprise Framework](#Robotic-Enterprise-Framework)
* [Technologies](#Technologies)
* [Licence](#Licence)


## Description
The realized automation process comes to the aid of a client who deals with the processing of multiple incidents that need to be resolved, by checking and managing insurances.

He was receiving the accident data by e-mail (policy number, accident date, damage amount), was checking the data in the database / excel management file, and had to communicate the maximum amount that could be recovered, if the policy was within contractual terms. Otherwise, he had to notify accordingly (eq: expired insurance policy).

As the large volume of data requires repetitive work, the introduction of such an automatic process comes to the aid of both parties involved - customer and beneficiary.

## Steps

1. Reading new emails and saving information

    When running a process, the robot reads all new emails and parses the values found after a certain format.

    <img src="images//rpa_email.JPG"> 

    After parsing the data, all the information found will be saved in exactly the same format in an excel file, which will later represent the INPUT of the problem.

    <img src="images//excel_emails.JPG" width="420"> 
    

2. Searching the data in the database/excel file

    Check *Polite asigurari.xlsx*

3. Sending the corresponding emails

    Depending on the data of the problem, determined by comparison with the database and data from the email, the customer will receive an email containing the necessary information in order to notify him about the status of the policy.

    <img src="images//nu acopera.JPG">    

    
## Robotic-Enterprise-Framework

"Robotic Enterprise Framework is a project template based on State Machines. It is created to fit all of the best practices regarding logging, exception handling, application initialization, and others, being ready to tackle a complex business scenario."

<img src="images//ref.JPG">

## Technologies
- UiPath Studio
- UiPath Robot

## Licence
MIT Licence

