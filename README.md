<p align="center" style="padding-top:20px">
 <img width="100px" src="images/logo-event-planner-pro.jpg" align="center" alt="Event Planner Pro logo" />
 <h1 align="center">EventPlannerPro.net</h1>
 <p align="center">TailBliss is an opinionated Hugo Starter with Tailwind CSS 3.2 and Alpine.js with light/dark modes.</p>
</p>

<p align="center">
<img src="" alt="Event Planner Pro stats" style="margin: 25px auto; max-width: 830px" width="100%" height="" />
</p>

**Install to VS Code with:**  
`git clone git@github.com:pbpyrojust/loanpro-challnege.git`

##### Install with NPM 
`npm install`
##### Install with Yarn
`yarn`

**To start developing:**
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

<a href="https://www.buymeacoffee.com/nusserstudios" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-blue.png" alt="Buy Me A Coffee" height="41" width="174"></a>

## Form
To use the form, visit [FormSubmit.Co](https://formsubmit.co/). Locate the contact form in "content/contact.md", and update the form action with the email address you want on this line: **action="https://formsubmit.co/your@email.com" method="POST"**