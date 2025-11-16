✨ Mohamed Awad — Backend Developer (Node.js / ExpresJs | NestJs)
<p align="left">
I’m Mohamed Awad, a Control & Computer Systems Engineer from Egypt with a deep passion for *backend development, **system architecture, and **scalable distributed systems*.
</p>

🚀 About Me
<p align="left">
💻 Backend Engineer focused on building scalable, secure, high-performance systems<br>
📚 Currently improving in *System Design, **SOLID, **Clean Architecture, and **Docker*<br>
🧠 Strong background in *C++, **Data Structures, and **OOP Principles*<br>
⚡ Experienced with *Node.js, **TypeScript, **MongoDB, **Redis, **Socket.io, and **Real-Time Apps*<br>
🎯 Goal: Build production-level backend systems with real-time communication, queues, caching, and microservices patterns  
</p>

🛠 I Code With
<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="40" />
  <img width="12"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" />
  <img width="12"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" />
  <img width="12"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" />
  <img width="12"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/6/64/Expressjs.png" height="40"/>
  <img width="12"/>
  <img src="https://nestjs.com/img/logo-small.svg" height="40"/>
  <img width="12"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="40" />
  <img width="12"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" />
  <img width="12"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sequelize/sequelize-original.svg" height="40" />
  <img width="12"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" />
  <img width="12"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" />
  <img width="12"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" height="40" />
</div>

📂 Notable Projects
🚀 Social Media Platform
Overview:
A full-featured, real-time social media backend built with Node.js, TypeScript, MongoDB, Redis, Socket.io, and BullMQ, following SOLID principles and clean OOP architecture.
Designed for scalability, security, and production-ready deployment with Docker, PM2, and AWS EC2 + Nginx.
Features:


Real-time chat (1:1 & group) with typing indicators and delivery status.

Real-time notifications (read/unread) via Socket.io.

User management: registration, login, roles, freeze/unfreeze, soft delete.

Posts & comments with AWS S3 media uploads.

Friend system with caching and efficient search.

BullMQ queues for background emails and notifications.

Redis caching for sessions, rate-limiting, and presence tracking.

Tech Stack: Node.js, TypeScript, Express, MongoDB, Redis, BullMQ, Socket.io, AWS, Docker, PM2

🛒 E-Commerce Platform
Overview:
منصة تجارة إلكترونية متكاملة لإدارة المنتجات، الطلبات، وحسابات المستخدمين. تم تطويرها مع التركيز على الأداء، الأمان، والتوسع، مع دعم الكاش والمهام المؤجلة (small Amazon).
Tech Stack:

Node.js, Express

MongoDB, Mongoose

Redis, BullMQ

JWT, bcrypt

AWS (Deployment)

Swagger (API Docs)

Features:


تسجيل الدخول والتسجيل للمستخدمين + إدارة الحسابات.

إدارة المنتجات (إضافة، تعديل، حذف) + عرض أعلى المنتجات مبيعًا وتقييمًا.

إدارة الطلبات مع إلغاء تلقائي للطلبات Pending بعد 4 أيام باستخدام BullMQ + Node-Cron.

Stripe Integration لدفع آمن بالبطاقات.

OTP عبر Redis للتحقق من البريد الإلكتروني واسترجاع الحساب.

نظام Ban/Unban للمستخدمين مع تخزين الكاش في Redis

Email Queue & Notification Queue لإرسال التنبيهات غير المتزامنة.

Security:

JWT + Refresh Tokens


التخزين الآمن في Cookies + Redis

إلغاء Refresh Tokens عند تغيير أو إعادة تعيين كلمة المرور.

bcrypt لتشفير كلمات المرور.

Helmet & CORS لتأمين الـ API.

Rate Limiting للحماية من الهجمات.

Global Error Handling موحد.

Deployment: AWS + MongoDB Atlas + Redis

✉ Saraha Anonymous Messaging
Overview:
منصة لإرسال واستقبال رسائل مجهولة مع الرد عليها، مع التركيز على الأمان والخصوصية والتوسع.
Tech Stack: Node.js, Express, MongoDB, Redis, Cloudinary, Nodemailer, JWT, bcrypt
Features:


إرسال واستقبال رسائل مجهولة + الرد عليها.

رفع صور وملفات عبر Cloudinary.

OTP عبر Redis لتأكيد البريد الإلكتروني وإعادة تعيين كلمة المرور.

Email notifications لتأكيد الحساب واستعادة الوصول.

استخدام Transactions لضمان الاتساق.

Security:

JWT + Refresh Tokens، تخزين في Cookies + Redis

bcrypt لتشفير كلمات المرور

Helmet & CORS

Global Error Handling

Deployment: EvenNode

🎓 Online Courses Platform
Overview:
نظام إدارة كورسات مع حجز وتصنيف، مع Workflow متكامل وإيميلات تأكيد.
Tech Stack: Node.js, Express, PostgreSQL + Sequelize, Nodemailer, JWT, bcrypt
Features:


عرض الكورسات حسب Category

Search بالكلمات المفتاحية

أكثر الكورسات حجزًا
Workflow للحجز: Pending → Confirmed

Email confirmations

Security: JWT + bcrypt + Helmet & CORS + Global Error Handling

🦷 Dental Clinic DB Design
Overview:
تصميم قاعدة بيانات متكاملة لإدارة عيادة أسنان مع نظام حجز ومتابعة.
Tech Stack: MySQL, Cloudinary, Node-Cron, Nodemailer, ExpressJS
Features:


نظام حجز كامل مع تشفير أرقام الهواتف


OTP عبر الإيميل لتأكيد الحجز

رفع صور وملفات عبر Cloudinary

استخراج الحجوزات اليومية والشهرية

تذكير تلقائي عبر الإيميل الساعة 9 صباحًا

هيكلة قاعدة بيانات منظمة بعلاقات Users – Doctors – Bookings – Advice


📫 Contact Me

📧 Email: mohamedahmedawad180@gmail.com

🌍 Location: Egypt
💬 Open for backend collaborations or DB design projects


“The only way to do great work is to love what you do.” – Steve Jobs
