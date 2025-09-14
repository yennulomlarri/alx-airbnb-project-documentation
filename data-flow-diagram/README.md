# Data Flow Diagram - Airbnb Clone

## Diagram Overview
![Data Flow Diagram](data-flow-diagram.png)

## Components Description

### External Entities
1. **Guest**: User searching and booking properties
2. **Host**: User listing and managing properties
3. **Admin**: System administrator managing platform
4. **Payment Gateway**: External payment processing service (Stripe/PayPal)
5. **Email Service**: External email notification service

### Processes
1. **User Authentication**: Handles user registration, login, and profile management
2. **Property Management**: Manages property listings, updates, and searches
3. **Booking Processing**: Handles reservation creation, modification, and cancellation
4. **Payment Handling**: Processes financial transactions and payouts
5. **Review Management**: Manages property reviews and ratings
6. **Admin Management**: Handles system oversight and moderation

### Data Stores
1. **Users DB**: Stores user accounts, profiles, and authentication data
2. **Properties DB**: Stores property listings, amenities, and availability
3. **Bookings DB**: Stores reservation details, dates, and statuses
4. **Payments DB**: Stores transaction records and payment status
5. **Reviews DB**: Stores property reviews and ratings

## Data Flow Description

### Authentication Flow
1. Guest → (Registration data) → User Authentication → (User data) → Users DB
2. User Authentication → (Confirmation email) → Email Service → Guest

### Property Management Flow
3. Host → (Property details) → Property Management → (Listing data) → Properties DB
4. Guest → (Search criteria) → Property Management → (Search results) → Guest

### Booking Flow
5. Guest → (Booking request) → Booking Processing → (Reservation data) → Bookings DB
6. Booking Processing → (Payment request) → Payment Handling → (Transaction) → Payment Gateway

### Payment Flow
7. Payment Gateway → (Payment confirmation) → Payment Handling → (Transaction record) → Payments DB
8. Payment Handling → (Payout instruction) → Payment Gateway → Host

### Review Flow
9. Guest → (Review content) → Review Management → (Review data) → Reviews DB
10. Review Management → (Review notification) → Email Service → Host

### Admin Flow
11. Admin → (Moderation action) → Admin Management → (Updated data) → Various Databases
12. Admin Management → (System reports) → Admin
