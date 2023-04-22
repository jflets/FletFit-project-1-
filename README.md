# FletFit - Your Mobile Personal Trainer

Welcome to FletFit, your ultimate solution for fitness on the go! We bring the gym to you with our mobile personal training services. Whether you're at home, at the office, or anywhere in Haywards Heath, West Sussex, UK, our expert trainers will come to your location, equipped with state-of-the-art fitness equipment, to help you achieve your fitness goals.

![Responsive Mockup](/assets/images/responsive-mockup.png)

# User Experience (UX)

The FletFit website is the online platform for FletFit, a mobile personal training service. The website provides information about FletFit's personalized training plans that are tailored to meet individual fitness goals and levels. Visitors can learn about FletFit.

The site emphasizes the convenience and flexibility of having a personal trainer come to you, wherever you are. Additionally, the website provides a contact form for those interested in learning more or signing up for a training plan. Overall, the FletFit website is a helpful resource for anyone seeking personalized mobile training services to enhance their fitness journey.

## Key Points

  - Information explaining what FletFit does.
  - What are the plans we provide.
  - A form to sign up and become a client.
  - A way for users to contact FletFit with any questions.
  - A way to easily find FletFit through an embedded map.
## User Stories

  1. As a client, I want to access the FletFit website on any device and have a consistent user experience.

  2. As a first-time visitor, I want to easily understand what FletFit offers and become a member, so that I can start achieving my fitness goals with expert guidance.

  3. As a first-time visitor, I want to navigate the site without difficulty and find the information I need, so that I can quickly learn about the gym's services and features.

  4. As a returning visitor, I want to get prompt and helpful assistance from FletFit, so that I can contact the gym easily with any questions.

  5. As a first-time visitor, I want to be able to find the social links for FletFit easily.

# Design

## Color Scheme

![Color Pallet](/assets/images/coolors-pallet.png)

