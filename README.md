# Be_Positive
# 🩸 BePositive - Blood Donation Management System

BePositive is a Django-powered web application that streamlines the process of blood donation, management, and request handling. It supports three types of users — **Admins**, **Donors**, and **Patients** — each with their own specific roles and functionalities to maintain an efficient blood donation system.

---
##Admin Dashboard Capabilities:
View:

Units of blood available by group

Number of donors

Number of blood requests

Number of approved requests

Total blood units in stock

Manage Donors:

View / Update / Delete donor details

Manage Patients:

View / Update / Delete patient records

Manage Blood Donation Requests:

View requests submitted by donors

Approve/reject requests based on donor health (e.g., disease status)

On approval, donated blood is added to stock

On rejection, 0 units are added

Manage Blood Requests (by Donors or Patients):

Approve/reject blood requests

On approval, blood units are reduced from stock

On rejection, 0 units are deducted

View history of all blood requests

Update unit count for a specific blood group

##🩸 Donor
Donor Capabilities:
Register with basic details

Login to:

Submit a Blood Donation Request

Added to stock only after admin approval

View donation history with statuses:

Pending, Approved, Rejected

Submit Blood Requests

View blood request history with statuses

Dashboard summary:

Total blood requests made

Approved, Pending, and Rejected request counts

✅ Note: A Donor can donate and also request for blood.

##🧑‍⚕️ Patient
Patient Capabilities:
Sign up and log in without admin approval

After login:

Request blood for specific blood group and unit

View request history with statuses:

Pending, Approved, Rejected

Dashboard summary:

Total blood requests made

Approved, Pending, and Rejected counts

## 🔑 User Roles & Functions

### 👩‍💼 Admin

To create an admin account, run:

```bash
py manage.py createsuperuser




