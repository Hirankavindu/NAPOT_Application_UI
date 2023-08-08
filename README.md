<img width="509" alt="Screenshot 2023-08-08 at 16 46 41" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/9bbcb07b-0081-40c8-8aec-8a17a56cf885"># NAPOT_Application_UI
<h1>NAPOT Application</h1>
<br><br>
<h2>Introduction</h2>
<p>main concept
"One app for the all parties of NSBM"
NAPOT is our designed mobile application for managing all parties and their tasks at one place. The extended name of NAPOT is NSBM All Portal. Name also implies the "all can access one place for fulfill their requirements in NSBM Green University". when we designing this application we mainly considered what are the problems faced by students and what are the new features available in international and local university applications. We do a research about those stuffs and we add those functionalities to our application design. This application can be considered as the extended mobile version of NSPOT and we used university color theme (blue, green & white) when designing.
In this application, we considered security concerns and we give access to the functions accordingly to the correct parties. Following accounts are the pre defined default account :-
Admin
Canteen person Librarian
Guest
Other parties can use system after creating account in the system with some restriction levels because of security concerns.
We hope to use following technologies in our development process of this application.</p>
<div>
<img width="111" alt="Screenshot 2023-08-08 at 15 35 17" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/37493943-e742-4417-8a45-5274acd15f21">
<img width="120" alt="Screenshot 2023-08-08 at 15 35 21" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/c5985623-d13e-4a72-aaef-896d90e03d27">
<img width="90" alt="Screenshot 2023-08-08 at 15 35 25" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/19499540-8bff-45e8-8554-2d46babffa9c">
</div>
<br><br>
<h3>Problem Identification</h3>
<p>
1. Students have to search here and there to find their exam results (because they are send via outlook mail) and the other thing is if we want to get the hard copy of result sheets , then we have to follow a very lengthy process (do appointments, waiting for the dates, standing in the queues).<br>
2. Students have to maintain another profile such as LinkedIn for going to the interviews. If we can add those functionalities to the existing NSBM student profile, it is easy for students.<br>
3. When we want to change our personal details of the student profile, we have to go to the front office or it department to do the process.<br>
4. There is no way to order foods or check the availability of the items in the canteen.<br>
5. No way to book the library study place and students have to go there to full fill that requirement.<br>
6. Lengthy process for doing complains.<br>
7. No way to track the shuttle service or bus service of NSBM.<br>
</p>
<br><br>

<h3>Proposed Solution</h3>
<p>
1. Students have to search here and there to find their exam results (because they are send via outlook mail) and the other thing is if we want to get the hard copy of result sheets , then we have to follow a very lengthy process (do appointments, waiting for the dates, standing in the queues).<br>
2. Students have to maintain another profile such as LinkedIn for going to the interviews. If we can add those functionalities to the existing NSBM student profile, it is easy for students.<br>
3. When we want to change our personal details of the student profile, we have to go to the front office or it department to do the process.<br>
4. There is no way to order foods or check the availability of the items in the canteen.<br>
5. No way to book the library study place and students have to go there to full fill that requirement.<br>
6. Lengthy process for doing complains.<br>
7. No way to track the shuttle service or bus service of NSBM.<br>
</p>
<br><br>

<h3>Features</h3>
<div>
  
  <p>
    Newly added features to the app by the research of foreign and some local university applications. We added following new feature to our application.<br><br>
Virtual tour<br>
QR Scanner<br>
My timetable<br>
Online food order from canteen Library Room Booking<br>
NSBM Shuttle Booking Complains page<br>
Post graduate Life page Chat option<br>
Question and answer discussion page Student Profile Like LinkedIn profile Event Calendar<br>
Add student Searching feature to the lecturers<br><br>
And we added same as the current existing function that are available in the web version of NSPOT (student dashboard(Nlearn), studet profile, courses and etc)
background.
  </p>
</div>

