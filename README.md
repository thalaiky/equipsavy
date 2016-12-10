Skip to content
This repository
Search
Pull requests
Issues
Gist
 @akhilpen
 Watch 3
  Star 2
 Fork 0 cse442equipsavy/equipsavy
 Code  Issues 18  Pull requests 5  Projects 0  Wiki  Pulse  Graphs
Branch: Developer Find file Copy pathequipsavy/README.txt
541ea77  a minute ago
@akhilpen akhilpen Update README.txt
4 contributors @thalaiky @tgsyre @akhilpen @cooljjkid
RawBlameHistory     
39 lines (30 sloc)  2.26 KB
#EquipSavy

####Made by Sai Akhil Pendyala, Satya Kranthi Penumanchili, Thalaikya Voggu, JJ Fincken, Tristan Syre and Abhinav Mahajan

######Semi working web version : http://equipsavy.000webhostapp.com/

##Overview:
Equipsavy is a web application with the functionality to share equipment effectively in a class. To Log onto the website, first log onto
firebase console, add a user in the authentication using email and password and then you can log into the website. It achieves this mainly
by providing three levels of access: Instructor, Student, and Department. The user logs in and, based on what they are assigned, are able
to do different things. The student can select his/her class s/he wishes to reserve equipment for and then reserve all pieces of equipment
they think is necessary, at that point, it will be sent to the instructors to be approved or denied. Instructors can add pieces of
equipment to the courses that they teach, either by adding a .csv file with equipment and quantity, an .xlsx file, or submitting each piece
of equipment individually. Teaching assistants are unique in that they have the access of both the students and instructors. The department
page allows department members to add or cancel classes, add instructors to those classes, and add TA’s to a class.

 ##Student features:
- able to select a class to reserve equipment for
- able to reserve 1 of all necessary pieces of equipment

##Instructor features:
-	Choose a class to look over.
-	Able to submit new pieces of equipment individually or in groups using .csv or .xlsx
-	Able to approve or deny students requests for equipment.
-	Able to track which student has which piece of equipment.
-	Can add/remove  TA’s from a class

##Department features:
-	Can add/remove instructors from a from a course

##Software:
-	Used a firebase console as the backend to the website.
-	Firebase has a built-in authentication which allow different users different levels of access into the site.
-	We also used firebase’s real-time database to store data such as equipment name and quantity.

##External Library Reference:
-https://github.com/SheetJS/js-xlsx
This library was used in order to upload files in a multitude of formats including xlsx, the default format for Microsoft Excel files
Contact GitHub API Training Shop Blog About
© 2016 GitHub, Inc. Terms Privacy Security Status Help