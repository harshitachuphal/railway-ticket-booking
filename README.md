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
- 
## 7. Travel Class Component - Completed 7 July 2026
**What I did:**
- Added option to select travel class like Sleeper, 3AC, 2AC, 1AC
- Fare changes dynamically based on selected class

**Flow:**
Passenger Details → Travel Class Selection → Seat Preference

## 8. Seat Preference Component - Completed 7 July 2026
**What I did:**
- User can select seat preference: Lower, Middle, Upper, Side Lower, Side Upper
- System assigns seat based on preference + availability

**Flow:**
Travel Class → Seat Preference → PNR Generation

## 9. PNR + Coach + Seat Number Generation - Completed 7 July 2026
**What I did:**
- Auto-generated unique PNR number for each booking
- Assigned coach number and seat number based on class and preference
- Stored booking details temporarily using state

**Flow:**
Seat Preference → PNR/Coach/Seat Generated

## 10. Dynamic Fare Calculation - Completed 7 July 2026
**What I did:**
- Fare calculated based on distance, travel class, and seat preference
- Displayed total fare before final booking

## 11. E-Ticket Generation - Completed 7 July 2026
**What I did:**
- Created e-ticket with passenger details, train info, PNR, coach, seat, and fare
- Displayed ticket on screen after successful booking

**Flow:**
Booking Confirmed → E-Ticket Shown

## 12. Cancel Ticket Feature - Completed 7 July 2026
**What I did:**
- Added cancel ticket functionality
- Shows alert "Ticket Cancelled Successfully" on cancel
- Removes booking from active bookings

## Current Progress - Updated 7 July 2026
- ✅ Login UI + Basic validation - Complete
- ✅ CSS Styling - Complete  
- ✅ Search Component - Complete
- ✅ Train List Component - Complete
- ✅ Booking Component - Complete  
- ✅ Passenger Details Component - Complete
- ✅ Travel Class Selection - Complete
- ✅ Seat Preference - Complete
- ✅ PNR/Coach/Seat Generation - Complete
- ✅ Dynamic Fare - Complete
- ✅ E-Ticket Generation - Complete
- ✅ Cancel Ticket - Complete
- ⏳ Backend API with Node.js + Express - Pending
- ⏳ Database for storing bookings - Pending
- ⏳ Register System UI - Pending

