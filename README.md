# airbnb-clone-project

- Web application that allows users to browse property listings, view detailed property information, and complete bookings

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - ["UI/UX Design Planning"](#ux/ui-design-planning)
  - ["UI Component Patterns"](#ui-component-patterns)
  - ["Project Roles and Responsibilities”](#project-roles-and-responsibilities)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- Browse available listings with filters such as location, dates, price range, and amenities
- View detailed information about each listing, including photos, host info, reviews, and availability
- Book a listing by selecting dates, entering guest details, and submitting payment
- Log in and register with secure authentication (email/password or third-party OAuth)
- List their own properties with images, descriptions, availability, and pricing
- Manage their bookings and hosted listings through a user dashboard
- View a responsive layout optimized for both desktop and mobile devices
- Interact with buttons, links, and form inputs that include clear hover and focus states

### Screenshot

![](./screenshot.jpg)

- To be added later ...

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)
- To be added later ...

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Version Control: Git and GitHub
- Design Tools: Miro for UI/UX design
- Desktop-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

### UX/UI Design Planning

---

1. Landing Page / Home
   Search bar (Location, Dates, Guests)
   Featured listings or categories (e.g., "Beachfront", "Cabins", etc.)
   Responsive listing grid
   Header with navigation (Login, Signup, Become a Host)
   Sticky navbar with filters on scroll

2. Listing Detail Page
   Image carousel or gallery
   Title, location, host info, amenities, rules
   Pricing breakdown, calendar availability
   “Reserve” section with date picker and price summary
   Reviews section with ratings and comments

3. Checkout:

   3.1 Booking Summary:
   Auto-filled: dates, guests, price details
   Editable options

   3.2 User Info:
   Autofill if logged in, prompt to login/signup if not

   3.3 Payment Section:
   Stripe card form (Card number, expiry, CVV)
   Optional billing address
   "Pay Now" button

   3.4 Confirmation Page:
   Booking confirmation message
   Booking details, host info, cancellation policy
   CTA: “Go to Dashboard” or “View Trip Detail

---

Figma Design Specifications
Color Styles:

Primary: #008489
Background: #FFFFFF
Text: #222222
Secondary Text: #717171
Typography:

- Primary Font: Circular, Medium (500), 16px
- Headings: Circular, Bold (700), 24px-32px
- Secondary Text: Circular, Book (400), 14px

### UI Component Patterns

Components:

- Navbar
- Footer
- Button
- Input
- Modal
- Card # Property preview
- SearchBar
- DatePicker
- PriceBreakdown
- ListingGallery
- ReviewList

Pages:

- index # Landing/Home
- listings/[id] # Listing details
- checkout
- login
- register
- success

Features:

Services

- auth # login, register, getUser
- listings # fetchAll, fetchById, create, update, delete
- bookings # createBooking, getUserBookings
- stripe # createPaymentIntent
- reviews # getReviews, postReview

Utils:

- formatCurrency
- formatDate
- calculateNights
- validateForm
- authGuard # Redirect if not logged in

Styles:

Hooks:

Contexts:

### Project Roles and Responsibilites

1. Project Manager
2. Frontend Developers
3. Backend Developers
4. Designers
5. QA/Testers
6. DevOps Engineers
7. Product Owner
8. Scrum Master

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.proud-of-this-css {
	color: papayawhip;
}
```

```js
const proudOfThisFunc = () => {
	console.log("🎉");
};
```

- To be edited later...

### Continued development

Add messaging between host and guest
Add Google Maps integration for location view
Implement wishlist/favorites feature
Improve accessibility (ARIA, keyboard nav)
Add calendar sync for hosts

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.
- To be added later ...

## Author

- Name: Lawrence Mile
- Website - [Lawrence Mile](https://www.your-site.com)
- Twitter - [@Lawrenc30684436](https://x.com/Lawrenc30684436)

## Acknowledgments

- Inspiration: Airbnb
- Tech Guides: Stripe Docs, Next.js Tutorials
- Design Patterns: Miro, Figma, Airbnb UI
