# Testing

  NOTE: The readme file was built before the last mentor session so there were a lot of changes made after the last session with mentor. Too many screenshots need to be changed so I did add some of the needed new screenshots. Some of the screenshots I did not add because it was too time-consuming, so I just wrote them in the readme file.

  In the commit, some bad names were used. Gitpod had a problem with its live server, and I was struggling with it. Therefore I chose to save it on GitHub to see what the website looks like. Later on, in the mentor session, mentor said I wasn't supposed to do that.

   ![this is an image of showing bad commit made in the git, one](assets/images/readme-images/git-bad-commit-one.png)  

   ![this is an image of showing bad commit made in the git, two](assets/images/readme-images/git-bad-commit-two.png)

* I tested this website on three different browsers: Google Chrome, Microsoft Edge and Firefox.
* The website works perfectly on all the different devices listed at the bottom of the text image.

  ![this is an image showing website works on differnt sizes devices](assets/images/readme-images/devices-resolutions.png)

## Bugs
* ### Bugs Occurred
  * When I clicked on about us or contact us through the navigation, the main text of about us and contact us was hidding.

    ![this image for buggy about us](assets/images/readme-images/buggy-abt-us.png)

    ![this image for buggy contact us](assets/images/readme-images/buggy-contact-us.png)
  
  * When I checked into the lighthouse, I encountered an accessibility lower score, the reason being that the color contrast wasn't matching with the background.
 
* ### Bugs Fixed


  *  Therefore, I used a scroll-margin in CSS to fix this issue.

      ![this image for fixed about us issue](assets/images/readme-images/fixed-abt-us.png)

     ![this image for fixed conatct us issue](assets/images/readme-images/fixed-contact-us.png)  

    * I had to change the color contrast from red to tomato.

      ![this image for bug color Issue](assets/images/readme-images/bug-color.png)

* ### Unfixed Bugs
  * when you click on contact us or about us, the border-bottom disappears. I can fix this issue by using javascript but I haven't learned that yet so in the future I will fix this bug.

  ### Accessibility 

   * I checked accessibility using the Google Chrome dev tools lighthouse. I got a score of 100 for accessibility.

  ### Performance
   * My project report was generated using Google Chrome lighthouse. I was having an issue that I kept getting a Low-Performance score, sometimes it got to below 85. When I tried checking in the incognito window mode, the same issue was occurring so I reached out to Slack to ask about this issue.  
Several Slack users helped me out by checking my project score on their own devices. The score appeared to be perfectly fine on their devices.  
However, I wasn't sure so I reached out to tutor support, and they confirmed their score was same as other users, which led me to realize the lower performance was related to hardware/software, rather than the code itself.  
As a result, I uploaded my lighthouse report screenshot and another user's report screenshot for my project, for mobile and desktop both.      
 
 * ### Other User Screenshots.
   * ### [Desktop](assets/images/readme-images/other-user-lighthouse-dekstop.png) 

     ![this is an image of other user desktop](assets/images/readme-images/other-user-lighthouse-desktop.png)

    * ### [Mobile](assets/images/readme-images/other-user-lighthouse-phones.png)

      ![this is an image of other user android](assets/images/readme-images/other-user-lighthouse-phones.png)

 * ### My own device screenshots.
   * ### [Desktop](assets/images/readme-images/my-lighthouse-desktop.png)

     ![this is an image of my devices for desktop](assets/images/readme-images/my-lighthouse-desktop.png)
    
   * ### [Mobile](assets/images/readme-images/my-lighthouse-phones.png)

     ![this is an image of my devices for android](assets/images/readme-images/my-lighthouse-phones.png)

## Code Validator Testing
 * HTML 

    Checking the HTML code by using [W3C HTML Validator](https://validator.w3.org/#validate_by_input) did not find any errors.    
    
    ![this is an image of html code Validator text](assets/images/readme-images/html-validator.png)

 * CSS 

    Checking the CSS code by using [W3C CSS Validator (Jigsaw)](https://jigsaw.w3.org/css-validator/#validate_by_input) did not find any errors.  

    ![this is an image of css code Validator text](assets/images/readme-images/css-validator.png)