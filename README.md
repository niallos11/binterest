# Binterest
A e-commerence platform for Upcycled & Recycled & Sustainable products.

## Features


###  To Do assessment criteria:
at least 3 original custom models with associated functionalities, markedly different from those present in the Boutique Ado walkthrough project if they have been used as a basis for your project.
at least one form on the front end, which provides either admin or regular users with CRUD functionality without having to access the admin panel.
at least one UI element on the front end, which allows either admin or regular users to delete records in the database without having to access the admin panel.
evidence of agile methodologies followed during the development of your project in the GitHub repository.
a robots.txt file.
a sitemap.xml file.
descriptive meta tags in the HTML.
at least one link to an external resource, which makes use of a rel attribute.
a custom 404 error page.
evidence of either a real Facebook business page, or mockup of one, for the purposes of digital marketing.
evidence of a newsletter signup form for the purposes of digital marketing.
a description of the e-commerce business model including marketing strategies in the README file.
~~DEBUG mode set to False.~~
working functionality for users to register and log in and out of the application without issues.
working E-commerce functionality for users to make purchases within the application.
detailed testing write ups, beyond results of validation tools.


## User stories 
- As a site user I can login to a registered account so that access the comment and like functionality
- As a Site Admin I can create, read, update  posts so that I can manage the blog content
- As a Site Admin I can create draft posts so that I can finish writing the content later
- As a Site Admin I can approve or disapprove comments
- As a Site User & Admin I can view comments on an individual 
- As a Site User & Admin I can view the number of likes on each post 
- As a Site User I can register an account 
- As a site user I can logout of my registered account
- As a Site User I can view a list of posts so that I can select one to read
- As a Site User I can view a paginated list of posts so that easily select a post to view
- As a Site User I can click on a post so that I can read the full text
- As a Site User I can leave comments on a post so that I can engage with other users
- As a Site User I can like or unlike a post so that I can interact with the content
- As a Site User I can login to my profile so that I can view all my previously created posts
- As a site user I can filter the reviews 
- As a site user I can edit my comments to add additional content


## Testing
- I have tested page on Chrome,Firefox,Safari,Edge
- I have tested page with Google lighthouse
- I have tested with W3C HTML Validator
- I have tested with W3C CSS Validator
- I have tested with JSHint

## Bugs

## Lighthouse

## Mobile
![image](https://github.com/niallos11/binterest/assets/5288061/08f52d97-fa65-472d-a5da-85fee1b66a70)

## Desktop
![image](https://github.com/niallos11/binterest/assets/5288061/5616d7e1-3b5d-473c-96e2-c1fe1b3c8afd)


### Validator Testing

### HTML
https://validator.w3.org/nu/?doc=https%3A%2F%2Fapp-binterest.herokuapp.com%2F

Error: Element li not allowed as child of element nav in this context. (Suppressing further errors from this subtree.)

From line 109, column 17; to line 109, column 45

          <li class="list-inline-item">↩    <

Contexts in which element li may be used:
Inside ol elements.
Inside ul elements.
Inside menu elements.
Content model for element nav:
Flow content.
Error: Element li not allowed as child of element nav in this context. (Suppressing further errors from this subtree.)

From line 131, column 1; to line 131, column 38

iv>↩</li>↩<li class="list-inline-item dropdown">↩    <

Contexts in which element li may be used:
Inside ol elements.
Inside ul elements.
Inside menu elements.
Content model for element nav:
Flow content.
Error: Duplicate ID user-options.

From line 132, column 5; to line 132, column 146

own">↩    <a class="text-black nav-link d-block d-lg-none" href="#" id="user-options" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">↩     

Warning: The first occurrence of ID user-options was here.

From line 73, column 25; to line 74, column 71

          <a class="text-black nav-link" href="#" id="user-options" data-toggle="dropdown"↩                            aria-haspopup="true" aria-expanded="false">↩     

Error: Element li not allowed as child of element nav in this context. (Suppressing further errors from this subtree.)

From line 145, column 1; to line 145, column 29

iv>↩</li>↩<li class="list-inline-item">↩    <

Contexts in which element li may be used:
Inside ol elements.
Inside ul elements.
Inside menu elements.
Content model for element nav:
Flow content.
Error: Element style not allowed as child of element body in this context. (Suppressing further errors from this subtree.)

From line 265, column 3; to line 265, column 9

div>↩  ↩  <style>↩  .ob

Contexts in which element style may be used:
Where metadata content is expected.
In a noscript element that is a child of a head element.
Content model for element body:
Flow content.
Warning: The type attribute is unnecessary for JavaScript resources.

From line 292, column 5; to line 292, column 35

↩    ↩    <script type="text/javascript">↩  

### CSS - Errors

https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fapp-binterest.herokuapp.com&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en
webkit-user-select is a vendor extension
214		-moz-user-select is a vendor extension
215		-ms-user-select is a vendor extension
231	.allauth-form-inner-content button:hover	Same color for background-color and border-color
231	.allauth-form-inner-content input[type="submit"]:hover	Same color for background-color and border-color
262	.custom-checkbox .custom-control-input:checked ~ .custom-control-label::before	Same color for background-color and border-color


### Color Contrast Accessibility Validator
![image](https://github.com/niallos11/binterest/assets/5288061/85d21f66-9054-4422-a97e-5afbc3b20d05)


### Javascript


### Python


### Unfixed Bugs


### WireFrames
This site was designed and planned out with wireframes before deployment. 


### Deployment:
- The site was build using CodeAnywhere
- The site was deployed to GitHub.
- The site was deployed to Heroku.


The live link can be found here - https://app-binterest.herokuapp.com


## Credits
- Code Institute
- Special thanks to student care
- Boutique Ado walkthrough project


### Content
- The main code base was taken from Boutique Ado walkthrough project


### Media
- The images used for the background page were taken from a Open Source site.
- The fav icon was taken from - https://www.favicon.cc
- The images were resized with Bulk Resize Photos - https://bulkresizephotos.com/en
