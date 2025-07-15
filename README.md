# 📝 TO-DO LIST Uygulaması (Python)

Bu proje, terminal tabanlı basit bir görev yönetim (to-do list) uygulamasıdır. Kullanıcılar bilgisayar üzerinden görev oluşturabilir, görüntüleyebilir, düzenleyebilir ve silebilir. Yapılan işlemler kalıcı olarak `.txt` dosyasına kaydedilir. Böylece uygulama kapatıldığında görevler kaybolmaz.

---

## 📋 Menüde Yer Alan Seçenekler

1. **Görevleri Listele:**  
   Mevcut görevler numaralandırılmış biçimde listelenir. Eğer hiç görev yoksa, kullanıcı bilgilendirilir.

2. **Yeni Görev Ekle:**  
   Kullanıcıdan bir görev metni istenir. Boş görev girilmesine izin verilmez. Geçerli bir görev girildiğinde listeye eklenir.

3. **Görev Düzenle:**  
   Görevler listelenir, ardından kullanıcıdan düzenlemek istediği görev numarası ve yeni metin istenir. Boş metin girilirse uyarı verilir.

4. **Görev Sil:**  
   Görevler listelenir, ardından kullanıcıdan silmek istediği görev numarası istenir. Geçerli numara girildiyse görev listeden kaldırılır.

5. **Çıkış:**  
   Uygulamadan çıkmak için bu seçenek kullanılır.

---

## 🎯 Uygulama Nasıl Kullanılır?

- Program çalıştırıldığında ekranda bir menü görünür.  
- Kullanıcı, yapmak istediği işlemin numarasını yazarak **Enter** tuşuna basar.  
- Her işlem sonrası kullanıcı yönlendirilir:
  - Görev listesi boşsa bilgilendirme yapılır.
  - Geçersiz seçimlerde uyarı verilir.
  - Hatalı girişlerde tekrar denenmesi istenir.

Uygulama, yapılan tüm değişiklikleri `gorevler.txt` adlı dosyaya kaydeder ve işlem sonrası listeyi güncel tutar. Program, kullanıcı çıkış yapana kadar çalışmaya devam eder.

---

## 💻 Proje Dosyaları

- `AyberkYaren_Kıvırcık_Python_ToDoList.py`  
- `kullanici_kilavuzu.pdf`

---

## 👩‍💻 Geliştirici

**Ayberk Yaren Kıvırcık**  
📫 www.linkedin.com/in/ayberk-yaren-kıvırcık-065b2516a

---

> Bu proje, temel Python bilgileriyle sade ama etkili bir terminal uygulaması geliştirme sürecini kapsar. Kullanıcı dostu yapısı ve veri saklama özelliği sayesinde işlevsel bir deneyim sunar.
