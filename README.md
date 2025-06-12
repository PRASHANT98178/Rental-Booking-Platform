# Rental Booking System 🏠

A full-stack web application for booking rental properties, developed using Node.js, Express, MongoDB, and Cloudinary for image storage. This system allows users to list, view, and book properties with ratings, map integration, and responsive UI styling.

## 🚀 Features

- 📍 Google Maps integration for property locations
- 🌄 Cloudinary image uploads for rental listings
- 📋 MongoDB schema for property data
- ⭐ Property rating system
- 🎨 Styled with custom CSS and rating effects
- 📱 Responsive frontend design

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Image Hosting**: Cloudinary
- **APIs**: Google Maps API

---

## 📂 Project Structure

rental-booking-system/
├── app.js                 
├── cloudConfig.js         
├── schema.js             
├── public/
│   ├── style.css          
│   ├── rating.css         
│   ├── script.js       
│   ├── map.js             
├── views/
│   ├── index.html         
│   ├── add.html           
│   ├── view.html          
├── uploads/              
├── .env                   
├── package.json          
└── README.md             

## 🧪 How to Run the Project Locally
Step 1: Clone the repository
git clone https://github.com/your-username/rental-booking-system.git
cd rental-booking-system

Step 2: Install dependencies
npm install

 Step 3: Add environment variables
touch .env
Add the following:
PORT=3000
MONGODB_URI=your_mongodb_connection_string
CLOUD_NAME=your_cloudinary_cloud_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
GOOGLE_MAPS_API_KEY=your_google_maps_api_key

# Step 4: Start the server
node app.js


## 📸 UI Screenshots
Home Page

![image alt](https://github.com/PRASHANT98178/Rental-Booking-Platform/blob/618c07489de1a5087dd1ac206957c14b4b5a641d/Home%20Page.jpeg)

Card Info

![image alt](https://github.com/PRASHANT98178/Rental-Booking-Platform/blob/1aea55a8267e811aae89a49eaede1e5b98949c7d/Card%20Info.jpeg)


## 📌 Future Enhancements
🔐 User Authentication with JWT

📅 Booking availability calendar

💬 User reviews and feedback

📊 Admin dashboard for property management

🧾 Email confirmation on booking
