# Katkıda Bulunma Rehberi

Bu rehber adım adım nasıl katkıda bulunacağınızı anlatır.

## 1. Repo'yu Fork Edin

Bu sayfanın sağ üst köşesindeki **Fork** butonuna tıklayın.
Bu, repo'nun kendi GitHub hesabınıza bir kopyasını oluşturur.

## 2. Fork'unuzu Clone Edin

Terminal (Git Bash / Terminal / PowerShell) açın:

    git clone https://github.com/SIZIN-KULLANICIADIN/git-github-101-atolye.git
    cd git-github-101-atolye

## 3. Yeni Bir Branch Oluşturun

    git checkout -b isminiz-tanitim

Örnek: `git checkout -b ali-veli-tanitim`

**Not:** Branch isminde Türkçe karakter (ş, ç, ğ, ü, ö, ı) ve boşluk kullanmayın.

## 4. Tanıtım Dosyanızı Oluşturun

`katilimcilar/` klasörüne gidin ve kendi isminizle bir `.md` dosyası oluşturun:

    cd katilimcilar

Dosya adı örneği: `ali-veli.md`

Dosya içeriği için `ornek-tanitim.md` dosyasını referans alabilirsiniz.

## 5. Değişikliklerinizi Kaydedin

    git add .
    git commit -m "Ali Veli tanıtım eklendi"

## 6. GitHub'a Gönderin

    git push origin isminiz-tanitim

## 7. Pull Request Açın

GitHub'da kendi fork'unuza gidin.
Sarı bir banner göreceksiniz: **"Compare & pull request"** butonuna tıklayın.

- Başlık yazın: `Ali Veli - Tanıtım eklendi`
- Kısa bir açıklama ekleyin
- **Create pull request** butonuna tıklayın

## Hepsi Bu Kadar! 🎉

Biz PR'ınızı inceleyip merge edeceğiz.
Tebrikler — ilk açık kaynak katkınızı yaptınız!