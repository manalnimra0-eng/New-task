# New-task
# 📱 Mobile App QA Documentation

A tuition management app that connects **students** with **teachers**, managed via an **Admin panel**. This repository contains bug reports and test cases from manual QA testing conducted on **iOS and Android**.

https://drive.google.com/drive/folders/1B4ktrSjuOJoWGVi3ChlNf_1X2lXauw9C?usp=sharing


---

## 🐛 Bug Reports

| File | Role | Bugs Found |
|------|------|-----------|
| `Admin_bug.xlsx` | Admin, Teacher & Student (2nd Round Testing) | 15 bugs |
| `student_bug.xlsx` | Student Panel (iOS,android) | 24 bugs |
| `teacher_bug.xlsx` | Teacher Panel (iOS,android) | 32 bugs |

> **Note:** `Admin_bug.xlsx` was reported during the **2nd round of testing**, which covered all three roles — Admin, Teacher, and Student — together under the Admin panel review.

**Common issues found across roles:**
- Profile updates (city, institute, location) not saving properly
- Profile pictures and documents upload successfully but don't display
- Notifications appear but are not clickable
- Missing input validation (invalid email, phone number accepted)
- Location field shows lat/long instead of address name
- No subject groups (Science/Humanities/Business) for Classes 9–12

---

## ✅ Test Cases

| File | Module | Total TCs |
|------|--------|-----------|
| `test_case.xlsx` | SICOREMO / TVMS Admin Panel (iOS) | 48+ |

**Modules covered:** Login, Guest User, User Info Display, Video Recording, Local Storage, Delete & Hold functionality.

---

## 🔧 Environment

- **Platform:** iOS & Android
- **Testing Type:** Manual — Functional & UI
- **Reporting Format:** Excel (.xlsx)
