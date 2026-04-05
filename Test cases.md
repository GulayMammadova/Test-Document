# 📌 Pure Organic – Test Cases

Bu sənəd Pure Organic layihəsi üçün hazırlanmış test case-ləri əhatə edir.

---

## 🧪 Test Cases

### TC_001 - Doğru məlumatlarla istifadəçi qeydiyyatı
**Preconditions:** İstifadəçi qeydiyyatdan keçməmişdir, Sign Up səhifəsi açıqdır  
**Steps:**
1. Register səhifəsinə keç  
2. Ad, soyad, email, şifrə daxil et  
3. Sign Up klik et  
**Expected Result:** Qeydiyyat uğurlu, login səhifəsinə yönləndirmə  
**Actual Result:** Uğurlu  
**Status:** Passed  

---

### TC_002 - Yanlış email ilə qeydiyyat
**Expected Result:** Xəta mesajı  
**Actual Result:** Xəta göstərildi  
**Status:** Passed  

---

### TC_003 - Boş məlumatlarla qeydiyyat
**Expected Result:** Validation mesajı  
**Actual Result:** Göstərildi  
**Status:** Passed  

---

### TC_004 - İstifadə olunmuş email
**Expected Result:** Xəta mesajı  
**Actual Result:** Göstərildi  
**Status:** Passed  

---

### TC_005 - Şifrələr uyğun deyil
**Expected Result:** Error mesajı  
**Actual Result:** Göstərildi  
**Status:** Passed  

---

### TC_006 - Məcburi sahələr boş
**Expected Result:** Validation mesajı  
**Actual Result:** Göstərildi  
**Status:** Passed  

---

### TC_007 - Ad sahəsinə rəqəm daxil edilməsi
**Expected Result:** Xəta mesajı  
**Actual Result:** Göstərildi  
**Status:** Passed  

---

### TC_008 - Qısa şifrə
**Expected Result:** Error mesajı  
**Actual Result:** Göstərildi  
**Status:** Passed  

---

### TC_009 - Böyük hərflərlə email
**Expected Result:** Qəbul edilir  
**Actual Result:** Uğurlu  
**Status:** Passed  

---

### TC_010 - Doğru login
**Expected Result:** Uğurlu login  
**Actual Result:** Uğurlu  
**Status:** Passed  

---

### TC_011 - Yanlış login
**Expected Result:** Error  
**Actual Result:** Error  
**Status:** Passed  

---

### TC_012 - Boş login
**Expected Result:** Validation  
**Actual Result:** Göstərildi  
**Status:** Passed  

---

### TC_013 - Qeydiyyatda olmayan email
**Expected Result:** User not found  
**Actual Result:** Error  
**Status:** Passed  

---

### TC_014 - Enter ilə login
**Status:** Passed  

### TC_015 - Show/Hide password
**Status:** Passed  

### TC_016 - Email + space
**Status:** Passed  

### TC_017 - Çox klik login
**Status:** Passed  

### TC_018 - Invalid email format
**Status:** Passed  

### TC_019 - Uzun email
**Status:** Passed  

### TC_020 - Space email
**Status:** Passed  

---

## 🔍 Search Testləri

### TC_021 - Məhsul axtarışı
**Status:** Passed  

### TC_022 - Mövcud olmayan məhsul
**Status:** Passed  

### TC_023 - Oxşar məhsullar
**Status:** Passed  

### TC_024 - Təkrar axtarış
**Status:** Passed  

### TC_025 - Uzun mətn
**Status:** Passed  

### TC_026 - Case sensitivity
**Status:** Passed  

### TC_027 - Multiple nəticə
**Status:** Passed  

### TC_028 - Space ilə axtarış
**Status:** Passed  

### TC_029 - Sorting
**Status:** Passed  

### TC_030 - Məhsula klik
**Status:** Passed  

---

## 📂 Category Testləri

### TC_031 - Kateqoriya göstərilməsi
**Status:** Passed  

### TC_032 - Kateqoriya dəyişmə
**Status:** Passed  

### TC_033 - Filter + category
**Status:** Passed  

### TC_034 - Pagination
**Status:** Failed  

### TC_035 - Təkrar seçim
**Status:** Passed  

### TC_036 - Loading
**Status:** Passed  

### TC_037 - Boş siyahı
**Status:** Failed  

### TC_038 - Səhv kateqoriya
**Status:** Failed  

### TC_039 - Back
**Status:** Passed  

### TC_040 - Stress klik
**Status:** Passed  

---

## 🎛 Filter Testləri

### TC_041 - Qiymət filteri
**Status:** Passed  

### TC_042 - Kateqoriya filteri
**Status:** Passed  

### TC_043 - Multi filter
**Status:** Passed  

### TC_044 - Reset
**Status:** Passed  

### TC_045 - No result
**Status:** Passed  

### TC_046 - Apply işləmir
**Status:** Failed  

### TC_047 - Wrong nəticə
**Status:** Failed  

### TC_048 - Freeze
**Status:** Failed  

### TC_049 - Update
**Status:** Passed  

### TC_050 - Klik məhsul
**Status:** Passed  

### TC_051 - Refresh
**Status:** Passed  

### TC_052 - Empty filter
**Status:** Passed  

---

## 📦 Product & Cart

### TC_053 - Məhsul məlumatı
**Status:** Passed  

### TC_054 - Şəkillər
**Status:** Passed  

### TC_055 - Qiymət
**Status:** Passed  

### TC_056 - Add to cart
**Status:** Passed  

### TC_057 - Stock
**Status:** Passed  

### TC_058 - Responsive
**Status:** Passed  

### TC_059 - Cart əlavə
**Status:** Passed  

### TC_060 - Increase
**Status:** Passed  

### TC_061 - Decrease
**Status:** Passed  

### TC_062 - Delete
**Status:** Passed  

### TC_063 - Limit
**Status:** Passed  

### TC_064 - Save state
**Status:** Passed  

---

## 💳 Checkout

### TC_065 - Checkout keçid
**Status:** Passed  

### TC_066 - Data input
**Status:** Passed  

### TC_067 - Empty fields
**Status:** Passed  

### TC_068 - Invalid phone
**Status:** Passed  

### TC_069 - Payment methods
**Status:** Passed  

### TC_070 - Invalid card
**Status:** Passed  

### TC_071 - Successful order
**Status:** Passed  

### TC_072 - Empty cart checkout
**Status:** Passed  

---

## 📌 Nəticə
Bu test case-lər layihənin əsas funksiyalarını əhatə edir və sistemin stabil işlədiyini göstərir. Bəzi hallarda kritik bug-lar (filter və kateqoriya) aşkar edilmişdir.
