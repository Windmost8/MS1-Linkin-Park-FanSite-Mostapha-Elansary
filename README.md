# Linkin Park Fan-Site MS1
This is a site intended for users who have heard about Linkin Park but want to know more, but also for users that have never heard about
Linkin Park and want to explore. 

Here, users shall be exposed to small facts about the band's background, and also given the availablity to discover the band's style of music and genre, as well as the chance to
connect and contact with Linkin Park and the sites owners, through inquiries or social media.

## UX
This site is intended for fans that don't know it yet, and fans yet to become. Therefore as such, all users alike must
have access to information on the band, such as small facts, or a brief history, or be able to listen to some sample songs most importantly 
as this a site is about a musical band. Having said that, the goal is to allow users a simple way to navigate and explore.


### User Stories
* As a visiting user, I want to be able to explore the bands history and what they are about. Whats their style of music?
* If I want to be able to explore deeper or engage with the band further, how will I do that? There are links to Linkin Park's socials at the 
footer of each page.
* Who are the members of this band? I would want to find that out in order to connect with them.
* What if I want to inquire about the band, or the site owners, how shall I do that?

### Wireframes
All wireframes for the 3 major devices, desktop, mobile, and tablet are included in the directory folder "wireframes". Shown there are the intended
outcomes of the project and its responsivness. In terms of the mobile and tablet devices, certain wireframes were elongated so simulate scrolling.
Also, the burger icon shows the menus already out on the wireframes, whereas in reality they are only shown that way when clicking on the burger
icon. By default they are hidden.

Links provided:

https://github.com/Windmost8/MS1-Linkin-Park-FanSite-Mostapha-Elansary/blob/master/wireframes/desktop-wireframes.pdf

https://github.com/Windmost8/MS1-Linkin-Park-FanSite-Mostapha-Elansary/blob/master/wireframes/tablet-wireframes.pdf

https://github.com/Windmost8/MS1-Linkin-Park-FanSite-Mostapha-Elansary/blob/master/wireframes/mobile-wireframes.pdf

### Technologies Used
* HTML
* CSS
* Bootstrap 4 (library)
* Balsamiq
* Chrome Dev tools
* Github/Gitpod

This project was done using HTML and CSS , with the help of boostrap's library. 
[bootstrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
Bootstrap offers a wide variety of tools and useful layout and functionality aid, in order to both optimize your site for responsivness, 
which was a big reason for the use of bootstrap in this project, but as well as for smooth design that is user friendly.

---

## Features
* Feature: **Navigation and Home Link** - Allows for easy navigation throughout the site to desired information.
* Feature: **Footer Socials** - Social media links are displayed at each page for easy acess to related social medias, opened by a new link.
* Feature: **Explore page Music** - In the explore page, that can be either clicked on directly, or taken to by a "Learn More" buton from the Home page
allows for easy sampling of music to listen to what type and genre Linkin Park plays music in. Simple click of a button to play.
* Feature: **Contact** - Allows users to fill out a form in order to inquiry anything they wish relating to the band. Form includes first name, last name
email address, and text area for inquiry.

#### Future possible Features:
1. We could showcase collabarations with other bands so that fans and users may broaden their knowledge on the band and genre.
2. A merchandise menu/page for purchases.

### Typography and Color Scheme
Typography included bootstrap classes for h1-h6 displays and certain p tags. 
Also included werre various font sizes, ranging from px to %.
In addition, the Oswald font family was used for easier readabilty in the "Learn More" button.

In terms of color, a beige body background was used to ease unto the eyes.

---

## Testing

All user story conditions work on both tablets and mobile, in addition to desktop. The abiltiy to listen to music and view images is possible
and the readabilty of the present text is also clear. The images are responsive with the aid of bootstrap.

Testing was done through the inspect option of google chrome for mobile and tablet responsivness. Although mobile was more the focus.
These devices included:
* Moto G4
* Galaxy S5
* Pixel 2
* Pixel 2 XL
* iPhone 5/SE
* iPhone 6/7/8
* iPhone 6/7/8 Plus
* iPhone X
* iPad
* iPad Pro
* Surface Duo
* Galaxy Fold

#### The output of these devices is the intended output provided in the wireframes, with the exception of slight scroll differences.

* Testing for the HTML code passed the W3c benchmark.
* Testing for the CSS code passed the Jigsaw benchmark.

Supported browsers include Google Chrome.

### Test Cases
**Test Case 1** - All navigation links should work when clicked, from the navigation menu in the header relaying to their respective paths, to the main logo on the left corner
taking you to the home page when interacted with, and also the "Learn More" button found itself in the home page taking you to the explore page.

**Test Case 2** The footer of each page should direct you to the correct social media links when clicked, which should open up a new tab everytime you click.

**Test Case 3** In the explore page, both the image and soudcloud players should be interactble. When clicking on the image, a new tab should open up showcasing the image in it's original size. The music sample players should 
play the tracks presented for a short while.

**Test Case 4** The Contact page form should correctly showcase error tooltips when attempting to submit an empty form. Vice versa, should you submit a full for, the page should refresh itself.

### Fixed issues
* Responsiveness on contact form for Ipad and Ipad Pro without media queries was very messed up. However this was fixed through dev tools inspection and trying out different ranges.

* Soundcloud responsivess was fixed though altering the embedded code from their site as well as aid from Dave Rupert's responsive soundcloud code. Mentioned below in Acknowledgements.
* Explore page shows syntax errors in the code, however it is not really an error and it is explained in comments in the code.

### Screenshots
Below are links with screenshots provided in order to visually see the intended output of the sites functionality and structure. Both dekstop and mobile screenshots are available. They may also be found in the screenshots folder directory.


--- 
## Deployment
#### Gitpod
Previewing the site in gitpod was done through the command python3 -m http.server.
Once the command is used, a popup with port 8000 will ask you to "Make Public" or "Preview Browser".
You can click on "Make Public First" and if another popup arrives you click on "Prievew Browser" in order to see the site.
Alternatively, you can ctrl-click on the port 8000 link that will be shown in the terminal.
There is no autosave so saving after each change was optimal, as well as commiting to github.
The template used here was the full template issued by Code Insitutite.

#### Github
Deployment was done through github pages. The documentation of which can be found here: https://pages.github.com/

---

## Credits
#### Content
The text in the Explore page is a summarized brief paragraph of information from "https://en.wikipedia.org/wiki/Linkin_Park"

#### Acknowledgements
Music sources were embedded from soundcloud, using responsive iframes. Credit to creator: "https://codepen.io/davatron5000/pen/hDipj"
Soundcloud was chosen for it's easy playabilty of music. 
The 2 major images in the Home page were sourced from the offcial Linkin Park wikipeadia page, and Rocksound.tv, an
offical rock news site.

https://upload.wikimedia.org/wikipedia/commons/4/42/LinkinParkBerlin2010.jpg

https://files.rocksound.tv/assets/uploads/linkinpark.jpg

The final image in the Explore page was sourced from the official independent.co.uk News site.
https://static.independent.co.uk/s3fs-public/thumbnails/image/2017/07/25/09/linkinpark-first.jpg?width=982&height=726

All links and social media links open up a new tab tab
to their offical links.
Quotes present on the home page were taken from Linkin Park's official song lyrics, with the songs mentioned and sourced on the page itself.

The idea of a band fan site resonated with me personally since I personally like and listen to the band.
This website is only for educational purposes.
