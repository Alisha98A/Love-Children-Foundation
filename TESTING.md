
# TESTING PAGE


### Overview:

I've learned it's important to test my projects often and especially before submitting, to ensure its quality is good enough. Validation is a confirmation that the project meets the requirements. It's also important to test to see if I have any bugs in my code, in that case, I need to solve them before releasing it. Another thing is that my website is going to be seen from different devices and screens. Testing is therefore good to see if my project performs well under various conditions and loads.

### Testing Methodology: 

For this project, I've used Manual testing, Lighthouse, W3C Validator and Jigsaw validator to see if I need to do any improvements in my HTML and CSS code. 

### During Development Testing:
During the development process, I was manually testing in following ways;
- Using developer tools in Chrome to check appearance and responsiveness. 
- Deploy to Github regurarly and check elements so I don't get any bad surprises at the end. 
- Manually testing each element through an extension from VS Code, where I could see a live preview. 
- Published the page via Github paged and shared my project with friends and family to test and recieved feedback.

### Manual testing:
- During testing, I used following browsers to ensure cross-compatibility:
  1. Chrome
  2. Opera 
  3. Firefox
  4. Edge

- **UI Rendering**
  - Ensured that HTML elements render correctly across different browsers (Chrome, Firefox, Safari, Edge). Meaning, checking that everything (such as text, buttons, images and other visual elements) works as it should. 
  - Checked for consistent rendering for different screen sizes and devices (desktop, mobile and tablet).
- **Responsiveness**
- Ensured that the website looks good in different screen sizes, by using Developers Tool on Google Chrome to resize the browser window.
- Checked that there is no overlapping between or breaking elements through different screen devices in Developers Tool.
- **Layout and Design:**
- Colors, spacing and overall look, are suitable on all pages with only 2 main colors, lightblue and orange to maintain consistency and recognition of the website. 

    
### Running automatic tests:
  - Lighthouse is a Chrome's extension and to run it, you have do download Google Chrome for Desktop.
In Google Chrome, go to the URL you want to audit. You can audit any URL on the web.
Open Chrome DevTools.
Click the Lighthouse tab. To the left is the viewport of the page that will be audited.
Click Analyze page load. 
Click Run audit.

  - [W3C validator](https://validator.w3.org/) and [Jigsaw validator](https://jigsaw.w3.org/css-validator/)
Just type (or Cut&Paste) the URL for the page you want to validate into the text field on the form and press the "Validate this page" button. If you have a local file you want to validate, choose the "File Upload" link from the navigation menu.


### Feature Testing:

- **Lighthouse**
- The tool gives you recommendations on how to improve page performance (Performance Optimization), accessibility issues, best practice recommendations, improving your site's performance, and fast page loads. 
- Lighthouse has helped me address problems early on, which I've tried to solve. I had to work a lot on my images, to get them resized in different dimensions, and also think of responsiveness, high resolution and fast loads. I started with one image, but thanks to Lighthouse and my mentor, I got to understand how I should upload files and what works best for better user experience. This resulted in uploading 4 different sizes of images, of the same image. To use them in different media queries. I converted 3 of the images to WebP, and saved one in JPG for a fallback image, in case some browser don't support WebP. The images containing a lot of data for example 1916x849 pixel, will be displayed on screens that are larger than 1200px. While the same image but with 618x274px instead, will be used for smaller screen devices. This improves both better resolution of image displayed (higher quality) and faster loads, which is a win win for the user experience. 
- Another problem I encountered was my list structure for the "Support Us" section at the bottom, I did not have any problem with it before. But after putting an anchor tag 
link outside my list and inside my ul (containing the list), my structure got broken. I got help from tutor team with this, helping me put my a href tag right and changing span to div because it would be displayed better then. I got help to wrap anchor tag inside li element correctly.

- **W3C Validator**
- The most errors I got from here was that I had to remove trailing slashes on void elements. After removing them on all pages, the issue was solved.
- 

- **Jigsaw validator**
- I got one error of my paragraph id for media query of 768px and up, where I missed to set a value to font-size, after setting a value to px. The issue was solved.

- **Manual testing**

Manual testing is good to see with your own eyes, that everything works as it should. By checking that every link goes

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator](x)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Falisha98a.github.io%2FLove-Children-Foundation%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=sv)
