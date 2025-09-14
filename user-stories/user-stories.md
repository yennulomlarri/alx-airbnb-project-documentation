# User Stories - Airbnb Clone

## 📋 Overview
This document contains user stories derived from the Use Case Diagram. Each story follows the format:  
**"As a [role], I want to [action], so that [benefit]."**

## 👥 Guest User Stories

### Authentication
1. **As a** new user, **I want to** register an account, **so that** I can access the platform as a guest.
2. **As a** registered user, **I want to** login to my account, **so that** I can book properties and manage my reservations.
3. **As a** user, **I want to** update my profile information, **so that** my details are current and accurate.

### Property Search & Booking
4. **As a** guest, **I want to** search for properties by location, dates, and filters, **so that** I can find suitable accommodations.
5. **As a** guest, **I want to** view detailed property information and photos, **so that** I can make an informed booking decision.
6. **As a** guest, **I want to** book a property for specific dates, **so that** I can secure my accommodation.
7. **As a** guest, **I want to** cancel a booking, **so that** I can adjust my plans when needed.

### Payments & Reviews
8. **As a** guest, **I want to** securely pay for my booking, **so that** my transaction is safe and protected.
9. **As a** guest, **I want to** view my booking history, **so that** I can keep track of my travels.
10. **As a** guest, **I want to** review and rate properties after my stay, **so that** I can share my experience with others.

## 🏠 Host User Stories

### Property Management
11. **As a** host, **I want to** create a property listing with details and photos, **so that** I can offer my space for rent.
12. **As a** host, **I want to** edit my property listing, **so that** I can keep the information up to date.
13. **As a** host, **I want to** delete my property listing, **so that** I can remove it from the platform when needed.
14. **As a** host, **I want to** manage my property's availability calendar, **so that** I can control when my space is bookable.

### Booking & Revenue
15. **As a** host, **I want to** view incoming booking requests, **so that** I can manage my reservations.
16. **As a** host, **I want to** receive payments for completed bookings, **so that** I can earn income from my property.
17. **As a** host, **I want to** respond to guest reviews, **so that** I can address feedback and improve my listing.

## ⚙️ Admin User Stories

### Platform Management
18. **As an** admin, **I want to** manage user accounts, **so that** I can maintain platform security and integrity.
19. **As an** admin, **I want to** moderate property listings, **so that** I can ensure content quality and compliance.
20. **As an** admin, **I want to** view system analytics and reports, **so that** I can monitor platform performance and make data-driven decisions.

## 💳 Payment System Stories

### Transaction Processing
21. **As a** payment system, **I need to** process secure transactions, **so that** guests can pay for bookings safely.
22. **As a** payment system, **I need to** handle refunds when cancellations occur, **so that** financial transactions are properly managed.

## 🎯 Acceptance Criteria (Examples)

### For Story #4 (Property Search):
- **Given** I'm on the search page
- **When** I enter the location, dates, and number of guests
- **Then** I should see relevant available properties
- **And** I should be able to filter results by price, amenities, etc.

### For Story #11 (Create Listing):
- **Given** I'm logged in as a host
- **When** I complete the property creation form
- **Then** the listing should be saved to the database
- **And** it should be visible in search results after admin approval
