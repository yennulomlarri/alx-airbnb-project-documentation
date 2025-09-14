# Use Case Diagram - Airbnb Clone

## Diagram Overview
![Use Case Diagram](use-case-diagram.png)

## Actors Description

### 1. Guest
- **Description**: Users who search for and book properties
- **Responsibilities**: Search properties, make bookings, make payments, write reviews

### 2. Host  
- **Description**: Users who list and manage properties
- **Responsibilities**: Create listings, manage availability, handle bookings, receive payments

### 3. Admin
- **Description**: System administrator managing the platform
- **Responsibilities**: User management, content moderation, financial oversight

### 4. Payment System
- **Description**: External payment processing service
- **Responsibilities**: Handle financial transactions securely

## Use Cases Description

### Authentication
- **Register Account**: New users create an account
- **Login/Logout**: Users authenticate into the system
- **Update Profile**: Users manage their personal information

### Property Management  
- **Create Listing**: Hosts add new properties
- **Edit Listing**: Hosts modify property details
- **Delete Listing**: Hosts remove properties
- **Search Properties**: Guests find accommodations
- **View Property Details**: See complete property information

### Booking System
- **Book Property**: Reserve a property for dates
- **Cancel Booking**: Cancel a reservation
- **View Booking History**: See past and upcoming bookings

### Payment Processing
- **Make Payment**: Process booking payments
- **Receive Payouts**: Hosts receive earnings

### Reviews & Ratings
- **Write Review**: Guests review properties
- **Respond to Review**: Hosts answer reviews

### Admin Functions
- **Manage Users**: Admin controls user accounts
- **Moderate Listings**: Admin reviews property listings
- **View Reports**: System analytics and financial reports

## Relationships
- **Include**: Authentication required for booking
- **Extend**: Payment processing extends booking
- **Association**: Actors connected to their use cases
