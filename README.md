# Organic Food

##
Our Organic Food Website is a single page website with three sections designed to enlighten users on healthy eating habits,it also educates users about the importance and benefits of organic foods whilst aiming at providing users with seamless experience in exploring and purchasing high quality organic food.The site features a home page with information on organic foods, a thank-you page for contact form submissions, and a custom 404 error page to guide users back if they encounter broken links.
![Organic Food](assets/images/page.png)

### Site Goals                                            
- To inform users about the benefits of organic food and provide available products.                                         
- To provide an easy-to-navigate user experience with a clear contact option.                                           
- To offer a professional and responsive interface for desktop and mobile users.                                            
- To ensure users can find relevant pages quickly using footer links.

### Target Audience                                        
- Health-conscious individuals and customers interested in organic food.                                                     
- Visitors seeking to inquire about what organic products are,its health benefits and where to source organic products.  

## User Goals

#### First time Visitors Goals:        
- As a visitor, I want to learn about the benefits of organic food so I can make better choices for my health.                                               
- As a visitor, I want to view a selection of organic products offered by the website to enable easy purchase of the available product.                                      
- As a visitor, I want to contact the website owners for further inquiries on organic food     
- As a visitor, I want to view the business location on a map (iframe) for easy guidiance to the office address.                         
#### Returning Visitor Goals:                           
- I want to re-access the product section to browse organic items.                                       
- As a returning visitor,I want to submit another inquiry using the contact form.                                      
#### Error Handling Goals:                       
As a visitor who navigates to a broken or incorrect URL, I want to be redirected to a helpful 404 page with a link back to the home page.

## Features                                            
- Home Page*:This page consists of the introduction to organic food and the definition aswell as the various categories of organic foods attaching images, examples, benefits and importance.
 ![Home section](assets/images/home-page.png)                                                                                                                                                                                                      
- A contact form allowing users to submit inquiries with required fields for name, email, subject, and message.![Contact](assets/images/contact.png)                                                          
- Iframe Section: Displays the location of the business in Nottingham, England, using a Google Maps iframe embedded on the home page.  
![iframe](assets/images/google-map.png)                                      
- Social media Icons: footer section includes Icons to the relevant social media sites for Organic food Website. ![Icons](assets/images/footer-icon.png)                                           
- Thank-You Page:A confirmation page displayed after the user submits the contact form, thanking them for their message. ![Thank you](assets/images/thank-you.png)                                                                   
- 404 Error Page:A custom error page with a friendly message and a "Go Back to Home" button for users who land on non-existent pages.![Error page](assets/images/404.png)

#### Future Features                                  
- Testimonials: A section for customer testimonials to build trust and engagement.                                          
- Newsletter Subscription: Allow users to sign up for email updates on organic food products.                         

