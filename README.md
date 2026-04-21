# SwapCircleBackend

Completed Features
User System
•	Username-based login (no password) — stored in localStorage
•	Auto-prompted on first visit
Item Listings
•	Add Item — title, description, price, condition, category, image upload (drag & drop)
•	Browse Items — search by keyword, filter by category, sort by price/newest
•	Item Cards — thumbnail, price, condition badge
•	Item Modal — full detail view with image, description, owner info
Offers
•	Submit a price offer on any item
•	Owner can Accept / Decline offers
•	Status tracking: PENDING → ACCEPTED / REJECTED
•	(Bug just fixed — amount was not displaying due to field name mismatch)
In-App Chat
•	Real-time messaging per item (polls every 3 seconds)
•	Buyer ↔ Seller conversation inside item modal
Image Upload
•	Upload images when listing items
•	Images served from ~/swapcircle-uploads/
Static Pages
•	Home — hero, category shortcuts, latest listings, "How It Works" section
•	Services — displays 6 service categories
•	Contact — contact form (frontend-only, no email sending)
 
Notable Limitations
•	No database — all data is in-memory, resets on server restart
•	No authentication — anyone can type any username
•	No notifications — no alerts when offer is accepted or chat received
•	Contact form — doesn't actually send emails
 

<img width="482" height="674" alt="image" src="https://github.com/user-attachments/assets/c941850a-1ab1-4fce-a3b0-6d9fb4806624" />
