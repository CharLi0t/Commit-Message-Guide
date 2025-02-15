# Commit-Message-Guide

## 🔹 ตัวอย่าง Commit Message ตามประเภทงาน

### 📌 1. เพิ่มฟีเจอร์ใหม่ (`feat`)

```sh
feat(auth): implement JWT authentication

Added JWT-based authentication for securing API endpoints. 
This replaces the old session-based authentication.
```

```sh
feat(ui): add dark mode toggle

Added a new dark mode toggle in the settings page.
The preference is stored in local storage.
```

```sh
feat(api): support pagination in user list

Implemented offset-based pagination for better performance.
Users can now request data in chunks instead of retrieving all at once.
```

---

### 🐞 2. แก้บั๊ก (`fix`)

```sh
fix(api): resolve 500 error on login

Fixed an issue where a missing token caused a server crash.
Now returns a 401 Unauthorized response instead.
```

```sh
fix(ui): fix broken navigation menu on mobile

Updated CSS styles to correctly display the navigation 
menu on small screens.
```

```sh
fix(db): correct column name in migration script

Changed `userName` to `username` in the migration script 
to align with the database schema.
```

---

### 🔧 3. ปรับโค้ด (Refactoring) (`refactor`)

```sh
refactor(auth): extract token validation logic

Moved token validation logic to a separate utility function
to improve code reusability and maintainability.
```

```sh
refactor(ui): optimize rendering of large lists

Replaced map function with virtualization to improve 
performance when displaying large datasets.
```

```sh
refactor(api): use async/await instead of promises

Refactored API calls to use async/await syntax 
for better readability and error handling.
```

---

### 📖 4. อัปเดตเอกสาร (`docs`)

```sh
docs(readme): update installation instructions

Added steps for setting up the project locally 
using Docker and environment variables.
```

```sh
docs(api): add endpoint documentation for user service

Documented the available API endpoints, including 
authentication and user management.
```

```sh
docs(contributing): clarify coding style guidelines

Added information about code formatting and branch naming conventions.
```

---

### 🧪 5. เพิ่ม/แก้ไข Unit Tests (`test`)

```sh
test(auth): add unit tests for token validation

Added test cases for expired and invalid tokens.
Ensures proper error handling.
```

```sh
test(api): increase coverage for user controller

Covered additional edge cases in user registration 
and login API endpoints.
```

```sh
test(ui): fix failing snapshot test for navbar

Updated snapshots to reflect recent UI changes.
```

---

### 📦 6. ปรับปรุง Dependencies (`chore`)

```sh
chore(deps): update lodash to v4.17.21

Updated lodash to address security vulnerabilities.
Ensured compatibility with existing functions.
```

```sh
chore(deps): remove unused axios dependency

Refactored API calls to use fetch instead.
Removed axios from package.json.
```

```sh
chore(ci): add GitHub Actions for automated tests

Configured CI/CD pipeline to run tests on every push.
```

---

### 🔄 7. ปรับปรุงโครงสร้างไฟล์หรือโค้ด (`style`, `perf`, `ci`)

```sh
style(ui): format code using Prettier

Applied consistent formatting to all JavaScript files 
using Prettier.
```

```sh
perf(api): improve database query efficiency

Optimized SQL queries to reduce response time 
from 500ms to 120ms.
```

```sh
ci(github-actions): add automatic deployment workflow

Configured GitHub Actions to deploy to AWS S3 after every merge to main.
```

---

### 🔄 8. ตัวอย่าง Commit Message สำหรับงานทั่วไป

✅ **เพิ่มฟีเจอร์**

```sh
feat(payment): integrate Stripe payment gateway
```

✅ **แก้บั๊ก**

```sh
fix(cart): prevent duplicate items in shopping cart
```

✅ **ปรับปรุงโค้ด**

```sh
refactor(profile): simplify user profile data fetching
```

✅ **เพิ่มเทส**

```sh
test(checkout): add tests for discount calculation
```

✅ **อัปเดตเอกสาร**

```sh
docs(README): update API usage examples
```

✅ **อัปเดต dependencies**

```sh
chore(deps): upgrade React to v18
```

✅ **ปรับปรุงประสิทธิภาพ**

```sh
perf(search): optimize query execution time
```

✅ **ตั้งค่า CI/CD**

```sh
ci(jenkins): add build and test pipeline
```

---

## 📌 สรุป

- ✅ **เขียนให้สั้น กระชับ และชัดเจน**
- ✅ **ใช้คำกริยาในรูปปัจจุบัน** (`Add`, `Fix`, `Refactor`)
- ✅ **ใช้มาตรฐาน Conventional Commits เพื่อความเป็นระเบียบ**
- ✅ **เพิ่มรายละเอียดใน commit description ถ้าจำเป็น**

---

🔥 **อยากให้ช่วยสร้าง commit message สำหรับโปรเจคของคุณไหม?** 🚀

