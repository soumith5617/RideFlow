# RideFlow — Ride Sharing Application Prototype

## What this is
A self-contained working web prototype based on the supplied Ride Sharing Application case study.

It implements a polished front-end model for:
- Passenger registration/login and profile
- Ride booking and location selection
- Available-driver selection
- Ride request / accept / reject
- Ride lifecycle: REQUESTED → ACCEPTED → IN_PROGRESS → COMPLETED / CANCELLED
- Simulated live tracking map
- Fare display
- Payment and receipt state
- Failed/cancelled/refunded states
- Notifications
- Ride history
- Ratings and reviews
- Driver dashboard, requests, trip management and availability
- Admin overview, users, drivers, rides, reports and settings
- Responsive desktop/tablet/mobile layouts
- Loading/empty/error/status UI patterns
- LocalStorage persistence

## Run
No server or package installation is required.

1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Select Passenger, Driver, or Admin on the login screen.
4. Use the prefilled demo credentials and sign in.

Demo accounts:
- Passenger: passenger@rideflow.app / demo123
- Driver: driver@rideflow.app / demo123
- Admin: admin@rideflow.app / demo123

## Important prototype note
External map, payment, SMS/email notification and authentication infrastructure are represented with working local simulations. This keeps the prototype runnable offline. The UI and state boundaries are structured so those services can later be replaced by real APIs.

## Case-study alignment
The prototype follows the supplied case study's major actors, modules and lifecycle, including:
Passenger, Driver, Administrator, Payment Gateway, Notification Service; registration/login, booking, driver assignment, trip tracking, fare/payment, cancellation/refund, notifications, rating/review, ride history and administration.
