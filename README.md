The goal for my first milestone project for Code Institute was to create a website for a wedding photographer to showcases their portfolio, and for couples looking to book a photographer for their wedding day. The aim of this project is to increase enquiries and photographic bookings for wedding events. I built this website using HTML5 and CSS3. 

### Overview

A website for a wedding photographer. The website features a home page, an about page, a gallery to showcase the photographer’s portfolio and a contact page so clients can enquire about bookings. The driving force of the website is to increase bookings. The way this is achieved is by directing potential clients to that contact page. 


### User Stories

* I want a website which is easily accessed on my mobile phone or tablet. 
* I want to be able to easily navigate the website. 
* I want to be able to view the photographer’s portfolio to see if their style suits my needs. 
* I want to be able to easily find the relevant information. 
* I want to be able to contact the photographer for any questions I may have. 
* I would like to see the photographer’s social media accounts to see more of their work. 



### UX 

The aim of this website is to target couples who are planning to get married. The priority focus is to drive potential clients to the contact page, as well as the social media accounts. Before deciding on a photographer for a wedding, it’s important to view their portfolio. For this reason, I opted to use a simple, and minimalist design with lots of photos. 

I also aimed to be very personable in text as it's not only the photos that attracted potential clients, but also the person behind the camera. 


### Strategy 

The goal of the website is to increase brand awareness by driving potential clients to social media accounts, and to grow bookings and enquiries via the contact page. 

##### Business Goals: 

Increase brand awareness.
Showcase examples of previous photographic events.
Drive users to the contact page to increase the number of bookings. 
Mobile first design to target large audiences who don’t have a PC/Laptop. 
Simple and effective UX to keep focus on the portofolio.


##### Customer Goals: 

Easy to navigate website on mobile.  
Searching for a high quality wedding photographer. 
A simple, and easy to navigate website. 
Possible to view photographer’s portfolio.
Contact the photographer easily. 
Being able to connect via social media. 
Someone who understands the importance of capturing special moments. 





### Scope 


The Scope and features of this project were based on market research of similar photographers in the wedding industry.  A simple and clean UX which allows the focus to remain on the two most important aspects of the website; the portofolio and the contact page. 

### Structure 

I am opting for a clean, and minimalist UI and UX. While the nav bar links to the relevant pages, I also linked the gallery via a button beneath the About Me section. I feel this helps to keep a streamlined approach to the website, and reduces users scrolling up/down every time they want to navigate between important pages. 
Initially I planned on showcases the photographer’s images via a sliding carousel. However, upon researching how effective carousels are for showcasing images, it did not seem like a good UI/UX design. The research shows that carousels are rarely cycled through by users. With this in mind, I opted to go for a straightforward layout design where all photos are visible to the user right away. 

### Skeleton 

All wireframes were developed with Balsamiq. As there are slight design changes for the mobile/tablet/desktop versions of the site, I have created wireframes for each screen type. I have linked the relevant pages below. 


- bootstap hamburger icon not working on mobile, so opted to use fontawesome icon instead.

#### Testing/troubleshooting
I ran into an issue where there is some extra margin showing on the right-hand side of mobile devices.

I seemed to have found a fix in setting a media query with my navbar max-width. Code here: 

 @media (max-width: 767px){
    .navbar {
       padding:0 20px;
    } 
 }

Solution found on Stack Overflow: https://stackoverflow.com/questions/17815390/large-right-margin-when-browser-is-shrunk-to-mobile-size-on-bootstrap

When adding images for the images on the home page - specfically for the section with two photos in black and white, there was another problem with overflow on the right-hand side. I solved the issue by adding 0px padding in the container. 

I ran into an issue where I was unable to hide an image on mobile only. Looking through the bootstrap documentation, I found a solution with display classes "d-none d-sm-block".  