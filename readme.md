# QOHWAH MOD for GTA V

## 🇮🇩 Bahasa Indonesia

### ✨ Fitur

- Input race manual via file `.ini`
- Countdown khas GTA, pelacakan kemenangan, dan auto-waypoint
- Tampilan health bar permanen
- Respawn dan restart otomatis setelah mati
- Marker finish dan HUD terintegrasi
- **Konfigurasi tombol trigger (default: tombol 1)**

---

### 📌 Persyaratan

- GTA V versi PC
- [ScriptHookV](https://www.dev-c.com/gtav/scripthookv/)
- [ScriptHookVDotNet v3](https://github.com/crosire/scripthookvdotnet/releases)
- [LemonUI untuk SHVDN3](https://github.com/LemonUIbyLemon/LemonUI/releases)
- [.NET Framework 4.8 atau lebih tinggi](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48)
- [Visual C++ Redistributable 2015–2022](https://aka.ms/vs/17/release/vc_redist.x64.exe)

---

### 📁 Cara Pemasangan

1. Ekstrak semua file dari folder mod ini.
2. Salin semua file dan folder ke direktori game GTA V:  
   `GTA V/`
3. Pastikan `LemonUI.SHVDN3.dll` dan `LemonUI.SHVDN3.xml` juga ada di folder `scripts/`.
4. Jalankan GTA V seperti biasa.

---

### ⚙️ Konfigurasi

Kamu dapat mengatur tombol untuk membuka menu mod dan perilaku pengurangan poin di file:
`GTA V/scripts/QohwahConfig.ini`

Isi default:
TriggerKey=D1
AutoDecreaseWinsOnDeath=true
ManualDecreaseKey=D2

Keterangan:

- TriggerKey: tombol untuk membuka menu Qohwah (bisa F1–F12, A–Z, dll.) (Default : Tombol Angka 1)

- ManualDecreaseKey: tombol untuk mengurangi 1 poin wins secara manual (default: Tombol Angka 2)

- AutoDecreaseWinsOnDeath:

- - true: otomatis kurangi wins saat karakter mati

- - false: kamu bisa tekan ManualWinLossKey untuk kurangi sendiri

Ganti tombol default dengan tombol lain sesuai kebutuhan, misalnya:

| Tombol      | Nilai       |
| ----------- | ----------- |
| Angka 1     | D1          |
| Angka 2     | D2          |
| Numpad 1    | NumPad1     |
| Ctrl kiri   | LControlKey |
| Shift kanan | RShiftKey   |
| Spasi       | Space       |

---

### 📄 Menambahkan Race Secara Manual

Races **tidak bisa ditambahkan dari dalam game**.  
Edit file ini:
`GTA V/scripts/QohwahRaces.ini`

Format:
[RaceName]|[StartX]|[StartY]|[StartZ]|[StartYaw]|[FinishX]|[FinishY]|[FinishZ]|[FinishYaw]

Contoh:
Airport To Mountain|-1034.59998|-2733.6001|13.3990097|29.27|501.79837|5603.78955|797.91009|172.20

---

### 🎮 Cara Menggunakan

- Tekan tombol trigger (default `D1`) untuk membuka menu Qohwah.
- Pilih race dari daftar.
- Kamu akan langsung teleport ke titik start dengan kendaraan.
- HUD akan menampilkan progress, countdown, dan marker finish otomatis.

---

### ⚠️ Catatan

- Tidak kompatibel dengan GTA Online.
- Karakter otomatis respawn dan restart race saat mati.

---

## 🇬🇧 English

### ✨ Features

- Manual race input via `.ini` file
- GTA-style countdown, win tracking, and auto-waypoint
- Always-on health bar display
- Automatic respawn and race restart after death
- Finish marker & HUD integration
- **Trigger key customization (default: 1)**

---

### 📌 Requirements

- GTA V PC version
- [ScriptHookV](https://www.dev-c.com/gtav/scripthookv/)
- [ScriptHookVDotNet v3](https://github.com/crosire/scripthookvdotnet/releases)
- [LemonUI for SHVDN3](https://github.com/LemonUIbyLemon/LemonUI/releases)
- [.NET Framework 4.8 or higher](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48)
- [Visual C++ Redistributable 2015–2022](https://aka.ms/vs/17/release/vc_redist.x64.exe)

---

### 📁 Installation

1. Extract all mod files.
2. Copy everything to your GTA V root folder:  
   `GTA V/`
3. Ensure `LemonUI.SHVDN3.dll` and `LemonUI.SHVDN3.xml` are inside the `scripts/` folder.
4. Launch GTA V.

---

### ⚙️ Custom Configuration

You can configure the trigger key and win loss key in:
`GTA V/scripts/QohwahConfig.ini`

Default content:
[General]
TriggerKey=D1
AutoDecreaseWinsOnDeath=true
ManualDecreaseKey=D2

Explanation:

- TriggerKey: key to open Qohwah menu (can be F1–F12, A–Z, etc.)

- ManualDecreaseKey: key to manually decrease wins by 1 point

- AutoDecreaseWinsOnDeath:

- - true: automatically decrease wins when player dies

- - false: manually decrease wins by pressing ManualWinLossKey

| Key         | Value       |
| ----------- | ----------- |
| 1           | D1          |
| 2           | D2          |
| Numpad 1    | NumPad1     |
| Left Ctrl   | LControlKey |
| Right Shift | RShiftKey   |
| Space       | Space       |

---

### 📄 Adding Races Manually

Races **cannot be added from within the game**.  
Edit this file:
`GTA V/scripts/QohwahRaces.ini`

Format:
[RaceName]|[StartX]|[StartY]|[StartZ]|[StartYaw]|[FinishX]|[FinishY]|[FinishZ]|[FinishYaw]

Example:
Airport To Mountain|-1034.59998|-2733.6001|13.3990097|29.27|501.79837|5603.78955|797.91009|172.20

---

### 🎮 How to Use

- Press trigger key (default `D1`) to open Qohwah menu.
- Choose a race and you’ll be teleported with a vehicle.
- Countdown, progress, and finish marker will appear automatically.

---

### ⚠️ Notes

- Not compatible with GTA Online.
- Player will auto-respawn and restart race after death.

---

**Author**: Qohwah - Izzi Digital  
💻 [github.com/izzi-digital](https://github.com/izzi-digital)  
🎵 [Tiktok](https://www.tiktok.com/@qohwah_id)  
🎞️ [Youtube](https://www.youtube.com/@qohwah-id)

- ☕ [Ko-fi](https://ko-fi.com/izzidigi)
- 💜 [SociaBuzz](https://sociabuzz.com/qohwah)
