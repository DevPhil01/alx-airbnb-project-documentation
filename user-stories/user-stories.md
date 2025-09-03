# Airbnb Clone User Stories 
## 1. User Registration & Login
**User Story:**  
As a guest or host, I want to register and log in with my email or phone so that I can access the platform and manage my bookings or properties.

**Acceptance Criteria:**  
- **Given** I am on the registration page,  
- **When** I enter valid credentials and submit,  
- **Then** my account should be created and I should receive a confirmation email.  

- **Given** I am a registered user,  
- **When** I provide correct login credentials,  
- **Then** I should gain access to my dashboard.

---

## 2. Search & Filter Properties
**User Story:**  
As a guest, I want to search and filter properties by location, price range, amenities, and availability so that I can find the best match for my stay.

**Acceptance Criteria:**  
- **Given** I am logged in,  
- **When** I enter search criteria (e.g., location, dates, price),  
- **Then** the system should return a list of matching properties.

- **Given** I refine filters (e.g., add amenities),  
- **When** I update my search,  
- **Then** the results should refresh accordingly.

---

## 3. Book Property
**User Story:**  
As a guest, I want to select a property, choose dates, and book it so that I can reserve accommodation for my trip.

**Acceptance Criteria:**  
- **Given** I am logged in and viewing a property,  
- **When** I select dates and click “Book Now,”  
- **Then** a booking record should be created with pending status.

- **Given** a booking is confirmed,  
- **When** I view my bookings dashboard,  
- **Then** I should see the booking listed.

---

## 4. Make Payment
**User Story:**  
As a guest, I want to securely pay for my booking using a preferred method (credit card, PayPal, etc.) so that I can confirm my stay instantly.

**Acceptance Criteria:**  
- **Given** I have a pending booking,  
- **When** I provide payment details and submit,  
- **Then** the payment should be processed, and the booking status should update to “confirmed.”

- **Given** payment fails,  
- **When** I attempt to pay,  
- **Then** the system should notify me of the failure and allow retry.

---

## 5. Cancel Booking
**User Story:**  
As a guest, I want to cancel a booking within the allowed cancellation window so that I can get a refund if eligible.

**Acceptance Criteria:**  
- **Given** I have a confirmed booking,  
- **When** I request cancellation before the cutoff,  
- **Then** the system should cancel the booking and initiate a refund.

- **Given** the cancellation window has expired,  
- **When** I attempt to cancel,  
- **Then** the system should prevent the action and notify me.

---

## 6. Leave Review & Rating
**User Story:**  
As a guest, I want to leave a review and rating after my stay so that I can share my experience with other users.

**Acceptance Criteria:**  
- **Given** my booking has ended,  
- **When** I submit a review and rating,  
- **Then** the system should save and display it under the property.

---

## 7. List Property
**User Story:**  
As a host, I want to add new property listings with descriptions, images, and prices so that guests can view and book them.

**Acceptance Criteria:**  
- **Given** I am a verified host,  
- **When** I fill in property details and submit,  
- **Then** the property should be listed and visible to guests.

---

## 8. Manage Availability
**User Story:**  
As a host, I want to update my property’s calendar so that guests can only book available dates.

**Acceptance Criteria:**  
- **Given** I have listed a property,  
- **When** I update its availability,  
- **Then** the system should reflect the changes immediately.

---

## 9. Accept/Reject Booking
**User Story:**  
As a host, I want to accept or reject booking requests so that I can control who stays at my property.

**Acceptance Criteria:**  
- **Given** I receive a booking request,  
- **When** I accept it,  
- **Then** the guest should be notified, and the booking status should change to “confirmed.”

- **Given** I reject the request,  
- **When** I submit rejection,  
- **Then** the guest should be notified, and the booking should be canceled.

---

## 10. Manage Users (Admin)
**User Story:**  
As an admin, I want to view, edit, or deactivate user accounts so that I can maintain platform security and compliance.

**Acceptance Criteria:**  
- **Given** I am an admin,  
- **When** I deactivate a user account,  
- **Then** the user should lose access to the platform.

---

## 11. Resolve Disputes (Admin)
**User Story:**  
As an admin, I want to review and resolve disputes between guests and hosts so that conflicts are fairly settled.

**Acceptance Criteria:**  
- **Given** a dispute exists,  
- **When** I resolve it,  
- **Then** both parties should receive a resolution notification.

---

## 12. System Settings & Reports (Admin)
**User Story:**  
As an admin, I want to update system settings and generate reports so that I can monitor platform performance and operations.

**Acceptance Criteria:**  
- **Given** I am an authenticated admin,  
- **When** I change system settings or generate a report,  
- **Then** the changes or reports should be stored for future reference.
