# 📚 RebookNg - ระบบร้านหนังสือออนไลน์

RebookNg เป็นโปรเจกต์ระบบร้านหนังสือออนไลน์ พัฒนาโดยใช้ Angular (Frontend) และ Spring Boot (Backend) รองรับการจัดการหนังสือ คำสั่งซื้อ ตะกร้าสินค้า ผู้ขาย ผู้ใช้ และรีวิว

---

## 🚀 Tech Stack

| Layer        | Technology         |
|--------------|--------------------|
| Frontend     | Angular 18         |
| Backend      | Spring Boot        |
| Styling      | Bootstrap / Tailwind (เลือกได้) |
| Database     | MySQL / PostgreSQL |
| Auth         | Google Login (OAuth2), JWT      |

---

## 📦 โฟลเดอร์โครงสร้างหลัก (Frontend)

```
src/
├── app/
│   ├── core/          # Auth guard, Interceptors, Services
│   ├── shared/        # Components ที่ใช้ร่วมกัน
│   ├── modules/       # Feature Modules (book, cart, order, user)
│   └── app-routing.module.ts
│   └── app.module.ts
```

---

## 🔧 การติดตั้งโปรเจกต์

### 1. Clone โปรเจกต์

```bash
git clone https://github.com/sodelight26/rebook-ng.git
cd rebook-ng
```

### 2. ติดตั้ง dependencies

```bash
npm install
```

### 3. รัน Angular dev server

```bash
ng serve
```

> เปิดเว็บที่ `http://localhost:4200`

---

## 📘 คำสั่งอื่นที่ใช้งานบ่อย

### สร้าง Component, Module, Service:

```bash
ng generate component components/book-list
ng generate service services/book
ng generate module modules/book --routing
```

---

## 🧪 Unit Testing

```bash
ng test
```

## ⚙️ Build

```bash
ng build
```

---

## 🔐 ระบบ Authentication

- Login ด้วย Google (OAuth2)
- ตรวจสอบ token ด้วย Interceptor
- Backend รองรับการ verify Google ID token และออก JWT

---

## ✅ ฟีเจอร์ในระบบ

- 🔍 ค้นหาหนังสือ
- 🛒 เพิ่มสินค้าลงตะกร้า
- 📦 ทำรายการสั่งซื้อ
- 📝 รีวิวหนังสือ
- 🧍‍♀️ ระบบผู้ใช้ + ผู้ขาย
- 📊 จัดการสินค้า + แพ็กสินค้า
- 🔔 การแจ้งเตือน (Notification)

---

## 👨‍💻 ผู้พัฒนา

> พัฒนาโดย [@sodelight26](https://github.com/sodelight26)  
> หากคุณชอบโปรเจกต์นี้ ฝาก ⭐ ไว้ที่ GitHub ด้วยนะครับ!