#### Design:
Color Scheme:     
- The website uses a palette of natural, earthy tones like shades of green (#2d8659) (#4CAF50), black, and white, symbolizing health and nature.   
- Typography
Headings: "roboto", sans-serif – to evoke a rustic, organic feel.
Body Text: 'roboto', sans-serif – for clean, modern readability.    
- Imagery
Images of fresh organic food and natural landscapes are used throughout the site to promote a clean and healthy lifestyle.

- A wireframe was created to plan the layout and structure of the website before development.![wire frame](assets/images/wire-frame.png)

#### Technologies:                                   
Languages:                                           
-HTML5: Used for the structure of the website.       
-CSS3: Used for styling and making the website responsive across different devices.               

Tools & Libraries:   
Google Fonts: For typography.                    
Font Awesome: For icons used in the footer and the burger menu.   
Git: For version control.                   
GitHub Pages: For hosting the live website.

### Testing

| Feature | Action | Expected Result | Actual Result| Pass/Fail
| ------------- | ------------- | ------------- | ------------- |  ------------- |
| Home link| Click on home link | Navigate to the position on the page where the home is featured | Navigated to the position on the page where the home is featured | Pass |
![Home navigation](assets/images/nav-home.png)

| Feature | Action | Expected Result | Actual Result| Pass/Fail
| ------------- | ------------- | ------------- | ------------- |  ------------- |
| Product link | Click on the product link | Navigate to the position on the page where the product section is featured | Navigated to the position on the page where the product section is featured | Pass |
![Product navigation](assets/images/nav-product.png)

| Feature | Action | Expected Result | Actual Result| Pass/Fail
| ------------- | ------------- | ------------- | ------------- |  ------------- |
| Contact link | Click on the contact link | Navigate to the position on the page where the contact section is featured | Navigated to the position on the page where the contact section is featured | Pass |
![Contact navigation](assets/images/nav-contact.png)

| Feature | Action | Expected Result | Actual Result| Pass/Fail
| ------------- | ------------- | ------------- | ------------- |  ------------- |
| thank-you | Click on the send message button | Redirect user to a thank you page | Redirected user to a thank you page | Pass |
![Send message](assets/images/message.png)

| Feature | Action | Expected Result | Actual Result| Pass/Fail
| ------------- | ------------- | ------------- | ------------- |  ------------- |
| Go Back to Home | To Redirect user back to home page | Redirect user back to home page | Redirected user back to home | Pass |
![Back features](assets/images/back.home.png)

| Feature | Action | Expected Result | Actual Result| Pass/Fail
| ------------- | ------------- | ------------- | ------------- |  ------------- |
| Footer links | Click on the footer icon | Navigate to the respective social media website | Navigated to the social media website | Pass |
![footer link](assets/images/footer-icon.png)

#### Home Page

- Verified that the product section and contact form are visible and functioning correctly on all screen sizes.
- Ensured all footer links navigate to the correct sections.

#### Contact Form
Verified that the form fields are working as expected (name, email, subject, a message valid).
After form submission, users are redirected to the Thank-You page.

#### 404 Error Page
Tested broken and incorrect URLs to confirm that the 404 page displays and the "Go Back to Home" button functions properly.                                          

#### Responsive Testing
The website was tested on multiple devices (desktop, tablet, mobile) using Chrome Developer Tools and confirmed to be fully responsive.          

#### Validator Testing:                                   
HTML: Passed validation with the W3C HTML Validator.                                         
 ![W3C-Validator]https://validator.w3.org/nu/#textarea     
CSS: Passed validation with the W3C CSS Validator.
![Css] https://jigsaw.w3.org/css-validator/validator                                    
#### Browser Compactibility
The website was tested on different browsers(chrome, firefox and safari) to ensure compactibility

#### Accessibility
The website was tested using light house to ensure accessibility ,it achieved a good score for Accessibility, Best practises and SEO. ![light house](assets/images/light-house.png)

#### Performance
The image was optimized using TinyPNG and light house reports were run to check the load time.       
#### Links Testing
All internal and external links were tested to ensure they direct to the correct page and open in new tabs.

#### Clone 
To run website locally,
- Clone the repository
 ![clone](assets/images/clone.png)
- Navigate to the project directory.
- Open index.html in your browser to view the website locally.

#### Deployment
The site was deployed to GitHub pages.
 The steps to deploy are as follows:      
- In the GitHub repository, navigate to the Settings tab     
- From the source section drop-down menu, select the Master Branch      
Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.              
The live link can be found here - https://mildred-prog.github.io/Organic-Food/

#### Bugs

|    Bug   |   Fix   |
| ------------- | ------------- |
| The link in the nav section when clicked had an overline.  | Removed the overline attribute |
| The last icon on the social media links did not redirect properly | Changed the links on the html to target the link properly |
| Header being ignored  | Gave header size dimensions  |
| Google Maps showing causing trouble with validator  | Take out transferred info from link to only necessary code  |
| Home page link stays highlighted when visiting another page | Remove active attribute on non-active pages |

### Credits

#### Media

In order of appearance

- Hero image on landing page - https://themewagon.github.io/foody2/index.html
- Fruits image -https://www.pexels.com/photo/grape-fruits-708777/
- Vegetable - https://www.pexels.com/photo/flat-lay-photography-of-variety-of-vegetables-1435904/
- Milk image -https://www.pexels.com/photo/time-lapse-photography-of-strawberry-falling-on-milk-2064356/
- Images of the organic food products - https://themewagon.github.io/foody2/product.html
#### Code

- The website - Done in co-ordination with the 'Love Running' project steps
- Contact section and iframe doesn"t fully display -https://chatgpt.com/c/66fa9cb8-1e6c-8008-ae28-3204c7ce701a
- Footer - https://philipwalton.github.io/solved-by-flexbox/demos/sticky-footer/ - helped to fix bug

### Acknowledgement
I would like to take the opportunity to thank:
- Code Institute: For their thorough curriculum, valuable resources, and excellent support, which have been integral to the development of this website.
- Vernell Clark for his continuous guidance, insightful feedback, and unwavering support throughout the project which helped refine my approach and ensured the project meet a good standard.(https://github.com/VCGithubCode)
- My Husband Samuel that has been an amazing support and pillar for my new found career.