File system structure  
LI E File System Structure (Simplified)  

assets: Images, icons, fonts for your website.  
css: Stylesheets for website appearance.  
data: JSON files containing your project's data.  
js: JavaScript code for website interactivity.  
pages: Individual HTML pages for different sections:   
* about.html    
* blog/ (blog content)  
* contact.html  
* data-bank/ (data & visualizations)  
* donate.html  
* encyclopedia/ (entries)  
* help.html  
* home.html  
templates: Reusable templates for page layout and content.  
articles: Longer-form website content.  





New File System
root/ 
├── assets/ 
│   ├── fonts/
│   ├── icons/
│   ├── images/
│   │   ├── encyclopedia/
│   │   └── visualizations/
│   └── videos/ 
├── css/ 
|   └── styles.css
├── data/ 
│   ├── cultural/
│   ├── demographics/
│   ├── historical/ 
│   └── ... (add other categories as needed)
├── js/ 
│   ├── app.js (Main application logic)
│   └── visualizations/ (Complex JavaScript visualization code?)
├── pages/ 
│   ├── about.html 
│   ├── contact.html 
│   ├── data-bank/ 
│   │   ├── index.html 
│   │   └── visualizations/ (Simple, embedded visualizations) 
│   ├── donate.html 
│   ├── encyclopedia/
│   │   ├── index.html
│   │   └── topics/
│   │       ├── topic-1/
│   │       │   ├── article-1.html
│   │       │   └── ...
│   │       └── ...
│   ├── help.html 
│   └── home.html 
├── templates/ 
│   ├── base.html 
│   ├── components/ 
│   └── ... 
└── ... (README.md, license, etc.) 



Phase 2
root/
├── src/
│   ├── assets/
│   │   ├── fonts/
│   │   ├── icons/
│   │   ├── images/
│   │   │   ├── encyclopedia/
│   │   │   └── visualizations/
│   │   └── videos/
│   ├── data/
│   │   ├── cultural/
│   │   ├── demographics/
│   │   ├── historical/
│   │   └── ... (add other categories as needed)
│   ├── js/
│   │   ├── app.js
│   │   ├── components/
│   │   ├── routes.js (Client-side routing)
│   │   └── visualizations/
│   ├── pages/
│   │   ├── about.jsx
│   │   ├── contact.jsx
│   │   ├── data-bank/
│   │   │   ├── index.jsx
│   │   │   └── visualizations/
│   │   ├── donate.jsx
│   │   ├── encyclopedia/
│   │   │   ├── index.jsx
│   │   │   └── topics/
│   │   ├── help.jsx
│   │   └── home.jsx
│   ├── styles/
│   │   ├── base.scss
│   │   ├── components/
│   │   ├── pages/
│   │   └── utilities.scss
│   ├── templates/
│   │   ├── base.html
│   │   ├── components/
│   │   └── ...
│   └── utils/
│       ├── database.js (Database management)
│       └── ... (Other utility functions)
├── dist/ (Output directory for production build)
├── scripts/ (Build scripts, config files, etc.)
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js (Server entry point)
├── .env (Environment variables)
├── .gitignore
├── package.json
├── README.md
└── ... (Other project files)