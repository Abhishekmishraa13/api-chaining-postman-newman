# API Chaining using Postman & Newman 🚀

Today I explored API Chaining and learned how dependent APIs work together.

## What I Learned

✅ API chaining without manual intervention  
✅ Dynamic variables (token, userId, cartId)  
✅ Collection Runner execution  
✅ Running APIs outside Postman UI using Newman  
✅ End-to-end API automation flow


## Project Demo

<img width="1470" height="956" alt="Screenshot 2026-05-27 at 01 14 39" src="https://github.com/user-attachments/assets/c27d09bb-31e8-4f11-91b3-5029b532b714" />











## What is API Chaining?

API chaining is a process where the response from one API becomes the input for another API.

Example Flow:

Login API  
↓  
Get Token  
↓  
Get User Profile  
↓  
Get Products  
↓  
Add To Cart  
↓  
Get Cart

Instead of manually copying token/data between APIs, dynamic variables are stored and passed automatically.

## Run via Newman

newman run "API Chaining E2E.postman_collection.json" -e "Automation Practice.postman_environment.json"

## Tech Used

- Postman
- Newman
- REST APIs
- DummyJSON API



Still learning and improving 🚀
