Developer: Sechaba Mothobi
Project: Sample code using Bootstrap Sass
Date: 13 November 2014
------------------------------------------------------------------------------------------------------------

Guidelines to read and adhere to:
--------------------------

•	CSS style guide (How we should write and format our CSS) https://github.com/styleguide/css
•	Using Bootstrap http://getbootstrap.com/components/
•	JavaScript guidelines http://taitems.github.io/Front-End-Development-Guidelines/#javascriptSection
•	Using Sass http://thesassway.com/
•	Loading multiple JavaScript files http://requirejs.org/


Development Process:
--------------------------

1.	Local Development
2.	Run unit tests
3.	Push to testing server
4.	If push back, start at step 1

Software and tools:
--------------------------

1.	Compiles SASS files
2.	External dependencies (Bootstrap, sass compass etc..)
3.	Live browser refreshing
4.	CSS, HTML and JS Linting with error notification
5.	Sublime editor with package control.
6.	SoureTree for git repository 


Methods:
--------------------------

•	CSS structure will be defined by SMACSS methods - http://smacss.com
•	Want to leverage some benefits of SASS preprocessing for our css. We will use separate .scss (SASS) files and folders to maintain our css code. We will stick to standard css output. This way we can leverage the benefits of variables in a themes file to define global styles. Such as colours, font-size, etc.
•	Support IE8 and above and will include Modernizr - http://modernizr.com - and HTML5Shiv - https://code.google.com/p/html5shiv to detect and support HTML5 features in older browsers
•	We will use and write HTML5 semantic markup and test to be standards compliant
•	Multiple Bootstrap Javascript files wil be using RequireJS is a JavaScript file and module loader. It is optimized for in-browser use, but it can be used in other JavaScript environments

Folder structure for dev:
--------------------------

see image:
src /assets/folderstructure.png

