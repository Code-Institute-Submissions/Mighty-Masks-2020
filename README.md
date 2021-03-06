# MIGHTY MASKS #
This project showcases a fictious supplier (Mighty Masks) based around Shanghai seeking orders from big retailers and government agencies during the current pandemic.

I work in the fashion industry and believe suppliers could stand to benefit from better standards of presentation and communication that emphasises quality of product and a partner that can be trusted to deliver.  

In my regular job I negotiate and engage with suppliers based in The East on behalf of a Western company - I thought would offer an excellent challenge to take the opposite point of view in the business relationship

## UX ##
My UX is designed to appeal to the archetypal buyer or procurement manager. They are visually minded (wanting to see product and usage) but also cautious and keen to mitigate against risk. To win orders the team at Mighty Masks will need to make a positive impression, capture attention and entice the visitor into providing contact information which can later be followed up.

As a buyer or procurement type in the market for fashion or medical masks, I most want to understand what product is offered, how it is made and by whom, so that I can place orders for in demand stock with confidence. I am very wary of potential product quality and reputational issues.

I tried to model Mighty Masks on number of presentation ideas I came across when researching various supplier & online retailer websites. I sought to blend the factual informative style of the average supplier and the impressive presentation style the online retailer.

My intention was to keep the design fresh and aesthetically minimalistic. 
I played around with and dropped navbars incl burger icon, home pg modal, jumbotron, zoom-in & out effects, timeline bar (both coded & image based) - as I felt these features detracted from user experience rather than improved it.

I've added my research & inspriration as a PDF (../assets/research-inspiration/Mighty%20Masks%20initial%20research.pdf)

Based on my initial research I then created a wireframes mock-up (../assets/wireframes/Mighty%20Masks%202020.pdf). 
I followed my Wireframes closely for most part. The small number of divergences are based on consideration of spacing and userbility (e.g. Get-In-Touch pg was org 3 features in top row, changed to 2 features in top row w/ 3rd (the map) placed in row below)

## Features ##
The project is divided into 5 pages with a number of features.

**1. Home Page**
Allows visitors to quickly evaluate MightyMasks product and reputation. 

Features include a navalert, header navigation links, a Hero Image, product panels that link to product page, customer quotes, a banner, hyperlink hover FAQ, a sign up link and form to subscribe to a newsletter, footer navigation links and social media icons that link to social media presence, and shopify link to website. 

Encourages progression to "Get In Touch" page through modal and hyperlinks.

**2. Product Page**
TBC

**3. Our Mission Pages**
Gives a background to company and founder behind it. 

Features include a border instead of a navalert, timeline on top of standard header and footer features.

Downloadable certification pdf.

**4. Our Values Page**
This showcases the ethical and responsible side of the business, a cornerstone in any supplier-retailer/govt relationship today. 

Features include a seocnd hero image and panelled squares giving a nice visual impact alongside information.

**5. Get In Touch Page**
The key page aimed at solidifying a potential new relationship based off initial interest. Want to make it possible to schedule in meetings and follow ups.

All pages link to this page, a central part of my design.

Features include a contact form, contact information, a Google Maps location of the Mighty Masks Head Office, a FAQ section, and a Free Swatch offer with hyperlink/hover.

#### Features Left to Implement : ####
I ran out of time but would have liked to have added a number of additional features. In particular :
[ ] A chat feature on the Home Page
[ ] Product page navalert for Sign Up to special offers
[ ] Product page carousel on the product page 
[ ] Product page options for size, color, box qty selection
[ ] Product page fabric and reusability fontawesome icons

I would add the following post-JavaScript course :
[ ] A timed modal that occupies the home pg showing latest order detail info - a common feature on fashion websites
[ ] A toaster that pops up with send confirmation message
[ ] A more robust test of acceptable emails - I noticed as long as you added an "@" & "." the form would accept it as valid, too basic

#### Technologies Used : GitHub, GitPod ####
**Languages** : HTML5, CSS3
**Tools** : Bootstrap, Flex Box, picresize.com, Font Awesome, Google Fonts, Chrome Developer Tools

#### JQuery ####
The project uses JQuery to simplify DOM manipulation.

#### Testing ####
I noticed speed load times were slow in Chrome Developer Tools. I initially resized all images from 5000KB to 1000-1500KB. 

Load time was still over 2s+ so I resized images a second time to 500KB or lower.
In my 2nd speed test, only Slow 3G takes 2.09s but all other throttling is much quicker than 2s. 

I also checked x 7 industry wide tests to run for a website : Lighthouse, WebPageTest, TestMySite, PageSpeed Insights, Speed Scorecard, Impact Calculator, Chrome Developer Tools

In my 3rd & final speed test, I have all images below 200KB (except some marginal cases where it lead to a poor result)
Avg DOMContentLoaded time is around 275ms on my network, 630ms on Fast 3G and 2.03s on Slow 3G 

All code successfully passed CSS & HTML validators (after a few tweaks)

## Contact form: ##
A this stage the Mighty Masks website contact form is inactive. The button works but will need to link to .php source at a future date. I would also add a toaster using JavaScript to show email sent confirmation.

My website looks good on different breakpoints. I designed with a view for desktop, i-pad and mobile. The images turn to photo style in mobile and flex box was instrumental in adjusting the content.

I've found Our-Mission to be a glitchy page. The image files are small after x 3 rounds of resizing. However, it always seems to take just a fraction longer to load on this page. This is despite having relatively little content.

If you have any feedback for me as an author I am reachable at peter.og.shearman@gmail.com