The website uses a pallet of dark and light contrasting colors. The color pallet was created using the [Coolors](https://coolors.co) website.

## Typography

Google Fonts was used fir the following fonts:

  - Syne ExtraBold 800 was used for all main headings.
  - Syne Regular 400 was used for the body text.

## Imagery

The Images used are copyright free images and I have credited the site in the credits section.

## Wireframe

The wireframe was created for the overall site using [Figma](https://www.figma.com)

![Wireframe](/assets/images/wireframe2.png)

# Features

- _Navigation Bar_

  - The nav bar includes links to the Logo, Home section, Join Us section and Contact section. The nav bar is fixed and will follow the user as the scroll down the site, allowing for easy navigation.
  - The nav bar links also have smooth section scrolling, this will make the navigation experience more pleasing for the user.

  ![Navigation Bar](/assets/images/nav-bar.png)

- _The landing page image_

  - The landing section includes a photograph with a text overlay to motivate a user into scrolling further on the site.
  - This section introduces the user to FletFit with contrasting text and a large join button to encourage the user to join.

  ![Landing Page Image](/assets/images/hero-section.png)

- _About Us Section_

  - The about us section will allow users to see the benefits of joining FletFit, as well as the benefits of having a trainer.
  - The user will understand the value of signing up to FletFit. This will motivate the user to take their fitness seriously.

  ![About Us Section](/assets/images/about-us-section.png)

- _Join Section_

  - The join section will allow the user to see the different fitness plans available and allow them to sign up through a form. The user will be able to specify what plan they will want plan 1, plan 2 or plan 3.
  - The join section is valuable as the user will understand what each plan provides and will understand the steps to fill out the form.

  ![Join Section](/assets/images/join-section.png)

- _Contact Us Section_

  - The contact us section will allow the user to see the location of FletFit and the contact information to get in touch.
  - The contact us section is valuable as the user will be able to easily find FletFit using the map and contact information is clear. This will motivate a user to contact FletFit for more information.

  ![Contact Section](/assets/images/contact-us-section.png)

- _The Footer_

  - The footer section includes social links and another clickable logo. The links will open in a new tab allowing easy navigation. The clickable logo takes the user back up to the landing page section for easy navigation.
  - The footer is valuable to the user as it encourages them to connect via social media. The footer also allows fast easy navigation back to the landing page section.

  ![Footer](/assets/images/footer.png)

## Features Left to Implement

- _Testimonial Section_
  
  - The testimonial section would allow a user to read positive reviews for FletFit from active users.
  - The testimonial section is valuable to a user as they will gain confidence that FletFit will help them.

# Testing

## Screen Size Testing
 
  - I used chrome developer tools to make sure that the site was responsive and worked on multiple screen sizes.

## Lighthouse Testing

 I used Lighthouse in the Chrome Developer Tools to test the performance, accessibility, best practices and SEO of the website.

 Suggestions:
   
   1. Preload the image used by the LCP element in order to improve your LCP time. Lighthouse suggests preloading the largest image on the site to reduce load up time. I have added a preload link in my HTML to preload the hero image.

   ![Lighthouse Score](/assets/images/lighthouse-1.png)
   ![Lighthouse Score](/assets/images/lighthouse-2.png)

## Validator Testing

- _HTML_
  - No errors or warnings returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fjflets.github.io%2FFletFit-project-1-%2F)

- _CSS_
  - No errors or warnings returned when passing through the official [W3C validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fjflets.github.io%2FFletFit-project-1-%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

## Solved Bugs

  1. The navbar would lose its alignment when on smaller devices, the navigation buttons on the top right would overlap the logo and would render the navbar unusable. To fix this I referred back to the [Love Running Project](https://code-institute-org.github.io/love-running-2.0/index.html) and added a media query that would make the navigation links drop below the logo with adequate spacing to keep a good user experience.

  2. The plan cards in the join section on smaller devices, would become very long and thin, making it hard to read and creating a bad user experience. By using a media query I was able to change the plan cards to display as inline-block to make the cards stack on top of each other, making them easy to read, providing a good user experience.

  3. When running the HTML through the W3C HTML validator the embedded google map was coming up as having an "bad value" this was due to having a percentage sign within the iframe tag, the sizing for width and height. To fix this i gave the iframe width and height fixed sizing and the within the CSS stylesheet, I gave the map responsive sizing. This fixed the error in the W3C validator.

  4. When running the HTML through the W3C validator the main hero join button came back with an error, the error was that a button tag cannot be a child of an "a tag". To fix this is removed the a tag and places the href link inside the button element tag.

## Testing User Stories

  1. As a client, I want to access the FletFit website on any device and have a consistent user experience.
  

  2. As a first-time visitor, I want to easily understand what FletFit offers and become a member, so that I can start achieving my fitness goals with expert guidance.


  4. As a returning visitor, I want to get prompt and helpful assistance from FletFit, so that I can contact the gym easily with any questions.


  5. As a first-time visitor, I want to be able to find the social links for FletFit easily. 

# Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, go to the Settings tab.
  - Scroll down the page to pages, then navigate to the branch dropdown menu. 
  - From the menu select main/master branch.
  - once selected press save and the page will automatically refresh with a detailed banner om the top to indicate successful deployment.

The live link can be found here - https://jflets.github.io/FletFit-project-1-/

# Credits

## Content

 - The navigation menu and footer design was taken from [Code Institute](https://code-institute-org.github.io/love-running-2.0/index.html)
 - The form implementation was taken from [Code Institute](https://code-institute-org.github.io/love-running-2.0/index.html)
 - The icons in the footer where taken from [Font Awesome](https://fontawesome.com/)
 - The embedded google maps section implementation was taken from [YouTube](https://youtu.be/inkP0lstoxU)
 - The text shadow implementation was taken form [Youtube](https://youtu.be/lP0VWUUW-Vs)

## Media

 - All photos on the site where taken from [Unsplash](https://unsplash.com/s/photos/gym)