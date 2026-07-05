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
