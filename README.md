#Welcome to ![Love Children Foundation](file:///Users/alishaandersson/Desktop/Love-Children-Foundation/index.html)

Love Children Foundation is a website that hopes to give people awareness about the poor/homeless children in Africa. With a proper website, we hope to give the audience all the information they need about our organisation and what we do for these children. The site will be targeted toward all kinds of people, that wants to help us with donation, funding or by volunteering at our orphanage in Africa. Our website will be useful for companies and people of all ages to easy navigate through our site, to quickly learn who we are and what we do, and also get information about what they themselves can do.

The reason for doing a website for Love Children Foundation is to give easy accessibility for people who wants to know more about our organisation. I chose this subject because I myself been helping other orphanages with money, and I’ve also visited many orphanages around Thailand. The organisation I’ve created now, is not located in Thailand. However, it’s the same issue in Africa. Therefore, I really wanted to create a website for Love Children Organisation because I’m super passionate about helping other people, and specifically children with poor background.

The first step was to structure everything out using Figma. Since my website is about children, I thought of having a colorful website. And since I want a very simple and basic site, I’m only using two main colors: orange and light blue. The layout is simple, with the logo (Love Children Foundation) to the top left and navigation bar menu to the right. I also added Instagram and Facebook icon to the right that links to www.instagram.com and www.facebook.com. Since I created a website with a non existing organisation, the links goes to facebook and instagram homepage. Due to the fact that I don’t have a real organisation, and therefore cannot link to real accounts.
Directly under navigation bar menu, we have a big picture of some happy African kids. I chose this image because it represents what the whole website Is about - children, and specifically African children. On the picture, we can see kids that are smiling towards the camera. They look happy.

(Remove this after re-writing)
Notes on what I've done until rewriting this:
Media query applied to navbar and logo, credits to Code Institute where in Love running project, showed me how to apply media query.
Added title with favicon footsteps to represent kids. Link -> https://favicon.io/emoji-favicons/footprints
Added metatags with keywords related to homepage

Changed font-family style with Google Fonts. Link -->
https://fonts.google.com/specimen/Manrope?preview.text=Love%20Children%20Foundation

Copied screen size max width responsive from Love Running project. Is it okay or should I remove?

challenges: to make section 2 look good at different screen sizes.

didn't manage to make images in project section display better when bigger screen size than 992px (wanted bigger and more space between)
didn't get "change the world with us" text at the homepage image fit when smaller screen size.

change video size from 768px and up, didn't manage to make the change. It must be larger - solved this 24/1 by removing max-width on line 255. Got help from Tutoring session.
text-video next to video is a link? - solved this 24/1 by closing a tag, now it's no link anymore
make video section look better at bigger screen sizes
change button link so its the same size for every button at every media query
failed with making list in volunteer section centered from 768px and up.
cannot add margin top to media query of 768px and higher when i want to target learn-more-buttom
volunteer button, cannot move more right in media query of 768px and up

VIDEO BUTTON from 630px and higher doesn't move. Something is blocking. I want it inline with video.
PROJECT BUTTON on 1228px and higher needs to be positioned more up, right now its outisde of section. FIX THIS
SAME BUTTON needs to be centered on 280px and up
VIDEO SECTION needs to be fixed from 630px and up. FIX THIS

VIDEO BUTTON NEEDS MORE SPACE from 280px FIX THIS
VIDEO NEEDS TO BE CENTERED FROM 480PX, when i add width. It's not centered anymore
Too much space at the top from 630px and up in video section
FROM 992PX AND UP, VIDEO IS NOT SHOWING FULL HEIGHT
added flexbox to list for bigger screens, but it didn't work 
Project button from 768px and above has an absolute positioning, line 661. Therefore, it moves when screen gets bigger

SOLVING:
Video section, had trouble with positioning of elements. Tried different methods but finally solved it by having 2 divs, 1 for header and text and one for video and button. 

credits:
I was stuck on video section. Elements didn't move. With help from John on tutoring team, I got help to move iframe inside of video container div. So that I could target all three elements (video, text and button) into position:flex;. Before, iframe container was outside of video container div.

https://www.w3schools.com/html/html_links.asp
This website helped me understand how hyperlinks works which I applied to the logo, to link to homepage.

 Responsive youtube code adapted from avexdesigns.com/blog/responsive-youtube-embed

<!--Add a photo of how the website looks like on different screen devices-->

![Responsice Mockup](copy link from github and the image)
