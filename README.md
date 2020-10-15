<img src="/assets/images/logo.png" height="100">

# Cross Street Barbers
The website is built to serve as a web presence for a barbershop. The site features testimonials, an embedded Google Map showing the shop's location, opening times, social media links, a pricelist, contact information, a contact form, and a booking form. 

## UX 
The site is intended to inform potential customers about the shop's services and to secure customer bookings. The website is designed with this business-to-consumer model in mind.

Information must be presented in a clear, straight-forward manner, and keep in mind the overall goal of securing customer bookings. For this reason, it is also important to maintain a simple navigational structure with convenient call-to-action buttons which direct customers to the booking process.

[Click here to view screenshots of design prototype.](mockups.pdf)

### User Stories
Potential user stories which were taken into consideration when deciding what features the website should include. The following are user stories for which solutions are essential
1. As a first-time customer, I want to know the shop's location so I know how to get there.
2. As a customer, I want to know the business' opening hours so that I can visit the premises.
3. As a first-time customer, I want to know what services the shop offers to see if it has what I need within my budget.
4. As a first-time customer, I want to see some reviews so I know the business is worth visiting.
5. As a customer, I want to book an appointment online to save time and get booking confirmation.
6. As a customer, I want to know how to contact the business directly to ask a question.
7. As a customer, I want to quickly send feedback / a suggestion / a question to the business.
8. As a customer, I want to visit the business' social media so I can see examples of their work & keep up to date with offers. 

