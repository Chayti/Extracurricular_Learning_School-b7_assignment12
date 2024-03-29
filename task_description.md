﻿# **Task description**

## **Theme: Extracurricular Learning School** :school:


You are asked to build a MERN stack website based on a school that allows instructors and students to perform all the activities discussed in the requirements. The website must be exclusively dedicated to one type of school **(Music school, Dance school, Art & craft school, Language School, Drama/Theatre school, Sports academies, Design school, Photography School)**. Your website will be based on one of these categories mentioned above. If you choose, for example, the category photography school, your website should only have all the information and activities based on photography only. 
>**Note: You can not do anything related cooking school.**

Make sure your website design is :unicorn: unique. Remember, a :unicorn: unique project will add more value to your portfolio. :v:

   - Visit ThemeForest, Dribble, google, etc. to get some ideas. 
   - Visit [this blog to get free images, illustrations & animations for your website.](https://bootcamp.uxdesign.cc/free-images-and-resources-collection-for-website-c77f2fc46ce5)
   - Try to explore component libraries other than DaisyUI. You can explore MUI, Ant design, Chakra UI etc.

Read the task carefully.

<hr/>
<br/>

## :writing_hand:**Main Requirements**

1. Focus on making the website visually appealing. Ensure that
    - color contrast is pleasing to the eye
    - the website does not have a **"gobindo design"**
    - the website has proper alignment and space
    - Do not directly just copy paste a component design from a component library you are using. You will have to customize the design. (e.g. If you are using  DaisyUi & you decided to use a card component, you will have to customize the styling of that card, rather than just copy & paste it)

    <br/>
    
    >**Note:** Your website must not be related to your previous assignments layout/ design or any practice project shown in the course modules or our conceptual sessions. Ex: You can't copy any design or similar functionality/ layout of

        ● Dragon news
        ● Espresso Emporium
        ● Car Doctor
        ● Travel guru
        ● Volunteer network
        ● Bistro Boss
        ● Doc House
        ● Job Portal Website/ Aircnc or Any conceptual session project etc.

    **If any similarities are found, you will get zero(0) as a penalty.**

    <br/>

2. Make sure to keep the navbar and footer **on all the pages except on the 404 page**. Create a reasonable, stylish and meaningful footer. (including website logo or name or both, copyright, some contact information, address etc.)

<br/>

3. Your website should have a navbar with the **Website logo or Website name or both, Home, All Instructors, All Courses, Dashboard** and **User profile picture**\. The **user profile picture** and **Dashboard** on the navbar are conditional\. If the user is signed in, the navbar will show the profile picture; otherwise, it will show the **Login button**\.

<br/>

4. **Profile page will be private:**

    On clicking the user profile picture, the user will be redirected to the Profile page where he/she will see all the information:
    - Name
    - Image
    - Email
    - Phone Number
    - Address
    - Role **(Instructor/ Student/Admin)**
    - Gender
    - Update button

    **Update Action:** On clicking the Update button a user can update his/her information **except role and email**.

<br/>

5. **Registration & Login System:**

    **Login Page:**
    When a user clicks on the login button, they will be redirected to the login page having the following:
    - Email
    - Password **(This field can hide/unhide the password by clicking on an icon)**
    - A link that will redirect to the registration page
    - Keep at least one social login

    <br/>

    **Registration Page:**
    The Registration page will have the Email/Password form having the following fields:
    - Name
    - Email
    - Password
    - Confirm Password
    - Photo URL
    - Gender
    - Phone Number
    - Address

    <br/>

    >**Note:** Keep at least one social login

    >**Note:** Do not enforce **forget password feature** and  the **email verification method**, as it will inconvenience the examiner. If you want, you can add email verification/forget password  after receiving the assignment result.

    <br/>

    **Error for Registration system:**
    On the Registration page, display errors when:

    The password
    - is less than 6 characters
    - don't have a capital letter
    - don't have a special character

    <br/>

    >**Note:** A user cannot submit empty email and password fields.

6. **Homepage:**

    - **Top Slider Section -** Will have a relevant slider.
    - **Message from the School Director/President section -** give a relevant message and a picture. The design is entirely up to you.
    - **Gallery Section -** Show relevant pictures related to the school activities. For example, pictures  - festivals, seminars, student activities, etc.
    - **(Bonus task) Events section -** It will have 2 tabs called **Latest Events & Previous Events**. If the event date has already passed, it will be displayed in the **Previous Events tab**. Otherwise, the event will be displayed in the **Latest Events tab**. **Suppose, today is 28 May, 2023. Your event date is 27 May, 2023. Then, this event will go to Previous Events tab.**
    
    Display some events related to the school (trainings, competitions, cultural events etc.)

        The information will be the following:
        - Event poster (image)
        - Event Title
        - Event Date
        - Description

    - **Extra Section -** Add one relevant section. Make it attractive :heart_eyes:. Try to use any animation effects.

<br/>

7. **All Instructors Page:**
The All Instructors will have the information of the instructors that work in the school. The information will be:

   - Image
   - Name
   - Email
   - See courses button **(connected with point 9)**
   - Follow button **(Disable it if logged in user is already an admin / instructor)**

<br/>

8. **All Courses page:**
The All Courses will have the information of the courses that are offered in the school. The information will be:

   - Image
   - Name
   - Instructor name
   - Available seats
   - Course Price
   - Select Button **(Disable it if logged in user is already an admin / instructor)**

   <br/>

    >**Note:** You will have to display the courses in **tabular form**. Disable the **Select button** when the available seats become **zero** and make the row of that course :red_circle: **red colored**.

<br/>

9. After clicking on the **See courses** button, a student can see all the courses taken by that instructor and also **approved by the admin**\. If the course is in **pending/ denied status** in the instructors dashboard, it **will not be shown** here\. **See point 12(3)**\. Each course will have all the information discussed in **point 8**\.
    
    <br/>

    >**[hints: You may use instructor /email as route params]**

<br/>

10.  **Student Dashboard:**
    <br/>
    ***It will be private & only a student can access this route.***
    
     - **Student Profile:** A student will see all the information discussed in point 4

     - **My Selected Courses:** The student will see all the courses he/she booked after clicking the Select button. You will have to display the relevant information of a course, a Delete button and a Pay button. More in point 11.

     - **My Booked Courses:**  Show all the courses a student selected after successful payment.

     - **(Optional task) Following:** A student will see all instructors he/she is following after clicking the **Follow button** on **All Instructors page** & then make sure to disable the **Follow button**. Show relevant information of an instructor, an **Unfollow button** and **See courses button**.

        - **Unfollow button action:** On clicking the **Unfollow button**, a student can unfollow an instructor and the instructor will disappear from the Following page. Make sure to make the **Follow button active** on the **All Instructors Page** again.

        - **See courses button action:** Same as point 9.

<br/>

11. **My Selected Courses: (Student dashboard)**

    - **Pay button Action:** Upon clicking the **Pay button** for a course, the student will be redirected to the payment page to finalize his/her payment. After a successful payment, the **Available seats** for the particular course will be reduced and the course information will be shown on the **My Booked Courses page**. Make sure to remove the course from the **My Selected Courses page**.

    - **Delete button Action:** On clicking the **Delete button**, a student can remove a selected course from the list.

<br/>

12.  **Instructor Dashboard:**
    <br/>
    ***It will be private & only an instructor can access this route.***

      - **Instructor Profile:** An instructor will see all the information discussed in **point 4**
      - **Add Course:** This page will have a form with the following fields:

        - Course Image
        - Course name
        - Instructor name **(use default name value of logged in instructor)**
        - Instructor email **(use default email value of logged in instructor)**
        - Available seats
        - Course Price
        - Add button


      - **My Courses:**  Show all the courses of an instructor that he/she has added after clicking the **Add button** from the **Add Course page**. Each course will show relevant information including **pending/ approved/ denied** status, **Total Enrolled Students**, **Feedback** & **Update button**.
        
        - **Total Enrolled Students:** Initially it will be zero. Show the total number of students If any student has successfully booked the course.

        - **Feedback:** 
            - If the course is in pending status, just show the message "It is in pending state."
            - If the course is in approved state, show the feedback of approve reason from admin.
            - If the course is in denied state, show the feedback of deny reason from admin.

        - **Updated button Action:** An instructor can update a course information. You can show the form either in a modal or in another route. The **update button** will be **disabled** if the status is approved.

<br/>

13.  **Admin Dashboard:**
    <br/>
    ***It will be private & only an admin can access this route.***

       - **Admin Profile:** An admin will see all the information discussed in **point 4**

       - **Course Approval:** This page will show the courses added by the instructor from the **Add Course page**. Show the following information: **Course Image, Course name, Instructor name, Instructor email, Available seats, Course Price, Status(pending/approved/denied) 3 buttons( Approve/Deny) and send feedback**.
        
         >**Note:** By default, the status will be pending. When an admin clicks on the Approve button the status will be updated to approved. The Deny and the Approve button will become disabled.
        
         >**Note:** If the admin clicks on the Deny button, the status will be updated to denied.The Deny and the Approve button will become disabled. 

         >**Note:** When the admin clicks on the send feedback button, a modal will be opened. Admin will write the approve/ deny reason in a text field and send to instructor. You can also do this in another route except modal.

        </br>

       - **Manage Users:**  The admin can see the relevant information of all registered users. There will be 4 tabs: **All Users, All Admins, All Instructors, All Students**. **All Users tab** will display the informtion of all registered users. **All Admins** tab will display only all admins information, **All Instructors** tab will display only all instructors information and **All students tab** will display only all students information. **"No users found" will be shown in the tab if any tab has empty data.** 
       
       Only For **All Users tab**, there will be **2 buttons**: **Make Instructor** button, **Make Admin** button. If a user clicks any of the button, make sure to disable it.

         - **Make Instructor button Action:** Update the user role as an instructor.

           >**Note:** If the admin makes a user instructor, that user profile page will have the instructor as the role]

         - **Make Admin button Action:** Update the user role as an admin.

          </br>

          > **Note:** When a user registers or logs in he/she will have the student role  by default until the admin assigns instructor or admin role.

        - **Add Events:** There will be a form where the admin will add the information discussed in **point 6(D)**. If he/ she gives event date which has already passed, then it will automatically displayed in the **Previous Events tab**.

        - **Manage Events:** The admin can update and delete the event.