<h3>Requirement</h3>
<h4>Non-Functional Requirement</h4>
<p>
  This app is mostly same as the mobile version of NSPOT and we extend it for all parties of the NSBM in our application. When we design the interfaces of our app we mainly focused NSBM University color themes (green, blue and white color theme). And also consider the simplicity of the interfaces because we have to do the process in small mobile screen. Another thing is we add already existing application used logos, icons and functions in our app for increasing the user experience. This application can easily access with any mobile device because application is compatible with both android and IOS platforms.<br><br>
Newly added features to the app by the research of foreign and some local university applications<br><br>
Virtual tour<br> My timetable<br> Eat & Drink<br> Library<br><br>
Same as we added current existing function that are available in the web version of NSPOT (student dashboard (Nlearn), student profile, courses and etc.) for feeling familiarity to users with the existing app.
Functional requirements are described by following use case diagram, DFD and interfaces descriptions.
</p>
<br><br><br>
<h3>UseCase Diagram
</h3>
<br>
<img width="479" alt="Screenshot 2023-08-08 at 15 50 14" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/b995a544-5f43-4e26-b935-bc4e743a9ca5">
<img width="486" alt="Screenshot 2023-08-08 at 15 50 28" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/e5979434-ca17-4baa-bffe-d70f71ae5e06">
<img width="472" alt="Screenshot 2023-08-08 at 15 50 37" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/cc279914-7dab-47c8-844d-bf16c1f2f2cf">
<img width="481" alt="Screenshot 2023-08-08 at 15 50 48" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/f651b951-1db7-4f75-afb8-cf18bf9813a3">

<br><br>
<P>
  This use case enables users to log into the system and access the appropriate functionalities according to their role. The various user roles are lecturer, Admin, student, canteen, librarian and guest. To login to the system, lecturer, student, Admin, canteen and librarian must enter their unique username and password. Cleaning staff and security staff can enter the system using guest mode.
There are six main actors,<br><br>
Lecturer<br>
Student<br>
Admin<br>
Canteen<br>
Librarian<br>
Guest (Cleaning staff, security staff and other)<br><br>
Lecturers can access the Today schedule, Timetable, manage lecture materials,3rd party service, enter mark, Submission manage, Complain, Notification, Search students.<br>
Students can access Explore Nsbm, Virtual tour (uni map), Profile (like LinkedIn profile), Course plan, my courses, Eat & drink, library, Calendar & even, Student Shuttle and 3rd party services. They can use the help desk to ask questions and solve their problems. And also, they can complain to academic staff or dean.<br>
Canteen login to the system and the they can access manage available and student or lecturer order list.<br>
Librarian login to the system and they can manage resources and place request.<br>
Cleaning staff, security staff and other can access the system use the guest mode and they can complain repairs, student fault...etc.<br>
New students also come to the system as guest and they can explore the functionalities such as facilities, beauty of NSBM, courses, virtual tour and if there is any thing to complain they can do it via complain function without any logins.
</P>
<br><br>
<h3>DFD Diagram</h3>
<br><br><br>
<img width="481" alt="Screenshot 2023-08-08 at 15 54 54" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/84130016-598b-4a2a-86b9-7f3534b1a3fb"><br>
<img width="477" alt="Screenshot 2023-08-08 at 15 55 06" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/6c6878d1-9dac-4af3-942a-900dfa2a8964"><br>
<img width="419" alt="Screenshot 2023-08-08 at 15 55 13" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/23fb64b8-f938-49d3-9f29-2988368555d7"><br>
<img width="363" alt="Screenshot 2023-08-08 at 15 55 19" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/63e73814-260a-44b1-8fc4-7e36744d939a"><br>

