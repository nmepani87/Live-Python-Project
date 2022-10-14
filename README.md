<h1>Live Project (Python)</h1>

<h3>Introduction</h3>

<p>During a bootcamp that I was doing with <a href="https://www.learncodinganywhere.com/">The Tech Academy</a>, for two weeks of it, I was involved in a working on a web application with other students and supervisors. The page contained apps, based on various topics, and would show CRUD operations. It was a great opportunity to learn how to make functions dependent on certain requirements, fixing bugs when things didn't not work straight away and learning to use Django. We were given the chance to focus on both front and back end work, which helped improve past skills that were touched upon already, ie. HTML, CSS and Javascript.</p>

<h3>CRUD Functionality</h3>

<p>CRUD is an acronym that stands for Create, Read, Update and Delete. These are the four basic functions that a model should have. On this project we were each tasked with building a model that contained those 4 functions and more.</p>

<h3>Create</h3>

<li><a href="./Media/Model_create.png">Create Code</li>
<li><a href="./Media/Model_model.png">Model Code</li>
<li><a href="./Media/Model_forms.png">Forms Code</li><br>
  
<p>The above image shows the code that I created that allows a user to be able to input an entry into the database and saves it. The model sections shows the fields, the types they are given and limitations as to what is allow to be entered. Through the forms I was able to use widgets for certain fields, the placeholder being an important one to show the user how to enter the time and date the correct way to allow the form to be valid. I've also shown the use the ModelForm and through the meta class how I renamed a field as needed.</p>
  
![Create](https://user-images.githubusercontent.com/108291876/195746518-3a7f188a-1a71-4a7b-bdd8-62592aa34fff.gif)

<h3>Read</h3>

<li><a href="./Media/Model_views2.png">Read Code</li><br>

<p>Through the creation of the two functions shown, the user it able to view a page that contain a list of all the entries added to the SQLite database and, if wanted, by clicking on an individual entry, via the use of a primary key, they can view all the details of that specific entry.</p>

<h3>Update/Delete</h3>

<li><a href="./Media/Model_update_delete.png">Update/Delete Code</li><br>

<p>Shown in the code is how a user, once on a specific entry, can choose to either delete or update that entry. Embedded into it, with the use of JavaScript, is a pop up message that shows to the user the requested action was successful.</p>

![DeleteFunction](https://user-images.githubusercontent.com/108291876/195746873-a04eeeae-99ae-4983-a5d4-69a2a0e67fae.gif)

<h3>Web Scrapping/API</h3>
  
<li><a href="./Media/API_BS_01.png">API Code</li>
<li><a href="./Media/API_BS_02.png">Web Scrapping Code</li><br>

<p>Through the use of an API I was able to provide a fast way for the user to know the latest currency exchange rates for the GBP. This was done by parsing the API information through JSON and retrieved only certain information as wanted. Each currency in the html page was easily seperated by using block tags to show each individual from the dictionary.
By using web scrapping, I was easily able to render a page from another by only targetting a specific tag in its html code. Then due to the originally page not wrapping certain information within certain div tags, I took the ones needed by using their index point and putting that into a dictionary. The dictionary is then show in a page another with some other text I put in.</p>

<img width="1387" alt="API" src="https://user-images.githubusercontent.com/108291876/195748584-b7ef257c-cf7e-47a0-8342-ca5cd5c7fee3.png">

  
