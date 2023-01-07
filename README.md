# Everyday Lifehacks - Milestone Project 1

Welcome to Everyday Lifehacks, a simple website set up with the main goals of providing useful tips and tricks you can use around your house to make your life easier and save money. Whether that be cooking, cleaning or giving old things a new purpose, you're sure to learn something new on Everyday Lifehacks.

## Initial Discussion
---

Everyday Lifehacks is a collection of useful lifehacks with the aim to provide value to its users and act as a place where people can share their own lifehacks and pick up tips and tricks along the way. 
Everyday lifehacks had a large following on social media platforms sharing pictures and videos from different accounts on many different platforms. They needed a central location to share content and for their engaging audience to submit their own content to be featured on the site. By having their own website, Everyday Lifehacks plan to become the number one destination for people looking to hack their way through life!

## User Stories

### Client Goals

- To be able to view the site on a range of device sizes.
- To be able to clearly read and view articles on mobile, tablet and desktop
- To make it easy for users to view different categories of lifehacks
- To make it easy for users to submit their own lifehack with supporting pictures or videos
- To access the original content creators’ websites, channels or social media platforms

### First Time Visitor Goals

- I want to find quickly be able to navigate to the lifehack category I need
- I want to be able to navigate through the site easily with minimal clicks
- I want to be able to link to their social media accounts

### Returning Visitor Goals

- I want to be able to easily submit a hack using the form on the site
- I want to be able to find new lifehacks when they are added to the site


# Design
---

### Colour Palette

![website colour scheme](documentation/color-scheme.png)

I went for this colour scheme as I wanted a main colour of blue to be bright, welcoming and easily recognisable. The other colors went went with the theme with purple used as my main second colour along with black and white

### Typography 

I used Google fonts in this project

- I used Lato for the body paragraph elements with Arial as a backup
- I used Roboto Mono for the headings and sans-serif as a backup

### Media

My images and videos were taken from a variety of different places. My embedded YouTube videos come from various lifehacks channels, all which are credited on the website and below in the credits section

My images were taken from lifehack websites and free stock photo websites, pexels, unsplash and pixabay. All photos are also credited in the credit section

# Features

This website is made up of 7 pages in total, the home page, the hacks category page, 3 different category pages with articles, a submit form page and a thank you page. 

### Navigation Bar

The Navigation bar features on all pages and contains the website logo and links to the main 3 pages. The nav bar is fully responsive to different page sizes. The Everyday Lifehacks logo is also a link back to the homepage. I made the page links a different colour when hovered on to help with user experience

![page navigation and logo screenshot](documentation/navigation-ss.png)

### Hero Image

The hero image is the main image seen when a user uses the site. The images was chosen as it goes with my colour theme and it features a magnifying glass over a euro coin, signifying the money saving aspect of the lifehacks. I thought the picture went well with the overall theme of the website. The hero image also contains text to welcome the user to the site and a button with a link to the hacks category page so the user can access the info they need quickly without having to scroll through the page.

![home page hero image of magnifying glass](documentation/hero-image-ss.png)

### Main body

The main body of the home page further explains the purpose of the website. It gives users an insight into what to expect on the website and offers direct links to the 3 different category pages. The main body text carries on the colour theme of the website.

![screenshot of main body text with links to category pages](documentation/main-body-ss.png)

### Submit A Hack Button

This section of the home page allows users to jump straight to the submit a hack page to fill out the form and submit their own lifehacks. This section follows the colour theme of the website with a blue overlay over the background image and a scroll effect on the background making it seem like the image is moving behind the text. This section also included a button with the same colour scheme as previously used

![screenshot of submit a hack homepage section](documentation/submit-a-hack-ss.png)

### Footer

The idea for the footer came from the love running project. I liked the simple but effective layout of the social media icons. I changed the icon colour to the secondary website colour to match the theme and added a little bit of copyright text below. Lifehacks are often shown in videos and pictures so social media would be a big part of this website so I thought the simple footer with the social icons fit perfectly.

