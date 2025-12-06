# 🚀 Biz Bize Hackathon - Yarışma Reposu

Hoş geldiniz! Bu repository, **Biz Bize Hackathon** kapsamında sorulacak kodlama sorularını ve çözümlerinizi göndereceğiniz alanı barındırır.

## ⚠️ Yarışma Formatı ve İşleyiş

1.  **Parça Parça Yayın:** Sorular yarışma süresince belirli aralıklarla (Örn: Saat başı veya etap etap) bu repoya yüklenecektir.
2.  **Upstream Bağlantısı:** Yeni yüklenen soruları anında görebilmek için aşağıda anlatılan `upstream` (kaynak) bağlantısını kurmanız şarttır.
3.  **Teslim:** Çözümlerinizi kendi fork'unuza yükleyip bize **Pull Request (PR)** atarak teslim edeceksiniz.

---

## 🛠️ Kurulum Rehberi (Sadece Yarışma Başında 1 Kere Yapılacak)

Yarışmaya başlamadan önce bilgisayarınızı hazırlamak için sırasıyla şu adımları izleyin:

### 1. Fork Etme (Kopyalama)
Bu sayfanın sağ üst köşesindeki **"Fork"** butonuna basın ve repoyu kendi GitHub hesabınıza kopyalayın.

### 2. Clone (Bilgisayara İndirme)
Kendi profilinizde oluşan repoyu bilgisayarınıza indirin (Terminal veya Git Bash kullanın):

```bash
# Kendi kullanıcı adınızı yazmayı unutmayın!
git clone [https://github.com/KULLANICI_ADINIZ/Biz-Bize-Hackathon_2025.git](https://github.com/KULLANICI_ADINIZ/Biz-Bize-Hackathon_2025.git)
cd Biz-Bize-Hackathon_2025
```
### 3. Upstream (Kaynak) Ekleme ⚠️ ÖNEMLİ ADIM
Bizim ana repomuzdan yeni soruları çekebilmek için bu komutu girin:

```bash
# Bu link organizasyonun ana repo linkidir, değiştirmeyin:
git remote add upstream https://github.com/medipolmeditech/Biz-Bize-Hackathon_2025.git
```
Kontrol için git remote -v yazdığınızda hem origin (sizin hesabınız) hem de upstream (bizim hesabımız) görünmelidir.

---
## 📥 Yeni Soru Geldiğinde Ne Yapacağım?
Yarışma esnasında "Yeni Sorular Yayınlandı" duyurusu yapıldığında, yeni soru dosyasını bilgisayarınıza indirmek için şu komutu çalıştırın:

```bash
git pull upstream main
```
Bu komut, yazdığınız kodları silmez; sadece bizim eklediğimiz yeni soru klasörünü projenize dahil eder.

---

## 📤 Çözümü Nasıl Göndereceğim?
Soruyu çözdünüz ve teslim etmek istiyorsunuz. Sırasıyla şu adımları izleyin:

### 1. Kendi Reponuza Yükleme (Push)

```bash
git add .
git commit -m "Soru X Cozumu - Yarışmacı Ismi"
git push origin main
```
### 2. Pull Request (PR) Açma

1. GitHub'da kendi reponuzun sayfasına gidin.

2. Sayfada "Contribute" veya "Pull Request" butonunu göreceksiniz.

3. "Open Pull Request" butonuna tıklayın.

4. Başlık kısmına: [Yarışmacı Adı] Soru X Çözümü yazın.

5. Create Pull Request butonuna basarak işlemi tamamlayın.

## ⚖️ Kurallar ve İpuçları
Klasör Düzeni: Her soru için oluşturulan klasörün içinde çalışın (Örn: Soru-1/cozum.c).

Conflict (Çakışma): Eğer git pull upstream main yaparken hata alırsanız, üzerinde çalıştığınız dosyaları masaüstüne yedekleyin, projeyi silip baştan clone alın ve dosyalarınızı geri içine atın.

Etik: Kopya çekildiği tespit edilen kodlar veya yapay zeka tarafından doğrudan üretilip mantığı açıklanamayan kodlar geçersiz sayılacaktır.

## Herkese başarılar! 🚀
