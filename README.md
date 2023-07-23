Pen B Wildlife Photography Workshops

Pen B Wildlife Photography Workshops is a business website offering photography workshops in the New Forest, Hampshire, UK. The two main workshops offered are half day and full day walking photography workshops, where the customer joins a small group and they receive a tour of a specific area of the New Forest, Hampshire. The chosen tour area will have been selected to provide the best opportunities to photograph specific wildlife and/or landscapes. This will focus on opportunities to photograph:
 - Deer, ponies, donkeys, pigs (all allowed to roam wild in the area).
 - Flora and fauna.
 - Birds, insects.
 - Landscapes - woods, lakes, rivers. 
 - Seasonal events, such as deer rutting season or the yearly drift where ponies are rounded up so they can be health checked.

The main target audience will be amateur photographers, keen walkers and holiday-makers as the New Forest is a popular tourist destination in the UK. 

User Stories and Features

#1a User Story: 

1. As an amateur photographper.
2. I want to to be able to carry out a general search.
3. So that I can find companies offering Wildlife Photography Workshops.

#1b User Story: 

1. As a holiday-maker visiting the New Forest.
2. I want to know what activities are available.
3. So that I can plan my holiday. 

User Steps: 

General search: SEO tags - photography, courses, wildlife, horses, nature, workshops, safari, Hampshire, Dorset, Wiltshire, New Forest, techniques, learn, holiday, groups, social, landscape photography, forests , woods, birds, deer, rut. 

Features/Acceptance Criteria:
The website will have the above tags so that it can be found in searches. 

#2 User Story

1. As an amateur photographer
2. I want a choice of photography workshops.
3. So that I can decide if I want more information.

User Steps: 

Easily navigate to product on page (workshops). Easily find more information on the workshops. Easily fill in a short form for more information. 

Features/Acceptance Criteria: 
There are links to the products (workshops) from the start of the webpage in the navbar then in the: 
- Hero image.
- Introduction section
- Main section
- Click in and out of different workshops to compare.
- There is a quick and simple form where the user can provide their name and email and request more information.

#3 User Story 

1. As a customer considering buying a photography workshop.
2. I want to know more about the photographer and their work.
3. So that I can decide if I want to take part in a course.

User Steps: 

Easily navigate to a section about the photographer. Easily navigate to a section or link showcasing the photographer's work. 

Features/Acceptance Criteria: 
-There is an about link in the navbar. 
-The first section contains a picture of the photographer and a summary of who they are. There is a link to "find out more" where I can read more about the photographer's background and work. 
-There is a link in the navbar that takes me to examples of the photographer's work. 

#4 User Story
1. As a customer with an interest in photography workshops.
2. I want more specific information about the workshops.
3. So that I can decide if I want to book/request more information.

User Steps: 

Easily navigate to an overview of the workshops available. Easily navigate to more information about each workshop. Social proof in the form of the reviews from previous customers. 

Features/Acceptance Criteria: 
-There are reviews from previous customers. 
-There are cards with brief summaries of the workshops available. 
-There are links on the cards to find out more. 
-There is a more detailed section about each workshop which includes:
 - Duration of workshop.
 - Examples of photographic opportunities.
 - Price per person.
 - If there are group reductions.
 - Number of people per group.
 - Transport.
 - Food.
 - Clothing and equipment needed.

Current Features

Navigation Bar
Responsive, fixed navbar with links to home, workshops, and prints/gallery of photographers work. the navbar is fixed and identical on both the main page and the form page, in this way the user doesn't need to click back to return to each page and can easily navigate to their desired section of the webpage. The text on the navbar is hidden on smaller screens and replaced with a hamburger menu.  The navbar theme and hamburger menu are from a bootstrap template. They have been modified by font styling and the links have been changed and a hover effect over the links added. 

The Hero Image
The Hero Image is a carousel, showcasing three of the photographer's photos. The carousel was chosen because research into similar photography workshop or photography safari webpages showed that there was often a carousel with images and this is a good opportunity to immediately present the user with ideas of the types of things they could photograph.
There is text overlaying the images providing basic information about the website: 

1. What: "Wildlife Photography Worksops"
2. Where: The New Forest, Hampshire, UK.

