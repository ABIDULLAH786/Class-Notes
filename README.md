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
**5/15/2022**
**mongoDB**

Model Creation:
![image](https://user-images.githubusercontent.com/67856787/168421934-2657a1db-0907-4ade-af5e-db1d6a8ee5a4.png)


![image](https://user-images.githubusercontent.com/67856787/168421971-2888d2f0-3d14-41d7-8954-cda90b2c584a.png)


![image](https://user-images.githubusercontent.com/67856787/168422607-b2d0e393-f1a1-46ae-ba83-c251967c4012.png)


Body Parser

![image](https://user-images.githubusercontent.com/67856787/168422752-8f41e863-34fd-4364-b5a5-1142f63e5280.png)


![image](https://user-images.githubusercontent.com/67856787/168422950-cf7b4240-7205-4ec5-80fe-f78b949b0016.png)


![image](https://user-images.githubusercontent.com/67856787/168422961-422d686f-ea16-45fe-9ea7-49393dd3c872.png)



MiddleWares


![image](https://user-images.githubusercontent.com/67856787/168585224-92604b22-5d5f-4cd3-b5c0-9739c9c3adcb.png)



![image](https://user-images.githubusercontent.com/67856787/168594503-7ef76a90-707d-4fce-999a-7da79b56bbb8.png)


# Class-Notes After 2nd Mid

**User Authentication**

![image](https://user-images.githubusercontent.com/67856787/171993868-acb9dbb0-3c96-44ba-9ddf-1c19f4985053.png)


![image](https://user-images.githubusercontent.com/67856787/171994092-b7613f06-8cf4-4c97-86cb-6759c09f70ce.png)


![image](https://user-images.githubusercontent.com/67856787/171994194-541d07c3-f255-497e-a6c1-3e71a02f47c6.png)



**Session** 

![image](https://user-images.githubusercontent.com/67856787/171994294-b34fd2cb-7034-412e-8fb1-61b8074ca052.png)


Authenticat and verify via session

![image](https://user-images.githubusercontent.com/67856787/171994563-3d15471c-f64b-4484-919a-ebc195f22c32.png)


![image](https://user-images.githubusercontent.com/67856787/171994740-8b254634-0445-4248-a10f-1f5486517501.png)

Login Authentication 


![image](https://user-images.githubusercontent.com/67856787/171994967-d652bd38-5f7a-4ea4-938d-4a75ea2dc4f1.png)


![image](https://user-images.githubusercontent.com/67856787/171994978-c18d1f46-08fd-4188-8d88-b06b9be8effd.png)





**Logout and Login**

![image](https://user-images.githubusercontent.com/67856787/171995911-f0866870-660e-4328-9e3a-2a64892eaa5b.png)


![image](https://user-images.githubusercontent.com/67856787/171996131-a3ca2ddb-3380-42ef-b41b-29e3325fbe55.png)




#unit Testing

first install jest (as a dev dependency)

create directory in you project as  __test__
  create file for testing component with js extention.
  add test script
    like: "test": "jest"
  
  now write test in the file you created in __test__ directory



![image](https://user-images.githubusercontent.com/67856787/174432531-3787186b-3a0f-4109-9765-b63db765eb87.png)

test like this

![image](https://user-images.githubusercontent.com/67856787/174432546-cd81001b-e627-4ec0-a6be-2241432ea187.png)


- What if we give incorrect input 

![image](https://user-images.githubusercontent.com/67856787/174432559-b230ff16-9c3b-4c73-a597-d03a58da87d3.png)


- testing function

![image](https://user-images.githubusercontent.com/67856787/174433116-c39a5e1c-4fce-46b0-94c3-d199a14ec507.png)


- checking variable types

![image](https://user-images.githubusercontent.com/67856787/174433193-5b6477ca-4ce5-46df-a93e-a31531bdf20c.png)


![image](https://user-images.githubusercontent.com/67856787/174433614-4dcae613-9979-4f3e-9e14-f8074fb47499.png)



![image](https://user-images.githubusercontent.com/67856787/174433676-1cddd139-cfb5-4483-91a0-4faaaece48bb.png)





API Test (Super test)
-
- for that we have to install super-test

- Now code the following 
  
**API Test**

FileName: my.test.js
const app = require('../index')
const request = require('supertest')
```
describe('POST APIs', () => {
    test('It should create user', async () => {
        let result  = await request(app).post('/signup2')
            .send({
                username: "Abid",
                password: "1234"
            })

            expect(result.body).toEqual({
                username: "Abid",
                password: "1234"
            })

    })
})
```

**in index.js**
```
app.post("/signup2",(req,res)=>{
  res.json(req.body);
});
```


------------------------------
## JWT
-

install jsonwebtocken by 
npm i jsonwebtocken

![image](https://user-images.githubusercontent.com/67856787/175768013-72a20405-09d9-4c40-94a0-454d245116ef.png)


**jwt cnontroller**

![image](https://user-images.githubusercontent.com/67856787/175768025-9916f67a-2138-4269-bba4-66286b30e5d1.png)


middle ware for verifying tocken

![image](https://user-images.githubusercontent.com/67856787/175769451-87693fb4-9618-4dd9-af39-60c4115ecec4.png)


get request on product route/api

![image](https://user-images.githubusercontent.com/67856787/175769613-a1528906-23f6-4887-9f6a-64b4b7c99042.png)


get api response after expire

![image](https://user-images.githubusercontent.com/67856787/175769660-f1379f8e-a7cf-4099-89d0-b62df317908a.png)


sending token in header

![image](https://user-images.githubusercontent.com/67856787/175942835-685a5822-0528-4fc0-979b-4d67251ed0e9.png)


post api with jwt

![image](https://user-images.githubusercontent.com/67856787/175942872-00f2d0ad-9dce-4ba8-b4ab-48de22a4b34a.png)

-----------------------------------
## Put vs Patch <a href="https://stackoverflow.com/questions/28459418/use-of-put-vs-patch-methods-in-rest-api-real-life-scenarios">Resource</a>

------------------------------------------------
## json schema <a href="https://www.jsonschema.net/">Site Link</a>
-


install jesonschema
and import it in your app

![image](https://user-images.githubusercontent.com/67856787/175770416-9ec6ca64-d4ab-457a-9c65-b7e12e871cf5.png)


save the jsonschema in a variable and apply it on api or route

![image](https://user-images.githubusercontent.com/67856787/175770444-de55924b-5d73-42e8-ae08-7e8678c60965.png)


![image](https://user-images.githubusercontent.com/67856787/175770561-763d6832-db82-4c55-961c-c86c0cc46e9a.png)













