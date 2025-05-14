# Module 1: Plan & Track

This module outlines the planning and foundational decisions for the Library Management System project. It defines the problem scope, intended users, functional goals, and technology stack. It also provides a high-level architecture that will guide the rest of the DevOps pipeline.

---

## Objectives
- Digitize book lending and return processes
- Enable CRUD operations for books and borrowers
- Provide a secure and scalable backend
- Deploy using a fully automated DevOps pipeline on Google Cloud

## Key Roles
- Developers: Build and test the Django application
- DevOps Engineers: Set up CI/CD and deployment pipelines
- Admin Users: Use the Django admin to manage library data

## Use Cases

1. **Librarian adds new books**
   - Add/update book title, author, ISBN, availability

2. **Borrower checks out a book**
   - Borrower details recorded with borrow/return dates

3. **Admin views overdue books**
   - Highlight borrowed books past return date

4. **System maintains audit log**
   - All transactions (add, update, borrow, return) are timestamped

5. **Web Interface**
   - Accessible UI for staff with basic authentication

## Technology Stack

### Backend
- Django (Python)
- SQLite (for development) / PostgreSQL (for production)

### Frontend
- Django Admin
- Optional: Bootstrap/CSS for public-facing portal

### DevOps & Deployment
- GitHub Actions (CI)
- Docker (Containerization)
- Google Cloud Run (CD)
- Google Artifact Registry

### Monitoring & Logging
- Google Cloud Monitoring
- Google Cloud Logging