14.  Implement  JWT token for Login and Registration systems (Email/ password & social login)\. You will send the token for the Dashboard routes and verify the user\.

</br>

15.  Create a 404 page\. Add any interesting image/ animation & a back to home button on the 404 page\. **Do not add header & footer in this page**\.

</br>

16.  Must Use [react-hook-form](https://react-hook-form.com/) in the registration & login page.

</br>

17.  Use the Environment variables both in client side & server side\.

</br>

18. Use **relevant icons** in your **dashboard menus**, animations on your website.\. You have to use **any one** of the animation librabies below:
    - [Framer-motion](https://www.framer.com/motion/)
    - [React-awesome-reveal](https://react-awesome-reveal.morello.dev/)
    - [React-spring](https://www.react-spring.dev/)
    - [React-anime](https://github.com/juliangarnier/anime)

<hr/>
<br/>

## :writing_hand: **Bonus Task:**

1. Minimum 20 meaningful git commits on the client-side repository and minimum of 12 meaningful commits on the server-side repository.

2. Create a readme for client-side and write about your project.

    - Website name or logo or both
    - Minimum 5 points of your website features
    - Used packages/ technology name
    - Live site link

3. Implementing a dark/light theme toggle for your website\.

4. Most likely the framework will do it for you\. However do not forget to make your entire website responsive\. (It is ok if the table is not responsive\.) Please note, all the pages including the dashboard will be responsive\.

5. Use tanstack query in all of the get APIs of admin dashboard.

6. Follow point **6(D) of main task**.


<hr/>
<br/>

## :writing_hand: **Optional Task:**

1. (Highly Recommended) Add extra features of your own you have learnt so far or you can explore new things. This will help you in the future to differentiate your project from others.

2. You can explore the below packages & try to to make your website more attractive:

    - [React-simple-typewriter](https://www.npmjs.com/package/react-simple-typewriter)
    - [React-joyride](https://www.npmjs.com/package/react-joyride)
    - [React-card-flip](https://www.npmjs.com/package/react-card-flip)
    - [React-image-zoom](https://www.npmjs.com/package/react-image-zoom)

3. Explore [Tanstack query mutations](https://tanstack.com/query/latest/docs/react/guides/mutations)

4. If you want you can add an intro video button in each course information, clicking on this button will open a modal which will play the video\.

5. Do point **10(4) of main task.**

<hr/>
<br/>

## :pushpin: **What to submit:**

- Your client-side code GitHub repository
- Your server-side code GitHub repository
- Your live website link
- Admin email and password.

<hr/>
<br/>

## :page_with_curl: **Some Guidelines:**

1. Do not waste much time on the website idea. Just spend 20-30 minutes deciding, find a sample website, and start working on it.
2. Do not waste much time finding the right image. You can always start with a simple idea. Make the website and then add different images.
3. Don't look at the overall task list. Just take one task at a time and do it. Once it's done, pick the next task. If you get stuck on a particular task, move on to the next task.
4. Stay calm, think before coding, and work sequentially. You will make it.
5. Be strategic about the electricity issue.
6. Use ChatGPT to generate JSON data. You can use chatGPT for other purposes as well.

<hr/>
<br/>


The Power of Self-Belief

Believe you can and you're halfway there




