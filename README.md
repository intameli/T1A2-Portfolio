# T1A2: Portfolio

Jacob Smith

[Link to website github](https://github.com/intameli/T1A2-Portfolio)

## Site overview

### Purpose of site

This site was created to advertise myself to potential employers. It aims to showcase my abilities through my side projects, my personality through the blog, and provide details about my work experience.

### Target audience

The target audience is a potential software employer and as such the audience can be assumed to have technical knowledge relating to software.

### Site structure and features

The site will have 8 pages. As well as content, each page will have a header, footer and nav bar. The nav bar will contain three always visible links to the pages: home, info and blog list. The five other pages will be blog posts, and links to them will be shown in a drop-down menu when the mouse is hovered over the blog list link in the nav bar. Links to the individual blog posts will also be shown in the blog list page which is necessary for mobile users as hover doesn't work with touch devices.

Each blog post will contain an image gallery and a video as well as text. The image gallery will be images stacked on top of each other in a skeuomorphic style. Left and right buttons below will allow the user to cycle through which image is displayed on top.

The info page will have descriptions and links to my side projects. The info page will also have cards displayed in a grid that contain information about my experience. The home page will explain the site and provide links to my cv, github and linkedin.

The site will be fully responsive so that it works on all devices. Additionally semantic html elements will be used and images will have alt text so that the site will be navigable by screen reader. Rem units will be used for font so that users who require larger text are accommodated.

![sitemap](docs/sitemap.png)

### Tech stack

It will be a static site with no backend. Html and css will be used to create the site. Additionally, a small amount of javascript will be required to make the image gallery work.

## Components

### Header (graphical)

The header is a photo I took on my holiday to British Columbia this year. I think it gives the site a nice vibe.

### Footer (text)

### Nav (text)

The nav is designed to feel snappy and responsive. Originally the animations on the nav were slower. But after using the nav for I while I realised that having a slower transition allowing you to see many frames of the animation was hurting its useability and general feel. I ended up making the animations as fast as I could while still having the animations read properly.

![nav](docs/nav.png)

### Home content (graphical/text)

This component contains text, the links component and an image.

### Links (text)

### Info content (text)

### Experience card (graphical/text)

The experience cards with their large size, border and greyed-out background draw the audience's eye.

### Blog posts list (text)

The links are a larger font than the created date helping to focus the audience's attention on the main content.

### Blog post (graphical/text)

This component contains text and a video.

### Image gallery (graphical)

The image gallery engages the audience by being a familiar and clear design. The images are laid out (using css grid) to overlap each other while still having a portion of the image visible. A border and a drop shadow on each image help to separate them from each other. The style of the gallery is reminiscent of a stack of images stacked on a desk.

![image gallery](docs/gallery.png)

## Pages breakdown

### Overall design choices

Black text on a white background is the easiest to read so I decided on a light theme for my website. Similarly, I chose the Roboto font as it is easy to read. The nav bar went through several design iterations. It wasn't until I added a line below the nav bar that I realised having the drop-down menu form out of that line would look nice. Overall I went for a less is more approach to the design of the site, generally trying to keep it simple.

### Home

I decided to add an image to this page to make the site look less bare. A mern stack image seemed appropriate considering the target audience of potential software employers. To make this page responsive I switch from a one column layout to a two column layout at 600px. The left column with the text takes up most of the space at 1.5fr, with the image at 1fr. I made this decision as the text is more important and the image is largely decorative. A tablet layout was not required on this page as it is fairly simple so it looks normal at tablet sizes.

#### Mobile

![index page mobile wireframe](docs/index-mobile.jpg)
![index page mobile screenshot](docs/Screenshot-index-mobile.png)

#### Desktop

![index page desktop wireframe](docs/index-desktop.jpg)
![index page desktop screenshot](docs/Screenshot-index-desktop.png)

### Info

The info page requires three layouts to look good at all screen sizes. A one column layout for mobile devices. At tablet sizes the content sits on top of the experience cards which are in a two column layout. And at desktop sizes there are three columns, one for the content and two for the cards. I added a small image to represent each card as I felt it gave the page more personality. Each card also has a drop shadow to help it pop off the page.

#### Mobile

![info page mobile wireframe](docs/info-mobile.jpg)
![info page mobile screenshot](docs/Screenshot-info-mobile.png)

#### Tablet

![info page tablet wireframe](docs/info-tablet.jpg)
![info page tablet screenshot](docs/Screenshot-info-tablet.png)

#### Desktop

![info page desktop wireframe](docs/info-desktop.jpg)
![info page desktop screenshot](docs/Screenshot-info-desktop.png)

### Blog list

I decided to keep the blog list page very simple. Just one layout for all sizes. I thought this page should be utilitarian.

![blog list page wireframe](docs/bloglist.jpg)
![blog list page screenshot](docs/Screenshot-bloglist.png)

### Blog post

At the desktop size, I reused the two column layout(1.5fr 1fr) from the home page as I liked the look of the text taking up more space than the video. As I wanted the gallery images to be as wide as possible I placed it below taking up two columns. At mobile size the text is stacked on top of the gallery and the video is not displayed so that the site loads fast on mobile. The buttons for moving between the gallery images are large so that they are easy to click on mobile.

#### Mobile

![blog page mobile wireframe](docs/blog-mobile.jpg)
![blog page mobile screenshot](docs/Screenshot-blog-mobile.png)

#### Desktop

![blog page desktop wireframe](docs/blog-desktop.jpg)
![blog page desktop screenshot](docs/Screenshot-blog-desktop.png)
