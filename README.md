# Lab 01 Web Technologies

**Natalia Espínola**

### Activity

#### 3.
###### Describe the structure of the document
The structure follows the following hierarchy:
- <html>
  - <header>
  - </header>
  - <body>
    - <center>
      - <table>
	- <tbody>
	  - <tr>
	  - </tr>
	  - <tr>
	  - </tr>
	  - <tr>
	    - <td>
	      - <table>
		- <tbody>
		  - **<tr>**
		    - <td>
		      - <span>
		      - <span>
		    - </td>
		    - <td>
		      - <center>
			- <a>
			- </a>
		      - </center>
		    - </td>
		    - <td>
		      - <a>
		      - </a>
		      - <span>
			- <a>
			- </a>
		      -</span>
		    - </td>
		  - **</tr>**
		  - **<tr>**
		    - <td>
		      - <span>
		      - <span>
		    - </td>
		    - <td>
		      - <center>
			- <a>
			- </a>
		      - </center>
		    - </td>
		    - <td>
		      - <a>
		      - </a>
		      - <span>
			- <a>
			- </a>
		      -</span>
		    - </td>
		  - **</tr>**
		  ...
		- <tbody>
	      - </table>
	    - </td>
	  - </tr>
	- </tbody>
      - </table>
    - </center>
  - </body>
- </html>

It can be seen that each element is closed with the same name by adding a /.
Each element is enclosed by <>.
The function of each html element found on the website is as follows:
- html: Represents the root of an HTML document. All other elements must be within it.
- header: Defines the header of a page or section.
- body: Represents the main content of an HTML document. There is only one <body> element in a document.
- center: is used to center-align text.
- table: Represents data with more than one dimension.
- tbody: Represents the block of rows that describe the specific data of a table.
- tr: Represents a row of cells in a table.
- td: Represents a data cell in a table.
- span: Represents text without a specific meaning.
- a: Represents a hyperlink, linking to another resource.

###### How is the list of news articles structured with HTML?
Each new article is inside a <tr> element, which are inside a <tbody> element and this is inside a <table>, as shown in the previous hierarchy.

####4.
###### Briefly describe what you see in files with names starting with hn.js and news.css.
Inside the hn.js file I see only functions. In news.css I see elements to which a style is selected.

###### How are these files different? What is their purpose?
Inside news.css you can notice that there are parameters that define style for the html elements. CSS is the language used to describe the presentation of HTML documents. The hn.js file is JavaScript code from the website. This file contains code routines that are executed on the web page when called. Each function performs a particular task, for example, the function vote (ev, the, how) {} handles the logic of the votes.

####5.
###### How many requests has it taken for the browser to download the Hacker News main page?
Seven request.

###### What are the HTTP request methods in each case?
The cases are:

- news.ycombinator.com
- news.css?FipHmofufc0acGUN2
- y18.gif
- s.gif
- hn.js?FipHmofufc0acGUN2LQH
- grayarrow.gif
- favicon.ico

For each case the request method is GET and they have a status code of 200 (OK), but five of them have the message: (from disk cache), the other two are news.ycombinator.com and favicon.ico

###### Check out the HTTP response headers and find out what kind of web server is used for this website.
The web server is nginx.
