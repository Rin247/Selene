# Selene — Offline Period & Moon Cycle Tracker

Selene is a 100% offline, privacy-focused Android application for tracking menstrual cycles, fertility windows, symptoms, and lunar phases. Built with Kotlin, Jetpack Compose, and Material 3, Selene guarantees complete data privacy with on-device encrypted storage and zero network telemetry.

---

## 🌙 Key Features & Module Breakdown

### 🩸 Menstrual & Cycle Tracking (`tracker-cycle`)
- **Current**: Cycle logging, period duration prediction, ovulation & fertility window estimation, and custom symptom/mood logging.
- **Planned / Roadmap**: Machine-learning cycle irregularity detection, BBT (Basal Body Temperature) charting, and custom hormone test logging.

### 🌕 Lunar Phase Synchronization (`tracker-lunar`)
- **Current**: Astronomical moon phase calculation, lunar calendar view, and cycle-lunar phase correlation visualization.
- **Planned / Roadmap**: Eclipse & astrological transit overlay, customizable lunar notifications, and historical phase alignment graphs.

### 🔒 Encryption & Data Vault (`vault`)
- **Current**: SQLCipher database encryption, PIN/Biometric app lock, local JSON export/import, and automatic backup.
- **Planned / Roadmap**: Encrypted peer-to-peer sync, auto-wipe on failed PIN attempts, and zero-knowledge cloud backup.

---

## 🏗️ Architecture & Technology Stack

- **Platform**: Android 13+ (minSdk 33, targetSdk 37).
- **UI & Layout**: Kotlin, Jetpack Compose, Material 3.
- **Database**: Room + SQLCipher hardware-backed encryption.
- **Licensing**: AGPL-3.0.

---

## 🛠️ Building & Running

```bash
./gradlew assembleDebug
./gradlew installDebug
```

---

## 📜 License

Selene is released under the **GNU Affero General Public License v3.0** (AGPL-3.0). See [`LICENSE`](LICENSE) for details.
