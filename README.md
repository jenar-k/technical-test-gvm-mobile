# 📱 Technical Test – Mobile Automation (Maestro)

Automated mobile testing project using **[Maestro](https://maestro.mobile.dev/)**.  
This repository contains mobile UI test flows for validating application functionality (Android & iOS).

---

## 🚀 Tech Stack
| Tool | Description |
|------|--------------|
| **Maestro** | Mobile test framework for Android & iOS |
| **YAML** | Test flow definition language |

---

## ⚙️ Setup Instructions

### 1️⃣ Install Maestro
Install Maestro CLI:
```bash
curl -fsSL "https://get.maestro.mobile.dev" | bash
```

💡 Requires Java 17+ and Android SDK for emulator usage.

---

## 🧠 Run Tests
### Jalankan satu flow
```bash
maestro test flows/login.yaml
```

### Jalankan semua flow
```bash
maestro test flows/
```
