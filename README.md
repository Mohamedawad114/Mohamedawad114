<h1 align="left">Hey 👋 What's up?</h1>

###

<p align="left">My name is Mohamed Awad and I'm a Control and Computer Systems Engineer from Egypt.</p>

###

<h2 align="left">About me</h2>

###

<p align="left">
💻 Passionate about backend development and software architecture<br>
📚 Currently learning and working with modern web technologies like NestJS, TypeScript, and MongoDB<br>
🧠 Solid foundation in C++, Data Structures, and Object-Oriented Programming (OOP)<br>
🎯 Goal: Build scalable, secure, and well-structured backend systems for real-world applications<br>
</p>

###

<h2 align="left">I code with</h2>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="40" alt="C++ logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="JavaScript logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="TypeScript logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" height="40" alt="Node.js logo" />
  <img width="12" />
<img src="https://upload.wikimedia.org/wikipedia/commons/6/64/Expressjs.png" height="40" alt="Express.js logo" />
  <img width="12" />
  <img src="https://nestjs.com/img/logo-small.svg" height="40" alt="NestJS logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="40" alt="MongoDB logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" alt="MySQL logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sequelize/sequelize-original.svg" height="40" alt="Sequelize logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="40" alt="HTML5 logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="40" alt="CSS3 logo" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" height="40" alt="Bootstrap logo" />
</div>

###

<h2 align="left">📂 Notable Projects</h2>
# 🚀 My Backend Projects

هنا مجموعة من المشاريع العملية اللي قمت بتطويرها باستخدام **Node.js** و**Databases مختلفة** (MongoDB, PostgreSQL, MySQL,Expressjs).  
التركيز الأساسي كان على: **الأمان – الأداء – التجربة العملية – الـ Deploy**.  

---
## 🛒 E-commerce Platform

**Overview:**
منصة تجارة إلكترونية متكاملة لإدارة المنتجات، الطلبات، وحسابات المستخدمين. تم تطويرها مع التركيز على الأداء، الأمان، والتوسع، مع دعم الكاش والمهام المؤجلة (small Amazon).

**Tech Stack:**

- Node.js, Express
- MongoDB, Mongoose
- Redis, BullMQ
- JWT, bcrypt
- AWS (Deployment)
- Swagger (API Docs)

**Features:**

- تسجيل الدخول والتسجيل للمستخدمين + إدارة الحسابات. 
- إدارة المنتجات (إضافة، تعديل، حذف) + عرض أعلى المنتجات مبيعًا وتقييمًا.
- ادارة الطلبات مع إلغاء تلقائي للطلبات Pending بعد 4 أيام باستخدام BullMQ + Node-Cron.
- OTP عبر Redis للتحقق من البريد الإلكتروني واسترجاع الحساب.
- نظام Ban/Unban للمستخدمين مع تخزين الكاش في Redis.
- Email Queue & Notification Queue لإرسال تنبيهات البريد الإلكتروني بشكل غير متزامن.

**Security:**

- JWT + Refresh Tokens

- التخزين الآمن في Cookies + Redis
- إلغاء Refresh Tokens عند تغيير أو إعادة تعيين كلمة المرور.
- bcrypt لتشفير كلمات المرور.
- Helmet & CORS لتأمين الـ API.
- Rate Limiting للحماية من الهجمات.
- Global Error Handling موحد.
- API Documentation:

- موثق باستخدام Swagger (OpenAPI) لتسهيل اختبار الـ Endpoints والتكامل مع الخدمات الأخرى.

**Deployment:**

- مرفوع على AWS مع إعدادات إنتاج كاملة (MongoDB Atlas + Redis).
## ✉️ Saraha Anonymous Messaging
**Overview:**  
منصة تتيح إرسال رسائل مجهولة والرد عليها بدون كشف الهوية. تم تصميمها مع التركيز على **الأمان** و**الخصوصية** و**التوسع**.

**Tech Stack:**  
- Node.js, Express  
- MongoDB, Redis  
- Cloudinary, Nodemailer  
- JWT, bcrypt  
- Deploy على EvenNode  

**Features:**  
- إرسال واستقبال رسائل مجهولة + الرد عليها.  
- رفع صور وملفات عبر **Cloudinary**.  
- **OTP عبر Redis** لتأكيد البريد الإلكتروني وإعادة تعيين كلمة المرور.  
- إرسال **إيميلات تنبيهية** لتأكيد الحساب واستعادة الوصول.  
- استخدام **Transactions** لضمان الاتساق في العمليات الحساسة.  

**Security:**  
- **JWT + Refresh Tokens**:  
  - التخزين في Cookies + Redis.  
  - حذف Refresh Tokens تلقائيًا عند تغيير أو إعادة ضبط كلمة المرور.  