![screenshot of page footer with social media icons](documentation/footer-ss.png)

### Hacks page

On the hacks page I wanted to create a visual way of sorted the lifehacks into 3 main categories. I done this by creating 3 seperate divs with borders and background images and using this as my category page. You can see by the pictures below the icons in the background match the corresponding category and i have used the main colours of the website as an overlay. I also used the scroll effect on these background as it appears when your scroll down the page the background changes. I thought this was a sun way of making a category page and adds to the design of the website. These divs are also fully responsive and change size to better fit smaller screens as to not be too big on mobile devices. 

![screenshot of cleaning hacks category page](documentation/hacks-category-1.png)
![screenshot of cooking hacks category page](documentation/hacks-category-2.png)
![screenshot of upcycling hacks category page](documentation/hacks-category-3.png)

### Hacks articles

In the hacks pages I used a combination of iframes and images in my articles for photos and videos. I thought this would give a better user experience as visual aids are more helpful when learning. The iframes are videos taken from youtube and all links and videos will be referenced below. The video and image dimensions are the same in order for the website to look uniform and they both are fullt responsove to smaller screen sizes

![screenshot of article on hacks page](documentation/article-ss.png)

### Submit A Hack Form

The submit a hack form is where users can submit their own hacks to be featured on the website. This will drive website interaction and create a community of lifehackers! The form design follows the website colour scheme. The form also allows users to submit a photo or video with their hack so they can show their hacks in more detail

![screenshot of submit a hack form](documentation/submit-form-ss.png)

### Thank you page

This page was created to let the user know their form was submitted. This is a simple page with a thank you message and a button to return to the home page. This was a later addition to my website as I thought the user might get confused when submitting the form if their was no feedback to tell them their submission was successful.

![screenshot of thank you page](documentation/thank-you-ss.png)

## Accessibility
I have tried to make my website as accessible as possible by using the below features

- Using semantic HTML.
- Using alt attributes on all images on my website.
- Making sure that there is a sufficient colour contrast throughout the site and text and headings are easily readable.



# Testing
---

During this project I regularly tested my site using Chrome developer tools and HTML and CSS code validator. This helped me with the responsiveness of my sit and also to make sure the code I had written was up to industry standard and there was no obvious mistakes.

## W3C Validator Results

I tested each page of my website's code in the HTML Validator and the results are linked to below. I also tested my CSS code in the validator and the results are also linked below

- [HTML Validator Tests and Results](supporting/html-test.md)
- [CSS Validator Tests and Results](supporting/css-test.md)


## Lighthouse

I used lighthouse to test the performance of my website. These tests returned some unexpected results and forced me to change some elements of my site in order to increase the website speed. Below are the results

### Homepage

The first test I did on lighthouse was the index.html page. The score for accessability and best practices were good but the performance and SEO score were letting me down. I knew my images on the homepage were not optimised for web so this is something that will bring up my performace score and also I haven't added any keywords to my pages so this should bring up my SEO score.

![screenshot of lighthouse test 1](documentation/lighthouse-test-1.png)

To improve this score I converted my hero image and my submit a hack background images to webp files. This drastcally reduced the file sizes leading to faster loading times. I also added a meta description and meta keywords to the head of the page to improve SEO.


### Cleaning Lifehacks Page

When I tested this page with lighthouse I found that my embedded youtube videos were seriously reducing the speed of my site. When doing some research I found that because of how much external content they have to load, they require a longer page loading time. 

![screenshot of lighthouse test on cleaning page](documentation/lighthouse-test-cleaning.png)

As you can see from the above screenshot, my performace score was very low. To fix this I researched how to load YouTube embeds faster. There was some solutions using JavaScript but my knowledge of this language got in the way of me being able to use this as a solution. I found a website that converts Youtube videos for embedding into smaller load times so I tested this out. This allows me to only load the video when the user presses the play button, greatly improving site speed on first load



