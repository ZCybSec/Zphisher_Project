
# 🎯 مشروع: Zphisher

## 👥 فريق العمل
- **اسم الفريق:** Zphisher
- **الأعضاء:**
  - 🧑‍💻 عضو 1: (Zaid Hijazi)

## 💡 الفكرة
- المشروع بيعتمد على استخدام أداة Zphisher لتوضيح فكرة **🎣 التصيد الإلكتروني (Phishing)**.  
- الهدف تعليمي بس، عشان نشرح كيف هاي الهجمات بتشتغل ونحذر منها.

---

## ⚙️ كيفية تثبيت الأداة

### 1️⃣ تثبيت Zphisher على Kali Linux:
1. 🖥️ افتح الطرفية (Terminal) واكتب الأمر:
   ```bash
   git clone --depth=1 https://github.com/htr-tech/zphisher.git
   ```
2. 📂 ادخل على المجلد اللي نزلته:
   ```bash
   cd zphisher
   ```
3. 🚀 شغل الأداة بالأمر:
   ```bash
   bash zphisher.sh
   ```
4. إذا كانت هاي أول مرة تشغل فيها الأداة، رح تثبت كل المتطلبات بشكل تلقائي. ✅

---

### 2️⃣ تثبيت Zphisher على Termux:
1. 📱 افتح تطبيق Termux، ونزل الحزم المطلوبة:
   ```bash
   pkg install tur-repo
   pkg install zphisher
   zphisher
   ```

---

### 3️⃣ تشغيل Zphisher باستخدام Docker:
1. 🐋 نزل صورة Docker بالأمر:
   ```bash
   docker pull htrtech/zphisher
   ```
2. ⏯️ شغل الأداة مؤقتاً باستخدام:
   ```bash
   docker run --rm -ti htrtech/zphisher
   ```

---

## 📸 النتائج (لقطات شاشة)
1. **▶️ تشغيل الأداة:**
2. ![1za](https://github.com/user-attachments/assets/30caca43-86e6-4092-b054-5f82f87d675c)


3. **🖱️ اختيار القالب:**
![2za](https://github.com/user-attachments/assets/7db439bf-c08a-4937-a5ef-5770e58881cd)

4. **🔗 إنشاء الرابط:**
5. ![Screenshot_2024-12-12_21-01-09](https://github.com/user-attachments/assets/5c0fd7ec-e5be-4340-b357-7b900478d49b)

6. **📊 التقاط بيانات الضحية:**
![Screenshot_2024-12-12_21-01-29](https://github.com/user-attachments/assets/f2194dab-0308-46be-9acc-08e9f4db21b8)

---

## 📝 ملاحظات
- ⚠️ الأداة مصممة للأغراض التعليمية فقط. **لازم ما تستخدمها لأي غرض غير قانوني!**
- ❌ التصيد بيخالف القوانين، ورح تتحمل المسؤولية إذا استعملتها بشكل خاطئ.
