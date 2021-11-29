# How to run SASS
=================
Sass will take your preprocessed file and save it as a normal CSS file that you can use in your website.

# Steps to run .scss file and get .css
======================================

Step 1:
======= 
* Install Sass using the options below :

If you use Node.js, you can install Sass using npm by running -
    
    npm install -g sass

Step 2: 
=======
* To be sure sass is installed correctly run,
    sass --version 

Step 3: 
=======
* Once Sass is installed, you can compile your Sass to CSS using the sass command. You'll need to tell Sass which file to build from, and where to output CSS to. For this website use following command -

    sass index.scss index.css

Step 4: 
=======
Now css file is generated and you can view index.html with full styles!!

## Note:
If you are using VS. code, you can also install ' Live sass compiler ' in the extension. After installation at the bottom you will see an icon written ' watch sass '. Just click on it and compiler will convert your sass file into css and also update your work whenever you will save any changes.