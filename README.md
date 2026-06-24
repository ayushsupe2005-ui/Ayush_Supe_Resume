# Ayush_Supe_Resume
This is my resume. I made it in HTML and CSS so I figured that it would be a good idea to share this online on github. 

This github repo has a very simple structure. Inside the resume folder, there are 2 documents: 
1. index.html: This is where the content and structure of the resume resides. 
2. style.css: This is where the different styles and formatting settings reside. 

To print the resume, just open the HTML document in a web browser and press ctrl + P. 

## The HTML document

### Basic Structure
The different sections of the resume are structured as follows:  
1. Header: This is where the the name and hyperlinks reside.
    1. Name: This is enclosed in `<h1>` tags.
    2. Links: enclosed in `<p id='links'></p>` and separated by | symbols. The links have the property `target="_blank"` so that they open in a new tab.
2. Education: This is where the GPA, University, and degree is found.
3. Certifications/Achievements: This is where any awards and certifications.
4. Experience: This is where any previous jobs or other forms of experience are found.
5. Projects: This is where any projects done previously can be found.
6. Technical skills: Any skills and strengths can be found here.

### `<head>`
inside the head tags, there are 3 main parts: 
1. Linking the css document:  
`<link rel="stylesheet" href="style.css">`  
2. Importing the font from fonts.google.com (Roboto):  
`<link rel="preconnect" href="https://fonts.googleapis.com">`  
`<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>`  
`<link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">`  
3. A title that is displayed in the browser tab:  
`<title>resume</title>`  

### `<body>`
The body uses the following tags: 
1. The `<h1>` tag is used for the name.
2. The `<h2>` tags are used for labeling the different sections in the resume.
3. The `<p>` tags are used for the content relating.
4. The `<ul>` and `<li>` tags are used to create unordered bulleted lists to describe content in the `<p>` tags.
5. The `<hr>` tags are used to separate the different sections. These are used directly after the `<h2>` tags.
6. The `<a>` tags are used for hyperlinks. 

## The CSS document

### The CSS document is structured as follows: 
1. Print Settings: These are settings that change how the resume looks when it is printed. 
2. Link Settings: These are settings that change how the links in the header section of the HTML document look.
3. Body Settings: These are the settings that change the overall style of all of the visible contents in the resume. 
4. Margin and Line Height Settings: These settings can be used to configure the line height and line spacing of `<hr>`, `<h1>`, `<h2>`, `<p>`, `<ul>`, `<li>` tags. 
5. Name Settings: These are settings that change how `<h1>` tags looks. 
6. Section Label Settings: These are settings that change how `<h2>` tags look. 
7. Paragraph Settings: These are settings that change how `<p>` tags look. 
8. List Settings: These are settings change how `<li>` tags look. 
