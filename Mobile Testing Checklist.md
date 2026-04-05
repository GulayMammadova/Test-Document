# Kapital Bank (Birbank) – Mobile QA Checklist

## 1. Quraşdırma və Launch
- Tətbiq ilk açılışda sürətli start verir  
- Splash screen zamanı donma və gecikmə olmur  
- App ilk açılışdan sonra stabil qalır (yenidən açılan zaman problem yoxdur)  
- Update-dən sonra app normal açılır və əlavə login tələb olunmur  

---

## 2. Login / Authorization
- Biometric login (Face ID / Fingerprint) ilk dəfə aktivləşdirilə bilir  
- Biometric uğursuz olduqda PIN kod ilə tətbiqə keçid edir  
- App background-dan açıldıqda yenidən login tələb olunmur  
- App bağlanıb yenidən açıldıqda istifadəçi yenidən login etmir, biometrik autentifikasiya ilə daxil olur  

---

## 3. Navigation
- Səhifələr arasında keçid zamanı gecikmə yoxdur  
- Ekran dəyişərkən UI “jump” və ya nasazlıq etmir  
- İstifadəçi sürətli klik etdikdə navigation qarışmır  
- Gesture-lər (swipe back və s.) düzgün işləyir  

---

## 4. UI / UX
- Dark mode düzgün işləyir  
- Light/Dark mode keçidi problemsizdir  
- Fərqli ekran ölçülərində UI düzgün görünür  
- Orientation dəyişəndə UI pozulmur  
- Mətnlər bütün hallarda oxunaqlıdır  

---

## 5. Input və Validasiya
- Input sahəsinə klik edəndə ekran avtomatik yuxarı qalxır (keyboard örtmür)  
- Keyboard bağlandıqdan sonra UI əvvəlki vəziyyətinə qayıdır  
- Input zamanı gecikmə yoxdur  
- Autofill (varsa) düzgün işləyir  

---

## 6. Şəbəkə (Network)
- İnternet kəsildikdə istifadəçi əməliyyatı dayandırılır və məlumat itmir  
- Şəbəkə dəyişəndə (Wi-Fi → mobile data) əməliyyat yarımçıq qalmır  
- Zəif internet bağlantısında istifadəçiyə loading göstərilir və UI responsiv qalır  
- Retry etdikdə əməliyyat davam edir  

---

## 7. Performans
- App açıldıqdan sonra ilk ekran tez yüklənir  
- Eyni səhifəyə təkrar keçiddə daha sürətli açılır (cache varsa)  
- Scroll zamanı donma və gecikmə yoxdur  
- Uzun müddət istifadə zamanı performans düşmür  

---

## 8. Background / Foreground
- App background-a keçəndə aktiv proseslər pozulmur  
- Geri qayıdanda istifadəçi eyni yerdən davam edir (əgər session aktivdirsə)  
- Uzun müddət background-da qaldıqda təhlükəsizlik səbəbi ilə session sıfırlanır  
- Background-da olarkən kritik əməliyyatlar düzgün tamamlanır  

---

## 9. Device və OS uyğunluq
- Köhnə və yeni cihazlarda davranış fərqi yoxdur  
- OS update-dən sonra app stabil qalır  
- Kamera hissəsi olan telefonlarda UI elementləri örtülmür  
- Fiziki button-larla (home/back) problem yaranmır  

---

## 10. Permissions
- Permission sorğusu istifadəçini narahat etmədən düzgün vaxtda çıxır  
- İcazə verilmədikdə app alternativ davranış göstərir  
- İcazə sonradan settings-dən aktiv ediləndə app bunu tanıyır  

---

## 11. Tətbiq funksionallığı (Application Testing)

### 11.1 Login
- PIN kod ilə giriş işləyir  
- Biometric login-dən sonra istifadəçi uğurla daxil olur  
- Yanlış PIN daxil edildikdə uyğun error mesajı göstərilir  

---

### 11.2 Kartlar (Cards)
- Kart siyahısı düzgün yüklənir  
- Kart balansı düzgün göstərilir  
- Kart detalları açılır və düzgün görünür  
- İstifadəçi balansı gizləyə bilir (göz ikonuna klik edildikdə balans görünmür)  
- Kart məlumatları (nömrə və s.) təhlükəsizlik səbəbi ilə qismən gizli göstərilir  
- Kartlar arasında keçid düzgün işləyir  

---

### 11.3 Transferlər (Transfers)
- Kartdan karta transfer uğurla həyata keçirilir  
- Yanlış məlumat daxil edildikdə error mesajı göstərilir  
- Uğurlu əməliyyatdan sonra təsdiq (confirmation) mesajı çıxır  
- Kart limiti aşıldıqda əməliyyat icra olunmur və balansdan vəsait çıxılmır  
- Eyni karta transfer zamanı uyğun xəbərdarlıq göstərilir  
- Transfer zamanı səhv və ya boş formatlı məlumat daxil edildikdə əməliyyat icra olunmur  

---

### 11.4 Əməliyyat tarixçəsi (History)
- Əməliyyatlar siyahısı düzgün yüklənir  
- Əməliyyat detalları açılır və düzgün göstərilir  
- Uğurlu və uğursuz transfer sonrası əməliyyat history-də əks olunur  
- Əməliyyatlar tarixə görə düzgün sıralanır  
- Əməliyyat məbləği və statusu düzgün göstərilir
