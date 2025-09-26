Sweet-Shop-Management

The Sweet Shop website provides users with the ability to purchase a wide variety of sweets.
Upon landing on the site, you are greeted with three main options that indicate the purpose of the site.

🚀 Live Website

The Sweet Shop – Live Website  https://the-sweet-shop-davidhearl.herokuapp.com/

📑 Table of Contents

Objective

About

User Experience

User Registration

Agile Development

Database

Technologies

Project Installation Requirements

Scope

Structure

Testing

Pass Criteria

Business Model

Bugs

Newsletter

Deployment

🎯 Objective

The Sweet Shop is an e-commerce website that allows users to purchase a selection of confectionary items.
This project was developed as the 5th portfolio project as part of a Diploma in Software Development.

🏪 About

The Sweet Shop website provides users with the ability to purchase a wide variety of sweets.
Upon landing on the site, visitors are greeted with three main options which clearly indicate the purpose of the site.

Non-logged-in users can browse all products and add them to their bag for checkout.

They can complete checkout by entering their details along with a valid card.

A confirmation page is displayed and a confirmation email is sent after successful payment.

Logged-in users enjoy additional benefits:

Faster checkout with saved profile information.

View order history.

Leave reviews on their favorite products.

Add favorite sweets to a personal page for quick and easy repeat purchases.

💡 User Experience

Simple, intuitive UX experience.

Easy navigation for all users.

Visually appealing and responsive across multiple devices.

👤 User Registration

An important feature of the site is the option to purchase without signing up.
Some users may find forced registration frustrating, so guest checkout is available to provide a smoother experience.

🛠 Agile Development

The project followed an agile development approach to ensure iterative improvements and user-centric design.

🗂 Database

The project utilizes a database to manage:

User accounts

Product details

Orders

Reviews

💻 Technologies

The project is built using:

Django (Backend framework)

Stripe (Payment integration)

Pillow (Image processing)

Crispy Forms (Enhanced form rendering)

Gunicorn (Deployment server)

Boto3 & Django Storages (Static/media file management)

PostgreSQL (Database)

⚙️ Project Installation Requirements

Install the required dependencies using:

pip3 install Django==3.2
pip3 install django-allauth
pip3 install Pillow
pip3 install django-crispy-forms
pip3 install stripe
pip3 install django-countries
pip3 install dj_database_url
pip3 install psycopg2-binary
pip3 install gunicorn
pip3 install boto3
pip3 install django-storages

📋 Scope

Provide a simple and intuitive UX.

Ensure easy navigation for the user.

Create a visually appealing and responsive site across multiple devices.

🏗 Structure

A straightforward and clear layout ensures users can navigate intuitively.

Fixed Navbar at the top of every page allows quick access to all sections.

Fixed Footer at the bottom of all pages provides essential links and information.

🧪 Testing

The website was thoroughly tested to ensure:

Cross-browser compatibility.

Responsive design across multiple screen sizes.

Secure and error-free payment processing.

✅ Pass Criteria

Smooth navigation and checkout experience.

Functional user registration and guest checkout.

Accurate order confirmation emails.

💼 Business Model

The site follows a direct-to-customer (D2C) e-commerce model, allowing users to purchase sweets directly from the platform.

🐞 Bugs

Any known issues and their resolutions are documented during development.

📰 Newsletter

Users can subscribe to a newsletter to receive updates about:

New sweet arrivals

Discounts and offers

Seasonal promotions

🚢 Deployment

The application is deployed on Heroku with:

PostgreSQL as the production database.

Gunicorn as the WSGI HTTP Server.

AWS S3 for static and media file storage.
