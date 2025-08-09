# 🏥 Appointy - Doctor Appointment Web App

**Appointy** is a full-stack web application designed to make healthcare more accessible by simplifying the process of booking doctor appointments. It offers three levels of login — **Patient**, **Doctor**, and **Admin** — each with distinct features tailored to their roles.  

The app integrates online payment gateways (**Stripe** and **Razorpay**) to facilitate seamless and secure payments. Built using the **MERN** stack (MongoDB, Express.js, React.js, Node.js), Appointy provides an efficient, user-friendly experience for both patients and healthcare providers.

---

## 🛠️ Tech Stack
- **Frontend:** React.js  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Payment Gateways:** Razorpay  
- **Authentication:** JSON Web Token (JWT)  

---

## 🔑 Key Features

### 1. Three-Level Authentication
#### 👤 Patient Login:
- Sign up, log in, and book appointments with doctors.
- Manage appointments: view, cancel, or reschedule.
- Multiple payment options (Cash, Stripe, Razorpay).
- User profile with editable information (name, email, address, gender, birthday, profile picture).

#### 🩺 Doctor Login:
- Manage appointments via a dedicated dashboard.
- View earnings, patient count, appointment stats, and recent bookings.
- Update profile details (description, fees, address, availability).
- Access patient and appointment details.

#### 🛡️ Admin Login:
- Create and manage doctor profiles.
- Dashboard analytics: total doctors, total appointments, total patients, and recent bookings.
- Add new doctors (image, specialty, degree, experience, address, fees, etc.).
- Manage all appointments (cancel or mark as completed).

---

## 🏠 Home Page
- Search for doctors by specialty.  
- View top doctors and their profiles.  
- Sections: About Us, Delivery Information, Privacy Policy, Contact Us.  
- Footer with navigation links.  

---

## 🩺 All Doctors Page
- List of all doctors.  
- Filter by specialty.  
- Click on a doctor to view their **Doctor Appointment Page**.  

---

## 📄 About Page
- Appointy’s vision and mission.  
- **Why Choose Us** section:  
  - **Efficiency:** Streamlined booking process.  
  - **Convenience:** Online booking & payment.  
  - **Personalization:** Tailored experience.  

---

## 📞 Contact Page
- Office address & contact details.  
- Careers section.  
- Footer navigation links.  

---

## 📅 Doctor Appointment Page
- Doctor details: photo, qualifications, experience, description.  
- Appointment form: date, time, payment method (Cash, Stripe, Razorpay).  
- Related doctors section.  
- Requires login for booking.  

---

## 👤 User Profile
- View & edit profile (name, email, address, gender, birthday, profile picture).  
- See upcoming & past appointments.  
- Logout option.  

---

## 🗄️ Admin Panel
### Dashboard:
- Stats: doctors, appointments, patients, latest bookings.
- Cancel bookings.

### Add Doctor:
- Add doctor with image, specialty, email, password, degree, address, experience, fees, description.

### Doctor List:
- View, edit, or delete doctors.

### Appointments:
- List all appointments (patient info, date, time, doctor, fees).
- Cancel or mark as completed.

---

## 🩺 Doctor Dashboard
- **Earnings Overview** from completed appointments.  
- **Appointments List** with patient info & status management.  
- **Profile Management** (update description, fees, address, availability).  

---

## 💳 Payment Integration
- Cash Payment  
- Razorpay Integration  
- Secure transactions  

---

## 🌐 Project Setup

### Clone the Repository
```bash
git clone https://github.com/your-username/appointy.git
cd appointy

## . Install Dependencies
```bash
npm install
cd client
npm install
### Folder Structue
appointy/
├── client/          # Frontend (React.js)
├── server/          # Backend (Node.js, Express.js)
├── models/          # MongoDB Schemas
├── controllers/     # API Controllers
├── routes/          # API Routes
├── middleware/      # Authentication & Error Handling
├── config/          # Configuration Files
├── utils/           # Utility Functions
├── public/          # Static Files
└── .env             # Environment Variables

