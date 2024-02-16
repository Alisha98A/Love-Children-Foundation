
# TESTING


### Overview:

I've learned it's important to test my projects often, especially before submitting, to ensure their quality is good enough. Validation is a confirmation that the project meets the requirements. It's also important to test to see if I have any bugs in my code, in that case, I need to solve them before releasing it. Another thing is that my website is going to be seen from different devices and screens. Testing is therefore good to see if my project performs well under various conditions and loads.

### Testing Methodology: 

For this project, I've used manual testing, Lighthouse, W3C Validator and Jigsaw validator to see if I need to do any improvements to my HTML and CSS code. 

### During Development Testing:
During the development process, I was manually testing in following ways;
- Using developer tools in Chrome to check appearance and responsiveness. 
- Deploy to Github regurarly and check elements so I don't get any surprises at the end. 
- Manually testing each element through an extension from VS Code, where I could see a live preview. 
- Published the page via Github paged and shared my project with friends and family to test and recieved feedback.

### Manual testing:
- During testing, I used following browsers to ensure cross-compatibility and for checking elements work correctly, such as text, buttons, images and other visual elements:
  
  1. Chrome
  2. Opera 
  3. Firefox
  4. Edge               

- I used Developer Tools to ensure that the website looks good from different screen sizes, from 280px up to 1228px in width, which is normally desktop, mobile and tablet device. 
- Checked that there is no overlapping between or breaking elements through different screen devices in Developers Tool.
- Ensured that the overall look of the page looks good with layout, spacing and color. Used to 2 main colors, lightblue and orange to maintain consistency and easy recognition of the website. 

#### Overview over Project Features:

| Feature | Expectation | Testing | Result |
| ------- |:-----------:|:-------:| ------:|
|  Homepage | Logo, homepage image and menu is displayed correctly| Run page | All showing correctly |
|  Logo | Click on logo to go to homepage | Click on logo | Redirected to homepage | 
|  Menubar for larger screens | Menu bar is displayed correctly, with side menu showing up when you hover | Run page, hover over menu | Menu bar displaying correctly, sidemenu shows up when hovering over menu |
|  Menubar for smaller screen | Icon menu is displayed, menu shows up when clicking on icon | Click on icon | Icon showing correctly and menu shows after clicking on icon |
|  Links in menubar| Redirected to right page after clicking on menu links | Test all menu options to see if directed to the right page| All links is working in menubar |
|  Learn More About Us button | Click on button to go to About Us page | Test button by clicking on it | Button link goes to About Us page |
|  See More Of Our Projects button| Click on button to go to Our Projects page | Test button by clicking on it | Button link goes to Our Projects page |
|  1a. Youtube Video Responsiveness| Responsive in different screen sizes| Use DevTool to check if the video is responsive by viewing from different screen sizes | Video is responsive|
| 1b. Youtube video function | Plays only when clicking on video, muted automatically | Reload page, see if video is paused, click on video to check if it's muted automatically| Video does not start on it's on, muted when clicking on video |
|  Our Vision button | Click on button to go to Our Vision section in About Us page | Test button by clicking on it | Button link goes to About Us page, and more specific directly to Our Vision section |
| Game input steps nothing | Hitting enter without any input will prompt the user to try again | Hit enter on each step of the game through to the end | Input line correctly repeats itself until correct input is given |
| Volunter with Us button | Click on button to go the Volunteer section in Support Us page | Test by clicking on the button | Button link goes to Support Us page, and more specific directly to the Volunteer section in the page |
| Support Us links| The links will take you to the right section in Support Us page when clicking on it | Test each link and see if it goes to the right section| All link works
|  1a. Sidebar in About Us, Our Projects and Support Us page | Sidebar is displayed correctly | Run pages | All showing correctly |
|  1b. Sidebar functionality | Sidebar menu takes you to the right section when clicking on an alternative | Test all sidebar options on all pages by clicking on them| All sidebar menus work and are linked to the right section of the page|
|  1c. Sidebar responsiveness| Sidebar displayed on top of the content on smaller screens and on the left side of the content on larger screens| Use DevTools to see if it's displayed correctly | Sidebar is displayed correctly both for smaller and larger screen devices |
|  Scrollable content | The main content in About us, Our Projects and Support Us page is displayed in a box with scrollable content | Run page the pages to see if the content is scrollable| All showing correctly |
|  1.a Contact Us form| Contact form in Support us page is showed correctly with a form to fill in Name and e-mail| Test by typing in the form | Contact form displayed correctly |
|  1b. Concact Us function| If name, email, @ or .com is missing in the field, warning text comes up and the submit button wont work | Test function by not filling in those requierements | Warning sign shows up telling me I have to fill in correctly| 
|  1c. Submit button | When hover over Submit button, button turns green| Hover over button | Button turns green|
|  1d. Submit button function | When clicking on Submit button, you get redirected to a Thank You page| Click on button| Redirected to Thank You page |
|  Thank You page | Thank You page with a note and a link to go back to homepage| Run page, test link to homepage | All showing correctly, link works|
|  404 page| Logo, 404 note and footer is displayed correctly | Run page | All showing correctly |

