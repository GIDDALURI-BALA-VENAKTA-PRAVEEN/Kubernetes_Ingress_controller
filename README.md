2. Why Use an Ingress Controller?
•	Single entry point — one NodePort for all apps, not one per app
•	URL-based routing — /app01 and /app02 hit different backends
•	Domain-based routing support — api.company.com, app.company.com
•	SSL/TLS termination at the ingress level
•	Centralized traffic management: rate limiting, auth, redirects

