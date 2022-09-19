<h1>Live Project (Python)</h1>

<h3>Introduction</h3>

<p>During a bootcamp that I was doing with <a href="https://www.learncodinganywhere.com/">The Tech Academy</a>, for two weeks of it, I was involved in a working on a web application with other students and supervisors. The page contained apps, based on various topics, and would show CRUD operations. It was a great opportunity to learn how to make functions dependent on certain requirements, fixing bugs when things didn't not work straight away and learning to use Django. We were given the chance to focus on both front and back end work, which helped improve past skills that were touched upon already, ie. HTML, CSS and Javascript.</p>

<h3>CRUD Functionality</h3>

<p>CRUD is an acronym that stands for Create, Read, Update and Delete. These are the four basic functions that a model should have. On this project we were each tasked with building a model that contained those 4 functions and more.</p>

<h3><li>Create</li></h3>

<img width="689" alt="Model_create" src="https://user-images.githubusercontent.com/108291876/191062992-83c4941b-a6ee-4262-9d07-43e226f0c489.png">

<img width="909" alt="Model_model" src="https://user-images.githubusercontent.com/108291876/191065051-2e98940e-c470-4102-b608-9c678fa4d850.png">

<img width="976" alt="Model_forms" src="https://user-images.githubusercontent.com/108291876/191066555-64f741af-e5ff-4af0-bb0a-58b2fd4f5779.png">

<p>The above image shows the code that I created that allows a user to be able to input an entry into the database and saves it. The model sections shows the fields, the types they are given and limitations as to what is allow to be entered. Through the forms I was able to use widgets for certain fields, the placeholder being an important one to show the user how to enter the time and date the correct way to allow the form to be valid. I've also shown the use the ModelForm and through the meta class how I renamed a field as needed. 

<h3><li>Read</li></h3>

<img width="692" alt="Model_views2" src="https://user-images.githubusercontent.com/108291876/191067603-e4a886f4-cde6-45ab-8484-f9ad7d2e1352.png">

Through he creation of the two functions shown, the user it able to view a page that contain a list of all the entries added to the SQLite database and, if wanted, by clicking on an individual entry they can view all the details of that specific entry.
