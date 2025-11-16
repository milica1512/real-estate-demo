# 🏡 Real Estate Listing App

A modern real-estate web application for browsing property listings, viewing detailed information for each property, and sending visit requests.  
This project demonstrates the usage of React, API fetching, routing, and clean UI styling.

---

##  Project Overview

The goal of this application is to provide a simple and clean interface for:

- Viewing real estate listings  
- Seeing detailed information about each property  
- Checking bedrooms, bathrooms, square footage, and description  
- Sending a “Book a Visit” request through a form  
- Browsing agents and testimonials  
- Navigating through pages using React Router

All property data is fetched from a custom JSON API created using **my-json-server (GitHub fake REST API).**

---

## 🛠️ Frontend Technologies
- **React.js**  
- **React Router DOM**  
- **Axios**  
- **React Query / TanStack Query**  
- **CSS3**  
- **Vite**

---

## 🗄️ Backend / API

Using **my-json-server** (GitHub-based REST API).  
The mock database includes:

- `/listings` – main property data  
- `/listingDetails` – bedrooms, bathrooms, area, description  
- `/agents` – agents section  
- `/testimonials` – user reviews  

All data is stored in a GitHub repository as a `db.json` file.

---

## 📁 Project Structure

src/
│
├── assets/ # Images, icons
│
├── components/ # Reusable components
│ ├── Footer.jsx
│ ├── NavBar.jsx
│ └── WelcomePop.jsx
│
├── pages/ # Application pages
│ ├── Home.jsx
│ ├── Listing.jsx
│ ├── ListingDetails.jsx
│ ├── Agents.jsx
│ ├── Contact.jsx
│ ├── Login.jsx
│ └── Register.jsx
│
├── styles/ # CSS styling for each page
│ ├── Home.css
│ ├── Listing.css
│ ├── ListingDetails.css
│ ├── Agents.css
│ ├── Contact.css
│ ├── NavBar.css
│ ├── Register.css
│ └── Footer.css
│
├── main.jsx # Entry point, routing setup
└── App.jsx # Application wrapper


---

## 🔗 API Endpoints (Mock Database)

- `/listings` – list of all properties  
- `/listingDetails/:id` – detailed info  
- `/agents` – real estate agents  
- `/testimonials` – user reviews  

Hosted using **my-json-server (typicode)**.

---

## ▶️ How to Run the Project

### 1. Install dependencies  


npm install


### 2. Start the development server  


npm run dev


### 3. Open in browser  


http://localhost:5173/


---

## 👤 Author
**Milica 1512**  
GitHub: https://github.com/milica1512


