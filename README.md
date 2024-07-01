# Footage_Booking
Footage Booking System - Data Flow Diagram
Users
Super-administrator/ICT
Administrator/Librarian
Manager/Supervisor
Employees

Footage Categories 
Video and Audio 
	Editorial 
	TV
	Radio
	Digital
	

Non-functional Requirements
Usability:
The system should be easy to use and navigate for users with varying levels of technical expertise.
The system should have a consistent and intuitive user interface.
The system should provide clear and concise instructions and feedback to users.
Performance:
The system should be able to handle a large number of users and footage without significant performance degradation.
The system should be able to handle simultaneous uploads and downloads without significant performance degradation.
The system should have a response time of less than 2 seconds for most operations.
Scalability:
The system should be able to scale horizontally and vertically to accommodate increasing numbers of users and footage.
The system should be able to handle spikes in traffic without significant performance degradation.
Reliability:
The system should be available 99.9% of the time.
The system should have measures in place to prevent data loss in the event of a system failure.
The system should have a backup and recovery plan in place.
Security:
The system should use secure protocols (e.g., HTTPS) to protect user data and footage.
The system should use encryption to protect footage during upload and download.
The system should have measures in place to prevent unauthorized access to footage and user data.
The system should have measures in place to prevent data breaches and cyber attacks.
Maintainability:
The system should be easy to maintain and update.
The system should have a modular design to facilitate code reuse and maintenance.
The system should have a version control system in place to track changes and roll back to previous versions if necessary.
Compatibility:
The system should be compatible with various web browsers and devices.
The system should support various video and audio formats.
Accessibility:
The system should be accessible to users with disabilities.
The system should comply with accessibility standards such as WCAG 2.1.
Internationalization:
The system should support multiple languages.
The system should support multiple currencies.
Legal and Regulatory Compliance:
The system should comply with relevant laws and regulations, such as GDPR and copyright laws.
These non-functional requirements should ensure that the footage booking system is usable, reliable, secure, and compliant with relevant laws and regulations.

Functional Requirements
User Registration and Authentication:
Users will be automatically uploaded from the users database. 
Users should be able to log in to their account using their usernames and password.
Users should be able to reset their password if they forget it.
Footage Upload:
Reporters should be able to upload video or audio footage to the MAM storage facility.
The system should support various video and audio formats.
The system should provide a progress bar or other indicator to show the upload progress.
The system should automatically generate a unique identifier for each uploaded footage.
Footage Booking:
Users should be able to browse and search for available footage.
Users should be able to view a preview of the footage before booking it.
Users should be able to select the footage they want to book and add it to their booking cart.
Users should be able to review their booking cart and make changes before submitting the booking request.
Users should be able to submit their booking request, which should include the selected footage and the desired download format.
Booking Approval:
The system should send a notification to the supervisor and the librarian when a booking request is submitted.
The supervisor and the librarian should be able to review the booking request and approve or reject it.
The system should send a notification to the user when their booking request is approved or rejected.
Footage Download:
Once a booking request is approved, the user should be able to download the footage in the desired format.
The system should provide a download link or button for the user to download the footage.
The system should provide a progress bar or other indicator to show the download progress.
Footage Access Control:
Reporters should not be able to access their uploaded footage until they book it via the system.
Only approved users should be able to download the footage.
System Administration:
The system should have an administration panel for managing users, footage, and bookings.
Administrators should be able to add, edit, and delete users, footage, and bookings.
Administrators should be able to view reports and statistics on system usage.
User Interface:
The system should have a user-friendly interface that is easy to navigate.
The system should be responsive and work well on various devices and screen sizes.
The system should provide clear and concise error messages and feedback to users.
Security:
The system should use secure protocols (e.g., HTTPS) to protect user data and footage.
The system should use encryption to protect footage during upload and download.
The system should have measures in place to prevent unauthorized access to footage and user data.
Performance:
The system should be able to handle a large number of users and footage without significant performance degradation.
The system should be able to handle simultaneous uploads and downloads without significant performance degradation.
Manual Footage Booking Process
Each footage should be captured using a unique serial number in the database. 
The librarian should be able to manage the footage recorded in the  database. 
Data Flow Diagram


The  MAM storage facility
The librarian manages the MAM facility. The system should be able to integrate the work of the librarian, through access to the MAM storage facility. 

1. Is this a permanent storage or it has to be cleared for some other footage to be uploaded?
2. Can Access to footage uploaded to the MAM facility be restricted. 
3. Integration issues to the new system, such that footage uploaded to the MAM facility, directly shows on the system in real time. 
4. Titling and assigning of unique IDs or serial numbers to each footage facility. 
