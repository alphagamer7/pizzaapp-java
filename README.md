# JAV1001-Pizza-app
This is the solution for Final project of JAV-1001</br>

Athif Ahamed Mohamed Shaffy A00256229</br>

Shivam Sharma A00253431</br>

Shubham Dhamane A00257743</br>

Gurpreet Kaur A00252915</br>

APK link- https://drive.google.com/file/d/17hogAyKone-oBRg1Vv1Bn-J5_9PwDxCR/view?usp=sharing

<h1>Description:</h1>

<p>In our Pizza order app, We customize pizza according to customer specifications and also record the previous orders as history orders. In addition to, we provide option for customers to select toppings such as Pepperoni, Bacon, Mushrooms, Tomatoes, Capsicum, etc. Moving towards, ordering section in which user have to fill some of their personal information as Name, Address, City, Zipcode. We allow users who have placed orders to delete orders as well  </p>

Cool features we added:
- Saved in GSON
- Added app icon and splash screen
- Researched and did firebase related on https://github.com/alphagamer7/pizzaapp-java/tree/feature/add-firebase 
- Colloborated through pull request way with team members, so all contributed.
- Hoping to deploy app to playstore. We got playstore console and saw the app preview screens and we need to publish a website with app privacy in order to release app.

<h1>Data storage Consideration:</h1>
<p>We considered several options as follow</br>

- SQLite db(https://developer.android.com/training/data-storage/sqlite)</br>

- Firebase firestore (https://firebase.google.com/docs/firestore )</br>
We considered Firebase after Professor email that we could check firebase. We did an initial research on firebase. We created firebase project and added the google-services.json file and did initial CRUD operations, but later decided not to sicne we already did a significant portion via GSON. 
Branch with firebase R&D: https://github.com/alphagamer7/pizzaapp-java/tree/feature/add-firebase 

- GSON solution (https://github.com/google/gson) </br>
Simple solution to save in shared preference as JSON and load to java based arraylist.


At the end, after researching on each option, we went with GSON which helps serialization/deserialization and using
sharedPreferences for data persistance without too much issues with dependancies.</p>


<h1>Screenshots:</h1>

![Screenshot_20220819_081128](https://user-images.githubusercontent.com/17358908/185531760-96764c7f-96af-4efe-8d2d-9bc7f3408547.png)
![Screenshot_20220819_081142](https://user-images.githubusercontent.com/17358908/185531733-23148ab9-5646-45c1-9abf-806a5e47567e.png)
![S2](https://user-images.githubusercontent.com/106410851/185513741-afc92221-c0c5-47cd-9594-183213e5b42d.png)
![S3](https://user-images.githubusercontent.com/106410851/185513751-de97795b-2b99-4017-9f80-8c6353c1b800.png)



