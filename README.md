# Divine Timing
Divine Timing is an Eccommerce store that specialises in handcraft digital watches and traditional watches.

![responsive page](https://user-images.githubusercontent.com/65243328/184502312-b607df79-aee3-44f3-b988-e257eb320d37.JPG)

[Deployed site here](https://divinetiming.herokuapp.com/)


## UX
### Users
The user should be able to interact with the website freely and be able to visit the product pages of the site including, watches, glasses, watch straps etc. They will be able to also Sign up and login with an authenticated account that allows them to interact with their previous orders on their account etc.

### Admins
The Admins should be able to manage the accounts of the users registered to the site, and freely able to use product management to alter and delete products at will.

### Agile Methodology

Agile Methodology was used via Github Projects Kanban board in order to create user stories and execute them as issues in a sprint fashion.

### User Stories
| iD | Story | Resolution |
| --- | --- | --- |
| #1 | Account registration | Admin App |
| #2 | View a list of products | Web App |
| #3 | View individual product details | products Section |
| #4 | Able to identify different sectors of the site, Deals, clearance, offers etc. | Booking Section |
| #5 | Register for an account | Web App |
| #6 | Easy to login or logout | Web App |
| #7 | Enabled to password reset if lost account details  | Web App |
| #8 | Receive an email confirmation after registering  | Web App |
| #9 | Able to view purchases any time | Checkout App |
| #11 | Able to sort and search products  | Web App |
| #12 | Sort a specific category or product  | Web App |
| #13 | Search for a product by name or description  | Web App |
| #14 | View order history  | Checkout App |
| #15 | Remove or add items to cart/bag  | bag App |
| #16 | Easily able to enter Payment information  | Web App |
| #17 | Assured that payment information is safe and secure  | Web App |
| #19 | Receive an email confirmation after checking out  | Web App |
| #20 | Add a productt  | Admin App |
| #21 | Edit/update a product | Admin App |
| #22 | Delete a product  | Admin App |

![Kanban Board](https://user-images.githubusercontent.com/65243328/184502572-72f29e53-1d57-442c-a0d9-1308e92fc290.JPG)

### Purpose
The Application is designed as an eccomerce Watch and Jewelry store to attract users and purchase the products online via the store.
They will be sent the uxury items to their address once purchased.

  
### Colours


![divinetiming](https://user-images.githubusercontent.com/65243328/184502587-e0d671b3-d77c-4e0a-98d1-0fbda6783322.png)


#000000 Black used for the main grid lines of the site. To give the clean aesthetic.


#BC2B3F Cardinal for the featured sections of the site


#0E0D0F Rich Black Fogra for the some of the products on the site


#F93D5C Radical red for text on some of the main sections of the site i.e. logo and products.



## Features
Home Page

The home page has an attractive layout that is bright and iniviting. It also hosts a review section of previous customers and additional information on the features of the digital watches. The page has a Navigation bar that links to other sections of the site and buttons on the page that link straight to the profile and orders of the customer. If the user is not a registered user and not logged in. The navbar has a login/register option and the button to take the user to the login page.

![divin1](https://user-images.githubusercontent.com/65243328/184503091-c1ba9f57-1e34-4c04-9f55-e1473179f33b.JPG)
![divin2](https://user-images.githubusercontent.com/65243328/184503098-ed260371-6b5a-4d6b-95a4-51714281714c.JPG)


product Page

the product Page is a simple page that is not distracting for the user and catches their eye right away with a list of various products users can buy.
Ranging from watches, to glasses and watch straps.

![products1](https://user-images.githubusercontent.com/65243328/184503147-b549f2e3-d8e7-42bb-8cb7-91a0902a154d.JPG)
![products2](https://user-images.githubusercontent.com/65243328/184503156-ebb231a2-5a85-472c-b650-c50c7b560018.JPG)



Profile Page

The Profile page will contain the details of user that is logged in and a list of all their previous purchases and order history.

![prof1](https://user-images.githubusercontent.com/65243328/184503298-9f10dcbc-8357-4ae9-acd4-962558c1966c.JPG)


Login Page / Sign up Page

Allowing new users to sign up to the site to purchase products and existing users to log back in and purchase more or check their order history.

![signup1](https://user-images.githubusercontent.com/65243328/184503345-51ff929e-5b9a-4f99-a2b7-c6574fa5170b.JPG)
![signup2](https://user-images.githubusercontent.com/65243328/184503353-6264c334-1ece-41e7-af6b-8f90fd1567df.JPG)


Manage Products page

Allowing Admins to add/edit/delete products as they see fit.

![prodmanage1](https://user-images.githubusercontent.com/65243328/184503537-d0fa30d1-347e-466c-b6d3-fb1ebe14db46.JPG)

![prodmanage2](https://user-images.githubusercontent.com/65243328/184503543-0320b9ed-02fb-4349-8341-d7ed8090c69b.JPG)


## Future Features




## Testing
[Link to TESTING.MD here:](https://github.com/MikaCodez/GHITrestaurant/blob/main/Testing.md)


## Deployment
The site was deployed to Heroku. The below steps were carried out to deploy.

Deployment steps add the list of requirements by writing in the terminal "pip3 freeze > requirements.txt"

Git add and git commit the changes made

Log into Heroku or create a new account and log in

top right-hand corner click "New" and choose the option Create new app, if you are a new user, the "Create new app" button will appear in the middle of the screen

Write app name - it has to be unique, it cannot be the same as this app

Choose Region - Europe selected in this instance

Click "Create App"

The page of your project opens. 8. Choose "settings" from the menu on the top of page 9. Go to section "Config Vars" and click button "Reveal Config Vars"

Go to git pod and copy the content of "creds.json" file

In the field for "KEY" enter "CREDS" - all capital letters

Paste the content of "creds.json" and paste to field "VALUE" Click button "Add"

Add another key "PORT" and value "8000"

Go to section "Build packs" and click "Add build pack"

in this new window - click Python and "Save changes" click "Add build pack" again in this new window - click Node.js and "Save changes" take care to have those apps in this order: Python first, Node.js second, drag and drop if needed Next go to "Deploy" in the menu bar on the top

Go to section "deployment method", choose "GitHub"

New section will appear "Connect to GitHub" - Search for the repository to connect to

type the name of your repository and click "search"

once Heroku finds your repository - click "connect"

Scroll down to the section "Automatic Deploys"

Click "Enable automatic deploys" or choose "Deploy branch" and manually deploy

Click "Deploy branch"

Once the program runs: you should see the message "the app was successfully deployed" 23. Click the button "View"

Forking the GitHub repository By forking out of this repository you will be able to view and edit the code without affecting the original repository.

Locate the GitHub repository. Link can be found here: GHIT Restaurant Click the button in the top right-hand corner "Fork" This will take you to your own repository to a fork that is called the same as the original branch.

Making a local clone Locate the GitHub repository. Link can be found here. Next to the green Gitpod button you will see a button "code" with an arrow pointing down You are given the option to open with GitHub desktop or download zip You can also copy https full link, go to git bash and write git clone and paste the full link


## Technologies Used
Python All packages used can be found in the [requirements.txt](https://github.com/MikaCodez/Divine_Timing/blob/main/requirements.txt) File.
HTML - Used for the template structures.
CSS - Used to style the markup.
Javascript - Custom use minimal, to set a timeout on bootstrap messages.
GitHub - to store the overall project repository.
GitPod - used as a workspace to do the coding.
Django - django frameworks to manage apps.
Figma - To design the wireframe of the complete project.
Google Fonts - to brandize 'Harmonic Poems' with google fonts. Used for logo and all the written content.
Fontawesome - fontawesome icons for social media links and as additional design.
Bootstrap - grid, layout, columns, cards and forms structure.
Heroku - for the deployment of the project.
Coolors - to choose the colour palette and colour shades.
PostgreSQL - database storage of the models.
AWS - image and static files storage.
AmIResponsive - responsiveness of the site.
Lighthouse - used for testing site functionality.
PEP8 - used for Python files testing.
W3C Markup Validation Service - used for HTML testing.
W3C CSS Validation Service - used for CSS testing

## Resources
Code Institute's Slack Community.
Code Institute's Codestar Django Blog was used in the beginning stages of the development of this project.
Code Institute's Boutique Ado app was used as a base for the products and navigation
Django Documentation - Heavy Reliance on Django documentation to implement forms, models, views etc.
W3Schools documentation for CSS
Bootstrap Documentation - For implementing Bootstrap styles across project
Google
Stack overflow
Youtube - Also Heavy Reliance on youtube tutorials from Codemy.com and Pretty Printed especially when it came to views and models in py


## Credits

SCOPE code credits to Code Institute, Boutique Ado Walkthrough Project. HTML template credit to Nikhil. I have amended the code to my Eccomerce sites specification.

Credits also due to Code Institute staff for helping especially Tutor Support.

Images for Reviews taken from [Unsplash.](https://unsplash.com/)

Images taken for products from various watch stores: [Rolex](https://www.rolex.com/en-us), [Jomashop](https://www.jomashop.com/), [sunglasseshut](http://sunglasseshut.com/), [strapsco](https://strapsco.com/), [monkey glasses](https://www.monkeyglasses.com/)


