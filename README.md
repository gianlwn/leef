# LEEF (Local Educational Event Finder)

## Description

LEEF is a mobile application that helps students, teachers, event organizers, school administrators, parents, and freelancers in the Philippines discover and participate in local educational events. The app addresses the lack of a centralized platform for event discovery by giving users a single feed of seminars, competitions, and school-related activities that they can search and filter by interest, location, and date. Users can register for an event directly in the app, which adds it to their personal event dashboard and sends a reminder before it starts. Event organizers can post and promote their own events to reach a wider audience, and users can message each other to build connections within the academic community. After attending an event, users are prompted to leave feedback, helping organizers improve future events.

## Services / APIs

Backend Server (Firebase)

- To store and verify user credentials, event listings, and registrations
- To handle scheduling of event reminder notifications

**Google Maps API**

- Used to display event locations and help users find directions to a venue

**Push Notification Service**

- Used to remind users of events they registered for or saved

**Messaging Service**

- Enables in-app messaging between users, organizers, and attendees
- Email API (e.g., SendGrid/Firebase Extensions) - sends registration confirmations, event reminders, and notifications to a user's email
- Social Media Share API (Facebook, Instagram, X) - lets users share an event or their experience directly to their social media accounts

**Payment Gateway API (e.g., PayMongo/Xendit)**

- Processes payments for paid event registrations and organizer event boosts (GCash, Maya, or card)

## Scope of Work

| Function              | Description                                                                                                                                                                                                    |
| --------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Register              | The user must create an account before accessing the app's features.<br>Users provide their full name, school/organization, email, role<br>(student, teacher, organizer, parent, or freelancer), and password. |
| Log-in                | The user must log in with a registered email and password before<br>joining or posting an event.                                                                                                               |
| View Event List       | The user can browse a centralized feed of educational events<br>(seminars, competitions, school activities) with basic details shown for<br>each listing.                                                      |
| View Event Details    | Selecting an event shows its complete details, including date, venue,<br>organizer, tags, and pricing.                                                                                                         |
| Filter/Search Events  | The user can search by keyword and filter events by date, location,<br>category, age group, and price (free or paid).                                                                                          |
| Create/Post Event     | Event organizers (schools, clubs, or admins) can create and publish a<br>new event listing, attach files, and set tags and pricing.                                                                            |
| Register/Join Event   | The user can register for an event directly through the app; the event is<br>added to the user's personal event dashboard.                                                                                     |
| Event Reminders       | The app sends a notification to remind the user of an upcoming event<br>they registered for.                                                                                                                   |
| Boost/Promote Event   | Organizers may pay a small fee to feature their event with better<br>visibility and reach.                                                                                                                     |
| Pay for Event/Boost   | The user completes payment for a paid event registration or an<br>organizer's event boost through an integrated payment gateway (e.g.,<br>GCash, Maya, or card).                                               |
| Messaging             | Users can message other users, event organizers, or attendees to build<br>connections within the academic community.                                                                                           |
| Notifications (Email) | The app sends registration confirmations, reminders, and updates to<br>the user's registered email address.                                                                                                    |
| Share to Social Media | Users can share an event listing or their event experience to Facebook,<br>Instagram, or X to help organizers reach a wider audience.                                                                          |
| Feedback              | After an event, the app prompts the user to rate the event and share<br>feedback, helping organizers improve future events.                                                                                    |
