# Class-Notes


Class 4/18/2022
--------------------------------------------------------------
js is single thread and synchronous. 

--------------------------------------------------------------
How we can make js as multithread? 
Ans: we can acheive it via childprocess and cluster.

--------------------------------------------------------------
Differtences between (childprocess, cluster and worker threads)
which one is best?

---------------------------------------------------------------
Authentication and verification in js

---------------------------------------------------------------
**Types of modules:**
1) **Built in**: trranspiler, etc
2) **third party**: indtall via npm/yarn (react/redux)
3) **custom module**: user created modules



---------------------------------------------------------------
Types of Dependencies:
dev Dependenies
Dependenies

**==========================================================================================**


Class 4/23/2022
---------------------------------------------------------------
**File System**

app.use("style",express.static('public/css'));


---------------------------------------------------------------
**Template Engines:** 
  1) Jade (Now it know as pug)
  2) ejs/egs 
//ejs start
  #esj
  Egample:
  Step-1: Install the engin
  Step-2: Use engion
  
   create views (
   
   ![image](https://user-images.githubusercontent.com/67856787/164886342-90e97bc4-6a5c-41d9-92f7-ae28d7270176.png)
   )
   
  Step-3: 
  
  ![image](https://user-images.githubusercontent.com/67856787/164886205-fa2c7241-aa58-4cf3-ad4f-37afa0950c18.png)

  Step-4:
  * change the extention of .html file as ejs/pug (
  
  ![image](https://user-images.githubusercontent.com/67856787/164886312-6e9238e2-1a4e-4bbf-bdc3-220704b93edf.png)
  
  )
  * now go to file and write the fucntion as (
  
  ![image](https://user-images.githubusercontent.com/67856787/164886293-9a15f070-be6d-413b-b9eb-d4cac723c8a2.png)
  
  ) 



**Dynamic Rendering on server side:**
  on server side: (
  
  ![image](https://user-images.githubusercontent.com/67856787/164886444-5ff105de-2215-466d-94e2-5f3ec840d07c.png)
  
  )
  
  On Client side To Print user (=means print): (
  
  ![image](https://user-images.githubusercontent.com/67856787/164886423-802b28ef-0771-42c3-b525-56378fe5a34d.png)
  
  )
  
  
**Multiple rendereing includign array**
On server side: (

![image](https://user-images.githubusercontent.com/67856787/164886628-a2197295-9e65-4b64-aff4-af98aecbc421.png)

)

On Client Side 1st Way: (

![image](https://user-images.githubusercontent.com/67856787/164886733-2b8d2207-acb7-43a2-b572-f6bb0be6182f.png)

)

On Client Side 2nd Way: (

![image](https://user-images.githubusercontent.com/67856787/164886935-855ecf0b-92ff-4956-aae8-b7bc03a190f3.png)

)

---------------------------------------------------------------
**Single Nav Page**

**Step-1**: Create new folder layouts and create a file for your layout here we are creating navbar.ejs

![image](https://user-images.githubusercontent.com/67856787/164888247-8cc92314-da70-42bf-bd4f-5c9710f10266.png)

**Step-2**: Use the created layout

![image](https://user-images.githubusercontent.com/67856787/164888275-3b709bd2-ff5b-4a98-995d-b40c3103f9c9.png)

//ejs work end





---------------------------------------------------------------

#pug start
1) install pug
2) create view directory in src
3) create file with .pug extention

![image](https://user-images.githubusercontent.com/67856787/164888437-02bcd979-55ce-4093-8ade-0201581d7905.png)


Server Side:

![image](https://user-images.githubusercontent.com/67856787/164888504-e26c9c24-a13a-48f0-a5a3-6f5766c3c877.png)


Clet Side:

![image](https://user-images.githubusercontent.com/67856787/164888551-ed95c1c3-a9b1-4fcc-8971-e672c6ef70bd.png)




for loop
1) Clients Side:

![image](https://user-images.githubusercontent.com/67856787/164888613-d356f942-f22d-4501-89d6-a3b56e4e4170.png)

2) Server Side:

![image](https://user-images.githubusercontent.com/67856787/164888661-9cfc7752-be7f-4775-bfa5-39f783cfdc72.png)




Other Examples:

![image](https://user-images.githubusercontent.com/67856787/164888687-7f0ec446-e273-4593-9c17-b6b7e712d14e.png)


**Reacp:**

1) **Difference between EJS: <%= versus <%- (https://stackoverflow.com/questions/11024840/ejs-versus)**
2) **Difference Between Ejs and Pug**
3) Ejs can compile asn use as html




---------------------------------------------------------------
**4/25/2022**
**mongoDB**


Step 1: Create Database 
Step 2: Create Collection

(
![image](https://user-images.githubusercontent.com/67856787/165073578-d4dbe4d3-2d70-47b2-958a-18c2b1626269.png)
)

Step 3: Insert Record/document in MongoDB

![image](https://user-images.githubusercontent.com/67856787/165074515-d5e96a1d-8968-4e15-a683-35ece996dfd5.png)


Find a record 

![image](https://user-images.githubusercontent.com/67856787/165074628-dd84a8ca-fb21-4dac-a11d-8765d2591c7a.png)


Insert Multiple document

![image](https://user-images.githubusercontent.com/67856787/165074798-65d8ff96-204f-44c6-a3f7-af902bcd12b8.png)


find and display in organized way

![image](https://user-images.githubusercontent.com/67856787/165074957-6ef58ea4-ffb9-4802-854e-136168f5603d.png)


insert and order

![image](https://user-images.githubusercontent.com/67856787/165075363-2e9dc5ba-c160-41fb-843c-5c910cb29f44.png)


find and findOne

![image](https://user-images.githubusercontent.com/67856787/165075466-3d4c8bbc-86d3-457e-a5d1-709fcee91c2e.png)


Find on atribute base 

![image](https://user-images.githubusercontent.com/67856787/165075684-cf35d5ce-3a5f-4de6-b970-e01c7ebf1e87.png)

update

![image](https://user-images.githubusercontent.com/67856787/165075980-c7e81898-af58-4346-b33e-5e930264bbed.png)

**Note this commond relace the previouse whole data.**

Update on mentioned data of the object

![image](https://user-images.githubusercontent.com/67856787/165076337-a4a9986b-4d39-4f6e-84d9-c389c0d02fb7.png)


Logical Operators

grater than or equal to:

![image](https://user-images.githubusercontent.com/67856787/165076684-0ab8cb4a-31f8-409f-b7fa-fa160c438dab.png)

less than:

![image](https://user-images.githubusercontent.com/67856787/165076723-e4f33783-f77e-4545-80ce-4833ebc22f30.png)



















---------------------------------------------------------------
