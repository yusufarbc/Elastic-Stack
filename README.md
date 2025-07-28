# 🔍 Etkileşimli ELK Stack SOC Kılavuzu

Güvenlik Operasyon Merkezleri (SOC) için tasarlanmış kapsamlı ve etkileşimli Elastic Stack (ELK) rehberi.

## 🌟 Özellikler

Bu proje, Elastic Stack'in güvenlik operasyonlarında nasıl kullanılacağını öğretmek için tasarlanmış interaktif bir web uygulamasıdır:

### 🎯 Ana Bölümler
- **Temel Kavramlar**: Elasticsearch, Logstash, Kibana ve Beats bileşenlerinin interaktif tanıtımı
- **Mimari ve Kurulum**: Veri akışı diagramı ve adım adım kurulum simülatörü
- **Tehdit Tespiti Atölyesi**: Praktik güvenlik kuralları ve görselleştirmeler
- **Gelişmiş Yetenekler**: Threat hunting, incident response ve AI destekli analitik

### 🎨 İnteraktif Özellikler
- **Tıklanabilir Bileşen Diagramları**: Her ELK bileşeninin detaylı açıklaması
- **Veri Akışı Görselleştirmesi**: 4 adımlı veri işleme sürecinin interaktif takibi
- **Kurulum Simülatörü**: Ubuntu 22.04 için tabbed kurulum rehberi
- **Tehdit Tespit Kuralları**: Chart.js ile görselleştirilmiş güvenlik senaryoları
- **Accordion Menüler**: Gelişmiş konuların organize sunumu

### 🛠️ Teknolojiler
- **Frontend**: HTML5, CSS3 (Tailwind CSS), Vanilla JavaScript
- **Görselleştirme**: Chart.js
- **Tasarım**: Responsive, mobile-first yaklaşım
- **Tipografi**: Inter font family
- **İkonlar**: Unicode emoji kullanımı

## 🚀 Canlı Demo

[**GitHub Pages'de Görüntüle**](https://yourusername.github.io/Elastic-Stack/)

## 📥 Kurulum ve Çalıştırma

### Yerel Geliştirme

1. Repository'yi klonlayın:
```bash
git clone https://github.com/yourusername/Elastic-Stack.git
cd Elastic-Stack
```

2. Dosyaları bir web sunucusu ile çalıştırın:

**Python ile:**
```bash
python -m http.server 8000
# veya Python 2 için: python -m SimpleHTTPServer 8000
```

**Node.js ile:**
```bash
npx serve .
```

**Live Server (VS Code Extension) ile:**
- VS Code'da `index.html` dosyasını açın
- "Go Live" butonuna tıklayın

3. Tarayıcıda `http://localhost:8000` adresini ziyaret edin

### GitHub Pages Dağıtımı

1. Repository'yi GitHub'a push edin
2. Repository ayarlarında "Pages" bölümüne gidin
3. Source olarak "Deploy from a branch" seçin
4. Branch olarak "main" ve folder olarak "/ (root)" seçin
5. "Save" butonuna tıklayın

## 📚 İçerik Yapısı

### Temel Kavramlar
- **Elasticsearch**: Dağıtık arama ve analitik motoru
- **Logstash**: Veri toplama ve işleme pipeline'ı
- **Kibana**: Veri görselleştirme arayüzü
- **Beats/Elastic Agent**: Lightweight veri göndericiler

### Güvenlik Kullanım Örnekleri
- **Brute-Force Tespiti**: Threshold tabanlı tespit kuralı
- **PowerShell Monitoring**: KQL ile şüpheli komut tespiti
- **Ransomware Detection**: EQL ile olay korelasyonu

### SIEM Yetenekleri
- Proaktif tehdit avcılığı (Threat Hunting)
- Olay müdahale (Incident Response) iş akışları
- Yapay zeka destekli güvenlik analitikleri

## 🎯 Hedef Kitle

- **SOC Analistleri**: Elastic Stack ile tehdit tespiti öğrenmek isteyenler
- **Güvenlik Mühendisleri**: SIEM çözümlerini araştıranlar  
- **DevSecOps Ekipleri**: Log analizi ve monitoring arayanlar
- **Siber Güvenlik Öğrencileri**: Pratik deneyim kazanmak isteyenler

## 🔧 Özelleştirme

### Yeni Güvenlik Kuralı Ekleme

`script` bölümündeki `contentData.rules` objesine yeni kural ekleyin:

```javascript
contentData.rules.newrule = {
    title: "Yeni Kural Başlığı",
    description: "Kural açıklaması",
    details: "Detaylı HTML içeriği"
};
```

### Yeni Chart Verisi Ekleme

`chartData` objesine yeni veri seti ekleyin:

```javascript
chartData.newrule = {
    labels: ['Label1', 'Label2'],
    data: [10, 20],
    description: "Chart açıklaması"
};
```

## 📱 Responsive Tasarım

- **Mobile-First**: Telefon ve tablet uyumlu
- **Breakpoints**: Tailwind CSS responsive sınıfları
- **Navigation**: Mobilde hamburger menü
- **Charts**: Otomatik boyutlandırma

## 🔒 Güvenlik Özellikleri

- **CSP Ready**: Content Security Policy uyumlu
- **XSS Protected**: Güvenli DOM manipülasyonu
- **No External Scripts**: Sadece güvenilir CDN'ler (Tailwind, Chart.js)

## 🤝 Katkıda Bulunma

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/AmazingFeature`)
3. Commit edin (`git commit -m 'Add some AmazingFeature'`)
4. Branch'e push edin (`git push origin feature/AmazingFeature`)
5. Pull Request açın


## 🙏 Teşekkürler

- **Elastic**: ELK Stack'in geliştirilmesi için
- **Tailwind CSS**: Modern CSS framework için
- **Chart.js**: Güzel görselleştirmeler için
- **MITRE ATT&CK**: Tehdit modelleme için


---

⭐ **Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!**

