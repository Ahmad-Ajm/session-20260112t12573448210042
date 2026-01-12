# Features Map – Project Feature Inventory

هذا الملف هو الخريطة المركزية لجميع الميزات (Features / Epics) في المشروع.

---

## 2. نظرة عامة – جدول الميزات

| FeatureId      | FeatureName              | FeatureType | Summary                                                     | Personas              | Requirements              | SpecFolders               | Priority | Status      |
|----------------|--------------------------|-------------|-------------------------------------------------------------|-----------------------|---------------------------|---------------------------|----------|------------|
| FEAT-EXAMPLE01 | Example Feature          | CRUD        | مثال لميزة CRUD كاملة (إنشاء/عرض/تعديل/حذف)                | Admin, User           | FR-EX-01, FR-EX-02        | 04-domain, 07-api, 08-ui  | P1       | Planned    |
| FEAT-CV-CREATION | CV Creation & Management | CRUD        | إنشاء وتعديل وحفظ السيرة الذاتية للمستخدم                  | User                  | FR-01                     | 04-domain,07-api,08-ui    | P0       | Planned    |
| FEAT-USER-REGISTRATION | User Registration & Login | Security | تسجيل المستخدمين وتسجيل الدخول                              | User                  | FR-02                     | 06-auth,07-api,08-ui      | P0       | Planned    |
| FEAT-CV-SEARCH | CV Search & Filter       | Search      | البحث والتصفية في السير الذاتية المتاحة                    | Visitor, Admin        | FR-03                     | 07-api,08-ui              | P1       | Planned    |
| FEAT-CV-EXPORT | CV Export                | Reporting   | تصدير السيرة الذاتية بصيغ PDF/Word مع إخفاء البيانات الحساسة | Visitor, User         | FR-04                     | 07-api                    | P1       | Planned    |
| FEAT-SECURITY-PRIVACY | Security & Privacy     | Security   | حماية البيانات وإخفاء المعلومات الحساسة                    | User, Admin           | NFR-01                    | 06-auth,12-testing        | P0       | Planned    |

---
