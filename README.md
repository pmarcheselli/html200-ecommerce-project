# Description

This is an assignment to build a responsive ecommerce web page. Nav and product container div will use flexbox. Sidebar/aside is a module that changes layout and location based on window size. Submitting the mailing list signup form results in user feedback on the page. Clicking a product's “add to cart” or “remove from cart” button updates cart count at top.

Students may use the provided mockups to guide their design to whatever extent they like. Matching the mockups is not required.

## Provided Materials

  - basic HTML and CSS
  - JSON list of products in script.js file
  - reset.css
  - images for all products
  - suggested design mockups

## Assignments

Lesson 03:

  - Make design decisions about how you'd like your site to look. You can use the provided mockups to guide your design to whatever extent you'd like- feel free to implement them exactly or make up your own design completely.
  - Code basic CSS for page. `reset.css` file should remain as it is. `main.css` file can be added to, changed, or completely redone.
  - `nav ul` and `.item-container` elements should be styled as flexbox containers. Implement a responsive grid system of your own design, or use a library, or don't use a grid at all. Be sure all important size values are proportional (em, rem, %).
  - We'll continue working on the CSS for this project throughout the course, in particular making it more responsive. The styling does not have to be perfect after this assignment. It's fine to change or add to the HTML as necessary for your styling.

Lesson 05:

  - Write a JS form handler function to be triggered on form submit. It should print to the console a friendly message that includes the value of the form element with name "email". Something like "Thanks for signing up for our mailing list, bobross@example.com!"

Lesson 06:

  - Serve appropriately sized images. Use GIMP or another photo-editing program to resize all images to more reasonable, consistent dimensions. This includes product images, the logo, and any background or other images you've included.

Lesson 07:

  - Write Javascript function that toggles the inclusion of a product in the "cart".
  - Add/edit HTML as necessary to trigger the function on click of a button for each product.

Lesson 08:

  - Write CSS that uses media queries to change layouts/style based on device size. There shoud be at least one obvious layout change in addition to elements fluidly changing width.
  - Finish styling the page.

Lesson 09:

  - Write Javascript that causes the total number of items in the cart to display next to the cart icon when that total changes.
  - Write Javascript that displays the friendly message on form submit in the page, not in the console.
  - Update the HTML and CSS as necessary to accomodate these changes.
  - Update the Testing section of this README with your own information.

*Extra Challenge*: Incorporate unit tests with [Qunit](https://qunitjs.com/).

*Extra Challenge*: Code a popup that toggles between hidden and displayed when user clicks on cart icon. It should show information about items in the cart (maybe list of their names, but up to you).

*Extra Challenge*: Serve appropriately sized images for user's device. Create multiple sizes of each image, and serve the appropriate one using the `srcset` and `sizes` attributes on the `img` tags. This will require naming all of the images consistently, e.g. "ombre-infinity400.jpg", "ombre-infinity200.jpg". [More](https://css-tricks.com/responsive-images-youre-just-changing-resolutions-use-srcset/) about [srcset](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)

*Extra Challenge*: Use browser storage to save details about a user's cart so when they revisit the page, it's in the same state as when they left it. [More about browser storage](https://www.w3schools.com/html/html5_webstorage.asp)

*Extra Challenge*: Dynamically generate the HTML for product listings from the JSON objects in script.js.

## Requirements

  - Site layout looks good on all sizes of devices. At a minimum, elements are proportionally styled and aside element changes location and layout at different screen sizes. This should be tested using a variety of devices and at least one online browser compatiblity testing tool.
  - Nav and product container elements are styled using flexbox.
  - Appropriately sized images are served.
  - User can add and remove items from their cart, which changes cart count number at top of page.
  - This README is updated to include information about the testing steps taken to ensure site quality.
  - Site is live on GH Pages hosting.

## Grading
Each weekly assignment will be graded independently. There will not be a final grade for the entire project.

## Testing

Target Audience:
Winter Wear Warehouse is an online-only e-commerce company selling hats, gloves, and scarves for both men and women. The target audience is primarily customers looking to buy winter gear at affordable prices. The website's aesthetic is simple and straight-to-the-point shopping putting its main focus on the products and the excellent prices Winter Wear Wearhouse can pass on to its customers.

Website Audience Classification:
Since the target audience for the website is primarily customers shopping directly on Winter Wear Wearhouse for winter gear, it is then further broken down to customers shopping for themselves and customers shopping for others (for family members or gifts). These customers will most likely be between the ages of 25-55 and most likely will be female. These customers are looking to buy affordable winter gear and want a simple website with very little extra gimmicks - they are not looking for social media or extra user interaction, simply to buy the winter gear at great deals. These customers will most likely be low-income to middle-income earners and most likely use older devices. Winter Wear Warehouse's users are located in regions of the United States of America that experience winter weather - from the Pacific Northwest to the Mid-West and to the Northeast Coast. Users are most likely to find Winter Wear Warehouse through a Google search and customer retention is maintained through a weekly newsletter highlighting new deals. 

Audience Devices:
Winter Wear Warehouse's target audience is identified as shoppers most likely using older devices.  These devices range from older iPhones to older tablets & PCs. Users are primarily using their mobile devices and tablets to shop so a responsive site that works for these devices is necessary. 

Device Testing:
Winter Wear Warehouse was tested using Responsive Design Checker (responsivedesignchecker.com) to check the functionality across various devices.

On older iPhone 3/4/4s (320x480 resolution) and iPhone 5/5s (320x568 resolution) models, the website was found to be fully responsive with clear, and easy to read content and the straight-to-the-point shopping target customers want. The "Add to cart/Remove from cart" button is both very accessible and visible and makes buying products easy.  Images scale down properly for mobile. The email sign up is in a very ideal location and all website categories are easy to find on the nav bar. 

Testing was also done on older iPad 2 (1024x768 resolution) and iPad 3 (2048x1536 resolution) models and additionally a standard PC monitor (1366x768 resolution) and same results were found. These screen sizes were not readily available on Responsive Design Checker but were found from a Google search and then input to Responsive Design Checker to verify functionality and site quality. 

Overall, testing showed that Winter Wear Warehouse website displays properly on all of its intended devices.

Performance Testing:
Website Page Test (WebPageTest.org) was used to check the site's performance across various browsers. User demographic research showed that users were more likely to use Internet Explorer 10 (IE10) and iOS 10 on older Apple devices. 

On IE10, Winter Wear Warehouse loaded fully in 3.5s with images making up the largest percentage of requests and bytes sent. 
Functionality was also checked on a iPhone 5c running iOS 10 and the website loaded in 3.29s with images again making up the largest percentage of requests and bytes sent. When checked on Chrome, the site was found to load the fastest (at 2.63s) although, Winter Wear Warehouse's users are most likely to not be accessing the site via Chrome.

Overall, performance testing of Winter Wear Warehouse has yielded satisfactory results in load time. 
