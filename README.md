# tech-support-pro
Full-stack PHP/MySQL customer support system with admin dashboard, secure login, and workflow automation.
# Tech Support Pro 🖥️  
A full-stack customer support and ticket management platform built with **PHP**, **MySQL**, **HTML**, and **CSS**.  
The system enables users to submit support tickets, while admins can manage, reply, and track issues through a secure dashboard.

---

## 🚀 Features
- User and Admin Authentication (Login / Register)
- Ticket Creation, Assignment, and Resolution Workflow
- Admin Dashboard with Live Ticket Updates
- Email Notifications for Ticket Replies (`email_config.php`)
- Blog and FAQ System (`blog.php`, `view_blog.php`)
- Profile and Account Management (`profile.php`, `register.php`)
- Service and Pricing Pages (`services.php`, `pricing.php`)
- Full CRUD operations (Create, Read, Update, Delete)

---

## 🧩 Project Structure

📄 about.php → About page
📄 admin.php → Admin panel
📄 blog.php → Blog page
📄 contact.php → Contact form
📄 dashboard.php → Admin dashboard
📄 email_config.php → Email SMTP configuration
📄 index.php → Homepage (main entry)
📄 list_categories.php → Ticket category listing
📄 login.php / register.php → Authentication pages
📄 logout.php → Session handling
📄 print_tickets.php → Ticket PDF generation
📄 reply_message.php → Admin reply handler
📄 update_ticket_status.php → Status update logic
📄 view_ticket.php → User view ticket page
📄 view_ticket_admin.php → Admin view


---

## 🗄️ Database
- **Database:** `tech_support_db`
- **Tables:** `users`, `tickets`, `categories`, `messages`, `status_log`
- **Normalization:** Up to 3NF
- **ERD:** Included in `/docs/ERD.png` (add later)

---

## ⚙️ Technologies Used
**Frontend:** HTML, CSS, Bootstrap  
**Backend:** PHP (Procedural)  
**Database:** MySQL  
**Server:** Apache (XAMPP)  
**Version Control:** Git, GitHub  

---

## 📊 Key Highlights
- Reduced response time by **20%** via ticket query optimization  
- Modularized backend using PHP includes for better scalability  
- Implemented **email notifications** for ticket updates  
- Delivered as part of **CSCI 7792 – Database Systems (Spring 2025)**

---

## 🧠 Future Improvements
- Migrate to **Laravel Framework** for MVC structure  
- Add **JWT authentication** for secure API access  
- Integrate **Admin analytics dashboard (Chart.js / Power BI)**  

---

## 🧑‍💻 How to Run
1. Install **XAMPP** 
2. Place project folder inside `/htdocs`  
3. Start Apache & MySQL  
4. Import `tech_support.sql` into phpMyAdmin  
5. Visit `http://localhost/tech-support-pro`

---

## 📬 Contact
Developed by **Omar Alotaibi**  
📧 [alotaibiomar7@outlook.sa](mailto:alotaibiomar7@outlook.sa)  
🌐 [LinkedIn](https://www.linkedin.com/in/omar-alotaibi11071998/) | [Credly]([https://credly.com](https://www.credly.com/users/omar_alotaibi))
