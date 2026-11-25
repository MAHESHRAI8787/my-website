# HomeNest — Real Estate Listing Platform

## Project objective
Build a responsive real-estate listing platform that demonstrates front-end web development, UI design, search/filtering, property presentation and basic form interaction.

## Technologies
- HTML5
- CSS3
- JavaScript (ES6)
- Google Fonts
- Browser LocalStorage for favourites

## Main features
1. Responsive navigation
2. Hero section with property search
3. Location, property-type and budget filters
4. Dynamic property cards
5. Property detail modal
6. Favourite button using LocalStorage
7. Services section
8. About/project section
9. Contact/enquiry form
10. Mobile responsive layout

## How to run
Open `index.html` directly in Chrome, Safari or VS Code Live Server.

## Future database integration
For a complete full-stack version, connect the UI to MySQL/MongoDB through Node.js/Express or PHP. A database can store users, properties, enquiries and favourites.

## Suggested database tables
- users(user_id, name, email, password)
- properties(property_id, title, location, type, price, bedrooms, bathrooms, area, description)
- enquiries(enquiry_id, user_id, property_id, message, created_at)
- favourites(user_id, property_id)

## Academic project modules
- Home / Search
- Property Listings
- Property Details
- User Enquiry
- Admin/Property Management (future extension)
