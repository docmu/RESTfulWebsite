# RESTfulWebsite
## Description 
This website was created using Node.js and Express. Data persistence is supported by MongoDB Atlas. It utilizes the principles of 
RESTful routing to render pages, add blogs, delete blogs, and edit blogs. A RESTful route is a route that provides mapping between HTTP verbs (get, post, put, delete, patch) 
to controller CRUD actions (create, read, update, delete). Semantic UI is used for css styling. An NPM package called Nodemailer is also used 
for sending emails through the contact page. This website is deployed through Heroku.
#### Live website: https://blooming-retreat-23153.herokuapp.com/blogs

## Code Samples
#### Mongoose Schema for Blogs  
![Alt Text](https://github.com/docmu/RESTfulWebsite/blob/master/Screenshot%20(82).png)

#### INDEX ROUTE- display all blogs  
![Alt Text](https://github.com/docmu/RESTfulWebsite/blob/master/Screenshot%20(70).png)

#### NEW ROUTE- displays a form for a new blog entry  
#### CREATE ROUTE- creates new blog post; utilizes express-sanitizer 
![Alt Text](https://github.com/docmu/RESTfulWebsite/blob/master/Screenshot%20(83).png)

#### SHOW ROUTE- displays a specific blog post  
![Alt Text](https://github.com/docmu/RESTfulWebsite/blob/master/Screenshot%20(72).png)

#### EDIT ROUTE- displays edit form for a specific blog post  
#### UPDATE ROUTE- updates a specific blog post; utilizes express-sanitizer  
![Alt Text](https://github.com/docmu/RESTfulWebsite/blob/master/Screenshot%20(84).png)

#### DESTROY ROUTE- deletes a specific blog post  
![Alt Text](https://github.com/docmu/RESTfulWebsite/blob/master/Screenshot%20(74).png)

#### Implementation of Nodemailer
![Alt Text](https://github.com/docmu/RESTfulWebsite/blob/master/Screenshot%20(131)_LI.jpg)
