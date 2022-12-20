# Vegan Sneaker Store

## Table of Contents
* [Introduction](#introduction)
* [Agile development](#agile-development)
* [Features](#features)
* [Marketing](#marketing)
* [Technologies](#technologies)
* [Testing](#testing)
* [Bugs](#bugs)
* [Deployment](#deployment)
* [Credits](#credits)
* [Acknowledgements](#acknowledgements)

***
## Introduction

As market for leather-free and sustainable clothing is growing, there was a natural decision to make a website that goes with changing times.
Eating vegetarian myself for decades and being more compassionate towards all life i started to look for alternative options to leather products.  

It was not an easy task at first, it was hard to find leather-free shoes or sneakers that i liked. I would go to local stores to inspect labels, speak with staff and even then, assortment was very limited. Online you would think it would be easier, but in reality most sites did not post full materials list or labels at all! Even big brands. Googling further often brought conflicting informations..  

So it became increasingly difficult and frustrating. Ofc i understood its a new industry, but still...
I was often thinking: "Why is there no big sneaker store with just leather free sneakers??
Time passed, i enrolled in web development course, still with this question popping from time to time.  

Eventually i connected the dots, and hence, a perfect idea was born.. :)

[Vegan Sneaker Store](https://vegan-sneaker-store.herokuapp.com/)
***

## Agile development

### User stories

To create user stories as per principles of agile development, we used kanban board in our development which is part of Github Projects.
We separated user stories into 5 logical categories, or milestones, and furthermore added assigned tasks and requirements. For illustrative purpose we will only list user stories with associated milestones here.

For full details please check out our link on Github: [V.S. Store User Stories](https://github.com/users/denisklopotan/projects/4)

#### EPIC | Navigation

* As a user I can easily navigate trough the website so that i can access acces preffered content
* As a user I can view list of products so that i can chose ones i like
* As a user I can open selected product so that i can see more details about it
* As a user I can sort products by category so that i can view only by preferred category
* As a user I can use search function so that i can find products quickly

#### EPIC | Purchasing

* As a customer I can select size and quantity so that i can purchase products that fit me
* As a customer I can add products to bag so that i can make purchase
* As a customer I can access my shopping bag so that i can add, remove or update products in it
* As a customer I can easily see subtotal so that i can keep track with my budget
* As a customer I can acess checkout page and enter my details so that I can purchase selected products
* As a customer I can see order confirmation so that i know order was placed correctly
* As a customer I can receive order email so that i have order receipt and details archived in email

#### EPIC | Authentication

* As a user I can create account (register) so that i can access additional features
* As a user I can log in/out from account so that i can have registered user privileges
* As a registered user I can have personalised user account so that i can store personal details like address or purchase history
* As a user I can easily see login status so that i can act accordingly and adress privacy or safety issues
* As a user I can receive email after creating user account so that i know registration was successful
* As a registered user I can recover my password so that i can still access the site in case of forgotten password

#### EPIC | Administration

* As an admin I can access admin panel so that i can use admin features and manage website
* As a site admin I can add or delete products so that i can manage site content / store stock

#### EPIC | Interaction

* As a user I can fill in the contact form so that I can contact store directly
* As a user I can subscribe to the newsletter so that i can be up to date with new products or promotions
* As a user I can access media links so that i can discover more of authors work or contact trough other means
* As a registered user I can write a product review so that i can give an honest feedback
* As a user I can like products so that i can save them to wishlist for future reference

### Wireframes
### Data models

!!! a description of the e-commerce business model including marketing strategies in the README file. ???

***
## Marketing

### Business model

Vegan Sneaker Store's Business model is **Business to Consumer (B2C)**. Products and services are sold directly from V.S. Store to consumers who are the end-users.

Customers of Vegan Sneaker Store would be clearly people eating Vegan / Vegetarian diet which is growing trend; people who support use of alternative, sustainable materials or care for animals. Last but not least, important demographic in this case is religious.

More than billion people are Hindus who are traditionally vegetarian and consider cow a sacred animal, and also other forms of life. Most leather used in industry comes from cows, so this is one initiative to offset that.

There are also 400 million Buddhist. One of the teachings prohibits taking the life of any person or animal. Many Buddhists interpret this to mean that you should not consume animals, as doing so would require killing. Buddhists with this interpretation usually follow a lacto-vegetarian diet.

From these few examples is seen that there is significant potential for this business on the market.

### Marketing types

#### SEO marketing
- meta tags
- sitemap.xml and robots.txt
#### Content marketing
#### Social Media marketing
- facebook page
#### Email marketing
- newsletter

***
## Features

### Homepage
#### Navbar
### Product page
### Authentication
### Purchasing
### Contact us
### To be implemented

***
## Technologies

Main technologies used for building this ecommerce from ground up where Python & Django.
To manage, store and host data as PostgreSQL we used ElephantSQL service.
And to process payments we integrated Stripe payments provider.

### Languages:

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
        - [CSS3](https://en.wikipedia.org/wiki/CSS)
        - [Python](https://www.python.org)
        - [JavaScript](https://www.javascript.com)

### Frameworks:

- [Django](https://www.djangoproject.com)
        - [Bootstrap](https://getbootstrap.com/)

### Libraries:

- [Google Fonts](https://fonts.google.com)
        - [Font Awesome](https://fontawesome.com)

### Packages:

- [Gunicorn](https://gunicorn.org/)
        - [psycopg2](https://www.psycopg.org/)
        - [Pillow](https://python-pillow.org/)
        - [django-allauth](https://www.intenct.nl/projects/django-allauth/)
        - [django-crispy-forms](https://github.com/django-crispy-forms/django-crispy-forms)
        - [Stripe API](https://github.com/stripe/stripe-python)
        - [django-countries](https://github.com/SmileyChris/django-countries/)

### Development:

- [GitPod](https://www.gitpod.io)

### Databases:

- [PostgreSQL](https://www.postgresql.org)
        - [ElephantSQL](https://www.elephantsql.com)

### Hosting:

- [GitHub](https://github.com) is an Internet hosting service for software development and version control using Git. It provides the distributed version control of Git plus access control, bug tracking, software feature requests, task management, continuous integration, and wikis for every project.
- [Heroku](https://www.heroku.com) is a platform designed to host dynamic websites. While Github pages is a great hosting platform for projects built entirely with front end languages  like HTML, CSS and JavaScript, it's not built to handle back end languages like Python, which  is why we use Heroku.

### Static:

- [Amazon Web Services (AWS)](https://aws.amazon.com)

### Payments:

- [Stripe](https://stripe.com)

### Testing:

- [Chrome DevTools](https://developer.chrome.com/docs/devtools)

### Tools:

- [Balsamiq](https://balsamiq.com)
        - [DrawSQL](https://drawsql.app)
        - [Django Builder](https://djangobuilder.io)

***
## Testing

To test the application we performed several categories of testing:
- validator, performance, manual, browser, device and unit testing.

Due to the amount of collected data, testing was moved to a separate file.
- full testing documentation can be found here [⮫TESTING.md](TESTING.md)

To summarise, website passed all testing without any major issues.

***
## Bugs

### Webhooks failing *solved

While following tutorial exactly as explained i still got webhooks failing. After consulting on slack and with tutors i found out the issue. It was due to module update for Stripe webhook handler that in my case was not necessary. I just needed to revert to original tutorial and it worked!

Code in question that was redundant in my case was:

        # Get the Charge object
        stripe_charge = stripe.Charge.retrieve(
            intent.latest_charge
        )

        billing_details = stripe_charge.billing_details # updated
        shipping_details = intent.shipping
        grand_total = round(stripe_charge.amount / 100, 2) # updated

So by deleting 'charge' instance and reverting back to original solved the issue:

        billing_details = intent.charges.data[0].billing_details
        shipping_details = intent.shipping
        grand_total = round(intent.charges.data[0].amount / 100, 2)

Full article on slack can be found [here](https://code-institute-room.slack.com/archives/C7HS3U3AP/p1669282486321559).
***
## Deployment

Since deployment documentation grew to quite significant size we will mention only main milestones here.

For rest we created separate deployment file which you can read here: [⮫DEPLOYMENT.md](DEPLOYMENT.md)

### Milestones:

1. Firstly, to start, we create a new project repository on Github. In this instance and to make it easier we used default Code institute's [gitpod-full-template](https://github.com/Code-Institute-Org/gitpod-full-template).
2. After repository has been created we then click green Gitpod button to open this repository in Gitpod. There we work on building project for majority of our time.
3. After project is done we can then continue with deployment to Heroku;
4. Creating external database on ElephantSQL - as the Heroku add-ons are not available on the Student Pack;
5. And setting up hosting for our static and media files with AWS. Specifically, we will use S3 ("Simple Storage Service") for this.

Deployed site link can be found here: https://vegan-sneaker-store.herokuapp.com/

***
## Credits

As basis for project we used Code Institute's walktrough project [Botique Ado](https://github.com/Code-Institute-Solutions/boutique_ado_v1). We customised css to match vision of our project and built on top of it our own apps, models and templates.

Alongside Code Institute's LMS tutorials i used following websites for education and project resources:

### Study

- [Django](https://www.djangoproject.com/)
- [Bootstrap](https://getbootstrap.com/docs/4.6/getting-started/introduction/)
- [W3Schools](https://www.w3schools.com/)
- [YouTube](https://www.youtube.com/)
   - [Python Django Web Framework - Full Course for Beginners](https://www.youtube.com/watch?v=F5mRW0jo-U4)
   - [Learn Bootstrap in less than 20 minutes - Responsive Website Tutorial](https://www.youtube.com/watch?v=eow125xV5-c)
   - [Personal websites never fail to impress me...](https://www.youtube.com/watch?v=RdcuOF4GSXk)
- [Django Sitemap Tutorial](https://learndjango.com/tutorials/django-sitemap-tutorial)
- [Bootstrap Grid System](https://www.tutorialrepublic.com/twitter-bootstrap-tutorial/bootstrap-grid-system.php)
- [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/#flexbox-background)
- [What's in the head? Metadata in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)

### Code

- [Stack Overflow](https://stackoverflow.com/)
- [Create Contact Form in Django for any website](https://www.youtube.com/watch?v=lSgRWA4PMt4)

### Media

Royalty free media for our site we downloaded from free image hosting sites:

- [Unsplash](https://unsplash.com/) &
        [Pexels](https://www.pexels.com/)

***
## Acknowledgements

So...my 5 minutes of Oscars speech has finally came ;D

Always, big big thanks to my mentor Jack Wachira, slack community, tutors and student support! :)  
To my family, friends and colleagues for their understanding and support too!  

NO, i was not abducted by aliens and i still love you all! I was just locked in my 'office' until i finish this lovely episode of life :))
Even though i stumbled a lot along the way,
I would not even be here writing this without your support.

Did i mentioned student suport? ;) Man i tested you as much as i was tested! You guyz are awesome!! Kieron and Bethany and others, thank you so much with all my heart <3

I wish us all to be best programmers and best humans as we can be..

Last but not least, thank you Code Institute.  

Om ॐ

[Back to top 🠕](#vegan-sneaker-store)