<p>After filling in the student registration form, the details related to the registration form will go to the admin through the signup process. After the admin checks it and accepts the student's registration, the login credentials will go to the student through the approve registration process. Also, the registry data and student credentials data are stored in the student data database.<br><br>
When student try log in to the system, the login process allows the student to enter the system by checking the data in the student data database.<br><br>
The view profile process is used to view the student data and the update profile is used to update the student's data and store the updated data in the student profile data database. The interviewer can also view student data through the view profile process.<br><br>
Through the view plan process, the student can know the schedule data and course guidelines.<br><br>
The view place order process allows students to order food and view available food. Through the study area booking process, the student can choose a study room, view the remaining study room and book the study room.<br><br>
The doing complain process stores the complaints of students, lecturers and guests in the complaint database.<br><br>
The admin can view the complaint through the view all complains process.<br><br>
Through the management event process, the admin can manage the event and store the event details in the event database.<br><br>
The lecturer can view their timetable through the view timetable process.<br><br>
Through the search student process, the lecturer can enter the student's index number and view the student's profile data.<br><br>
Student registration data, credentials data store the student data database. student data and student edited profile data store the student profile data database. course details store the course details database. Timetable data store the timetable database. Available canteen food details store the canteen stock database. student ordered order details store the order database. Booking data store the library space database. lecturer, student, guest complain store the complains database.<br></p>
<br><br><br>
<h3>Students</h3>
<p>1.Student Registration:
The student initiates the registration process.The system prompts the student to sign up and create an account.The student fills in the registration form with personal details.The system validates the form and requests the student to pay the registration fee.The student makes the payment.Upon successful payment, the system confirms the registration and grants access to the platform.
<br><br>2.Explore Features:
After registration, the student can explore various features and facilities provided by NSBM.This includes accessing information about hostel facilities, success stories, beauty of NSBM, course details, postgraduate studies, etc.
<br><br>3.Virtual University Map:
The student has the option to access the virtual university map.This feature provides a visual representation of the campus layout and facilities.The student can navigate through the map to locate buildings, classrooms, libraries, hostels, and other important locations within the university.
<br><br>4.Student Profile:
Each student has a profile similar to a LinkedIn profile.The profile displays results, badges, certificates, disciplinary actions, personal details, and a progress graph.The student can edit their profile details as needed.Dining and Scheduling:(eat &drinks).The student has a special option to access the dining and scheduling services.
<br><br>5. Course management plan:
The student can access the course plan and schedule.
The system provides a timetable for classes.
The student can view notifications related to courses and access the course dashboard.
<br><br>6. Dining and Scheduling :
The student has a special option to access the dining and scheduling services.
They can select meals and beverages.
The system allows the student to schedule their activities accordingly.
<br><br>7. Library and resources:
The student can place book requests in the library. They can access resources provided by NSBM.
<br><br>8.Calendder and events:
The student can view the academic calendar and upcoming events.
<br><br>9.Help desk and Q&A
The student can access the help desk for assistance. They can engage in direct chat for questions and answers.
<br><br>10.Student Shuttle Service:
The student has the unique feature of accessing the student shuttle service.
They can track shuttle locations, view details, and book seats.
<br><br>11.Third-party Services:
The student can utilize third-party services integrated into the platform.
<br><br>12.The student can raise complaints regarding various issues such as repairs, academic problems and others
<br><br>This use case diagram provides an overview of the main functionalities and interactions between the student and the NSBM learning platform. It encompasses activities from registration to accessing various resources and services provided by the platform.
</p>
<br><br><br><br>
<img width="521" alt="Screenshot 2023-08-08 at 16 11 57" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/051814e9-1c83-4bc6-9921-ec12613d1254">
<P>By using this login page, students who are already at the university can log into the application with the email address and password provided by the university. Also, they can change the password using the forgotten password.
By using this login page, students who are already not at the university can log into the application.for that they should submit their certifications required by the university such as o/l,a/l result sheet.as well as they can submit their DOCUMENT by using choose file option.
after completing thire paymentTheir request will be received by the administrator who will consider them and make selections for graduation. After the registration is completed, the admin will send an email and password to the concerned person which he can use to log into the application from the login page.</P>
<br><br>
<img width="506" alt="Screenshot 2023-08-08 at 16 12 10" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/ea9bfaa5-d2b9-4655-8806-9962b23e6884">
<img width="519" alt="Screenshot 2023-08-08 at 16 13 20" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/97dd87a4-d0b2-483b-9176-d4079e61d41c">
<p>In the home page students can get knowledge about our university. What are degree programs offered by NSBM and how is the value of these degree programs. Also we can get information about the university faculties and course details. Such as course duration, course fee, undergraduate, post graduate and PHD etc. And also students can get details about the next intake. Such as how many students are get the intake, when is the intake date, what is the batch, enrolment qualifications etc. If users want to see the university in virtually they can click the virtual Tour button and see the university.
We can get to know about the what are the foreign universities engaged with NSBM. We can get more information about the Plymouth university UK and their degree programs, Victoria university Australia and their degree programs.</p>
<br><br><br>
<img width="515" alt="Screenshot 2023-08-08 at 16 14 21" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/6d18b17c-dbaa-4cc9-8204-f1263df8ca74">
<p>In this facility page all the users can see the what facilities have in NSBM green university.
Also users can get knowledge about the all university facilities and current university facilities. The facility page is categorized as lecture hall facility, library facility, co- curricular activity, library facility, student accommodation facility and recreational facility etc.
Also in the lab facility users can how many labs are in the university and what kind if labs are they. Such as how many IT labs, how many bio medical as well.</p>
<br><br><br>
<img width="505" alt="Screenshot 2023-08-08 at 16 15 11" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/b9f723f4-4d66-487a-9ebe-9750ffd8f31b">
<p>In the student profile all the university students can see their batch, degree, GPA and the credits. Also they can see their personal details such as full name, NIC number, contact number, student ID, guardian name and the contact number etc. As well as students can add their skills to this page and can update it. If students joined some clubs and societies they can add them too. Addition to that students can add academic certificates they got. Students can chat with their lecturers through this platform and can clarify their problems.
There is a notification panel in this page. Then the students receive a notifications for their future activities. Also if student have a question to solve they can type that question in question forum and get help from others to solve that.</p>
<br><br><br><img width="515" alt="Screenshot 2023-08-08 at 16 16 00" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/268b911e-14f3-4da3-af4f-1508c77cff2d">
<img width="506" alt="Screenshot 2023-08-08 at 16 16 08" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/a56acec9-e5c8-4684-8de7-090549bd59ee">
<br><br><br>
<img width="510" alt="Screenshot 2023-08-08 at 16 16 43" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/a407c1db-94fe-4540-8b49-1bd99608c47d">
<p>IIn this lecture page students can easily get to know about the lecture schedule and day to day time table. Also students can go through the lecture notes and download the lecture materials , submit assignments, do online quizzes as well. And also students can give feedback through this page as well.
If students want to check their attendance, profile and marks they can simply type their ID number and can search it.
Lecturers can upload the lecture materials to this and also they can download the assignments done by the students. To upload the lecture materials lecturers have to add lecture number and the topic. As well as they can add an assignments, quizzes also to this platform.</p><br><br><br>
<img width="496" alt="Screenshot 2023-08-08 at 16 45 30" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/ca95bf30-3e35-412d-9df4-74aceef961f6">
<img width="517" alt="Screenshot 2023-08-08 at 16 45 44" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/bf8d354a-7eb3-4686-aacc-b94649ee7427">
<img width="504" alt="Screenshot 2023-08-08 at 16 45 57" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/0865b95f-9826-40ce-8533-85712aaf1585">
<img width="509" alt="Screenshot 2023-08-08 at 16 46 34" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/1908387b-62cc-4111-9430-ff5d2833345d">
![Uploading Screenshot 202<img width="518" alt="Screenshot 2023-08-08 at 16 46 48" src="https://github.com/Hirankavindu/NAPOT_Application_UI/assets/97301123/860f4d93-15a4-4107-a512-739135088272">
3-08-08 at 16.46.41.png…]()






