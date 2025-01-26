# Palms and Peaks Resort website

Palms and Peaks resort is a website which is responsive website which allows visitors to view on a range of devices from Mobile to Large computer monitors.

![Am I Responsive](docs/readme-docs/readme-images/am-i-responsive.png)

[View Palms and Peaks on GitHub Pages](https://nchrist89.github.io/Palms-Peaks-P1/)

## CONTENTS
-LINKS TO SECTIONS IN README
___
## User Experience (UX)

**UX information**

## Design

### Colour Scheme

![Palms and Peaks Website Colour Palette](docs/readme-docs/readme-images/colorpalette.png)

This is the colour palette I have used in the website. They were taken from the original image I was going to use as the main banner for the homepage. The colour palette was created using the [Image Colour Picker](https://imagecolorpicker.com/) website. The website provided different names for the colours so they are Tropical Themed in my website variable names but the Hexcodes remain the same.

### Typography

Google Fonts was used for the following fonts:

* Shojumaru is used for all major headings on the website and the navigation bar links. It is a chop suey style font.

* Klee One has been used as the body text for the website. It is a script font.

### Imagery

All images on the homepage of the website have been generated using [Prome AI](https://www.promeai.pro/ai-image-generation) website. Images from the Gallery are from various AI image tools Microsoft Designer, fal.ai, aitubo.ai.

Images for styling purposes such as the navigation bar wooden pattern and heading backgrounds was taken from google images.

### Wireframes

Wireframes was used prior to building the website but due to medical issues the project was cut down and therefore the wireframe for this doesn't quite match up but it gives an idea of what I originally wanted planned for the website.

[Desktop Wireframes](docs\readme-docs\readme-images\wireframes-desktop.png)

[Tablet Wireframes](docs\readme-docs\readme-images\wireframes-tablet.png)

[Mobile Wireframes](docs\readme-docs\readme-images\wireframes-mobile.png)

### Features

The website is comprised of four pages. Three of them are accessible from the navigation menu (home page, gallery and Win pages). The fourth page is a success page which is shown once the user submits the competition form on the win page.

* All pages on the website have:

  * A responsive navigation bar at the top of the page which allows users to navigate through the website. At the top left of the navigation bar is a logo of a parrot which is circular. Think of this as the mascot for the website which also doubles as a home button when clicked. When viewing the website on mobile devices the navigation bar switches the links to a burger toggler which when clicked opens the navigation links in a sidebar.

  * A footer which contains social media links which all open in a new tab when visited. Icons were used without titles as they are universally recognised.

* Home page.

  * A banner image showing the sign of Palms and Peaks Resort. This explains straight away to the user what the website is about.

  * A welcome note section to welcome new users to the website.

  * A new features section which shows the user what new and upcoming features will be available at the re-opening of the resort.

  * An about us section which includes some information about the resort and its history.

  * A section which shows an outline of what the resort has to offer visitors. Originally in my website creation these were supposed to link to their own full sections which were on other pages of the website. (Animals, Exploration, Stays, Shops, Rides, Camping, Beach Bars, Activities)

  * A map section which shows the geographical location of the fictional resort which was found using google maps.

* Gallery Page.

  * The gallery page shows a selection of images which show the resort, some animals and the park itself. All of the images were designed using AI. Some of which were to be used in the final project and I didn't want to not use them somewhere. Many hours went into getting many images the way I wanted.

* Win page.

  * The win page has a form which can be completed by the user for a chance to win a family holiday.

* Success Page.

  * Provides the user a success message for submitting the competition form on the win page.

### Accessibility

I have throughout the project ensured that the website has been accessibility friendly as possible. This has been achieved by:

* Using semantic HTML
* Using descriptive alt attributes on images on the site.
* Ensuring that there is sufficient colour contrast throughout the website.
* Ensuring that menu items are accessible by marking the current page as active for screen readers.

---

## Technologies Used

### Languages Used

HTML and CSS were used to create this website.

### Frameworks, Libaries & Programs Used

Balsamiq - Used to create Wireframes.

Git - For version control.

VS Code - For writing, saving and storing the files used for the website.

Google Fonts - To import fonts used on the website.

Font Awesome - For the iconography used on the website.

Google Dev Tools - To troubleshoot and test all features on the website. Check and resolve issues with the reponsivity on the website across devices.

Google maps - For the location of the resort on the home page.

[Prome AI](https://www.promeai.pro/ai-image-generation) - Used for generating the images used in the final project.

[Tiny Wow (highly recommend)](https://tinywow.com/) - To batch resize multiple images and to convert to WebP format for reduced file size.

[Image Colour Picker](https://imagecolorpicker.com/user/palettes) - Used for generating the palette which has been used throughout the project. The website also generated the names for the colours which are also referred to as their variables.

[Gimp](https://www.gimp.org/) - Used for modifying and editing images used on the website.

[Favicon.io](https://favicon.io/) - To create favicon.

[Am I responsive](http://ami.responsivedesign.is/) - To show the website image across a range of devices.

## Deployment and local development

### Deployment

Github Pages was used to deploy the live website. The instructions to achieve this are below:

1. Log in (or sign up) to Github.
2. Find the repository for this project, Palms-Peaks-P1
3. Click on the Settings link.
4. Click on the Pages link in the left hand side navigation bar.
5. In the Source section, choose main from the drop down and select branch menu. Select Root from the drop down select folder menu.
6. Click Save. Your live Github Pages site is now deployed at the URL shown.

### Local Development

#### How to Fork

To fork the Palms-Peaks-P1 repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, Nchrist89/Palms-Peaks-P1.
3. Click the Fork button in the top right corner.

#### How to Clone

To clone the Palms-Peaks-P1 repository:

1. Log in (or sign up) to Github.
2. Go to the repository for this project, Nchrist89/Palms-Peaks-P1.
3. Click on the Code button, select whether you would like to clone with HTTPS, SSH or GitHub CLI and copy the link shown.
4. Open the terminal in your code editor and change the current working directory to the location you want to use for the cloned directory.
5. Type 'git clone' in the terminal and then paste the link you copied in step 3. Press Enter.

## Testing

Testing was done throughout the entire build of the website. The website was deployed early to ensure that along the way any issues were dealt with prior to adding further features to ensure the build was being maintained and any issues and bugs were fixed. I utilized Chrome developer tools while checking any issues I faced, pinpointing where problems have arised from and resolving them.

***ADD IN INFORMATION HERE***

### W3C Validator

The W3C validator was used to validate the HTML on all pages of the website. It was also used to validate CSS in the style.css file.

* [Index page HTML](docs\readme-docs\readme-images\validation-home.png)
* [Gallery Page HTML](docs\readme-docs\readme-images\validation-Gallery.png)
* [Competition Page HTML](docs\readme-docs\readme-images\validation-win.png)
* [Success Page HTML](docs\readme-docs\readme-images\validation-success.png)
* [Style.css CSS](docs\readme-docs\readme-images\validation-css.png)

### Solved Bugs

1. I had an issue with the home page where I found that the image boxes all had a blank white line beneath them causing an issue making them not fit correctly. To correct this I had to look online where I found many other people had the same issue and to resolve it used various methods. In the end I used the display Flex method which removed the blank white line.

2. There was an issue with the cards I had created on the home page where the images would not fit correctly when they were adapting to other devices with responsiveness. After looking online but throughout troubleshooting this issue. I ended up playing around with the options I had available where I found that making the Width of the image 100% and the height as content-fit. This managed to resolve the issue.

3. Creating the about section for the park had caused me quite a headache. The idea came from the love running training and I used some of the knowledge from them but in the end it still wasn't how I wanted it. After asking ChatGPT and explaining what I wanted. It almost supplied code to get this working correctly but in the end I went back to pen and paper and drew out with borders what I desired. whilst also taking some help from the love running code and along with testing I was able to figure out how to do it. After countless hours of failure. It seemed through drawing it with pen and paper allowed me to see what I was unable to before and within 30 minutes I had it figured out.

4. The new features section which houses the new features boxes also caused much stress to resolve how I wanted them visually. Originally these new feature boxes were designed for a Stays.html page which is no longer used in the final project.
   The new feature box design had to show an image of the new feature and by the side of it with all the information about that new feature. The heading, the information and additional features were to show vertically but also stretched across the screen when viewing on a larger screen. In order to do this, I had searched the internet but couldn't quite explain how I wanted it and in the end I thought doing this myself would be a challege as I knew I could figure it out (figuring out myself always allows me to learn resolutions in the future easier).

   In order to resolve this I branched my repository and used a Training Branch which I would use as a playground to test any new features including this one. After quite a few hours. I managed to have the new feature box how I wanted it. Then I had to take it from being horizonal on a large viewing device to mobile and therefore working backwards from what I was originally doing. This then caused further issues when I copied the code over from a styling.css testing stylesheet. Therefore it was back to the playground to retest and find how to move over the code to my final project where it would successfully be responsive.

### Known Bugs

   1. The about section has a minor bug which means that the image box moves slightly when dragging the screen size to make it larger. Unfortunately due to Medical issues and time constraints I am unable to return to the playground to resolve this issue now and it will have to remain but I have tried to add media queries to rectify as best as I can.

### Testing User Stories

* First Time Visitors
  * I want to be able to see from the home page what the resort offers. The home page allows visitors to see an outline of all the main features of the resort and has a brief description of them.
  * I want to be able to navigate the site easily and find what I am looking for. All site navigation is through the top navigation bar which is visible on all pages throughout the website.

![Main features of resort](docs\readme-docs\readme-images\park-features.png)

* Returning Visitors
  * I want to to be able to see if there is anything new since my last visit. A new feature section allows visitors to see what has recently been added to the resort and what they can mainly look forward to in the future.

![New Features](docs\readme-docs\readme-images\whats-new.png)

### Lighthouse

I used Lighthouse within the Chrome Developer Tools to allow me to test the performance, accessibility, best practices and SEO of the website.

#### Index Page

Lighthouse testing:
**Images**

Suggestions:

1. reduce image file sizes in bytes by converting to WebP format.
2. resizing the image itself to properly accommodate the size it requires (width and height).

#### Gallery Page

Initial Lighthouse testing:

Suggestions:

Final Lighthouse testing

**Images**

#### Win Page

Initial Lighthouse Testing

Suggestions:

Final Lighthouse testing

#### Success Page

Initial Lighthouse testing:

Suggestions:

Final Lighthouse testing

**Images**

### Full Testing

To fully test my website I performed the following testing on a couple devices. Family and friends mobiles and different browsers on my own machine.

I also went through each page using Chrome Developer Tools to ensure that each page is responsive on all different screen sizes.

Links.

1. Tested each link on the index page. Each link worked as expected and any links leading to external pages opened correctly in a seperate tab.
2. Tested each link on the gallery page. Each link worked as expected and any links leading to external pages opened correctly in a seperate tab.
3. Tested each link on the gallery page. Each link worked as expected and any links leading to external pages opened correctly in a seperate tab.
4. Tested each link on the win page. Each link worked as expected and any links leading to external pages opened correctly in a seperate tab.
5. Tested each link on the success page. Each link worked as expected and any links leading to external pages opened correctly in a seperate tab.

Competition Form.

1. Testing the competition form. I tried to submit the form without filling any input fields. The form worked correctly and directed users to fill in the empty title field which are radio buttons. I then filled this in and continued to the First Name field.
2. leaving all other fields empty. Again it pointed out the First Name field was empty and needed to be input.
3. I then followed this onward through the form for each field and was successfully hit with the notification that the next field had not been input and could not be left empty.

## Credits

### Code used

* [Create responsive Navbar and sidebar](https://www.youtube.com/watch?v=8eFeIFKAKHw)
* Some code has been autocompleted with the help of AI Copilot. This was turned off mid project as it was too helpful and I wanted to write more myself.

### Content

Content for the website has solely been created by myself and with the assistance of ChatGPT, Sider (AI chrome extension).

### Media

#### Images

* Each image on the website has been created by proving AI with prompts to produce the desired image needed for my content. Prome AI has been mostly used on the home page Although a few others used have been Microsoft Designer, fal.ai, aitubo.ai which if any will be shown on the Gallery page.

### Acknowledgements

I would like to acknowledge the following people who helped me along the way in completing my first milestone project:

* Jubril Akolade - My Code Institute mentor
* Code institute for providing the nessesary tutoring support.
* My Tutor Rachel Furlong for all assitance provided throughout the journey providing assurance.







































