This is the README for my portfolio project.

Inspirations:

http://findmatthew.com/

www.singularitynet.io

[puzzle piece inspo - mood board screeny]

==============

TESTING

==============


-Tried on several diff phones, hauwei nova 3i (worked fine), iphone 6 () and safari integrations was having issues

both iphones tried didn't work - image "iphone-error-21-mar.png"


======

Improvements - could change the script for opening tiles etc - make it so that clicking the open box doesn't close them, only the X does

- Make about me more visual, and less text based, in fitting with the rest of the website ( this could be done by adding icons for JS, CSS etc)

ADD user feedback from nik etc in trello

- in future, make the bulk of the html first then style it




====

# Luke Turner's Portfolio

## A link (URL) to your published portfolio website

https://luketurnerdev.github.io/

Also available at www.lukedturner.com (backup)




## A link to your GitHub repository 

https://github.com/luketurnerdev/portfolio


## Description of portfolio
    
### Purpose


This portfolio project was designed for several reasons. 

Firstly, it is a great way to show off projects that I have worked on, which allows myself and potential future employers to get a sense of my progress as a developer over time.

Secondly, it is a very useful exercise in learning and applying HTML and CSS skills that are extremely valuable tools to have in my web development arsenal. This project is not only useful for learning the syntax and flow of how these languages work, but also how to employ proper web design skills such that a document flows properly and is not buggy.

Finally, the project is useful for improving my project management skills, in terms of defining an appropriate solution to the brief in the given amount of time, and determining which features are necessary to achieve a Minimum Viable Product (MVP), and which are not.

### Functionality / features

The site delivers on the key requirements of the assessment, including :

    -Displaying my name and contact details
    -Listing my study and work history
    -Listing my contact information
    -Displaying a brief description of me and my personality


These 4 requirements are delivered through a minimal, functional website. The user begins at a "launch-pad" section, and there is a clickable arrow to bring them down to the main section (they can also scroll themselves).

The main section contains 4 'puzzle pieces', for the different sections of content in the site:

    -About (provides a description of me and my skills, study and work history)
    -Projects (contains a link to my github page, and 3 of my recent projects + images of said projects)
    -Blog (A link to my blog, and 3 recent posts in the same format as the projects)
    -Contact (Various ways to get in touch with me, including various social media links.)


## Sitemap

    The site's map is fairly simple as it is only a single page:

    ![alt text](https://github.com/luketurnerdev/portfolio/blob/master/screenshots/website-sitemap.png) "Sitemap of the website. ")

    The sitemap shows the initial launchpad section, followed by the puzzle tiles and the fullscreen sections that they lead to.





## Screenshots

This is the top section of the site:

![alt text](https://github.com/luketurnerdev/portfolio/blob/master/screenshots/website%20SS1.png) "Website screenshot, top section")



    


## Target audience

    The main target audience for my website is potential employers, or people that are interested in my ongoing programming and personal projects.

    The site may also be of use to fellow web development students in order to demonstrate various aspects of web deveopment.




### Tech stack (e.g. html, css, deployment platform, etc)


    The website was built using: 
        -HTML
        -CSS (vanilla css with flexbox)
        -Javascript (for scripting the squares opening and closing)
        -Github (for deployment, hosting and version control)
        -Trello (for project management)
        -Balsamiq (for mockups)

## Design


### Design process

    When initially presented with the assignment, I started doing some research of various websites, to see wwhich kind of style I liked. The end product ended up being fairly different, but it was still an interesting exercise in researching different styles of web design.

    I got the idea of the 'launch-pad' section at the top of the site from Matthew Williams (http://findmatthew.com/). I admired the simplicity of this feature, because it immediately tells the user what Matthew does, without any clutter:

    [screen of matts site]

    I also really admired the flow of SingularityNET's website, with a big hero image at the top of the page and some info on the side. I was initially going to run with this idea, but I didn't really have a logo to display.

    [screen of singularitynets site]

    After getting a general idea of the look of the site, I then proceeded to make wireframes for both desktop and mobile using Balsamiq:
    
### Desktop

    ![alt text](https://github.com/luketurnerdev/portfolio/blob/master/screenshots/wireframe-desktop-1.png) "Desktop Wireframe 1")

    ![alt text](https://github.com/luketurnerdev/portfolio/blob/master/screenshots/wireframe-desktop2.png) "Desktop Wireframe 2")

### Mobile

![alt text](https://github.com/luketurnerdev/portfolio/blob/master/screenshots/mobile-mockup0.1.png) "Mobile Wireframe ")


These initial wireframes were quite similar to the singularityNET model, with a hero image appearing on the right hand side, and then various headings running down the page. I ended up combining the two in some sense, with my background image (the leaf in the hand) being the hero image, but it instead appears below the tagline (which was inspired by Matt's website).

I then came up with the idea of having a 'puzzle piece' design, where the four pieces of the square revealed different images. I ended up going ahead with this, as I thought it suited the minimalist them of the site. Initially, I had planned to make them appear as actual puzzle pieces (with small notches on the sides), but due to lack of time, I ended up just making them regular div squares that are clickable.

### Usability considerations:

The following usability elements were taken into consideration:

    -Alt tags on all images for visually impaired users.
    -

### Challenges

The design of the website is centred around the design of the 4 puzzle pieces, and as a result I ended up designing some of the more visual aspects first, before the more fundamental information was added. I realised this at the time, but due to the site not having a normal div structure, it was difficult to get around designing the puzzle piece animations first, as this is where the information is primarily displayed to the user.

As this was the first project I have written with HTML and CSS, there are definitely design methods that are not as functional as they could be. For example, I was having a lot of issues using position: relative versus position: absolute, and this caused the flow of the document to behave in unexpected ways. CSS can be difficult, as things appear to be displaying correctly, but behind the scenes, other elements are being shifted to unwanted places. I am used to more logical scripting languages, where an error message might alert you to the fact that something is incorrect.

A very small amount of JavaScript is used to play the animations of the squares opening and closing. This was determined to be the best solution to the problem (as it often is), but the functionality is simple enough (toggling a class on and off) that I didn't spend too much time on it.

There is a large amount of whitespace to the right and the bottom of the webpage. After 3 days of investigation and asking several people, I still haven't found a solution to this problem. I am going to try to take this as a learning experience for next time, to carefully investigate any CSS styling rules that I use before I employ them, to ensure that the document flows correctly as it becomes more and more complex.



Details of planning process including,
    Project plan & timeline
    Screenshots of Trello board(s)




## Short Answer Q&A


1. Describe key events in the development of the internet from the 1980s to today (max. 150 words):

In 1982, the TCP/IP protocol was first established, which is currently the most commonly used protocol for devices connecting to the internet, in order for them to be able to talk to eachother under the same set of rules.

In 1986, The National Science Foundation’s NSFNET went online, which allowed the internet to expand effectively throughout the United States.

1990 - Tim Berners-Lee Develops HTML, which still remains as the most prevalent markup language for creating webpages today.

1991 - The World Wide Web (WWW) is released to the public by CERN.

1993 - The White House and the UN establish a presence online.

1998 - The Google search engine is born.

2003 - Myspace, Skype and the Safari web browser are born.

2004-2005 - Facebook, Youtube and Reddit are born. Mozilla Firefox is released.

2006 - Twitter is launched.


2. Define and describes the relationship between fundamental aspects of the internet such as: domains, web servers, DNS, and web browsers (max. 150 words):








Define and describes the relationship between fundamental aspects of the internet such as: domains, web servers, DNS, and web browsers (max. 150 words)
Reflect on one aspect of the development of internet technologies and how it has contributed to the world today (max. 150 words)

