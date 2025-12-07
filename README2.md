# e-sikki

**E Şıkkı — Tüm Kavramların Birleştiği Metin**  
Bu repo, kullanıcı tarafından verilen kavramları (Allah, bilim, kuantum, rezonans, vs.) birleştiren kısa felsefi/şiirsel metni *web sayfası* ve *markdown* formatında içerir.

### İçerikler
- `index.html` — Basit, şık görselleştirilmiş web sayfası.
- `style.css` — Stil dosyası.
- `script.js` — Küçük etkileşim (kelime vurgulama).
- `poem.md` — Metnin markdown versiyonu.
- `LICENSE` — MIT lisansı.
- `.github/workflows/pages.yml` — GitHub Pages için örnek deploy workflow'u (isteğe bağlı).

### Nasıl kullanılır
1. Depoyu klonlayın:
```bash
git clone https://github.com/<kullanici_adiniz>/e-sikki.git
cd e-sikki
```
2. Değişiklik yapın, commit ve push:
```bash
git add .
git commit -m "Add E şıkkı site"
git push origin main
```
3. GitHub'da repo ayarlarından **Pages** bölümünü açıp `gh-pages` veya `main` branch'ini seçerek siteyi yayına alabilirsiniz.  
Alternatif olarak, GitHub Actions workflow'u (`.github/workflows/pages.yml`) otomatik deploy sağlar.

---

Hazırlayan: ChatGPT (kodlu versiyon)
