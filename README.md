# Ecom - api
E-Commerce-API ABOUT This is an E-commerce API made using Node.Js & MongoDB.
STEPS TO USE THE API:
1. run "npm init" command on terminal in this projects directory
2. start the server using node app.js
3. Open postman
4. Make a GET request on localhost:3000/api/ -- The products should be visible
5. STEPS TO CREATE A NEW PRODUCT:
      start the server using node app.js Open postman put localhost:3000/api/create as the url. 
      Body tab below the url textarea and then select x-www-form-urlencoded
      Add name,quantity and id as the keys and set the desired values for the keys.
      Make a POST request.
      If you recieve the message saying new product added successfully then you have done everything correct.
      The product is created.
      Check it out by making a GET request at localhost:3000/api
6. STEPS TO DELETE A PRODUCT:
      Copy the object id of the product you want to delete. add the id after localhost:3000/api/remove/:id
      Make a DELETE request.
      You will recieve a message saying deleted successfully.
7. STEPS TO UPDATE THE QUANTITY OF A PRODUCT:
      Copy the object id of the product whose quantity you want to update
      Put the id at localhost:3000/api/remove/:id
      Body tab below the url textarea and then select x-www-form-urlencoded
      Change name,quantity and id as the keys and set the desired values for the keys.
     Make a POST request and you should get a message containing the update product
TECHSTACK Node.Js, MongoDB
Live url : 
