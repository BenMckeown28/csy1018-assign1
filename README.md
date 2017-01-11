# Benjamin McKeown -CSY1018 Assignment 1- Student Number 16424393
https://benmckeown28.github.io/csy1018-assign1/index.html Link to website
# csy1018-assign1
During the assignment, I have discussed and asked raising questions between two other students who live in my flat:
Alfie England
Brook smith.
These questions included content about the design briefs requirements and restrictions which we needed to follow.
I also have been to a couple of the support sessions to ask Tom Rose about some problems I was having with some of the media queries for specific pages of my website and material design in general.
### Hours spent:
On average I spent around 35+ hours on the assignment, but it’s too difficult to give an exact figure because there were times when I had to research for specific code or doing other things towards the other assignment.
#Design
## Navigation diagrams
![Navigation diagram](https://i.gyazo.com/e2615e2b60ab5bc622ec988e603ba2af.png)
![Navigation diagram 2](https://i.gyazo.com/b82e71152c8e337127bf6910899976b6.png)

In terms of the navigation within my website I want it so that the user is able to user a menu bar along the top which will allow them to navigate to the area which they want to.
This is only design so its subject to change during production of the product if there are any easier solutions.

## wireframes/designs
![Logo](https://i.gyazo.com/ece19aabd5135049092feebdda9ca8df.png)
![Home Page](https://i.gyazo.com/a6ddf44be367ac22cfa080de79ba6224.png)
![CV Page](https://i.gyazo.com/f7418d323f9e77586c2fbb5f780d263e.png)
![Biography Page](https://i.gyazo.com/373d2b85a7e37408a64564d92e75c1eb.png)
![Contact Page](https://i.gyazo.com/35db45b118923c2da0fab9b18b06c62e.png)
![Mobile View](https://i.gyazo.com/f7e07bbd6c3e9872cbe03e8c57a953d7.png)

Designs and wireframes are subject to be edited to suit user need, for now it’s a general idea of what it will look like. The menu and footer bars will have hover effects for all different objects/words which are in this area to
make user interactivity more enjoyable.

#Work Log

## 13th November
Today I started the assignment and began to do the initial commit through Gitbash, for today all I have done is set up all the files within the repository.

## 21st November

Began starting to set up the navigation menu so that it has the content of the links between the different pages, also I created the logo and included it
within the design of the navbar.

##22nd November
I then began starting to develop the menu being responsive, for now as the user drags the navigation bar smaller in the horizontal direction, the text within the
navbar will get smaller.
 I also replaced the house Icon so that it was simpler to recognise.
 I also added content to the index page of the website
##23rd November
 I started to create the content for the footer of the website, this included the social links/icons and the copyright statement to say that it was developed
by me also I coded the background of the footer as well to match the rest of the colour scheme within the website.
 I began trying to use basic media quires to try and change the format of some of the content on the index page.
I began to try and make the footer more responsive in terms of desktop use by adding attributes to the <a> tags of the footer.
##24th November
I made some changes to the navigation bar so that it was more responsive and easier to use.
##28th November
Added some more media quires to make the website more responsive, only for desktop use still.
##29th November
Decided to change the font style to Vmin instead of pixels, the reason was because while I was trying to work out media quires it makes it a lot easier to work with.
##1st December
I then started to add links to the different web pages through the navigation bar, this made it easier to code the different pages of the website at the same time.
## 3rd December
 I then started to add the content of the CV page with the use of html
Then I used CSS to style this page so it began to look more like a CV.
## 5th December
I realised that the positioning of the skills part of the CV was slightly out of place, and so fixed it by changing the padding.
## 7th December
I then decided to add content and style it through CSS to the Biography page, I kept all the styling of all the other page’s headers and footers.
## 8th December
I added all the content to the Contact page and styled it, I gave the icons on the page animations also.
## 10th December
I decided to change all the sizing of the font and the padding to em instead of having it as Vmin. I also added media queries to the index page for the header and the footer.
## 12th December
I redesigned the Cv page of the website in more of a centralised format to make it simpler to read, also I changed the media queries for this so it suits the new design. I also added some media queries to the bio gallery page where the images automatically change the display when minimised. I also started to develop the media queries for the home page of the web page.
## 15th December
I added more media queries to the rest of the page so that its more responsive to desktop use.
##16th December
I decided to change the colour of most of the content of the web pages so that they suit the material design specification.
##19th December
I updated the media queries for the index, Cv and bio page so that its fully compatible through mobile devices. I decided to get rid of some of the content in the footer as it was not needed and was serving problems with the formatting of the resizing of the web page.
##11 January
I decided to make the form of the contact page bigger so that it was easily viewable to all users. The form has media queries associated with it so it can be used on mobile or minimised desktop view.


#Html checker
All HTML validation was done through the website: https://validator.w3.org/

![Home page Html checker](https://i.gyazo.com/f06fcd11d81ac98036127ce565e01548.png)
![CV page Html Checker](https://i.gyazo.com/32778649e7e103a4126b66ff178a576b.png)
![Biography page Html Checker](https://i.gyazo.com/ae099e87e05aba97478b78e39be04185.png)
![Contact page Html Checker](https://i.gyazo.com/38ddb3265a0704ac7239f7950bdacb12.png)

For the html checker, I ran the programme through each of the different web pages of the website. For a lot of the pages, the main issue was simple me forgetting to put <alt> tags onto the end of image tags, if I hadn’t put these tags on to the end, if someone was to open my website and the images wouldn’t load they would not know what was supposed to be there.

#CSS checker
All CSS validation was done through the website: https://validator.w3.org/
![Home page CSS checker](https://i.gyazo.com/2cd978b0ea1d9c3da50893a70bfcdd76.png)
![cv CSS checker](https://i.gyazo.com/c20b80fdff4e592353854a9519171f1f.png)
![Bio CSS checker](https://i.gyazo.com/beb89a9f291f5f2c7ceb11f802a5bd1b.png)
![Contact CSS checker](https://i.gyazo.com/ab2602687b3e43846a25baed9d7ec4b1.png)

After I completed the changes which I had to make towards the HTML of the webpages, I then began to start correcting the CSS of the web pages. There were quite a few errors on each of the pages, most of them were to do with the media queries of the webpages, particularly the mobile phone media queries. Other errors were to do with simple code which shouldn’t have been placed in that area e.g. position: block;
With the mobile queries I attempted to fix the problems to do with the "-webkit-device-pixel-ratio" which were for the mobile queries specifically, however after lots of testing no matter what the error kept popping up when i ran it through the CSS checker. This may be an error within CSS itself or the validator.

As with the font awesome errors in each of the different pages, it seems that this is a common problem which occurs when you put the web page through the checker.
