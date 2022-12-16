# Team_Raccoon_qr_gen

## Project Catalogue

- [Live link](#live-link)
- [Project Scope](#project-scope)
- [Problem Statement](#problem-statement)
  - [Modalities](#modalities)
  - [Niche](#niche)
  - [Links](#links)
- [Set Up and Installation](#set-up-and-installation)
- [Technologies Used](#technologies-used)

## Live link
https://zuri-training.github.io/Team_Raccoon_qr_gen/index.html

## Project Scope

           QR Code- Quick response Code

A QR code generator is software that stores data into a barcode (for example a text or a website address), barcodes are machine-readable codes with black and white squares, it is a platform that allows users generate QR code that specifically does something when scanned.

It is a niche tool that is used to generate different types of QR Codes. Depending on your purpose, you can use QR generator to create QR Codes to open a website, view a PDF file, listen to music, watch Youtube videos, store image files, connect to a WiFi network, and much more.

## Problem Statement

Maybe in your marketing and advertising campaigns you want to keep track of your products, how will you go about it?
QR codes are frequently used to track information about products in a supply chain and – because many smartphones have built-in QR readers – they are often used in marketing and advertising campaigns. More recently, they have played a key role in helping to trace coronavirus exposure and slow the spread of the virus.

Imagine trying to catch a train that will depart very soon, when you bought the ticket you were given a ticket ID to input before you can move into the train, maybe you met a queue before it will come to your turn to input you ticket ID the train might have moved. To tackle this issue we decide to create a platform that can generate downloadable barcodes which will make the process faster and more convienent for users.

### Modalities

#### User: Unauthenticated

User: Unauthenticated

1. Visit the platform to view basic information about it- adetail landing page.
2. View and Interact with the documentation - follow us on our social media handles, like documenation etc.
3. Register to view more details - Sign up to access more details.
4. No access to use until registered - Restriction for some special features untill user register.

#### User: Authenticated

1. Full access to the platform - get full access to platform
2. Allow setting on what should happen when qr is scanned - give at least 2 options
3. Allow user to download (allow png, jped and pdf download format), or share code by email or social media
4. Allow user save data and come back to it

### Niche

Advertising

### Links

<a href="#">Figma</a>

<a href="https://docs.google.com/document/d/1W27R8KDghq6MnFbq3X6fyIz-tDT19NLckybMwjhEwX8/edit?usp=sharing">Google Docs</a>

## Set Up and Installation

Clone the repository into your local machine, to install this project, using the following command;

                git clone https://github.com/zuri-training/Team_Raccoon_qr_gen.git

After cloning, change directory into the project folder, using the command below;

                cd <project-directory>

Create a virtual environment (unarguably a very useful practice for new projects) to install the required dependencies, using;

                virtualenv <virtual-environment-name>

Activate the virtual environment you created using;

    Linux/OS:

                $ source <virtual-environment-name>/Scripts/activate

    Windows OS:

                C:\Users\Name\<project-directory> path\to\<virtual-environment-name>\Scripts\activate

Install the required dependencies using;

                pip install -r requirements.txt

Prepare the models as tables to be migrated to the database using;

                python manage.py makemigrations

Migrate the tables using;

                python manage.py migrate

Then run your server using;

                  python manage.py runserver

## Technologies Used

### Design - Figma <a href="https://www.figma.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/figma-colored.svg" width="28" height="20"  alt="Python" /></a>

### Frontend - HTML5 <a href="https://developer.mozilla.org/en-US/docs/Glossary/HTML5" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/html5-colored.svg" width="28" height="20" alt="HTML5" /></a> CSS3 <a href="https://www.w3.org/TR/CSS/#css" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/css3-colored.svg" width="28" height="20"  alt="CSS3" /></a> Javascript <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/javascript-colored.svg" width="28" height="20" alt="Javascript" /></a>

### Backend - Stack: Python <a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" width="28" height="20" alt="Python" /></a>

### Framework - Django <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/django-colored-dark.svg" width="28" height="20"  alt="Django" /></a>

### Database - SQLite3 <a href="https://www.sqlite.org/index.html" target="_blank" rel="noreferrer"></a>