#### Bugs and fixes

- Problem was to change video size from 768px and up, solved this 24/1-24 by removing max-width on line 255. Got help from Tutoring Team on Code Institute.
- Problem with text-video next to video which in the beginning was a link. Solved this 24/1 by closing a tag, now it's no link anymore. Credits to Tutoring Team on Code Institute.
- Add tabindex="0" attribute to each anchor (<a>), links becomes focusable programmatically by keyboard navigation. When a user tabs through the page elements, these links will receive focus, making them accessible without relying on JavaScript event handlers like onmouseover() or onmouseout(). Lighthouse warned me of that. Fixed bug with help from [Developer Mozilla ](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/tabindex) article. 
- Fix Lighthouse results by adding an sr-only class for the checkbox element in the header.[CSS Tricks ](https://css-tricks.com/inclusively-hidden/) website helped me solve this. 
- Joanne from tutoring helped me with the ul li list. Before, anchor tag was outside of li which created problem with structure. Element ul not allowed as child of element span in this context. Joanne from tutoring helped me changing span to div, and anchor tag to be wrapped by li instead of ul wrapped by anchor tag.
- Link to Thank You page from Submit button in my form didn't work correctly, after changing method to GET and pasting my filepath. Issue got resolved. Got help from tutoring team. 


    
### Running automatic tests:
  - Lighthouse is a Chrome's extension and to run it, you have do download Google Chrome for Desktop.

  1. Go to the adress (URL) you want to test. 
  2. Open Chrome Devtools by rightclicking and click on "Inspect"
  3. Click on the Lighthouse tab by clicking on More Tabs to the right at the top.
  4. Click Analyze page load
  5. Click Run audit


  - [W3C validator](https://validator.w3.org/) and [Jigsaw validator](https://jigsaw.w3.org/css-validator/)

Type in the adress bar (URL) of the page you want to validate into the text field on the form and press the "Validate this page" button. 
You can also validate with a local file by choosing "File Upload".

### Feature Testing:

#### Lighthouse

- The tool gives you recommendations on how to improve page performance (Performance Optimization), accessibility issues, best practice recommendations, improving your site's performance, and fast page loads. 
- Lighthouse has helped me address problems early on, which I've tried to solve. I had to work a lot on my images, to get them resized in different dimensions, and also think of responsiveness, high resolution and fast loads. I started with one image, but thanks to Lighthouse and my mentor, I got to understand how I should upload files and what works best for better user experience. This resulted in uploading 4 different sizes of images, of the same image. To use them in different media queries. I converted 3 of the images to WebP, and saved one in JPG for a fallback image, in case some browser don't support WebP. The images containing a lot of data for example 1916x849 pixel, will be displayed on screens that are larger than 1200px. While the same image but with 618x274px instead, will be used for smaller screen devices. This improves both better resolution of image displayed (higher quality) and faster loads, which is a win win for the user experience. 
- Another problem I encountered was my list structure for the "Support Us" section at the bottom, I did not have any problem with it before. But after putting an anchor tag 
link outside my list and inside my ul (containing the list), my structure got broken. I got help from tutor team with this, helping me put my a href tag right and changing span to div because it would be displayed better then. I got help to wrap anchor tag inside li element correctly.

#### W3C Validator
- The most errors I got from here was that I had to remove trailing slashes on void elements. After removing them on all pages, the issue was solved.
  
#### Jigsaw validator
- I got one error of my paragraph id for media query of 768px and up, where I missed to set a value to font-size, after setting a value to px. The issue was solved.


### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator](http://jigsaw.w3.org/css-validator/validator?lang=sv&profile=css3svg&uri=https%3A%2F%2Falisha98a.github.io%2FLove-Children-Foundation%2F&usermedium=all&vextwarning=&warning=1)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Falisha98a.github.io%2FLove-Children-Foundation%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv)

 ![Lighthouse score for mobile device](https://github.com/Alisha98A/Love-Children-Foundation/blob/main/documentation/love_children_foundation_mobile_lighthouse.png?raw=true)
Lighthouse Score for mobile device


 ![Lighthouse score for desktop device](https://github.com/Alisha98A/Love-Children-Foundation/blob/main/documentation/love_children_foundation_desktop_lighthouse.png?raw=true)
Lighthouse Score for desktop device