- **bcrypt** لتشفير كلمات المرور.  
- **Helmet & CORS** لحماية الـ API.  
- **Global Error Handling** موحد.  

**Deployment:**  
- مرفوع على **EvenNode** مع إعدادات إنتاج كاملة.  

---

## 🎓 Online Courses Platform
**Overview:**  
نظام إدارة كورسات مع خاصية الحجز والتصنيف، مع **Booking Workflow** متكامل وإيميلات تأكيد.  

**Tech Stack:**  
- Node.js, Express  
- PostgreSQL + Sequelize ORM  
- Nodemailer  
- JWT, bcrypt  

**Features:**  
- عرض الكورسات حسب **Category**.  
- **Search** بالكلمات المفتاحية.  
- إظهار **أكثر الكورسات حجزًا**.  
- Workflow للحجز: يبدأ `Pending` → يتحول `Confirmed` بعد موافقة الأدمن.  
- إرسال **إيميل تأكيد** عند تأكيد الحجز.  

**Security:**  
- **JWT + bcrypt** لتأمين الحسابات.  
- **Helmet & CORS** كطبقة حماية إضافية.  
- **Global Error Handling** لإدارة الأخطاء بشكل احترافي.  

---

## 🦷 Dental Clinic DB Design
**Overview:**  
تصميم قاعدة بيانات متكاملة لإدارة عيادة أسنان مع **نظام حجز ومتابعة**.  

**Tech Stack:**  
- MySQL  
- Cloudinary  
- Node-cron + Nodemailer 
- ExpressJs

**Features:**  
- نظام حجز كامل مع تشفير أرقام الهواتف.  
- **OTP عبر الإيميل** لتأكيد الحجز.  
- رفع صور وملفات عبر Cloudinary.  
- استخراج الحجوزات اليومية والشهرية.  
- تذكير تلقائي عبر الإيميل عند الساعة 9 صباحًا في يوم الحجز.  
- هيكلة قاعدة بيانات **منظمة ومطبعة (Normalized)** بعلاقات واضحة بين (Users – Doctors – Bookings – Advice).  

## 🧾 Blog API System  
**Overview:**  
نظام **RESTful API** لإدارة المدونات (Blogs) مبني باستخدام Node.js و MySQL مع Sequelize ORM.  
يدعم كامل العمليات (CRUD) بالإضافة إلى ميزات متقدمة مثل البحث والصفحات (Pagination) وإدارة الصلاحيات.  
**Tech Stack:**  
- Node.js, Express  
- MySQL + Sequelize ORM  
- Multer (لرفع الصور والفيديوهات)  

**Features:**  
- CRUD كامل (إنشاء – تحديث – حذف – قراءة).  
- **Validation & Authentication** مع التحكم في الأدوار (Admins / Users).  
- رفع الصور والفيديوهات باستخدام **Multer**.  
- التأكد من **ملكية التدوينة** (Blog Ownership Check).  
- **Pagination & Search** لعرض المحتوى بكفاءة.  
- **Soft Delete** بدل الحذف النهائي.  

**Security:**  
- **Helmet** لحماية الـ API.  
- **dotenv** لإدارة المتغيرات السرية.  

---
## 🔐 Notes App – Secure Notes Management  
**Overview:**  
تطبيق لإدارة الملاحظات بشكل آمن مع دعم كامل للمصادقة والجلسات.  
مبني مع التركيز على **الأمان** و **التحكم في الوصول**.  
**Tech Stack:**  
- Node.js, Express  
- Redis (لـ Rate Limiting + OTP)  
- JWT, bcrypt, Joi  

**Features:**  
- **OTP System** لتأكيد البريد الإلكتروني وإعادة تعيين كلمة المرور.  
- مصادقة باستخدام **JWT** مع إدارة كاملة للجلسات.  
- **Encrypted Phone Numbers** لتأمين بيانات المستخدمين.  
- التحقق من صحة الإدخال (Validation) باستخدام **Joi**.  

**Security:**  
- **bcrypt** لتشفير كلمات المرور.  
- **Helmet + HPP** للحماية من الهجمات الشائعة.  
- **dotenv** لإدارة المفاتيح والبيئة السرية.  
- Redis لعمل **Rate Limiting** ومنع محاولات الاختراق.  

###

<h2 align="left">📫 How to reach me</h2>

- 📧 Email: mohamedahmedawad180@gmail.com  
- 🌍 Location: Egypt  
- 💬 Always open to backend collaboration or DB design projects

---

> “The only way to do great work is to love what you do.” – *Steve Jobs*
