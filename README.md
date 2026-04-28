# 📊 Load Testing Report

## 📌 Tested System
Lalafo.az saytının **idman və hobbi kateqoriyası** Apache JMeter vasitəsilə load testing edilmişdir.

---

## ⚙️ Test Konfiqurasiyası

- **Threads (Users):** 50, 100  
- **Ramp-up period:** 5 saniyə  
- **Loop count:** 2  

---

## 🧪 Test Nəticələri

### 👥 50 Users

- **Average Response Time:** 2649 ms  
- **Maximum Response Time:** 6575 ms  
- **Error Rate:** 0%  

---

### 👥 100 Users

- **Average Response Time:** 7123 ms  
- **Maximum Response Time:** 17996 ms  
- **Error Rate:** 0%  

---

## 📌 Nəticə

İstifadəçi sayı artdıqca sistemdə **ciddi gecikmələr müşahidə olunur**, lakin **error rate 0%** qalır.  

Bu onu göstərir ki:
- Sistem stabil işləyir  
- Amma performans (response time) yük artdıqca zəifləyir  
