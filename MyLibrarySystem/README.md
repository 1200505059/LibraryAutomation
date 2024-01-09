# Kütüphane yönetim otomasyonu

:information_source: **Dersin Kodu:** [16303](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ16303/716026/tr)  
:information_source: **Dersin Adı:** [YAZILIM MİMARİSİ VE TASARIMI](https://ebp.klu.edu.tr/Ders/dersDetay/YAZ16303/716026/tr)  
:information_source: **Dersin Öğretim Elemanı:** Öğr. Gör. Dr. Fatih BAL  [Github](https://github.com/balfatih)   |    [Web Sayfası](https://balfatih.github.io/)
   
---

## Grup Bilgileri

| Öğrenci No | Adı Soyadı           | Bölüm          		   | Proje Grup No | Grup Üyelerinin Github Profilleri                 |
|------------|----------------------|--------------------------|---------------|---------------------------------------------------|
| 1210505036 | Muhammet Sönmez			| Yazılım Mühendisliği     | PROJE_15       | [Github](https://github.com/MuhammetSonmez)     |
| 1200505059  | Eyüp Çakmaker        | Yazılım Mühendisliği     | PROJE_15       | [Github](https://github.com/1200505059)      |
| 1210505006  | Eren Ayık            | Yazılım Mühendisliği     | PROJE_15       | [Github]     |

---

## Proje Açıklaması

Kütüphane otomasyon sistemi projesinin amacı, kütüphanedeki kitapların takip edilmesi ve yönetilmesi amacıyla oluşturulmuş bir sistemdir. Projede java programlama dili ve Swing arayüz programlama kullanılmıştır.
Proje içerisinde DAO, Facory, Observer, Singleton, State ve Strategy tasarım desenleri kullanılmıştır.

---

## Proje Dosya Yapısı

Projenin dosya yapısı şu şekildedir.:
- **/src**
  - **/mylibrarysystem**
    - **/Entities**
      -  `Kullanicilar.java`
      -  `Kitaplar.java`
      -  `OduncAlinanlar.java`
      -  `Yetkiler.java`
    - **/FactoryDesign**
      - `Ogrenci.java`
      - `OgretimGorevlisi.java`
      - `Personel.java`
      - `User.java`
      - `UserFactory.java`
    - **/Observer**
      - `IKitapObserver.java`
      - `KitapObserver.java`
    - **/Singleton**
      - `BaglantiSingleton.java`
    - **/SingletonObserverDAO**
      - `DAO.java`
      - `KitaplarDAO.java`
      - `KullanicilarDAO.java`
      - `OduncAlinanlarDAO.java`
      - `YetkilerDAO.java`
    - **/StrategyAndStatePattern**
      - `AdinaGoreSiralamaStrategy.java`
      - `KayipKitaplarState.java`
      - `KitaplarState.java`
      - `KitaparSiralamaStrategy.java`
      - `KonuyaGoreSirala.java`
      - `Kutuphane.java`
      - `OduncKitaplarState.java`
      - `RaftaKitaplarState.java`
      - `StokGoreSiralamaStrategy.java`
      - `YazaraGoreSirala.java`
    - `1.png`
    - `2.png`
    - `3.png`
    - `3.png`
    - `123456.png`
    - `AkademisyenGirisForm.form`
    - `AkademisyenGirisForm.java`
    - `AkademisyenHome.form`
    - `AkademisyenHome.java`
    - `AkademisyenKitaoAra.form`
    - `AkademisyenKitapAra.java`
    - `AkademisyenProfil.form`
    - `AkademisyenProfil.java`
    - `AkademisyenTeslimiYaklasanlar.form`
    - `AkademisyenTeslimiYaklasanlar.java`
    - `AkademisyenTumKitaplar.form`
    - `AkademisyenTumKitaplar.java`
    - `arkaplan2.jpeg`
    - `book.png`
    - `book_5766015.png`
    - `book2.png`
    - `books.ico`
    - `books.png`
    - `bookSearh.png`
    - `bookshelf.png`
    - `bookss.png`
    - `cookbook.png`
    - `delete.png`
    - `digital-library.png`
    - `education.png`
    - `employer_10488334.png`
    - `exit.ico`
    - `exit.png`
    - `find_3729925.png`
    - `GorevliEkleForm.form`
    - `GorevliEkleForm.java`
    - `GorevliGirisForm.form`
    - `GorevliGirisForm.java`
    - `GorevliGuncelleForm.form`
    - `GorevliGuncelleForm.java`
    - `GorevliHomeForm.form`
    - `GorevliHomeForm.java`
    - `GorevliKitapAra.form`
    - `GorevliKitapAra.java`
    - `GorevliProfil.form`
    - `GorevliProfil.java`
    - `GorevliSilForm.form`
    - `GorevliSilForm.java`
    - `GorevliTumKitaplar.form`
    - `GorevliTumKitaplar.java`
    - `graduation-hat.png`
    - `issue book.png`
    - `issue.png`
    - `kutuphane.jpg`
    - `library.png`
    - `Login.form`
    - `Login.java`
    - `login.png`
    - `login_2250207.png`
    - `New book.png`
    - `OgrenciHome.form`
    - `OgrenciHome.java`
    - `OgrenciGirisForm.form`
    - `OgrenciGirisForm.java`
    - `OgrenciKitapAra.form`
    - `OgrenciKitapAra.java`
    - `OgrenciKitaplarim.form`
    - `OgrenciKitaplarim.java`
    - `OgrenciProfil.form`
    - `OgrenciProfil.java`
    - `OgrenciTeslimTarihiYaklasanlar.form`
    - `OgrenciTeslimTarihiYaklasanlar.java`
    - `OIP.jpeg`
    - `open-book.png`
    - `personel arka.jpeg`
    - `profile.png`
    - `profile-user.png`
    - `save-icon--1.png`
    - `search.png`
    - `search_3423732.png`
    - `Statics.png`
    - `student.png`
    - `teacher.png`
    - `team_8138333.png`
    - `update_1601884.png`
    - `updateted_5334827.png`
    - `user_1177568.png`
      


---

## Kurulum

Projenin kurulumu şu şekildedir:
- Öncelikle projeyi klonlamalısınız:
```
  git clone https://github.com/MuhammetSonmez/Yaz-l-m-mimarisi-ve-tasar-m-grup-devi/
```
- Mysql workbench 8.0 veya xampp kurulumu yapmalısınız. https://downloads.mysql.com/archives/installer/
- mysql connector jar dosyasını indiriniz. https://dev.mysql.com/downloads/connector/j/
- connector jar dosyanızı projeye ekleyiniz.
---

## Kullanım

projeyi github üzerinden indirin ardından  bilgisayarınıza kurduğunuz netbeans ideye jdk ve jdbc jar ve mysql connector jar ekleyerek projeti netbeans ide üzerinden çalıştırabilirsiniz.

---

## Katkılar

Projede tasarım desenlerini Dr. Fatih Bal'ın github reposundan yardım alınmıştır: https://github.com/balfatih/YAZ16303_Yazilim_Mimarisi_ve_Tasarimi
projede GUI ile arayüz tasarımında bilgiler: https://www.tasarimkodlama.com/java-programlama/java-swing-ile-gui-olusturma-ornekleri/
projede GUI ile arayüzünün tasarlanmasında: https://www.udemy.com/course/javada-masaustu-uygulama-gelistirme-kursu-proje-bazl/learn/lecture/18248476?start=300

---

## İletişim
Muhammet Sönmez: muhammetsonmez1011@gmail.com
Eyüp Çakmaker: cakmakereyup@gmail.com
Eren Ayık: Erenayiks66@gmail.com
