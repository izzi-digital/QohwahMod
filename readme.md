# QOHWAH MOD for GTA V

## 🇮🇩 Bahasa Indonesia

### ✨ Fitur

- Input race manual via file `.ini`
- Countdown khas GTA, Wins Point, dan auto-waypoint
- Tampilan health bar permanen
- Respawn dan restart otomatis atau manual setelah mati
- Marker finish dan HUD terintegrasi
- **Konfigurasi tombol**

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

Beberapa Konfigurasi dapat diatur dari dalam game.  
Kamu juga dapat mengatur konfigurasi di file:
`GTA V/scripts/QohwahConfig.ini`

Isi default:
- Wins=10
- TargetWins=20
- TriggerKey=D1
- ManualDecreaseKey=D2
- ManualIncreaseKey=D3
- ManualSetTargetWinsKey=D4
- BackToStart=D5
- AutoDecreaseWinsOnDeath=false
- AutoRestartRaceOnDeath=false
- SpawnWithVehicle=false

Keterangan:

- TriggerKey: tombol untuk membuka menu Qohwah (bisa F1–F12, A–Z, dll.) (Default : Tombol Angka 1)

- ManualDecreaseKey: tombol untuk mengurangi 1 poin wins secara manual (default: Tombol Angka 2)

- ManualIncreaseKey: tombol untuk menambahkan 1 poin wins secara manual (default: Tombol Angka 3)

- ManualSetTargetWinsKey: tombol untuk mengatur target wins secara manual (default: Tombol Angka 4)

- BackToStart: tombol untuk kembali ke titik start (default: Tombol Angka 5)

- AutoDecreaseWinsOnDeath:

- - true: otomatis kurangi wins saat karakter mati

- - false: kamu bisa tekan ManualWinLossKey untuk kurangi sendiri

- AutoRestartRaceOnDeath:

- - true: otomatis restart race saat karakter mati

- - false: kamu bisa tekan BackToStart untuk restart sendiri

- SpawnWithVehicle: true untuk spawn dengan kendaraan, false untuk spawn tanpa kendaraan

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
- [RaceName]|[StartX]|[StartY]|[StartZ]|[StartYaw]|[FinishX]|[FinishY]|[FinishZ]|[FinishYaw]

Contoh:
- Airport To Mountain|-1034.59998|-2733.6001|13.3990097|29.27|501.79837|5603.78955|797.91009|172.20

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

**Author**: Qohwah - Izzi Digital  
- 💻 [github.com/izzi-digital](https://github.com/izzi-digital)  
- 🎵 [Tiktok](https://www.tiktok.com/@qohwah_id)  
- 🎞️ [Youtube](https://www.youtube.com/@qohwah-id)

- ☕ [Ko-fi](https://ko-fi.com/izzidigi)
- 💜 [SociaBuzz](https://sociabuzz.com/qohwah)
