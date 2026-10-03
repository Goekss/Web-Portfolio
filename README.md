# Onur Gökhan Bicer — Developer Portfolio 🚀

[![Website](https://img.shields.io/badge/Live_Portfolio-GitHub_Pages-2ea44f?style=for-the-badge&logo=github)](https://goekss.github.io/Web-Portfolio/)
[![Vanilla JS](https://img.shields.io/badge/Vanilla-JavaScript_ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5 & CSS3](https://img.shields.io/badge/Stack-HTML5_%26_CSS3-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![DSGVO Compliant](https://img.shields.io/badge/DSGVO_%2F_GDPR-Compliant-0052cc?style=for-the-badge&logo=shield)](https://gdpr.eu/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](LICENSE)

> **Sprache wählen / Dil Seçimi:**  
> 🇩🇪 [Deutsch (DE)](#-deutsch-de) &nbsp;|&nbsp; 🇹🇷 [Türkçe (TR)](#-t%C3%BCrk%C3%A7e-tr)

---

## 🇩🇪 Deutsch (DE)

### 📌 Über das Projekt

Herzlich willkommen! 👋 Schön, dass du auf meinem Portfolio vorbeischaust.

Diese Seite dient als persönlicher Hub, um meine Softwareprojekte, Weiterbildungen und Nachweise übersichtlich an einem Ort zu bündeln. Ich verfolge moderne Technologien mit großem Interesse und habe den Anspruch, jeden Tag Neues zu lernen und mich kontinuierlich weiterzuentwickeln.

Das Portfolio habe ich ganz bewusst ohne überflüssige Frameworks umgesetzt – schlank, geradlinig und mit purem **HTML5, CSS3 und JavaScript**.

---

### ✨ Hauptmerkmale & Highlights

- **⚡ Zero-Dependency & No-Build:** Keine Node-Module, kein Bundler, kein Compile-Schritt erforderlich. Direkt im Browser lauffähig und auf GitHub Pages gehostet.
- **🎛️ Dynamische Content-Map & Overlay-Architektur:** Inhalte werden dynamisch aus einer zentralen Datenstruktur (`contentMap`) geladen. Das Vollbild-Overlay (`cvCardsWrapper`) ermöglicht detailreiche Projekt- und Dokumentansichten ohne Seiten-Reloads.
- **📄 Integrierte Dokumenten- & PDF-Vorschau:** Direkte Voransicht von Lebenslauf, Arbeitszeugnissen, Bildungsnachweisen und ehrenamtlichen Zertifikaten via interaktiver `<iframe>`-Einbindung und Direkt-Download.
- **🎨 Modernes Dark-Mode & Glassmorphism Design:** Ästhetische Benutzeroberfläche mit sanften Farbverläufen, Unschärfe-Effekten (`backdrop-filter`) und dynamischem Mauszeiger-Glow (`--mouse-x`, `--mouse-y`).
- **🎯 Phased Smooth Scrolling:** Eigene Scroll-Engine mit dreiphasiger kubischer Beschleunigung (`easeInCubic` & `easeOutCubic`) für ein natürliches Navigationsgefühl.
- **🏷️ Automatisches Tech-Stack Icon-Mapping:** Dynamische Umwandlung von Technologie-Schlagwörtern in offizielle Devicon- und CDN-Vektor-Icons mit Fallback-Textbadges.
- **🛡️ 100% DSGVO-konformes Cookie-Banner:** Google Analytics wird erst nach ausdrücklicher Einwilligung geladen. Integrierte Inline-Panels für **Datenschutzerklärung** und **Impressum**.
- **📱 Vollständig responsiv & Accessible:** Optimiert für Smartphones, Tablets und Ultra-Wide-Displays inklusive Screenreader-Labels (`aria-*`) und Skip-Links.

---

### 📂 Im Portfolio vorgestellte Projekte

| Projekt | Fokus & Architektur | Technologien | Repositories & Demos |
|---|---|---|---|
| **Vista.Core / Vista.CoreX** | Full-Stack SaaS, lokales RAG-System, CRM & Mandantenfähigkeit | C#, ASP.NET Core, EF Core, SQL Server, React, Vite, Ollama, Qdrant, Semantic Kernel, SignalR, Docker | [GitHub](https://github.com/Goekss/Vista.CoreX) · [Live Demo](https://goekss.github.io/CoreX-Demo/) |
| **GoAI ChatLab** | KI-Chatbot mit serverseitig geschütztem API-Key und Datei-Upload | React, Node.js, Express.js, Docker, GitHub Actions, OpenRouter AI | [GitHub](https://github.com/Goekss/GoAI-ChatLab) · [Live Preview](https://goekss.github.io/GoAI-ChatLab/) |
| **CRMApp-Nova** | Moderne React SPA mit Kanban-Board und JWT-Auth für ASP.NET API | React, React Router, JavaScript, REST API, JWT, Kanban State | [GitHub](https://github.com/Goekss/CrmAppNova) |
| **CRM-Anwendung** | IHK-Abschlussprojekt: Enterprise CRM mit 2FA (SMS & Mail), Exporten | C#, ASP.NET MVC, EF Core, SQL Server, Bootstrap, Twilio, MailKit | [GitHub](https://github.com/Goekss/CrmAPP) |
| **Klinik Raum Stuttgart** | Desktop-Verwaltungssoftware für Patienten, Termine und Räume | C#, .NET Framework, Windows Forms, SQL Server | [GitHub](https://github.com/Goekss/Klinikum_Stuttgart) |
| **Photo BLOG** | Mobile-First Web-Layout mit purem CSS Grid & Flexbox | HTML5, CSS3 (Reines CSS ohne Frameworks) | — |

---

### 🗂️ Verzeichnisstruktur

```text
my-portfolio/
├── index.html          # Semantisches HTML5-Grundgerüst, SEO, Meta & Navigation
├── app.js              # Anwendungslogik, State-Management, Content-Map & Events
├── style.css           # Design-System, CSS-Variablen, Layouts, Animationen & Dark Mode
├── img/                # Profilbilder, Favicon und visuelle Branding-Assets
├── projekte/           # Hochauflösende Screenshots der Softwareprojekte
├── dokumente/          # Strukturierte Nachweise und Zertifikate
│   ├── lebenslauf/             # Aktueller tabellarischer Lebenslauf (PDF)
│   ├── arbeitszeugnis/         # Qualifizierte Arbeitszeugnisse (PDF)
│   ├── schulische_akademische/ # Schul- und Weiterbildungsnachweise (PDF)
│   └── ehrenamtlich/           # Nachweise über ehrenamtliches Engagement (PDF)
└── README.md           # Projektdokumentation (DE & TR)
```

---

### 💻 Lokale Installation & Ausführung

Da dieses Projekt ohne Build-Tools auskommt, kann es sofort mit jedem statischen Webserver ausgeführt werden:

1. **Repository klonen:**
   ```bash
   git clone https://github.com/Goekss/Web-Portfolio.git
   cd Web-Portfolio
   ```

2. **Mit einem lokalen Server starten:**
   - **VS Code Live Server:** Rechtsklick auf `index.html` ➔ *Open with Live Server*
   - **Node.js (`npx serve`):**
     ```bash
     npx serve .
     ```
   - **Python:**
     ```bash
     python -m http.server 8080
     ```

3. **Im Browser öffnen:**
   Navigiere zu `http://localhost:8080` (oder dem Port deines Servers).

---

<br />

## 🇹🇷 Türkçe (TR)

### 📌 Proje Hakkında

Merhaba! 👋 Kişisel web portfolyoma hoş geldin.

Bu sayfayı; geliştirdiğim projeleri, aldığım eğitimleri ve çalışma belgelerimi derli toplu bir arada tutmak için tasarladım. Günümüz teknolojilerini yakından takip ediyor, her gün yeni bir şeyler öğrenerek kendimi bir adım öteye taşımaya odaklanıyorum.

Bu siteyi de tam bu bakış açısıyla, karmaşadan uzak standar **HTML5, CSS3 ve JavaScript** kullanarak sıfırdan hazırladım.

---

### ✨ Öne Çıkan Özellikler

- **⚡ Sıfır Bağımlılık & No-Build:** `node_modules` klasörü veya karmaşık derleme adımları yoktur. Kod doğrudan tarayıcı tarafından yorumlanır ve anında yüklenir.
- **🎛️ Dinamik İçerik Yönetimi & Modal Overlay:** Sayfadaki tüm sekmeler (`contentMap`) üzerinden dinamik olarak render edilir. Sayfa yenilenmeden tam ekran overlay mimarisiyle projeler ve belgeler incelenebilir.
- **📄 Canlı PDF ve Belge Önizleme:** Özgeçmiş (Lebenslauf), çalışma belgeleri (Arbeitszeugnisse), akademik diplomalar ve gönüllülük sertifikaları responsive `<iframe>` bileşenleri üzerinden doğrudan incelenebilir veya indirilebilir.
- **🎨 Premium Koyu Tema & Glassmorphism:** CSS modern değişkenleri, `backdrop-filter` cam efektleri ve fare hareketine duyarlı dinamik ışık halkası (`--mouse-x`, `--mouse-y`) ile zenginleştirilmiş kullanıcı deneyimi.
- **🎯 Aşamalı Pürüzsüz Kaydırma (Phased Smooth Scroll):** Standart `scroll-behavior: smooth` yerine üç aşamalı kübik hızlanma/yavaşlama (`easeInCubic` & `easeOutCubic`) formülüyle akıcı sayfa içi geçişler.
- **🏷️ Akıllı Teknoloji İkon Eşleştirmesi:** Projelerde ve yeteneklerde yazılan metinleri otomatik olarak Devicon veya özel vektörel CDN ikonlarına dönüştürür; ikonu olmayanlar için şık rozetler oluşturur.
- **🛡️ KVKK / DSGVO Uyumlu Çerez Bildirimi:** Kullanıcı açık onay vermeden Google Analytics izleme kodları çalıştırılmaz. Panel içinde anlık açılan Aydınlatma Metni (Gizlilik) ve Künye (Impressum) bölümleri mevcuttur.
- **📱 %100 Duyarlı (Responsive) & Erişilebilir:** Akıllı telefonlardan geniş ekranlı monitörlere kadar kusursuz görünüm ve erişilebilirlik (`aria-*`) standartları.

---

### 📂 Portfolyoda Sergilenen Projeler

| Proje | Mimari & Kapsam | Teknolojiler | Bağlantılar |
|---|---|---|---|
| **Vista.Core / Vista.CoreX** | Full-Stack SaaS, Kurumsal RAG Yapay Zekâ, CRM & Çoklu Kiracılık (Multi-Tenant) | C#, ASP.NET Core, EF Core, SQL Server, React, Vite, Ollama, Qdrant, Semantic Kernel, SignalR, Docker | [GitHub](https://github.com/Goekss/Vista.CoreX) · [Canlı Demo](https://goekss.github.io/CoreX-Demo/) |
| **GoAI ChatLab** | Güvenli Express proxy arkasında çalışan, dosya yükleme destekli yapay zekâ sohbet paneli | React, Node.js, Express.js, Docker, GitHub Actions, OpenRouter AI | [GitHub](https://github.com/Goekss/GoAI-ChatLab) · [Önizleme](https://goekss.github.io/GoAI-ChatLab/) |
| **CRMApp-Nova** | ASP.NET REST API ile haberleşen, Kanban panosu ve JWT doğrulamalı React SPA | React, React Router, JavaScript, REST API, JWT, Kanban State | [GitHub](https://github.com/Goekss/CrmAppNova) |
| **CRM-Anwendung** | IHK Bitirme Projesi: SMS (Twilio) & E-posta ile 2FA doğrulama, Excel/PDF raporlama | C#, ASP.NET MVC, EF Core, SQL Server, Bootstrap, Twilio, MailKit | [GitHub](https://github.com/Goekss/CrmAPP) |
| **Klinik Raum Stuttgart** | Hasta, randevu ve oda yönetimini sağlayan ilişkisel veritabanlı masaüstü yazılımı | C#, .NET Framework, Windows Forms, SQL Server | [GitHub](https://github.com/Goekss/Klinikum_Stuttgart) |
| **Photo BLOG** | Saf CSS Grid ve Flexbox mekanikleriyle geliştirilmiş Mobile-First fotoğraf arayüzü | HTML5, CSS3 (Kütüphanesiz Saf Tasarım) | — |

---

### 🗂️ Dizin Ağacı

```text
my-portfolio/
├── index.html          # Ana HTML5 iskeleti, meta etiketleri, SEO ve navigasyon
├── app.js              # Uygulama mantığı, içerik haritası (contentMap) ve olay dinleyicileri
├── style.css           # Tasarım sistemi, renk değişkenleri, responsive kurallar ve animasyonlar
├── img/                # Profil fotoğrafı, marka ve favicon görselleri
├── projekte/           # Yazılım projelerine ait yüksek çözünürlüklü ekran görüntüleri
├── dokumente/          # Sertifikalar, referanslar ve belgeler
│   ├── lebenslauf/             # Güncel CV / Özgeçmiş (PDF)
│   ├── arbeitszeugnis/         # Çalışma referans belgeleri (PDF)
│   ├── schulische_akademische/ # Diploma ve eğitim sertifikaları (PDF)
│   └── ehrenamtlich/           # Gönüllülük ve topluluk belgeleri (PDF)
└── README.md           # Kapsamlı proje dokümantasyonu (DE & TR)
```

---

### 💻 Yerel Ortamda Çalıştırma

Projede derleme adımı gerekmediği için herhangi bir yerel sunucu ile hemen çalıştırılabilir:

1. **Depoyu klonlayın:**
   ```bash
   git clone https://github.com/Goekss/Web-Portfolio.git
   cd Web-Portfolio
   ```

2. **Yerel sunucu başlatın:**
   - **VS Code Live Server:** `index.html` dosyasına sağ tıklayıp *Open with Live Server* seçeneğini kullanın.
   - **Node.js (`npx serve`):**
     ```bash
     npx serve .
     ```
   - **Python:**
     ```bash
     python -m http.server 8080
     ```

3. **Tarayıcınızda açın:**
   `http://localhost:8080` adresine gidin.

---

## 📬 Kontakt / İletişim

- **Geliştirici / Entwickler:** Onur Gökhan Bicer
- **Konum / Standort:** Stuttgart, Deutschland
- **E-Posta / E-Mail:** [gokhanbicer@mail.de](mailto:gokhanbicer@mail.de)
- **GitHub:** [@Goekss](https://github.com/Goekss)
- **Portfolyo:** [goekss.github.io/Web-Portfolio](https://goekss.github.io/Web-Portfolio/)

---

## 📄 Lizenz / Lisans

Bu proje [MIT Lisansı](LICENSE) kapsamında açık kaynak olarak sunulmaktadır.
