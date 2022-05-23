# Project_1_FSD

This project is related to Course 2 on the FSD program.

# Sprints:
1 - May 23rd
2 - Jun 6th

# Project description:
Create rest api application using .Net Core Web Api for EHealthcare application which can be consumed by clients like Angular, React or any mobile application. This application should be scalable to be able to use with any number of clients and end users.
## Background of the problem statement
ABC Healthcare is a Mumbai-based pharma company which sales medicines throughout India as per the demand they receives from multiple hospitals and clinics. They have been operating in India since last 15 years.
However in recent years since all industries are coming online to boost their sales and cover larger market space, ABC Healthcare missed the chance and as a result their sales has been dropping since last 2 years. To overcome this and bring sales back on track they have decided to bring their service online to allow their customers to purchase medicines by their web application.
You are hired as one of the .Net developer and have been asked to  develop the rest api application for the front-end application. The management team has provided you the  requirements and their business model so that you can easily arrange different  components of the application. 

## Features of the Api Application :
1. User Registration 
2. User Login 
3. Admin Login
4. Add/Update medicines to portal
5. Browse through medicines. 
8. Manage Cart
9. Place order  

## Recommended Backend Tools and Technologies :
1. Database management: SQLServer  
2. Back-end logic: ASP.NET Core Web API

## Project development guidelines
Learners should divide the entire project into multiple sprints to follow Agile development methodologies.
It is mandatory to perform proper sprint planning with user stories to  develop all the modules of the project. 
The learner must maintain the version of the application over GitHub and  every new change should be sent to the repository. 
Learner should follow REST Api standards to expose endpoints for clients.
Apis should use standard HTTP Status Codes for response to user’s requests.

## Admin Module
Admin is responsible for managing content in the portal. Admin will handle adding and updating data in portal.

Create end points for below functionalities.
Admin/addMedicine – To add new medicines.

Admin/updateMedicine – To update existing medicines.

Admin/getAllMedicine – To get all medicines from database

Admin/getMedicineById – To get one medicine and its details using ID.

Admin/deleteMedicineById – To delete medicine from database.

## User Module
From the user’s perspective, application should allow users to get all medicines, add them to cart and place order. New user should also be able to signup, upon which you need to return JWT token to the client.

Create end points for below functionalities.

User/signup  - To register new users

User/signin – To signin existing users

Cart/GetByUserID – Get User’s cart.

Cart/Add – Add medicine to cart.

Cart/PlaceOrder – Place Order for items in cart.
