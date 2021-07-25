# Python Live Project

## Introduction:
I was able to gain real-world experience during the Live Project at The Tech Academy. I worked on a Basic MVC Web Application of my choosing, utilizing HTML/CSS mark-up/styling languages, Django/Python programming languages, sqlite and database integration, and agile methodologies. My Web Application was part of a larger project that contained other similar projects that utilized Python and Django. It was a two week sprint, and during that time I was able to complete four stories and participate in daily standups - including a code retrospective. Our team used Azure Devops for the project, Pycharm as an IDE, and Discord for communication. Thanks to the Python final project, I can confidently navigate Python/Django with Pycharm and I fully understand the workflow for clean Version Control. I can create branches, update the local master branch, push code, create pull requests, resolve merge conflicts, and so much more. This README.md repository includes Project layout seperated into stories with code and picture snippets.

## Project Layout

![Base_MVC_App](https://user-images.githubusercontent.com/79550661/126885089-c419bcec-971b-4c44-9529-e3a433490f50.jpg)

## Project Story Table of Contents
1. Create a new app for the project, named appropriately for what you are tracking, and get it to display a home page with basic content.
2. Create a model for the collection item you will be tracking and add the ability to create a new item.
3. Display information from the database in a page.
4. Create a details page that will show the details of any single item from within the database.


## 1. Creating My Application:
1) Created a new app using manage.py startapp.
2) Created a base and home templates in a new template folder.

![image](https://user-images.githubusercontent.com/79550661/126885417-1915e37e-deb8-40a6-b2c1-79937ba8544c.png)
![image](https://user-images.githubusercontent.com/79550661/126885429-a30068bd-8943-4278-bb24-1c05b6f676ad.png)

3) Added a function to views to render the home page.

![image](https://user-images.githubusercontent.com/79550661/126885382-555f5625-12a1-4fcd-8f5c-b9c855b9ca59.png)

4) Registered urls with MainApp and create urls.py for my app and homepage.

![image](https://user-images.githubusercontent.com/79550661/126885397-cdf4969b-df64-4332-8848-b80a9c7b13fc.png)


5) Linked the app's home page to the project's home page by adding an image link on the main projects home page.
6) Added styling to application base HTML and home.

## Final Story Result:
![finalprojectpicture](https://user-images.githubusercontent.com/79550661/126885284-e83d1fda-51a1-4961-bf1e-af569049a9a4.jpg)


## 2. Creating My Model:
1) Created a model and added a database migration, as well as created categories to track for database objects. Also created an objects manager for accessing the database.
2) Created a model form that included any inputs the user needs to make.

![image](https://user-images.githubusercontent.com/79550661/126885455-977dc6db-218f-4568-b269-d0f8f641f236.png)


3) Added a template to the app's folder for creating a new item.

![image](https://user-images.githubusercontent.com/79550661/126885467-eac698fa-2c9f-42c6-86ef-0348de47ae6a.png)
![image](https://user-images.githubusercontent.com/79550661/126885473-cc302a6e-061c-4922-932f-f99a9ad05dfb.png)

4) Added a views function that renders the create page and utilizes the model form to save the collection item to the database.

![image](https://user-images.githubusercontent.com/79550661/126885481-6b2e28bf-ed1d-4734-8894-caebc6b7c39c.png)

5) Create a forms file to store user input information when entered into forms.

![image](https://user-images.githubusercontent.com/79550661/126885655-b2bfa142-68d3-4d4d-bb02-2db66b379dbc.png)


## Final Story Result:
![createuser](https://user-images.githubusercontent.com/79550661/126885298-75f9f45c-5af6-4470-abbf-1b8b26efcb04.jpg)
![addproduct](https://user-images.githubusercontent.com/79550661/126885299-8b7f42b2-b322-40a2-8fe5-045d74ca233a.jpg)


## 3. Display db(database) information:
1) Created a new HTML page that linked from the home page.

![image](https://user-images.githubusercontent.com/79550661/126885559-8aa2c963-fa15-432e-a0ba-992d6baf06f3.png)

2) Added in a function that gets all the items from the database and sends them to the created template.

![image](https://user-images.githubusercontent.com/79550661/126885546-00849775-1064-4885-9cf4-942c7ba13a36.png)

3) Display a list of items from the database, with some or all of the fields for that item displayed with labels/headers. 

## Final Story Result:
![databasedisplay](https://user-images.githubusercontent.com/79550661/126885304-7cae9d7e-6c0b-4b8a-add7-5362ab29fd57.jpg)


## 4. Created a Details Page:
1) Added a details template to the template folder and registered the URL pattern.

![image](https://user-images.githubusercontent.com/79550661/126885605-87e6437f-90c3-4b7d-bad0-a9562bbb50ea.png)
![image](https://user-images.githubusercontent.com/79550661/126885609-6c0dd74d-9ad4-4721-a3b6-a9cb4836afad.png)

2) Created a views function that will find a single item from the database and send it to the created template.

![image](https://user-images.githubusercontent.com/79550661/126885581-f379dbcf-3233-46e6-8fc7-31cd0a853e58.png)

3) Added in a link for each item on the display all items page that will direct to the details page for that item.
4) Display all the details of the item on the details page.

## Final Story Result:
![itemlist](https://user-images.githubusercontent.com/79550661/126885310-a1365126-a13c-44e6-a159-4ceddd4aa790.jpg)
![itemlistdisplay](https://user-images.githubusercontent.com/79550661/126885311-4c5f772f-e219-4fb0-b2e0-5767df561786.jpg)



## Agile Methodologies & Ending Notes:
We used Agile and Scrum as our method of development. I participated in a sprint-planning meeting, daily stand-ups, and a code-retrospective to discuss what worked well and what didn't. During the daily meetings, I had to mention what I worked on the day prior, what we were going to work on the day of, and what roadblocks we were facing. It was a great way to gain soft skills. The meetings held us accountable and even though for most of the Live Project I worked by myself, I still was able to complete the tasks needed for completion. It was also an opportunity to discuss things we were struggling with, which the instructors were great about reaching out and walking me through any roadblocks. My major take-aways from this project were:

1. Be patient yet persistent. You will figure it out as long as you're determined.
2. Even though you work on stories alone you really are apart of a team. Communicate with one another.
3. It's OK to ask for help, it shows that you care. But do your research, you might surprise yourself and figure a lot out on your own.
4. Code is time-consuming but extremely rewarding. The more you code and practice the more efficient you'll become. 
5. This career was 100% meant for me. 
