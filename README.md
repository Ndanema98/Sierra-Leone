# Milestone project 1
# Sierra Leone - The History & Facts
["Sierra Leone - The History & Facts"](https://ndanema98.github.io/Sierra-Leone/index.html) is a website designed to educate people of all ages on Sierra Leone.  

Users of this website will be able to further their knowledge on Sierra Leone, through the key facts and historical timeline section. The competition section also allows a lucky user to win a free trip to Sierra Leone. This incentive should encourage more users to visit my website. 

This website was targetted at people who wanted to gain a better understanding of Sierra Leone's history and facts. 

This website was built using knowledge gained from HTML and CSS modules, for the purpose of completing my first Milestone Project for the Code Institute's full stack developer course. This website is easy to navigate and easy to read, with a clear goal and aim. 

  ![A screenshot of my responsive website](/assets/images/responsive.jpeg)
 
 # Features
 - ## Navigation 
   - The website name at the top left of the screen has a link that navigates to the home page when clicked. 
   - The other navigation links are at the top right of the screen. These are the "home", "gallery" and "competition time" links and when clicked, take you to thier respective pages. 
   - The navigation bar's font and colour vary from the rest of the page so the user can easily identify it. 
   - Due to the navigation element, the different sections of information are easier to locate. 

  ![A screenshot of my navigation bar](/assets/images/navigation.jpeg)

 - ## The Hero Section 
   - This section has an opening statement which breifly gives some information about Sierra Leone. It explains the location of Sierra Leone and it's climate environment. 
   - The colour scheme for my project is green, white and blue; which is the same colours of the Sierra Leone flag. Due to this I have made the heading green and the text for this section white. 
   - The zoom element has also been added to the background image, to make it more aesthetically pleasing. 

   ![A screenshot of my hero section](/assets/images/hero-section.jpeg)

  - ## The Key Facts Section
    - This section includes some essential information about Sierra Leone. These sub-sections include "languages", "independance", "capital city" and "currency". 
    - The middle section contains the Sierra Leonean flag, which whilst being easy on the eye and matching the sites colour scheme, it also allows users to see what the Sierra Leonean flag looks like.
    - The heading's for this section were made green to match the colour scheme. Therefore the text was made blue, which compliments the white background. 

    ![A screenshot of my key facts section](/assets/images/keyfacts-section.jpeg)

  
 - ## The Timeline Section 
   - This section has a timeline of major historical events that have occured. 
   - Keeping with the colour scheme the text was made white as green or blue would not contrast with the background image enough. 

   ![A screenshot of my timeline section](/assets/images/timeline-section.jpeg)

  - ## The Gallery Section
    - This section has a range of pictures that I felt best represented Sierra Leone. 
    - Masonry styling was also used as the width of the images were kept the same but they had differing heights. 

   ![A screenshot of my gallery section](/assets/images/gallery-section.jpeg)

  - ## The Competition Section
    - This section has a form which can collect users answers for the quiz. The form also collects user details so that they can be considered for the prize. 
    - This section is important as it gives the users an incentive to use the website. 
    - Form validation requests users to input the correct information into the form. It also prevents users from submitting blank quizez. 
  

    ![A screenshot of my competition section](/assets/images/competition.jpeg)

  - ## Footer
    - This section encourages users to find out more through the social media links provided. 
    - The icons were made blue and the background was made white to match the colour scheme. 

    ![A screenshot of my footer](/assets/images/footer.jpeg)

 # Testing 
 - ## Manual 
   -  This website has been tested using three different browsers (Google Chrome, Firefox, Safari) and I can confirm that it works. 
   - This website has been tested with all the standard screen sizes and I can confirm that it is responsive. 
   - The navigation bar has been tested and I can confirm that all the different links take you to their respective pages. 
   - I can confirm that the form works and requires an entry in every field. The submit button also takes you to the appropriate page, when the form is complete. 

- ## Validator 
  - ### HTML
    - The official W3C validator was used to validate my HTML. No errors were found when my code was input. 

   ![A screenshot of my HTML validation](/assets/images/html-validator.png)

  - ### CSS 
    - The official W3C validator (Jigsaw) was used to validate my CSS. No errors were found when my code was input. 

    ![A screenshot of my CSS validation](/assets/images/css-validator.png)

  - ### Accessibility 
    - The Lighthouse function in devtools was used to see if the font and the font colours used were easy to read and access. I can confirm that all the pages on my website passed. 
      index.html
       ![A screenshot of the accessibility score for index.html](/assets/images/accessibility1.png)

      gallery.html 
       ![A screenshot of the accessibility score for gallery.html](/assets/images/accessibility2.png)

      competition.html 
       ![A screenshot of the accessibility score for competition.html](/assets/images/accessibility3.png)'
  
- ## Bugs 
   - ### Solved 
     - The Submit and Clear button were not visable. This problem was solved when i added "input[type=submit], input[type=reset] {
     border: 3px solid #1843DE; }" to my style sheet.
     - My heading for my facts on the right was floating the wrong way. This was fixed by using "float:left;".
     - The navigation bar on my competition page kept getting pushed under the image. This was fixed using "@media screen and (max-width: 1400px){
    #menu {
        clear:left;
        float:left;
        margin-left: 30px;
        margin-bottom: 15px;}. 

   - ### Unsolved 
      - The navigation bar overflows when the screen gets to 350px and under.
      - My central image overflows when the screen gets to 350px and under. 
      - My commit messages used the wrong attribute. Should have used "feat" instead of "docs".  

