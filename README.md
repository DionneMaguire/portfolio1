# The Three Teds

The Three Teds Website showcases the food items that The Three Teds offer in Stradbally, County Waterford.  The website shows images of the different products that The Three Teds offer and a google map to show exactly where The Three Teds are located.  It introduces Natalie, Rob and Mark to give the faces behind the business and to give users confidence in the quality that The Three Teds can provide. The details including costs of the different offerings are laid out so that the customer has all the information needed to make a decision. Finally they have an opportunity to contact The Three Teds for the final transaction. The site is targeted towards users in the Stradbally area interested in food and making life easier for themselves by what The Three Teds have to offer.

![](documents/images/amiresponsive.png)

## Features

### Navigation
- At the top of the page, the navigation shows the company name in the left hand corner : The Three Teds
- The other navigation links are to the right : Home, About Us, Product Details and Enquiries which link to different pages. 
- I have used a dark text against a white background so that all is easy to read.
- I have set the menu link to underline when we hover over it with the cursor, to provide visual clue to the user what link they are about to click on. 
- Also I have displayed a bottom border on the current page being viewed.
- The header is the same across the four pages for consistency.

![navigation feature](documents/images/nav-feature.webp)

### Home page
- The landing page is an image of people having a great time with food.
- The hero image is a background image but for it to be accessible I added a aria-label with the description of the image.
- The over text on the hero image is dark text on a pale background again to make the text easily readable.

![hero feature](documents/images/hero-feature.png)

#### Product section
- The product section of the home page showcases the four products that The Three Teds offer: 
- DIY pizza kits 
- Grazing platters 
- Sandwich packs
- Sausages and Blaas at Stradbally Market.
- I added the product images as an image tag so that I could add alt element for screen readers.
- The pictures give customers a clear idea of what they will get if they order from The Three Teds.

![product feature](documents/images/product-feature.webp)

##### Map section
- I have inserted a google map to show customers where Stradbally is.
- The map is clickable to open a larger map in a new tab, so customers still have my website open.

![map feature](documents/images/map-feature.webp)

##### Footer section
- The footer element is the same in all 4 pages for consistency.
- In the footer, I have set the social media links to open in a new tab so that the user will still have my site open.
- For these links I have added an aria-label for users who use screen readers.

![footer feature](documents/images/footer-feature.webp)

### About us page
- This page gives a little background and introduction as to how the The Three Teds came about, to give the user information and build confidence.
- It introduces the user to the Three Teds : Natalie, Rob and Mark.  
- There is a picture and a write up about each of the Three Teds.  
- The user can be confident in their hygiene and food standards with all having HACCP level 1.

![about us page](documents/images/about-us-feature.webp)

### Product Details page
- The product details page goes through the products mentioned on the home page but goes into more detail with prices and different options.  
- Gives the user all the information they need to make a decision on if The Three Teds offer what they want and at a price they are willing to pay.

![product detail page](documents/images/product-detail.webp)

### Enquiries page
- The enquiries page allows the user to contact The Three Teds with their name, email address and a text area with their query.
- The input form has been set so that the user can not enter an empty field on the form.
- In the input form I have set the send enquiry and reset buttons to change colors when the users mouse is hovering. 
- The input fields borders change color when the mouse hovers over each field.

![enquiries page](documents/images/enquiries-feature.webp)

### Future features left to implement
- In the future I could add a reviews section to display reviews by existing customers to again build confidence in what The Three Teds provide.   
- Also in the future I could update the site to include a diary so that customers can check availability for catering or ordering opportunities.

## Testing

### Validator testing

- HTML - no errors returned when passing through the official W3C HTML validator
- CSS - no errors returned when passing through the W3C CSS validator
- Accessibility - I ran it through lighthouse in devtools and got the following results:

1 For desktop:

![Lighthouse results for desktop](documents/images/lighthouse-desktop.png)

2 For mobile:

![Lighthouse results for mobile](documents/images/lighthouse-mobile.png)

### Manual Testing
- I checked that the navigation links worked and took the user to the correct page on all 4 pages.
- I checked that if I hovered on the navigation link the name was underlined.
- I checked that clicking the google map worked.
- As I added the social media links in the footer, I checked that they opened in a new tab and also opened to the correct site.

- In the enquiries page I checked:
- If you try and submit an empty form you get an warning message.

![Test for empty form](documents/images/test-empty-form.webp)

- If you enter an email address without a @ you get an error message.  HTML can't check if it is a valid email so I can just check if there is a @ present.

![Test for invalid email address](documents/images/test-incorrect-email.webp)

- When you fill in each element on the form and submit you get the congratulations message and the data that you have sent.

![test correct form entry](documents/images/form-test.png)

- I tested all the above on the development site and the fully deployed site.
- I tested that my website worked on different browsers - Google Chrome, Safari, Microsoft Edge, Mozilla Firefox.
- I tested that my website is responsive, looks good and functions on all standard screen sizes using devtools.
- I have also manually tested on a number of different devices - android phone, iphone, ipad, mini ipad.

### Bugs and fixes

- Initially I had my images as jpeg files and this was giving me performance issues so I converted them to webp files and compressed them.
- I am not completely happy with how the product detail page looks but didn't find a solution in time for this submission. So maybe in the future I could look at product cards to show the information and images in a more pleasing way.

## Deployment
This site was deployed to GitHub pages. The steps to deploy are as follows:

1. Open repository in GitHub

![](documents/images/deployment1.png)

2. Click settings and scroll down to GitHub pages

![](documents/images/deployment2.png)

3. At GitHub pages

![](documents/images/deployment3.png)

4. Here click on none and scroll down and select main

![](documents/images/deployment4.png)

5. Click save

![](documents/images/deployment5.png)

6. The page then displays the path that my site is published on

![](documents/images/deployment6.png)

- The live link can be found here - https://dionnemaguire.github.io/portfolio1/index.html

## Credits
- I went with the same fonts as Love Running, they are clear and easy to read, these are from Font Awesome.
- I used this video on CSS grid to help me with the product section of the home page CSS Grid Tutorial: Responsive Design Examples.
- I also used information from this video on youtube https://www.youtube.com/watch?v=9zBsdzdE4sM about css grid.
- I used the Love Running Project to help with the process of setting up The Three Teds.
- I used w3schools.com website to help with creating and styling the textarea.
- I used https://blog.duda.co/responsive-google-maps-for-your-website to add the google map.
- I used http://crushpixel.com for my hero image.
- I used w3schools and developer.mozilla.org to set up css cards in the about us page.
- I searched on Slack for issues that I was having to see had anyone else had similar problems.
- The images were compressed using  https://tinypng.com.
- The jpeg images were converted to webp using https://convertio.co.
- I got great help and tips from my msletb-nov-2021 cohort, our facilitator Kasia and my mentor Okwudiri Okoro.