<img src="/assets/images/logo.png" height="100">

# Cross Street Barbers
The website is built to serve as a web presence for a barbershop. The site features testimonials, an embedded Google Map showing the shop's location, opening times, social media links, a pricelist, contact information, a contact form, and a booking form. 

## UX 
The site is intended to inform potential customers about the shop's services and to secure customer bookings. The website is designed with this business-to-consumer model in mind.

Information must be presented in a clear, straight-forward manner, and keep in mind the overall goal of securing customer bookings. For this reason, it is also important to maintain a simple navigational structure with convenient call-to-action buttons which direct customers to the booking process.

[Click here to view screenshots of design prototype.](mockups.pdf)

### User Stories
Following are potential user stories which were taken into consideration when deciding what features the website should include. 
- As a first-time customer, I want to know the shop's location so I know how to get there.
- As a first-time customer, I want to know what services the shop offers to see if it has what I need.
- As a first-time customer, I want a list of prices so I can decide if they are within my budget.
- As a first-time customer, I want to see some reviews so I know the business is worth visiting.
- As a customer, I want to book an appointment online to save time and get booking confirmation.
- As a customer, I want to know how to contact the business directly to ask a question.
- As a customer, I want to know when the shop is open so I can contact them/visit.

## Features
### Existing Features
- Site navigation at the top of each page; allows users to easily navigate between all pages on the website.
- Toggleable menu on mobile devices; allows mobile users to show/hide site navigation to reduce on-screen clutter.
- Review carousel; shows the user a different TripAdvisor review every 5 seconds. 
- Embedded Google Maps; user is shown location of the business, and can open the location in Google Maps to find directions.
- Timetable; displays business opening hours in a clear manner.
- Pricelist page; lists services offered by the business and directs user to Booking form.
- Contact buttons; allows user to call/e-mail the business using hyperlinks which will open corresponding apps on user's device.
- Contact form; allows user to quickly send a short message to the business e-mail address, and provide contact details to receive a reply.
- Booking form; allows user to instantly book an appointment with the business by filling out a short form.
- Confirmation pages; provide user with confirmation that their queries have been received by the business.
- Social media links; using links on bottom of each page, users can easily access the social media pages of the business.

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
- Google Chrome version 86.0.4240.75 (Official Build) (Windows 64-bit), including on all screen sizes available on developer tools
- Firefox 78.0.2 (Windows 64-bit), including on all screen sizes available on developer tools
- Opera 70 (Windows 64-bit), desktop resolution
- Responsively.app 0.13.2, all available screen sizes
- Safari on iPhone 8 Plus, iOS 14.0.1
Website is functionally & visually working as intended on these platforms.

The following features have been tested in Chrome (including all screen sizes on developer tools), Responsively.app, and Safari on iPhone 8 Plus:
- Embedded Google Map
- Contact Form (ensuring necessary fields are marked as required)
- Booking Form (ensuring necessary fields are marked as required)
- Mobile navigation can be toggled on/off
- Review slider
- Opening Times timetable
- Contact; telephone & e-mail buttons open corresponding apps on iPhone 8 Plus
- Social media links open in new browser tab 
All above features are functionally & visually working as intended. 