A bootstrap Carousel Template was chosen for two reasons: firstly, it requires javascript which I am not proficient in and secondly because part of the aim of this project was to develop knowledge and skills using and modifying code using Bootstrap. The challenges of using a Bootstrap template carousel have been: 
-I don't fully understand how the whole thing works. 
-Modifying parts of the carousel took some time and effort and often had knock-on effects on other aspects of the carousel that were unexpected. 
-I initially started using a carousel template that used svg files rather than img files; this was problematic and after research and trial and error I eventually found an earlier version of the template which used images. 
-I've noted in the code where I have modified the template, the main changes/addtions are: 
  -Adding images and styling to make them responsive and scale correctly. 
  -Stopping the carousel from scrolling immediately as the webpage loads as this was distracting. 
  -Moving the text overlay position and changing the colour and font. 
  -Changing the top margin so that the images fit. 

I initially modified the bootstrap template by hiding the text on xs and sm screens, however despite the images being responsive and scaling, they looked a bit narrow.
I then made a separate hero image with text overlay to be displayed just for xs screens, and hid the carousel entirely. In this way, just the main product headline of the site - "Wildlife Photography Workshops" is shown. 

1. Carousel Template: [add credits]
2. Carousel Template: [add credits]
   
Welcome Section 

This section provides a photo and a brief introduction to the photographer, Penny; this was kept short as the webpage needed to be responsive so it would have taken up too much space on smaller screens. It was also kept short as the user's main objective visitng the site is to find out about the workshops being offered. There is a link to "read more" at the end of the introduction to the photographer which takes the user to the "About the Photographer" Section if they would like to read more. 

Workshops Cards Section

This section has 4 cards each with a brief overview of the different workshops available. Each card has a different image which is taken by the photographer. The cards are also links which take the user to the main "Workshops" section. My research showed that cards are a popular feature to use to give the user information. The cards also presented an opportunity to learn more about and experiment with both grid and flex. I initially started off with a youtube tutorial on how to make cards using grid (credits below) - however, I found that for my purposes and the way I wanted the cards to respond, I eventually went from using grid to flex. This meant that the cards would wrap responsively without media queries. Challenges I found here were keeping a track of which element was the flex parent and which the flex child. I also found the cards were bigger than I wanted so I experimented with changing the height, font size, margins and padding to get them to a size I wanted. I have not yet been able to get the cards to stay a fixed size, for example if the text length changes, so the workaround has been to experiment with the text length and content to keep all cards an equal size. 

Workshops Section (to be completed) 
-4 simple articles with image on top (on larger screens) and centered text. List the features of the each workshop. 
-Internal links from the workshop cards and links in this section to the register form page. 

This section will allow the user to see exactly when the meetups will happen, where they will be located and how long the run will be in kilometers.
This section will be updated as these times change to keep the user up to date.
Meetup Times

The Footer

The footer section includes links to the relevant social media sites for Love Running. The links will open to a new tab to allow easy navigation for the user.
The footer is valuable to the user as it encourages them to keep connected via social media
Footer

Gallery

The gallery will provide the user with supporting images to see what the meet ups look like.
This section is valuable to the user as they will be able to easily identify the types of events the organisation puts together.
Gallery

The Sign Up Page

This page will allow the user to get signed up to Love Running to start their running journey with the community. The user will be able specify if they would like to take part in road, trail or both types of running. The user will be asked to submit their full name and email address.
Sign Up

For some/all of your features, you may choose to reference the specific project files that implement them.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

Features Left to Implement
Another feature idea
Testing
In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

Validator Testing
HTML
No errors were returned when passing through the official W3C validator
CSS
No errors were found when passing through the official (Jigsaw) validator
Unfixed Bugs
You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed.

Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub)

The site was deployed to GitHub pages. The steps to deploy are as follows:
In the GitHub repository, navigate to the Settings tab
From the source section drop-down menu, select the Master Branch
Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html

Credits
In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism.

You can break the credits section up into Content and Media, depending on what you have included in your project.

Content
The text for the Home page was taken from Wikipedia Article A
Instructions on how to implement form validation on the Sign Up page was taken from Specific YouTube Tutorial
The icons in the footer were taken from Font Awesome
Media
The photos used on the home and sign up page are from This Open Source site
The images used for the gallery page were taken from this other open source site
Congratulations on completing your Readme, you have made another big stride in the direction of being a developer!

Other General Project Advice
Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work!

One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through this article by Chris Beams on How to Write a Git Commit Message

Make sure to keep the messages in the imperative mood
When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.

For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept.
Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:

Writing Your Best Code
HTML & CSS Coding Best Practices
Google HTML/CSS Style Guide
Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process!
