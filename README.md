- - [Online Dish App](#online-dish-app)
    + [**1. Description of my website**](#--1-description-of-my-website--)
      - [**1.1 Purpose:**](#--11-purpose---)
      - [**1.2 Functionality / Features**](#--12-functionality---features--)
        * [1.2.1 Major Features](#121-major-features)
          + [1.2.1.1 Users:](#1211-users-)
          + [1.2.1.2 Admin (Restaurant Owner)](#1212-admin--restaurant-owner-)
        * [1.2.2 Sprinkles](#122-sprinkles)
          + [1.2.2.1 Users:](#1221-users-)
          + [1.2.1.2 Admin (Restaurant Owner)](#1212-admin--restaurant-owner--1)
      - [**1.3 Target audience**](#--13-target-audience--)
      - [**1.4 Tech stack:**](#--14-tech-stack---)
      - [1.4.1 Backend](#141-backend)
        * [1.4.1.1 MongoDB](#1411-mongodb)
        * [1.4.1.2 Express](#1412-express)
        * [1.4.1.3 Node.js](#1413-nodejs)
      - [1.4.2 Front End](#142-front-end)
        * [1.4.2.1 React:](#1421-react-)
      - [1.4.3 Deployment](#143-deployment)
    + [**2. Dataflow Diagram of the application:**](#--2-dataflow-diagram-of-the-application---)
    + [**3. Architecture of the application**](#--3-architecture-of-the-application--)
    + [**4. User Stories**](#--4-user-stories--)
      - [**4.1 Major attributes**](#--41-major-attributes--)
      - [**4.2 Sprinkles:**](#--42-sprinkles---)
    + [**5. Wireframes**](#--5-wireframes--)
      - [**Desktop Views**](#--desktop-views--)
      - [**Mobile Views**](#--mobile-views--)
    + [**6. Task delegation and trello**](#--6-task-delegation-and-trello--)
    + [**7. Agile Project Management methodology**](#--7-agile-project-management-methodology--)
    + [**8. Source control**](#--8-source-control--)
    + [**9. Deployment**](#--9-deployment--)
    + [**10. Testing and Evidences**](#--10-testing-and-evidences--)
    + [**11. Screenshots after deployment**](#--11-screenshots-after-deployment--)
    + [**12. Challenges and Opportunities**](#--12-challenges-and-opportunities--)
    + [**13. Learning Outcome and Conclusion**](#--13-learning-outcome-and-conclusion--)







# Online Dish App


### **1. Description of my website**

This is an online food delivery application that can be used by consumers for ordering meal from a  restaurant and the restaurant is also the admin of this application. This web application is based on MERN stack and it has been designed as a tool for restaurants and the consumers to make deals entirely online so that the consumers can have dish varieties without travelling. It is also quite helpful for elderly and disabled people and even more, this web application will be quite handy in the current scenario of Covid-19 pandemic. The application consists of a full package for users to register, view the dish items listed, make an order from  the restaurant and receive the delivery of dish items. 

#### **1.1 Purpose:**

This application is being designed for online booking, payment and delivery of dishes from a restaurant. The purpose and ambitions of this projects can be listed as below:

- The main purpose of this application is to act as a bridge between the customers and the restaurants. So, this application eliminates the need to travel to a restaurant and have a dish over there or grab a take away. 
- In addition to saving time of consumers, this application  will also help the restaurants to  keep their businesses alive specially in this Covid-19 pandemic.

#### **1.2 Functionality / Features**

The core features of this application are as below:

##### 1.2.1 Major Features

######  1.2.1.1 Users:

 1. A non registered user can view the list of dish items posted, can view an individual dish post with details like ingredients and price.

 2. A user can can do more activities like register/login/logout either as a consumer or as a restaurant owner (admin)

 3. A logged in  consumer can make an order of dish items from the restaurant but can't post, delete or edit dish items posted

    

###### 1.2.1.2 Admin (Restaurant Owner)

1. The restaurant owner, being an admin,  has additional sensitive features like posting the dish items, deleting and editing a dish item posted by the the restaurant.
2. Admin can block a user for unacceptable behaviors like abusive comments.

##### 1.2.2 Sprinkles 

###### 1.2.2.1 Users:

1.  Consumer can pay online and get the food items delivered.
2.  User can make a comment on a post of food items.


###### 1.2.1.2 Admin (Restaurant Owner)

1. The admin can delete any of the  comments made on the dish posts (to handle abusive users)

#### **1.3 Target audience**

General people who like to have dishes from restaurants are the target audience as this application facilitates them to make online order through a restaurant. There is a facility of online payment as well. So, every people in the delivery range of the restaurant are the final users of this application. The significance of this application can be even more highlighted considering the need of social distancing in the fight against Covid-19 pandemic. 



#### **1.4 Tech stack:**

This application is totally based upon MERN web application stack which incorporates all the files and features comprising this application. Just like any other web application, this project also  requires a coordination between various  technologies such as frameworks, databases, libraries and many more. So, at the backend, the application uses Mongo Database for data storage and Express for serving the requests and data.  It is a node.js based model and React will be implemented to facilitate User Interface. In terms of programming language, the application is coded in JavaScript.

 MongoDB

 Express

 React

 Node.js

These four components will be combined and coordinated together which will ultimately  provide an end-to-end web development framework that the  developers can adopt for a MERN stack application.

#### 1.4.1 Backend

##### 1.4.1.1 MongoDB

I have preferred MongoDB because it is simpler and flexible compared to the conventional relational databases (schema based) which are  indeed based upon tables and columns, MongoDB is a schema-less database. It is a non-relational document-oriented database capable of performing in cross-platform environments. Data for MongoDB are stored in JSON documents

##### 1.4.1.2 Express 

In this project, Express will act as a server side web application framework for Node.js and drastically eases the tasks at the server side.  Express  avoids the necessity to write code for web server manually on Node.js directly. I have preferred Express because it is very well known for performance speed and least structural complexity.

##### 1.4.1.3 Node.js 

This application is based on node.js platform and I have applied Node.js to make the application light-weight and efficient. In this application design, node.js will be implemented to  construct  expansible network applications that is capable to run java script code outside a browser too. In addition, Node.js provides a cross-platform run environment for JavaScript. 

#### 1.4.2 Front End

##### 1.4.2.1 React: 

React will facilitate the front end requirements in this application which is a open-source JavaScript library  implemented to design user interfaces and is operated and maintained by Facebook along with a software committee  and companies of developers. React automatically creates  HTML rendered view.  React views are  declarative and it well eliminate most of the problems  regarding the  effects of modification in view’s state  or  data.

Another reason of adopting React for the application is its capability of building  repetitive as well as conditional DOM elements and React facilitates  both the browser and server to access and run the same code  simultaneously. 

#### 1.4.3 Deployment

- Netlify: a cloud platform that hosts the front-end of the application.
- Heroku: a cloud platform that hosts the back-end the application.

**Reources:** 

**Hyperion Development (2018). HyperionDev Blog. [online] HyperionDev Blog**, *date of retrieval 24 April 2020*, https://blog.hyperiondev.com/index.php/2018/09/10/everything-need-know-mern-stack



### **2. Dataflow Diagram of the application:**

**Dataflow Diagram of the application:**



![alt DFDimage](./pictures/dfd1.png?raw=true)

​								Fig: Dataflow diagram of the online food delivery application


![alt DFDimage](./pictures/dfd2.png?raw=true)



### **3. Architecture of the application**

![alt DFDimage](./pictures/arch.png?raw=true)



MERN is the framework of my online food delivery application and the diagram above demonstrates the association of server side and the client side. A user sends request from web browser and the user gets an interface (web page) rendered by React. React automatically creates the Html, CSS and Bootstrap those are required for the front end side.  User Interface is linked to server via API (application peripheral interface and from then on the request and response is handled by Express. Data transfer between the application and database (MongoDB in this project) is mediated by Database driver which is integrated within Node.js. 



### **4. User Stories**

#### **4.1 Major attributes**

1. As a guest user, I would like to see the list of all  posts of food items and view the details of an individual dish item posted including the price and location of the restaurant.
2. As a registered user (consumer),  in addition to what a guest user can do, I would like to order my favorite dish from the  restaurant.
3. As an admin (restaurant owner), I would like to  post dish items, delete and edit my posts.
4. As an admin, I would like to view orders for my restaurant.
5. As an admin, I would like to view all the orders placed by consumers and delete them as well. 
6. As an Admin, I want to have a full control over the application and I should be capable to delete any user and block a user (consumer or restaurant) if there is any issue of abuse.



#### **4.2 Sprinkles:**

1. Being  a registered user (consumer), I would like to  pay online for my order and get my favorite dish delivered to my home/office.
2. As a registered user, I want to comment on the food items listed.
3. As an admin, I want to delete any abusive comment posted by a user.



### **5. Wireframes**
#### **Desktop Views**

Homepage when users are not logged in

![alt wirefraame pic](./pictures/desktop1.png?raw=true)

Homepage when users are logged in


![alt wirefraame pic](./pictures/desktop1user.png?raw=true)

Homepage when admin is logged in

![alt wirefraame pic](./pictures/desktop1admin.png?raw=true)

Dish Items list Page

![alt wirefraame pic](./pictures/desktop2.png?raw=true)

Login Page

![alt wirefraame pic](./pictures/desktop3.png?raw=true)

Admin: Post a dish item

![alt wirefraame pic](./pictures/desktop4.png?raw=true)

User: Place an order

![alt wirefraame pic](./pictures/desktop5.png?raw=true)

Order Summary Page

![alt wirefraame pic](./pictures/desktop6.png?raw=true)

Dish item details page

![alt wirefraame pic](./pictures/desktop7.png?raw=true)

#### **Mobile Views**

HomePage and Login Page

![alt wirefraame pic](./pictures/mob1.png?raw=true)!

Dish Post lists and a dish item details

![alt wirefraame pic](./pictures/mobile2.png?raw=true)

Post an item and place an order

![alt wirefraame pic](./pictures/mobile3.png?raw=true)!

Order Details Page

![alt wirefraame pic](./pictures/mobile4.png?raw=true)!


### **6. Task delegation and trello**

Trello is the collaboration tool adopted to organize the online food delivery application project into dash board. Some of the screenshots of trello taken from the starting date of documentation has been presented below:

![alt DFDimage](./pictures/t1.png?raw=true)

![alt DFDimage](./pictures/t2.png?raw=true)

![alt DFDimage](./pictures/t3.png?raw=true)

![alt DFDimage](./pictures/t4.png?raw=true)

![alt DFDimage](./pictures/t5.png?raw=true)

![alt DFDimage](./pictures/t6.png?raw=true)

![alt DFDimage](./pictures/t7.png?raw=true)

![alt DFDimage](./pictures/t8.png?raw=true)

![alt DFDimage](./pictures/t9.png?raw=true)

![alt DFDimage](./pictures/t10.png?raw=true)

![alt DFDimage](./pictures/t11.png?raw=true)


specific Challenges Faced:

Node-Client integration: It took me more time than expected.

Design Part: Specially, the input section for dish items is complicated because a user may select more than one dish item quantity of each dish item may be more than one. 


### **7. Agile Project Management methodology**

This web app project is based on agile project management. Since the development of this application is not a straight forward approach, so many modifications were required as the project progressed and as I continued manual testing as an user throughout the process, there were many adjustments, mainly in the coding part. Also, while integrating the server and the client, I had to test and review the code not only at the client side but also at the server side. As a whole, the agile project methodology that I applied in this web application development can be visualized as below:

![alt agileimage](./pictures/agile.png?raw=true)


Although I have used Trello for task delegation, I found it even more flexible to use Monday for even more effective view and some of the screenshots are presented below:
![alt agileimage](./pictures/m1.png?raw=true)
![alt agileimage](./pictures/m2.png?raw=true)
![alt agileimage](./pictures/m3.png?raw=true)
![alt agileimage](./pictures/m4.png?raw=true)
![alt agileimage](./pictures/m5.png?raw=true)
![alt agileimage](./pictures/m6.png?raw=true)



The site map of the web application can be summarised by the picture below:


![alt DFDimage](./pictures/sitemap.png?raw=true)




### **8. Source control**


Git is the source control system for this project and Github is the hosting platform for source control.

The GitHub links to the server, client and the documents is as below:

Server: https://github.com/amrithub/final_project_server

Client: https://github.com/amrithub/final_project_client

documents: https://github.com/amrithub/final_project_documents


### **9. Deployment**
The links for deployed server and the client is as below:

Deployed Links

Client:  https://reverent-chandrasekhar-b06d1f.netlify.app/

Server: https://gentle-tundra-64079.herokuapp.com/




### **9. Testing and Evidences**

Unit Testings:

Unit testing was successfully done for all the routes. It was a mocha test with mocha as dependency. Testing codes for each of the routes( both for dish posts and order posts) were carried out individually and again tested after the completion of Express CRUD and the result of overall test was also successfully acquired which has been listed below:

**Individual unit Test:**
![alt testingimage](./pictures/ut2.png?raw=true)

![alt testingimage](./pictures/ut1.png?raw=true)

![alt testingimage](./pictures/ut3.png?raw=true)


![alt testingimage](./pictures/ut4.png?raw=true)

![alt testingimage](./pictures/ut5.png?raw=true)

![alt testingimage](./pictures/ut6.png?raw=true)

![alt testingimage](./pictures/ut7.png?raw=true)

![alt testingimage](./pictures/ut8.png?raw=true)

![alt testingimage](./pictures/ut9.png?raw=true)

![alt testingimage](./pictures/ut10.png?raw=true)



**Overall unit Test:**
![alt testingimage](./pictures/unittest.png?raw=true)


**Manual Testing**
The manual testing performed can be summarised by the table below:

| test        | expected o/p                                                                                                                          | actual O/p                                                                                                                        | remark               | Issue                           |
|-------------|---------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|----------------------|---------------------------------|
| register    | 1. should be able to register with  valid username, email and password 2. user shouldn't be able to  register with existing username. | 1. A new user with  valid details signed  up successfully. 2. Error generated  when attempted to  register with existing username | successful           | none                            |
| login       | Registered user can log in with correct username and password                                                                         | Login successful with correct username and password, showed  error with incorrect details                                         | successful           | none                            |
| logout      | Logged in user can logout to home page                                                                                                | As a user, I could log out                                                                                                        | successful           | none                            |
| Get Post    | 1. User should get  dish posts with and without logging in 2. Admin should get orders and not the user                                | 1. As a user, I could get dish  posts but not orders 2. As an admin, I could get orders                                           | partially successful | Admin role at client for orders |
| Make Post   | 1. Only Admin should be able to make dish post 2. user should be able to make an order                                                | 1. As an admin, I could easily  post a dish item 2. As an user, I could easily  post an order                                     | successful           | none                            |
| Delete Post | Only admin should be able to delete dish posts and orders                                                                             | 1. As an admin, I could delete  any post 2. As an user, I couldn't delete any of the posts even at server                         | successful           | none                            |
| Edit Post   | Only admin should be able to edit dish posts                                                                                          | 1. As an admin, I could edit any post 2. As an user, I couldn't edit any of the posts even at server                              | successful           | none                            |

Evidences:
Here are some of the evidences of manual testing where error is generated by unauthorised actions:

![alt testingimage](./pictures/error1.png?raw=true)

![alt testingimage](./pictures/error2.png?raw=true)

![alt testingimage](./pictures/error3.png?raw=true)


### **10. Screenshots after deployment**

Desktop views:

![alt testingimage](./pictures/dt1.png?raw=true)

![alt testingimage](./pictures/dt2.png?raw=true)

![alt testingimage](./pictures/dt3.png?raw=true)

![alt testingimage](./pictures/dt4.png?raw=true)

![alt testingimage](./pictures/dt5.png?raw=true)

![alt testingimage](./pictures/dt6.png?raw=true)

Mobile Views:

![alt testingimage](./pictures/mv1.png?raw=true)

![alt testingimage](./pictures/mv2.png?raw=true)

![alt testingimage](./pictures/mv3.png?raw=true)

![alt testingimage](./pictures/mv4.png?raw=true)

![alt testingimage](./pictures/mv5.png?raw=true)

![alt testingimage](./pictures/mv6.png?raw=true)

![alt testingimage](./pictures/mv7.png?raw=true)

![alt testingimage](./pictures/mv8.png?raw=true)

![alt testingimage](./pictures/mv9.png?raw=true)

![alt testingimage](./pictures/mv10.png?raw=true)




### **11. Challenges and Opportunities**

Node-Client integration: It took me more time than expected.

The admin role was easily implemented at server side but there was some issue with reading orders at the client side.

My next challenge is to implement Stripe Payment System in this app and that will be another opportunity for me to learn.

### **12. Learning Outcome and Conclusion**
1. I felt it was more like a learning process and overall project development taught me that web app development needs a lot of patience and the outcome is never the actual reflection of the performance for the outsiders or users. In fact I have learned to be more patient.

2. Web application development is building and learning side by side, my experience form this project says it.


