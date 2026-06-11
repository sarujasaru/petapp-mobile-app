🐾 PetCare – Pet Sitting Service Platform
📌 Overview
Android application connecting pet owners (Customers) with pet Caregivers

Built with Java and Firebase (Realtime Database + Auth)

Two user roles: Customer (pet owner) and Caregiver (pet sitter)

👤 Customer Features
Register / Login with email & password

Add pet profiles – name, breed, age, sex, category (Dog / Cat)

Create job posts – location, date/time, duration, select pets

View all my bookings (accepted caregiver requests)

View caregiver details and payment summary

Make payment (simulated) – generates a bill

Give feedback – rating (1–5 stars) + comment

👨‍⚕️ Caregiver Features
Register / Login with email & password

Browse available jobs (pending posts from customers)

Accept a job – sends real‑time notification to customer

View my bookings (accepted jobs)

Receive notifications when:

A job is accepted (customer side)

A bill is generated (caregiver receives alert)

A feedback form is requested (customer receives)

View ratings & feedback from customers

🔔 Notification System
Real‑time alerts for:

Job acceptance (customer receives)

Bill payment (caregiver receives)

Feedback request (customer receives)

💰 Payment & Billing
Payment calculation: (Cats × 500 + Dogs × 1000) × number of days

Payment generates a bill stored in Firebase

Bill can be shared (simulated)

Bill triggers notification to caregiver

⭐ Feedback & Ratings
Customers rate caregivers (1–5 stars) with optional comment

Caregivers can view all received feedback

🛠️ Tech Stack
Language – Java

UI – XML, Material Design (CardView, RecyclerView, Chip, TextInputLayout)

Backend – Firebase Realtime Database, Firebase Authentication

Image Loading – Glide (for GIF in splash screen)

Icons – Custom drawable resources

📁 Key Files (Selected)
Activity/LoginActivity.java – Email/phone login

Activity/RegisterActivity.java – User registration with role selection

Activity/CustomerDashboard.java – Customer main screen

Activity/CaregiverDashboard.java – Caregiver main screen

Activity/PetProfile.java – Add / view / edit pets

Activity/JobPost.java – Create a pet sitting request

Activity/AvailableJobsActivity.java – Caregiver view of open jobs

Activity/JobDetails.java – View job details, accept/reject

Activity/CustomerBookingActivity.java – Customer booking list

Activity/CustomerBookingDetailsActivity.java – Booking details + payment summary

Activity/Payment.java – Simulated payment & bill generation

Activity/BillActivity.java – View bill, share, send feedback request

Activity/FeedbackActivity.java – Submit rating & comment

Activity/CaregiverRatingActivity.java – View feedback received

Activity/NotificationActivity.java – View all notifications

Adapter/Petadapter.java – RecyclerView adapter for pets

Adapter/JobAdapter.java – Adapter for available jobs / bookings

Adapter/NotificationAdapter.java – Adapter for notifications

Firebase/FirebaseHelper.java – Firebase operations helper

models/User.java, Pet.java, post.java, Notification.java, Bill.java, Feedback.java

🧪 Usage by Role
Customer – Register (as Customer) → Add pets → Create job post → Wait for acceptance → View booking → Pay → Give feedback

Caregiver – Register (as Care giver) → Browse available jobs → Accept → View my bookings → Receive bill → Request feedback → View ratings
