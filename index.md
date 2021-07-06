## Overview

The LiftStation.cloud software suite consists of three main user classes: Technicians, Operators and Master users. Technician users collect well and lift station data. Operators are the administrators - they can create new Technician users and generate Excel reports with the data collected by Technician users. It should be noted that data can also be collected by a SCADA system. Finally there are master users - master users are the user who signed up for an organization. They automatically are Technician and Operator users. They are the ones that deal with billing.

The data collected by the software is the bare minimum needed to function. No location data is collected or stored. IP Addresses may be collected in the server logs but they are not associated with a user. This document will give an overview of data collected.

For convenience the app does not use passwords - you authenticate with a PIN sent by text message, and if you choose to set up Face ID, by taking a picture of your face.

## Data we collect
### Technician Users
#### Overview
If you are using this app, an Operator has added your name and phone number to the database. When you enter well and lift station data that data is collected, along with the date of the reading and the timestamp. These readings are associated with you. In the event that your account it deleted by an Operator these readings will no longer be associated with your account - they will be marked as having been read by a deleted user.

#### Face ID
If you would like to use Face ID you are submitting a photo of your face. This will be uploaded and stored on a cloud storage service. When you sign up and submit a photo that photo will remain on cloud storage and be displayed to you under the Face ID screen in the Technician App. It will also appear in the Operators app by your user profile. If you decide to turn off Face ID this photo will be deleted.

Every time you login with Face ID you will need to take a photo of your face. These photos will be stored on a cloud storage service but they will be deleted after one day. Only the original photo is retained until your account is deleted by an operator or until you deactivate Face ID.

#### Why is this information collected?
Your phone number and/or face are collected so that you can log into the app. Well and lift station data is collected so that it can be stored and reports can be generated. 

### Operator Users
Another operator has added your name, phone number, operator class and email address to the app. Operator users also have the abiilty to use Face ID. See the section above.

#### Why is this information collected?
Your phone number is collected so that you can login. Your email address, operator class and name are collected so that they will appear on reports to be given to the EPD. Reports are sent through email, either automatically or when requested. Operators will have a web app and that app will allow you to download a report instead of having it emailed to you.

### Non-User Data
In addition to the user data listed above, the following data is stored: 
- Names of water systems that make up your organization
- Names of Wells and Lift Stations and what water system they belong to
- Safe drinking water permit number, and which system it applies to
- Groundwater Withdrawal Permit number, which aquifer it covers, and which wells it covers
- Routes (a route is a collection of wells and lift stations in driving distance...)
- Which routes a user has access to

## What will this information be used for? Who has access?
Technician users cannot view any phone numbers, names or any other user data. They can view routes that they have been given access to and wells and lift stations that make up those routes, along with the previous and current readings for those wells and lift stations. Operator users have access to all data listed above and can edit all data.