## Features
### Existing Features
- Site navigation at the top of each page; allows users to easily navigate between all pages on the website.
- Toggleable menu on mobile devices; allows mobile users to show/hide site navigation to reduce on-screen clutter.
- Review carousel; shows the user a different TripAdvisor review every 5 seconds. (See user story #4)
- Embedded Google Maps; user is shown location of the business, and can open the location in Google Maps to find directions. (See user story #1)
- Timetable; displays business opening hours in a clear manner. (See user story #2)
- Pricelist page; lists services offered by the business and directs user to Booking form. (See user story #3)
- Contact buttons; allows user to call/e-mail the business using hyperlinks which will open corresponding apps on user's device. (See user story #6)
- Contact form; allows user to quickly send a short message to the business e-mail address, and provide contact details to receive a reply. (See user story #7)
- Booking form; allows user to instantly book an appointment with the business by filling out a short form. (See user story #5)
- Confirmation pages; provide user with confirmation that their queries have been received by the business. (See user story #5)
- Social media links; using links on bottom of each page, users can easily access the social media pages of the business. (See user story #8)

### Features to be implemented 
- Video reel on index page; user is shown a virtual tour of the premises and introduced to services offered by the business.

##  Technologies Used
- [Bootstrap 4.5.2](https://getbootstrap.com/docs/4.0/about/license/)
  - The project uses Bootstrap for layout purposes, its Carousel feature (on index.html), and form styling. 

- [declarativetoggle.js](https://github.com/LearnWebCode/declarativeToggle/blob/master/LICENSE)
  - The project uses declarativetoggle.js for its toggleable navbar at mobile resolutions. (Present as "/assets/js/toggle.js")

- [jQuery](https://jquery.org/license/)
  - declarativetoggle.js is dependant on the jQuery library.

- [hover.css](https://ianlunn.github.io/Hover/#licenses)
  - Link hover effects, except those used on the main site navbar, depend on this library.

- [FontAwesome](https://fontawesome.com/license/free)
  - Social media icons, as well as the "Phone" and "Envelope" icons on the contact page, depend on this framework.

- [ionicons](https://github.com/ionic-team/ionicons/blob/master/LICENSE)
  - Icons used in the site navbar depend on this framework.

## Testing
Each page of the website has been navigated to and tested on the following platforms
- Google Chrome version 86.0.4240.75 (Official Build) (Windows 64-bit): desktop, mobile & tablet resolution on developer tools
- Firefox 78.0.2 (Windows 64-bit): desktop, mobile & tablet resolution on developer tools
- Responsively.app 0.13.2: all available screen sizes
- Safari on iPhone 8 Plus, iOS 14.0.1
- Chrome on Huawei P-Smart 2019, Android 9

### Features tested 
- Site navigation
  - From homepage, all navigation buttons, when clicked, link to the correct respective pages and open within the same browser tab.
- Toggleable menu
  - Downsize the browser tab, or switch to mobile resolution on developer tools. Horizontal navigation bar hides. Menu icon appears.
  - When clicked, menu icon reveals a vertical navbar. Content is pushed down and therefore not hidden by this navbar.
  - From homepage, all navigation buttons, when clicked, link to the correct respective pages and open within the same browser tab.
  - When clicked again, menu icon hides the vertical navbar.
- Review carousel
  - On homepage, carousel displays. Every 5 seconds, the slide changes as it should.
  - Clicking on the TripAdvisor logo will open TripAdvisor website in a new tab.
  - Downsize the browser tab, or switch to mobile resolution on developer tools. Carousel displays correctly and changes slide every 5 seconds as it should.
- Embedded Google Maps
  - From homepage, scroll down. Google Map displays location of shop within iframe.
  - Click and drag the map; surrounding area and landmarks shown.
  - Clicking "View larger map" on desktop opens the map on Google Maps website. 
  - Clicking "View larger map" on mobile launches Google Maps if installed, or redirects the user to Google Maps website.
- Timetable 
  - From homepage, scroll down. Timetable is clearly visible on desktop and mobile resolution.
- Pricelist
  - From homepage, click "Pricelist" on site navbar. Pricelist page loads. Services are shown as individual items. 
    Images display correctly to the left of the text. 
  - Clicking "Book Now" links the user to the Booking page.
- Contact buttons, Contact form, Confirmation Page
  - From homepage, click "Contact" on site navbar. Contact page loads. 
  - Clicking the "Phone" button opens any installed VoIP software. On smartphones, clicking "Phone" button will open the associated phonecall app. (Tested on Windows 10 desktop, iPhone 8+ and Huawei P-Smart 2019).
  - Clicking the "Email" button opens associated e-mail program or app. (Tested on Windows 10 desktop, iPhone 8+ and Huawei P-Smart 2019).
  - Clicking each individual form item allows it to be filled by the user.
  - Form cannot be submitted without required fields ("Name", "Phone Num", "Email", "Message")
  - Clicking "Submit" submits the form and redirects user to Confirmation page.
- Booking form, Confirmation Page
  - From homepage, click "Booking" on site navbar. Booking page loads.
  - Clicking each individual form item allows it to be filled by the user.
  - Form cannot be submitted without required fields ("Name", "Phone Num", "Email", "Message", Time & Date)
  - Clicking "Submit" submits the form and redirects user to Confirmation page.
- Social Media Links
  - Social media links in the site footer open the corresponding media sites in a new browser tab.

## Credits
All images used are credited below. Images have been cropped & color-edited for website's purposes by Rory Brosnan using [GIMP](https://www.gimp.org/). 
- background.png - [Allef Vinicius](https://unsplash.com/photos/IvQeAVeJULw) | [License](https://unsplash.com/license)
- review-background.png, review-background-mobile.png - [Nathan Oski](https://unsplash.com/photos/EW_rqoSdDes) | [License](https://unsplash.com/license)
- service-1.png - ["cottonbro"](https://www.pexels.com/photo/man-in-white-and-black-stripe-shirt-holding-black-pen-3998429/) | [License](https://www.pexels.com/license/)
- service-2.png - [Chris Knight](https://unsplash.com/photos/vI3m5UnZ0aQ) | [License](https://unsplash.com/license)
- service-3.png - [Christoffer Engstrom](https://unsplash.com/photos/1ouGlRChSbY) | [License](https://unsplash.com/license)
- service-4.png - [Nick Demou](https://www.pexels.com/photo/gray-hand-tool-1319459/) | [License](https://www.pexels.com/license/)
- confirmation-image.png - [Chris Knight](https://unsplash.com/photos/_H1XXY96pqw) | [License](https://unsplash.com/license)
- Silhouette of razor used in logo - [pngwing](https://www.pngwing.com/en/free-png-yxgwm) | Non-commercial use, DMCA