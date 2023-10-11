<p align="center" style="padding-top:20px">
 <img width="100px" src="images/logo-event-planner-pro.jpeg" align="center" alt="Event Planner Pro logo" />
 <h1 align="center">EventPlannerPro.net</h1>
</p>

<p align="center">
<img src="images/logo-event-planner-pro-with-stats.jpeg" alt="Event Planner Pro stats" style="margin: 25px auto; max-width: 830px" width="100%" height="" />
</p>

**How to clone and run the website locally**  

**Install Git, NODE, NPM and yarn if you don't them already**  

**Git clone via Terminal to a directory**  
`git clone git@github.com:pbpyrojust/loanpro-challnege.git`

##### In the directory you cloned the repo to: Install with NPM 
`npm install`
##### In the directory you cloned the repo to: Install with Yarn
`yarn`

**To start developing:**
**Either of these commands will boot up your local sever and should give you a URL of localhost:1313**
##### Develop with NPM 
`npm run start`
##### Develop with Yarn
`yarn start`

**To generate the site HTML:**
##### Build with NPM 
`npm run build`
##### Build with Yarn
`yarn build`

**npm run start** will run two commands parallel:  
`npx tailwindcss -i ./assets/css/main.css -o ./assets/css/style.css --watch`

Has paginated Categories and Tags. Markdown files will automatically convert images put into `/assets` folder to .webp images. 

## Image shortcodes for webp as well.
{{< imgc src="img-name.jpg" alt="Place alt text here." >}}

## Form
To use the form, visit [FormSubmit.Co](https://formsubmit.co/). Locate the contact form in "content/contact.md", and update the form action with the email address you want on this line: **action="https://formsubmit.co/your@email.com" method="POST"**