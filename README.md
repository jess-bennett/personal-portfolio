# Personal Portfolio
The purpose of my project was to create a personal website to showcase my work as a software developer and also to provide some background information on my career up to this point. Essentially, I wanted to create a ‘living’ CV. 

It is important to me that the site reflects my personality and doesn’t appear to be just a generic website. For this reason I have used several images of myself, and all text has been written in a conversational-style. 

The quote on the homepage (which also appears in the About section) was something I came across on the Code Institute course. It resonates very strongly with me and I am hopeful that my site demonstrates a good balance between logic and creativity. 

Creating this project has been quite a learning curve. Not only with regards to putting into practice what I have learnt so far, but also in terms of understanding my way of working a lot better – and hopefully improving on this! I began building the site with quite a clear idea in my head. As can be seen in my wireframe document (user-centric-project-wireframe.pdf), I started out using a picture taken in the village where I grew up as my inspiration for the design (as part of the ‘reflection of my personality’ methodology). I used Adobe CC to create a palette based on this image, and was so pleased with the idea that I ignored the fact that I didn’t really like how the colours actually looked! I had also set upon a single-page site (which has caused me more issues than I first realised) and for some reason (which possibly made sense to me at the time, but doesn’t now!), set each section to be 100vh. 

About halfway through the project I realised my mistake on both these counts, and created a new index.html. I copied the code across line by line to make sure that I fully understood each design-decision I was making and at the same time, rectified those two major mistakes. Each section is no longer limited in height, which has helped enormously with the layout. And the colour palette, whilst still based on my original image, is a much more abstract take on the greens and blues of the countryside – and I think, more suited to the purpose of the site.

All these changes have meant that this project took quite a bit longer than I had anticipated. But for a first project, I have learnt a huge amount, which I hope will help the planning process for my next project.

## UX
The website has been built with prospective clients, recruiters, employers and collaborators in mind. Whilst a personal portfolio site is a fairly simple idea, I wanted it to appeal to different people for different reasons. Basically, I want something which is impressive, but more importantly, easy-to-understand for both technical and non-technical mindsets. 

With this mind, I have tried to ensure that the site is easy to navigate and that everything works and can be found where expected. But at the same time, many of the simple features include more complex programming to demonstrate what I have learnt so far. Examples of this are the animations used on the homepage and about sections, and the post-card style contact form.

### User stories
* As a prospective client, I want to see an example of the type of website that could be created. I am less interested in the content itself, and more interested in the different features that have been implemented and the overall look of the site.

* As a non-technical recruiter/employer, I am interested in the work history of the candidate and the availability of a hard-copy CV.

* As technical recruiter/employer, I would like to see work history of the candidate and also see a demonstration of their programming ability.

* As a prospective collaborator, I am interested in seeing the candidate’s programming ability and design choices.

My wireframe document (user-centric-project-wireframe.pdf) demonstrates how I attempted to meet the above requirements – with particular reference to the Strategy plane section.

## Features
### Existing Features
* Homepage – navbar
    * Responsive for desktop and mobile users. Allows all users to navigate to key sections of site.
* Homepage – navbar image
    * Keeps to ‘personal’ ethos of the site. Also allows user to quickly return to homepage.
* Homepage – main
    * Displays quote that has shaped the project. Demonstrates additional programming ability.
* About – svg
    * Showcases work history in a visual manner (text provides additional information to the icons)
* About – modals
    * Gives further information about each stage of work history and the skills (those that I deem relevant to software development) gained. Icons have been given hover effect and pointer-cursor to indicate that they are clickable. 
* About – svg animation
    * Demonstrates additional programming ability. JS added to ensure that user sees animation, rather than it happening ‘invisibly’ whilst they are on another page. 
* Skills page
    * On desktop, this page replaces the ‘software developer’ modal to allow for a more detailed overview. On mobile, it is a smaller additional section with just the progress bars. Its purpose is to give a back story to my career path, and is also designed to be updated as I continue to progress as a software developer.
* Portfolio page
    * Showcases work as a software developer. Also designed to be regularly updated.
* Portfolio cards animation
    * Designed to save space on layout, and also to demonstrate additional programming ability. This section has changed quite a lot since its original inception! This is mainly a design choice. The masonry style didn’t work at all with the typically ‘square’ webpages I wanted to display. I have added additional information about the website on the reverse of each card. This is viewable on larger devices, but not on mobile.
* Contact page
    * Currently more of a design-feature since it’s not actually useable! I did try investigating php files to see whether I could make it fit for purpose, but felt that I was going down a path that was not relevant to the current project. Its hypothetical purpose is to provide a quick way for all users to get in touch.
* Footer
    * I have kept this quite minimal with just additional contact options and copyright notice.

### Abandoned Features (from strategy plane)
* Image when loading homepage
    * I decided against this as I felt it was overly complicated visually, and decided to use the animated text on the homepage in its place
* Home image to show through modal
    * The idea behind this was to keep the image in place throughout, so it would still display when the menu modal was opened on mobile. However, I decided to make the menu modal narrower than the screen, and place to the right (in line with the hamburger icon), and so it didn’t make sense to have the home image shift over from its usual place.
* Email pop out to client
    *I realised this was relatively easy to implement. However, I didn’t like the fact that it took the user away from the site, and also seems pointless when I could just provide an email address instead.

### Features Left to Implement
* I originally wanted the hamburger icon to transition into the ‘close modal’ cross when clicked, via a rotation animation (rather than the cross just sitting on top of the hamburger). However, I have realised that this is more complex than I had originally anticipated and I am wary of undoing a lot of the design I am satisfied with, for the sake of a very small ‘nice-to-have’ feature. I may come back to this.
* Working contact form.
* Submit message on contact form – once the contact form is working correctly, I would like to change the current message box to one that indicates the user’s message has been sent successfully. 
