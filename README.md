# Razorpay-Tailwind

To setup tailwind css, run these commands
1. npm init -y // This initializes the directory as a NodeJs project
2. npm install -D tailwindess postess autoprefixer vite // installs required packages
3. npx tailwindess init -p
4. Create a css file "input.css", add it to your html and edit it with this content:
@tailwind base;
@tailwind components;
@tailwind utilities;
5. In your tailwind.config.js file replace content: [], with content: ["*"],
6. Add "start": vite" to your scripts in package.json
7. Run npm run start command to start a dev server

Razorpay Clone Website
This is a clone website for Razorpay, a popular online payments platform in India. The website is built using HTML and Tailwind CSS, a utility-first CSS framework that makes it easy to style and layout web pages.

Features
The website includes the following pages and features:

Home page with an overview of the services offered by Razorpay and a call-to-action button to sign up
Pricing page with a comparison table of different pricing plans and a sign-up form
Contact page with a form to submit inquiries or feedback
About page with information about the company and its mission
Footer section with links to social media profiles and legal pages
Responsive design that adapts to different screen sizes and devices
Getting Started
To run the website locally, you can follow these steps:

Clone the repository to your local machine: git clone https://github.com/sidgureja7803/Razorpay-Tailwind.git
Open the index.html file in your web browser
Modify the HTML and CSS files as needed to customize the website
