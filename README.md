# Purpose
This application serves as a template to integrate tracking of guest users on site. Its mainly intended for keeping track of how many views a page gets. The cookie is included in the implementation so one user isn't repeatedly counted every time they visit a site. The page count only goes up if the guest user with the cookie visits the page for the first time with that cookie. Cookies can expire or be deleted from the clients browser, but generally the cookie stays alive for either a year or the length until session timeout. Only tracking through the “guest_id” cookie, so the logged in users cookie “session” would not double count a page visit

# cookie

The cookie is a jwt which limits database lookups to the logging in request.

# Demo

- Intended as a base for building on

<img width="908" height="574" alt="image" src="https://github.com/user-attachments/assets/7bcfc22d-d249-4293-8093-f5fa53bfe7e4" />
