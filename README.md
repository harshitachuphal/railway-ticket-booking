# Railway Ticket Booking System

A simple railway ticket booking web app built with React. 
This is Step 1 of the project.

**Project Started: 5 July 2026** 
**Status: In Progress**

## 1. App.jsx - Login Logic
**What I did:**
- Used `useState` to handle email, password, and login state
- Added basic validation: Shows alert if email or password is empty
- On successful login, sets `isLoggedIn` to true
- After login, displays a welcome message and train search form with From, To, and Date inputs

**Flow:**
Login Form → Validation → Welcome Screen + Search Inputs

## 2. App.css - Styling
**What I did:**
- Used `flexbox` to center the login box on the screen
- Set `background:#f2f2f2` for a light grey page background
- `.login-box` - White card with `box-shadow` and `border-radius:10px`
- Inputs: Fixed `width:250px` with `padding:10px`
- Button: Blue background, turns `darkblue` on hover

## How to Run
1. `npm install`
2. `npm start`
3. Open `http://localhost:3000` in your browser

## Current Progress
- ✅ Login UI + Basic validation - Complete
- ✅ CSS Styling - Complete  
- ⏳ Backend API - Pending
- ⏳ Real Train Search - Pending

## Next Step
Build Node.js + Express backend for login and train search API.
## 3. Search Component - Completed 6 July 2026
**What I did:**
- Created search form with From, To, and Date inputs
- Added validation for empty fields
- On submit, passes search data to Train List component

**Flow:**
Login → Search Form → Train List

## 4. Train List Component - Completed 6 July 2026
**What I did:**
- Displayed list of trains based on search input
- Showed train name, number, time, and available seats
- Added "Book Now" button for each train

**Flow:**
Search → Train List → Book Now

## 5. Booking Component - Completed 6 July 2026
**What I did:**
- User can select train from Train List
- Shows selected train details on booking page

**Flow:**
Train List → Booking Page

## 6. Passenger Details Component - Completed 6 July 2026
**What I did:**
- Added form to collect passenger name, age, gender
- Validates required fields before proceeding

**Flow:**
Booking → Passenger Details Form

## Current Progress
- ✅ Login UI + Basic validation - Complete
- ✅ CSS Styling - Complete
- ✅ Search Component - Complete
- ✅ Train List Component - Complete
- ✅ Booking Component - Complete  
- ✅ Passenger Details Component - Complete
