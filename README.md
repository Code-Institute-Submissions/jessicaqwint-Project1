# Project1

Created a page aimed at companies and private individuals with a focus on coaching. Mindfulness and Mindset.
The page is divided into 5 html pages with html and css.
Media; pexels, audio; pexels
Q-Success
The Quality Success Team website is a platform aimed at both companies and individuals who want to carry out personal development in order to reach their goals or change their thinking for long-term well-being.

Users of this page will be able to get in touch with email, name form to be able to get more information about the company´s personal program.
Header: Shows logo, welcome to company website
HTML - Solved bugs 
<div id="imgContainer_1"> div id had to be unique (1) - before they were the same
<div id="imgContainer_2"> div id had to be unique (2) - before they were the same
<div id="imgContainer_3">  div id had to be unique (3) - before they were the same

<img id="images_1" src="images/IMG_9001.jpg" alt="text">
div id had to be unique (1) - before they were the same

<img id="images_2" src="images/IMG_9002.jpg" alt="text" >
div id had to be unique (1) - before they were the same

<img id="images_3" src="images/IMG_9003.jpg" alt="text" >
div id had to be unique (1) - before they were the same

And the alt attribute for all image was missing

/solved, fixed the problem.

CSS Bugs – jigsaw.w3 telling me that no bugs were found, but my menu whit buttom  “as below” are not showing like I wanted. 

#menu {
width : 100%;
max-width : 800px;
display : flex;
text-align : center;
}
#menu #imgContainer_1, #imgContainer_2, #imgContainer_3, #imgContainer_4 {
width : auto;
display : inline;
max-width : 100px;
height : 100px;
margin : auto;
padding-bottom : 200px;
}
#menu #imgContainer_1:hover, #imgContainer_2:hover, #imgContainer_3:hover, #imgContainer_4:hover > a {
color : red;
}
#menu #imgContainer_1, #imgContainer_2, #imgContainer_3, #imgContainer_4 img {
width : 100%;
}




Testing: I tested this page in Chrome, Firefox.
I confirmed that the navigation, header, about, business, private, mindfulness/mindset and contact tesxt are all readable.

Validator Testing: 
HTML – 
CSS- 
Accessibility

Unfixed Bugs: se CSS