- ## Technologies Used 
   - Git 
     - Allowed me to add commit and push my code to github for version control. 
   - Gitpod 
     - The programme used to code my website 
   - Github 
     - Allowed me to store my repository and files pushed from Gitpod 
   - Fontawesome 
     - Used to display icons to make my website more visually appealing. 
   - Chrome developer tools 
     - Allowed me to troubleshoot and edit my code.
   - Am I Responsive 
      - Allowed me to check the responsiveness of my website at different screen sizes. 
   - W3C Validator 
      - Allowed me to validate my HTML and CSS code against industry standard. 

- ## Deployment
   - ### Remote 

   1. Click on the settings icon in the navigation bar.
   2. Scoll until Github pages is visable.
   3. Once clicked change the branch to "main" and change the directory to "root". 
   4. Next, click the save button. 
   5. It may take a few moments for the website to publish but once its done, a link to the live website will be provided. 

    - ### Forking
    1. In the top right corner of the page click on the fork button. 
    2. The next page will show a forked version of my project. 

    - ### Cloning a repository
     1. Fork the repository using the steps above. 
     2. Next click code 
     3. You will then be asked if you want to clone using HTTPS, SSH or Github CLI
     4. Click the copy button
     5. Open Git bash and select the directory you want the clone to go to
     6. Type git clone and then paste the URL. 
     7. Lastly press enter and your clone will be created. 

- ## Credits
  - ### Images
    - The images for my gallery and my background images can be [found here.](/assets/images/images-links.txt)

  - ### Code
    - The code for my header was taken from Code Institute's [Love running walkthrough](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LR101+2021_T1/courseware/4a07c57382724cfda5834497317f24d5/637be1a2e3b84b25aa33f3ab4d98603c/)
    - The code for my footer was taken from Code Institute's [Love running walkthrough](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LR101+2021_T1/courseware/4a07c57382724cfda5834497317f24d5/e6d4cda2bc08458ba94d2092be9bad3a/) 
    - The code for my timeline and key facts was inspired by Code Institute's [Love running walkthrough](https://learn.codeinstitute.net/courses/course-v1:CodeInstitute+LR101+2021_T1/courseware/4a07c57382724cfda5834497317f24d5/f2db5fd401004fccb43b01a6066a5333/)

  - ### Information 
     - The information used in my timeline can be [found here](https://www.bbc.co.uk/news/world-africa-14094419)
     - The information used in my hero text can be [found here](https://en.wikipedia.org/wiki/Sierra_Leone)

- ## Acknowledgement 
    - The online tutors that Code Institute provides. 
    - My mentor Ben Kav for helping me when I was stuck. 
    - Everybody on slack, for their advice. 









