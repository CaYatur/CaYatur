# 🚀 Projelerim — CaYaDev

**Çağan TURGUT** · CaYaDev Kurucusu  
Web, masaüstü, sistem, gömülü, AI ve oyun alanlarında ürettiğim açık kaynak ve kişisel projelerin kapsamlı listesi.

Detaylı profil, başarımlar ve tüm kaynaklar:  
→ [cayadev.com/team/cagan-turgut](https://cayadev.com/team/cagan-turgut)

---

## 🔥 Aktif & Öne Çıkan Projeler

### 1. CaYaTrace
**Windows Application Forensics**  
Bir programın sistemde ve ağda yaptığı her şeyi tek bir nedensel zincir olarak kaydeder, sonra taşınabilir ve doğrulanmış kaldırma paketi üretir.

- Process / thread / module / file / registry / network / DNS / TLS izleme
- Causal tree (nedensel ağaç)
- Portable `.ctpkg` removal package + dry-run + rollback
- Workbench UI + CLI + fleet agent
- Loopback (127.0.0.1) konuşmaları yakalama (Npcap opsiyonel)
- Ollama entegrasyonu, VirusTotal hash lookup, risk skorlama

**Teknoloji:** C# · .NET 8 · ETW · WebView2  
**Repo:** [CaYatur/CaYaTrace](https://github.com/CaYatur/CaYaTrace)  
**Durum:** Aktif geliştirme (0.5.x preview)

---

### 2. Minecraft-CaYa-Bot-Panel
**Multi-bot Minecraft otomasyon paneli + MCP / AI Agent**

- Birden fazla botu aynı anda yönetme
- Gelişmiş otomasyon motoru (nested IF/ELSE, değişkenler, task queue)
- Schematic building, farming, mining, combat, survival
- **MCP sunucusu** → Claude, Cursor, VS Code vb. ile botları araç olarak kullanma
- Yerel Ollama ile in-game AI agent
- Türkçe + İngilizce arayüz

**Teknoloji:** TypeScript · Electron · Mineflayer · Socket.IO  
**Repo:** [CaYatur/Minecraft-CaYa-Bot-Panel](https://github.com/CaYatur/Minecraft-CaYa-Bot-Panel)  
**Durum:** Aktif

---

### 3. MinecraftServerManagementSystem (MSMS)
**Portable Minecraft Sunucu Yönetim Paneli**

- Vanilla, Paper, Folia, Purpur, Fabric, Forge, NeoForge, Mohist, Velocity desteği
- Canlı konsol, RCON, oyuncu moderasyonu, dünya yönetimi
- Plugin/mod yükleme (Modrinth entegrasyonu)
- Canlı harita, performans izleme, yedekleme, zamanlanmış görevler
- Web paneli + mağaza/ekonomi sistemi
- Tamamen portable (tek klasör)

**Teknoloji:** TypeScript · Electron · React  
**Repo:** [CaYatur/MinecraftServerManagementSystem](https://github.com/CaYatur/MinecraftServerManagementSystem)  
**Durum:** Aktif

---

### 4. SoundVisualizer (CaYaDev Visualizer)
**Multi-monitor gerçek zamanlı ses görselleştirici**

- Sistem sesi (WASAPI loopback) + mikrofon + çoklu kaynak
- 14 görselleştirici modu + 10 arka plan tipi
- Sahne sistemi, renk presetleri, logo pulse
- Video export (MP4)
- Windows Dynamic Lighting desteği
- Türkçe + İngilizce

**Teknoloji:** JavaScript · Electron · WebGL · Native (audify)  
**Repo:** [CaYatur/SoundVisualizer](https://github.com/CaYatur/SoundVisualizer)  
**Durum:** Aktif

---

### 5. PremiereProMCP (PPMCP)
**Adobe Premiere Pro için AI kontrol katmanı (MCP)**

- Claude / Cursor / herhangi bir MCP istemcisi ile gerçek timeline düzenleme
- Clip ekleme, kesme, trim, transition, efekt, audio gain, title, export
- UXP-first mimari + opsiyonel CEP bridge
- 270+ araç, checkpoint / rollback, rate limiting
- Kurulum sihirbazı (portable Node dahil)

**Teknoloji:** JavaScript · UXP · Node.js  
**Repo:** [CaYatur/PremiereProMCP](https://github.com/CaYatur/PremiereProMCP)  
**Durum:** Aktif

---

### 6. cayadev-ai-hub
**Yerel Ollama modelleri üzerinde çalışan coding agent framework**

- Küçük modeller bile kullanılabilir hale getirir
- Task-based model routing (planlama / kodlama / edit / sınıflandırma)
- Tolerant tool-call parsing
- Auditable permission sistemi
- Tauri tabanlı

**Teknoloji:** Rust · Tauri  
**Repo:** [CaYatur/cayadev-ai-hub](https://github.com/CaYatur/cayadev-ai-hub)  
**Durum:** Aktif

---

## 🛠️ Diğer Önemli Projeler

| Proje | Açıklama | Teknoloji |
|-------|----------|-----------|
| **Windows-to-Android-Bridge** | Windows PC’yi Android’den kontrol etme (medya, sistem bilgileri, güç) | Kotlin |
| **CaYaFix** | Diagnostics-first Windows sorun giderme + geri alınabilir onarım | C# |
| **CaYa-Network-Forensic-Observer** | Ağ forensics gözlemcisi | Python |
| **CaYaDiscordBot-GUI** | Discord bot yönetim merkezi (moderasyon, müzik, AI, web research) | TypeScript |
| **EzanVaktiWearOS** | Diyanet uyumlu, telefon gerektirmeyen namaz vakitleri Wear OS complication | Kotlin · Compose |
| **CaYaTunnel** | Self-hosted reverse tunnel (HTTP, Minecraft, TCP/UDP) – NAT/CGNAT arkasından servis açma | C# |
| **CaYa-Coding-Agent-ChatGPT-Web** | ChatGPT Web’i self-hosted coding agent’a çeviren köprü | JavaScript |
| **CaYaDevCLI** | Hafif, açık kaynak AI coding terminal aracı | JavaScript |
| **CaYaToDoList** | Kategoriler, etiketler, alt görevler, konum tabanlı hatırlatıcılar içeren Android to-do | Kotlin · Compose |
| **CaYaLineFollowerSensorLibrary** | Arduino için hızlı, kalibrasyonsuz çizgi takip sensör kütüphanesi | C++ |
| **CaYaSoundEdit** | Tarayıcıda çalışan ses düzenleyici (kanal, bas, kırpma, WAV) | JavaScript |
| **CaYaCircuitBoardDesign** | Çift katmanlı PCB tasarım uygulaması (Windows / macOS / Web) | TypeScript |
| **CaYaBasicOS** | BIOS & UEFI destekli bare-metal hobi işletim sistemi | C |
| **RoboCar** | ESP32 tabanlı Wi-Fi / Android / DualSense kontrollü robot araç | C++ · Arduino |
| **Orbo — Wear OS Games** | 85 oyun + 13 araç içeren Wear OS arcade paketi | Kotlin |
| **Kelime-Sayar** | Harflerden kelime üretme oyunu | JavaScript |
| **fable-mode** | Claude modellerini maksimum titizlikle çalıştıran disiplin protokolü | — |

---

## 🧪 Deneysel / Lab Projeleri

- **Zyxel-VMG3312-B10B-Lab** — Modem üzerinde deneysel araştırma ve özelleştirme
- **WearOS-Windows-Bridge-DEMO** — Windows ↔ Wear OS medya köprüsü (arşiv)
- **CaYaScreenBridge** — Ekran köprüsü
- **Claude-low-token-mode** — Claude Code için token tasarrufu düzenleri
- **enterprogram** — Belirli süre sonra Enter basan + ekran uykusunu engelleyen Tkinter aracı

---

## 📊 Teknoloji Dağılımı

- **Sistem / Forensics / Windows:** C#, .NET, ETW
- **Masaüstü uygulamalar:** Electron, Tauri, WPF / WinUI
- **Web & AI araçları:** TypeScript, JavaScript, Node.js
- **Mobil / Wear OS:** Kotlin, Jetpack Compose
- **Gömülü & Robotik:** C, C++, Arduino, ESP32
- **Oyun & Eğlence:** Kotlin, JavaScript
- **AI Agent / LLM:** Rust, Ollama, MCP

---

## 📌 Notlar

- Tüm projeler **CaYaDev** markası altında geliştirilmektedir.
- Çoğu proje **MIT** lisansı ile açıktır.
- Türkçe + İngilizce destek birçok uygulamada mevcuttur.
- Daha fazla detay, ekran görüntüsü, başarımlar ve indirme linkleri için:  
  **[cayadev.com](https://cayadev.com)**

---
