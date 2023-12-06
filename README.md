# Horse Riding

Click [here](https://soro82.github.io/horse-riding/) for the live link.

## Introduction

The Horse Riding website is for people who like horse riding or who are interested in starting horse riding. It tells the user the different types of horse riding and gives some information on each type.

There are pictures in the Gallery page of people horse riding in the different types of horse riding. The feedback page allows the user to tell us what type of horse riding they enjoy.

## Wireframes

I used [Balsamiq](https://balsamiq.com/) to create wireframes for my website to plan the layout of the pages. I found this very useful when I started writing the code for the website.

* Mobile View

  * Home
  * Gallery
  * Feedback

* Tablet View

  * Home
  * Gallery
  * Feedback

* Laptop/Desktop View

  * Home
  * Gallery
  * Feedback

## Features

* Navigation

  * The navigation bar is in the top right of the page inside the header on all three pages.
  * The first link is to the Home page.
  * The second link is to the Gallery page which contains pictures of horse and of people horse riding.
  * The third link is to the Feedback page where users can tell us what type of horse riding they enjoy the most.

* Home page

  * The Home page has a hero image of a person show jumping.
  * Below the hero image is an unordered list of the four main types of horse riding.
  * The rest of the page is divided into four sections, one for each type of horse riding.
  * Each section has a heading, an image and a paragraph about that type of horse riding.

* Footer

  * The footer section contains 4 links to Facebook, Twitter, YouTube and Instagram.
  * The footer is the same on all three pages.

* Gallery
  * The gallery page shows images of people horse riding in the 4 different types of horse riding.

* Feedback Page

  * The Feedback page contains 3 labels and 3 text boxes for the user's first name, second name and email address.
  * It has 4 radio buttons allowing the user to choose which type of horse riding they like to do.
  * At the bottom of the form there is a Submit button to submit their information.
  * Below the feedback form there is an IFrame with a link to Google Maps.

## Responsiveness

* Home Page

  * The four sections on the Home Page are displayed in a single column on mobile phone devices.
  * On tablets each section shows the heading on top and the image and the paragraph side by side underneath. They are displayed  in a single column.
  * For all larger screens they are displayed the same as on tablets but in two columns with two sections in each.

* Gallery
  
  * On mobile phone devices the gallery is displayed in a single column.
  * On tablets they are in two columns of four with the last image in the first column hidden to keep it even.
  * On larger screens the gallery is displayed in three columns of three.

* Feedback Form

  * The feedback form will be centered on all screen sizes.

## Testing

* I tested the website using Chrome, Firefox and Microsoft Edge.
* I confirmed that the website is responsive and fully functional using Chrome devtools and www.responsivedesignchecker.com.
* I have confirmed the form on the feedback page works and requires entries in all fields except the text area for any other information. When the Submit button is clicked it will open the response page.
* I have confirmed that the navbar works on the response page to allow the user to return to the website.
* I have confirmed that the images, paragraphs and heading in the types of horse riding section on the Home page line up horizontally and vertically.
* I have confirmed that the images in the gallery are shown in two columns of four on tablet screens and three columns of three on larger screens.

### Bugs

##### Fixed Bugs

* When testing the website using Wave, there were two errors on the Home page. I added an aria label to the input and the label for the toggle menu and it fixed the problem.
* When testing using Responsive Website Design Tester, the text area in the feedback form would push outside the form border on screens larger than 1200px. I removed the code to adjust the margins for the feedback form in the media query for min 1200px and it fixed the problem.

##### Unfixed Bugs

* There are no unfixed bugs.

### Validator Testing

#### HTML

#### CSS

#### Accessibility

## Deployment

The site was deployed to GitHub pages. The steps to deploy are:

* In the GitHub repository, navigate to the settings tab.
* From the source section drop-down menu, select the Master Branch.
* Once the Master Branch has been selected, the page provided the link to the website.

Click [here](https://soro82.github.io/horse-riding/) for the live link.

## Credits

### Content

* The code to make the social media links was taken from the CI Love Running project.
* The paragraph about show jumping was copied from www.horseandhound.co.uk.
* The paragraph about cross country horse riding was copied from www.wikipedia.com.
* The paragraph about hacking was copied from www.horseandhound.co.uk.
* The paragraph about dressage was copied from www.horsesportireland.com.

### Media

* The images were downloaded from Pexels.
* I used www.resizepixel.com to reduce the size of my images.
* The images were converted from jpg to webp using www.pixelied.com.

### Acknowledgments

* I used www.w3schools.com to learn how to use Flexbox in CSS.
* I got help with my first readme file from www.github.com/kera-cudmore/readme-examples and the Love Running readme file on the Code Institute LMS.
