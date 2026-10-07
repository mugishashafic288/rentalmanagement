RENTAL MANAGEMENT SYSTEM
Try now (no server): open login.html. Landlord: admin@rms.ug / admin123. Tenants: use "Create account" on the login page.
Go live (PHP + MySQL): 1) import backend/schema.sql  2) edit backend/config.php credentials  3) open backend/setup.php once, then delete it
4) in js/app.js set DEMO=false  5) serve the folder with Apache/XAMPP (PHP 8+).
Security: tenant sign-up always creates role 'tenant'; no route can create an admin. Tenants can only add/read their own bookings, payments and complaints.
Tenant pages: tenant/index.html (houses, prices, room photos, booking) and tenant/portal.html (bookings, payments, complaints).
Room photos: paste image URLs (comma-separated) on a property; if empty, placeholder room scenes are shown.
