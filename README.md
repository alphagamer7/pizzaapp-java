# JAV1001-Pizza-app
This is the solution for Final project of JAV-1001</br>

Athif Ahamed Mohamed Shaffy A00256229</br>

Shivam Sharma A00253431</br>

Shubham Dhamane A00257743</br>

Gurpreet Kaur A00252915</br>

<h1>Description:</h1>

<p>In our Pizza app, We customize pizza according to customer specifications and also record the previous orders as history orders. In addition to, we provide option for customers to select toppings such as Pepperoni, Bacon, Mushrooms, Tomatoes, Capsicum, etc. Moving towards, ordering section in which user have to fill some of their personal information as Name, Address, City, Zipcode. We allow users who have placed orders to delete orders as well  </p>


<h1>Data storage Consideration:</h1>
<p>We considered several options as follow</br>

SQLite db(https://developer.android.com/training/data-storage/sqlite)</br>
Consider

Firebase firestore (https://firebase.google.com/docs/firestore )</br>

We considered Firebase after Professor email that we could check firebase. We did an initial research on firebase. We created firebase project and added the google-services.json file and did initial CRUD operations, but later decided not to sicne we already did a significant portion via GSON. Branch wiht firebase R&D: https://github.com/alphagamer7/pizzaapp-java/tree/feature/add-firebase 

GSON solution (https://github.com/google/gson) </br>

At the end, after researching on each option, we went with GSON which helps serialization/deserialization and using
sharedPreferences for data persistance without too much issues with dependancies.</p>

<h1>Screenshots:</h1>


![image](https://user-images.githubusercontent.com/17358908/185530757-d519176b-59af-47c5-82bf-94396e962a09.png)
![S2](https://user-images.githubusercontent.com/106410851/185513741-afc92221-c0c5-47cd-9594-183213e5b42d.png)
![S3](https://user-images.githubusercontent.com/106410851/185513751-de97795b-2b99-4017-9f80-8c6353c1b800.png)
![image](https://user-images.githubusercontent.com/17358908/185530934-be15b15d-67d3-4763-a0c1-d7c2d71fcbcc.png)


