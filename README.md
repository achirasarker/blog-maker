# blog-maker
This is a dynamic blog maker web app created using Node.js, HTML and CSS. It uses EJS templating to allow users to create custom blog posts through a /compose route. Post requests were implemented to dynamically display newly created posts on the homepage and Express routing parameters were used to render a new page per post through an algorithm that searches through a posts array. 

This is an image of the home page, without any new posts: 
<img src="images/7EAC449E-005E-49B3-B438-579CD480A0F7.jpeg">

This is an image of the /compose route:
<img src="images/D5748869-9932-43FA-9465-15B43EAEA00C.jpeg">

This is an image of the home page, with new posts:
<img src="images/ED4F1933-9057-45FD-B332-FE18BEB32BCD.jpeg">

New post pages are rendered for every post using EJS templating as soon as they are composed:
<img src="images/5E7D8538-28E8-4C41-A2A7-D4DC08C4C91F.jpeg">

The project is currently hosted locally and my next steps are to implement MongoDB and deploy the app to a server. 