## Deployment ##
I've deployed Mighty Masks on GitHub Pages [(https://pjshvision.github.io/Mighty-Masks-2020/our-values.html)]
I found it slightly challenging given it was my first time deploying. 

To deploy I went to Settings in my repository. I selected the Master Branch.

There are two noticeable differences between the deployed version and the development version. 

The first is that it lands on the product page rather than the index.html page. 
This is an unexpected result as GitPod opens on index.html - note this has now been solved by correcting to index.html [(https://pjshvision.github.io/Mighty-Masks-2020/index.html)]

The second is that my logo is conspicuously missing. The documentation in my gitpod messages shows that the logo was the hardest challenge for me to solve. It is disappointing that it fails to show after the hard work was done finding an attractive solution.
I suspect it may be due to the img src link but will need to follow up on this.

I checked the deployed version on my mobile phone and it looks very nice bar the above two issues.

I was unaware prior to deployment that it could look any different from GitPod. 
This is a valuable lesson I will take onboard in the future.

## Credits ##
#### Content ####
- Text for Our Values page was copied from Avocado Green Mattress and re-written to suit MightyMasks. Any similarities will be due to this.
- Some code covering classes and children was copied from Code Institute projects Cool Runnings, Whiskey Drop, Rosie Odenkirk and re-written to suit MightyMasks
- Code snippet for quotes in Home Page was taken from Bootstrapious [(https://bootstrapious.com/p/bootstrap-quote)]
- Code on responsive squares derived from Bobby Kilpatrick [(https://spin.atomicobject.com/2015/07/14/css-responsive-square/)] 
- Also Shikkediel on squares [(https://css-tricks.com/forums/topic/making-a-responsive-css-square/)]
- How to make a CSS contact form [(https://www.w3schools.com/howto/howto_css_contact_form.asp)]

#### Media ####
The photos used in this site were obtained from Unsplash and Shutterstock. 
All Unsplash photos are fully accredited to photographer in assets folder and CSS code.

Attribution to Unsplash photographers in alphabetical order :
- Angelo Abea 
- Bara Buri
- Edward Howell
- Gryffn M
- Isaac Owens
- Juan Encalada
- Junho Chak
- Macau Photo Agency
- Marilia Castelli
- Obi Onyeador
- Sarah Y
- Sei Kakinoki
- Vera Davidova
- Yiranding
- Yue Iris

Shutterstock photos did not come with any photographer names I could attribute. 

#### Acknowledgements ####
I received inspiration for this project from my Dad who would not stop talking about coronavirus face mask. I also read articles including :
"Miley Cyrus fights coronavirus with fashion in Gucci face mask"
[(https://pagesix.com/2020/04/24/miley-cyrus-fights-coronavirus-with-fashion-in-gucci-face-mask/)]

"6 Fashion Brands Pivoting To Create Masks For The Public"
[(https://www.forbes.com/sites/sboyd/2020/04/24/5-fashion-brands-pivoting-to-create-masks-for-the-public/#475236bd648f)]

"Stylish face masks to shop now"
[(https://www.vogue.com/slideshow/stylish-face-masks-to-shop-now)]


I took inspiration from a number of supplier websites listed below (I already work with these suppliers in real life on Bathroom & Towel product) :
- Al Karam [(https://www.alkaram.com/corporate/)]
- Al Rahim [(https://www.alrahimtextile.com/)]
- Saad [(https://www.saadtextile.com/)]


I also looked at presentation styles from face mask retailers including :
- Katie May [(https://www.katiemay.com/)]
- RESA [(https://shop-resa.com/collections/masks)]
- 8 Other Reasons [(https://www.8otherreasons.com/collections/accessories/products/8or-masks-3pk)]
- Bleusault [(https://bleusalt.com/products/the-little-triangle-scarf?variant=31558005784689#navy)]
- Alice & Olivia [(https://www.aliceandolivia.com/shoes-accessories/facemasks/)]
- Buck Mason [(https://www.buckmason.com/products/washable-prevention-face-masks)]
- Onzie [(https://www.onzie.com/collections/mindful-masks)]
- Etsy [(https://www.etsy.com/market/linen_zero_waste)]
- Phlemuns [(http://www.phlemuns.com/shop/phlemuns/0420/cloud-mask)]
- Kes [(https://kesnyc.com/collections/face-mask)]
- Take Care [(https://us.takecaresupply.com/)]
- Hedley&Bennet [(https://www.hedleyandbennett.com/pages/wakeupandfightmask)]
- Avocado Green Mattress [(https://www.avocadogreenmattress.com/shop/organic-cotton-face-mask/)]
- MaskClub [(https://maskclub.com/)]


I attribute code taken & modified from :
- CSS-tricks.com Aside Wrapper [(https://css-tricks.com/snippets/css/a-guide-to-flexbox/)]
- CSS-tricks.com Flex Container/Item [(https://codepen.io/team/css-tricks/pen/EKEYob)]*/
- Kristen Spencer Flex Box [(https://codepen.io/kristencodes/pen/BopVyB)]
- W3Schools Contact Form ([https://www.w3schools.com/howto/howto_css_contact_form.asp])
- Google-Maps i-frame ([https://developers.google.com/maps/documentation/embed/start])
- Code Institute coursework including Cool Runnings, WhiskeyDrop, Rosie Odenkirk CV


I'd to thank my mentor Jonathan Munz who gave me some excellent tips. 
Also my friend Goutham Madhava who gave me some pointers on server capabilities and image resizing which was an Achilles Heel of mine.




