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







---------------------------------------------------------------

---------------------------------------------------------------
