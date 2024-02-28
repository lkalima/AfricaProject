File system structure  

root/  
├── assets/ (images, icons, fonts, etc.)  
├── css/ (stylesheets)  
├── data/ (JSON data files)  
│   ├── country_profiles.json  
│   └── ... (other data files)  
├── js/ (JavaScript code)  
│   └── script.js  
├── pages/  
│   ├── about.html  
│   ├── blog/  
│   │   ├── index.html (blog landing page)  
│   │   ├── post-1.html (individual blog post)  
│   ├── contact.html (Contact form)  
│   ├── data-bank/  
│   │   ├── index.html (page introducing data bank)  
│   │   └── visualizations/ (visualization code & assets)  
│   ├── donate.html (Donation page)  
│   ├── encyclopedia/  
│   │   ├── index.html (encyclopedia landing page)  
│   │   ├── entries/  
│   │   │   ├── country-1.html (individual encyclopedia entry)  
│   │   └── ... (other entry folders)  
│   ├── help.html (Help and FAQ section)  
│   └── home.html (Homepage)  
├── templates/  
│   ├── base.html (base layout template for all pages)  
│   ├── content.html (reusable content template)  
│   └── ... (other reusable templates)  
├── articles/ (long-form content)  
│   └── article-1.html  
└── ... (other files, e.g., license, README.md)  



File System Structure (Simplified)  

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
├── data/ 
│   ├── cultural/
│   ├── demographics/
│   ├── historical/ 
│   └── ... (add other categories as needed)
├── js/ 
│   ├── app.js (Main application logic)
│   └── visualizations/ (Complex JavaScript visualization code)
├── pages/ 
│   ├── about.html 
│   ├── articles/  (Moved here for unique structures)
│   │   ├── article-1.html
│   │   └── ...
│   ├── blog/ 
│   │   ├── index.html 
│   │   └── posts/ 
│   ├── contact.html 
│   ├── data-bank/ 
│   │   ├── index.html 
│   │   └── visualizations/ (Simple, embedded visualizations) 
│   ├── donate.html 
│   ├── encyclopedia/ 
│   │   └── topics/ 
│   ├── help.html 
│   └── home.html 
├── templates/ 
│   ├── base.html 
│   ├── components/ 
│   └── ... 
└── ... (README.md, license, etc.) 