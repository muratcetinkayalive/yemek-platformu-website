# Yemek Platformu - Yasal Belgeler

Bu repository, Yemek Platformu uygulamasının yasal belgelerini içerir.

## 📁 Dosya Yapısı

```
docs/
├── _config.yml          # Jekyll yapılandırması
├── Gemfile              # Ruby bağımlılıkları
├── index.md             # Ana sayfa
├── privacy-policy.md    # Gizlilik politikası
├── terms-of-service.md  # Kullanım şartları
├── CNAME               # Custom domain ayarları
└── README.md           # Bu dosya
```

## 🚀 Kurulum

### Yerel Geliştirme

1. Ruby ve Jekyll'i yükleyin:
```bash
gem install jekyll bundler
```

2. Bağımlılıkları yükleyin:
```bash
bundle install
```

3. Yerel sunucuyu başlatın:
```bash
bundle exec jekyll serve
```

4. Tarayıcıda açın: `http://localhost:4000`

### GitHub Pages'te Yayınlama

1. Bu dosyaları GitHub repository'nize yükleyin
2. GitHub Pages'i aktifleştirin
3. Custom domain ayarlayın (isteğe bağlı)

## 🎨 Tema

Bu site [Cayman](https://github.com/pages-themes/cayman) temasını kullanır.

### Tema Değiştirme

`_config.yml` dosyasında `theme` değerini değiştirin:

```yaml
theme: jekyll-theme-cayman    # Mavi tema
theme: jekyll-theme-minimal   # Minimal tema
theme: jekyll-theme-slate     # Koyu tema
theme: jekyll-theme-tactile   # Yeşil tema
theme: jekyll-theme-time-machine  # Retro tema
```

## 📝 İçerik Güncelleme

- Markdown dosyalarını düzenleyin
- Değişiklikleri commit edin
- GitHub Pages otomatik olarak güncellenecek

## 🔗 Linkler

- **Ana Sayfa:** https://yemekplatformu.com
- **Gizlilik Politikası:** https://yemekplatformu.com/privacy-policy.html
- **Kullanım Şartları:** https://yemekplatformu.com/terms-of-service.html

## 📞 İletişim

- **E-posta:** privacy@yemekplatformu.com
- **Destek:** support@yemekplatformu.com

---

*Son güncelleme: 15 Aralık 2024* 